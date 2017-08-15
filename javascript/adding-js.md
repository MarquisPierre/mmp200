---
layout: class
site: MMP 200 Multimedia Design
categories: javascript
title: How to add JavaScript to HTML code
---
JavaScript is a scripting language that is being interpreted by the browser (the browser is also called the ‘client’, which is why JavaScript is considered ‘client-side’ language.)

JavaScript can be typed in the HTML file inside the *script* tags, such as:

        <script type="text/javascript">
          function newWindow(webURL){
            var newWin=window.open(webURL, "new_window", "location=0,width=400,height=300");
            newWin.focus();
          }
        </script>

or in a separate text file that is saved with the extension .js and linked to the HTML file with the *script* tags. For example:

        <script src="myCode.js" type="text/javascript">
        </script>

