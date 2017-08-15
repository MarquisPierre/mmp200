---
layout: class
categories: javascript
site: MMP 200 Multimedia Design
title: Basic JavaScript Dropdown Menu
---
**HTML**

Nest a complete UL with all the drop down links inside the relevant LI. Give the nesting UL a unique ID. For example:

        <li><a href="#">Info</a>
          <ul id="info">
            <li><a href="#">Festival Map</a></li>
            <li><a href="#">FAQ</a></li>
            <li><a href="#">Food</a></li>
          </ul>
        </li>

**CSS**

The nesting UL has to be positioned absolute so it will overlap the content below it. It should also be initially hidden:

        nav li ul{
        position:absolute;
        display:none;
        }

The links in the drop down menu should be arranged vertically, so if your main menu is horizontal you need to correct it for the drop down LIs:

        nav li li{
        display:block;
        }

**JavaScript**

Add the following JavaScript code to the head portion of your HTML document:

        <script>
          function toggle_div(id){
            if (document.getElementById(id).style.display=="block"){
              document.getElementById(id).style.display="none";
            }else{
              document.getElementById(id).style.display="block";
            }
          }
          // Closes down menus when a user interacts with other things on the page
          // info, tickets... are the id names of the dropdown ULs. Change them if yours are different and add more as needed.
          var boxArray = ['info','tickets'];
          window.addEventListener('mouseup', function(event){
            for(var i=0; i < boxArray.length; i++){
              var box = document.getElementById(boxArray[i]);
              if(event.target != box && event.target.parentNode != box){
                box.style.display = 'none';
              }
            }
          });
        </script>

**Activate the script**

Call the toggle_div function via the onclick attribute. Pass the function the id of the drop down menu UL.

        <li><a href="#" onclick="toggle_div('info')">Info</a>
          <ul id="info">
            <li><a href="#">Festival Map</a></li>
            <li><a href="#">FAQ</a></li>
            <li><a href="#">Food</a></li>
          </ul>
        </li>
