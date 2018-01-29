---
layout: class
site: MMP 200 Multimedia Design
title: Schedule
---
{% for i in (1..15) %}<a href="#week-{{i}}" class="week">Week {{i}}</a>{% endfor %}

--------------------

### Week 1

**Review: HTML**
* HTML Syntax
    - [Basic HTML Structure](https://github.com/revitalk/mmp200/blob/master/html/basicHtmlStructure.html)
    - [HTML starter file](https://github.com/revitalk/mmp200/blob/master/html/html-starter.html)
    - [Elements, Tages and Attributes]({{site.url}}/mmp200/html/html-intro) 
    - [Empty and container elements]({{site.url}}/mmp200/html/empty-container)
    - Nesting: parents and children
* HTML elements
    - [HTML5 Sectional Elements: section, article, aside]({{site.url}}/mmp200/html/sectional-elements)
    - HTML5 text elements: p, strong, em, br, [blockquote and q]({{site.url}}/mmp200/html/quoting)
    - HTML list elements: ul, ol, li
    - [Elements to mark emphasis]({{site.url}}/mmp200/html/emphasis)
    - The div and span elements
  
**Publishing on Github Pages** 
- Sign up to get a FREE [Github](https://github.com/) account
- Create a new repository. In Setting determine which channel will be used for your website.
- Upload files and check published pages at username.github.io/repository/folder/filename.

**Assignment:** HTML code for [Assignment 1](assignments/assignment1/assignment1.md)

**Resources**
- [HTML validator](https://validator.w3.org/)
- [HTML5 Doctor](http://html5doctor.com/)

**Read:** [A Brief History of Markup](http://alistapart.com/article/a-brief-history-of-markup)

--------------------------

### Week 2
**Intro to CSS**
- [Types of CSS](css/css-types.md)
- [How to write CSS](css/writing-css.md)
- [CSS  selectors](css/selectors.md)
- [CSS box model: width, height, padding, margins, borders](css/box-model.md)
- CSS units
    - [Which CSS measurements to use when](http://thenewcode.com/775/Which-CSS-Measurements-To-Use-When)
- [Block-level and Inline elements]({{site.url}}/mmp200/css/block-inline)
   
**Adaptive Sizing and Typography**
- The [width](https://developer.mozilla.org/en-US/docs/Web/CSS/width) and [max-width](https://developer.mozilla.org/en-US/docs/Web/CSS/max-width) properties
- [em](https://www.sitepoint.com/power-em-units-css/), [rem](https://www.sitepoint.com/understanding-and-using-rem-units-in-css/) and percentage CSS units 
- [Viewport and Media Queries](css/viewport-media-queries.md) 

**Assignment:** CSS for [Assignment 1](assignments/assignment1/assignment1.md)

**Read:**[Build perfect website](http://geekfolk.blogspot.com/2015/01/build-perfect-website.html)

--------------------------

### Week 3
**Planning a Web Project**
- [The design process](http://zurb.com/word/design-process)
    - [Agile web development](https://webdesign.tutsplus.com/articles/a-designers-introduction-to-agile-methodology--cms-23349)
- [Web design deliverables](https://www.tpdesigns.net/Design-Articles/web-design-deliverables.html)

**Information Architecture**
- [Information Architecture]({{site.url}}/mmp200/information-architecture/information-architecture)
    - [The creative Brief]({{site.url}}//mmp200/assignments/festival-brief)
    - [Sitemap](information-architecture/sitemap.md)
    - [Designing navigation](information-architecture/type-navigation.md)

**Assignment:** [Midterm project](assignments/midterm.md) steps 1 and 2

**Read:** [Project Objectives and Approach (pdf)](https://href.li/?http://ptgmedia.pearsoncmg.com/images/9780321815385/samplepages/0321815386.pdf)

**Resources:** [EventBrite Music Festival Study](https://href.li/?http://eventbrite-s3.s3.amazonaws.com/marketing/MusicFestivalResearch/EventbriteStudyMusicFestivals8_25_14.pdf)

--------------------------

### Week 4
**Visual Design**
- Web typography
    - [Broad typeface categories]({{site.url}}/mmp200/typography/type-categories)
    - [Great free fonts]({{site.url}}/mmp200/typography/great-free-fonts)
    - [CSS typography]({{site.url}}/mmp200/typography/css-type)
- [Basics of color]({{site.url}}/mmp200/graphic-design/color)
-Creating a mockup in Photoshop

**Assignment** 
- [Midterm project](assignments/midterm.md) step 3

--------------------------

### Week 5
**Layout desgin**
    - [Visual Hierarchy](http://www.gdbasics.com/html/hierarchy/hierarchy.html)
    - [Grid]({{site.url}}/mmp200/graphic-design/grid)

**Inspiration**
- [http://www.panorama.nyc](http://www.panorama.nyc/home/)
- [Governors Ball](https://www.governorsballmusicfestival.com/)

**Assignment** 
- [Midterm project](assignments/midterm.md) step 3
- Mockup presentations

**Read:** [Organizing the Page: Layout of Page Elements](https://www.safaribooksonline.com/library/view/designing-interfaces/0596008031/ch04.html)

--------------------------

### Week 6
**CSS Layout**
- [CSS layout with Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes)
    - important properties: [flex](https://developer.mozilla.org/en-US/docs/Web/CSS/flex), [flex-basis](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-basis), [flex-direction](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-direction), [flex-flow](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-flow), [flex-grow](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-grow), [flex-shrink](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-shrink), [flex-wrap](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-wrap), [justify-content](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content), [order](https://developer.mozilla.org/en-US/docs/Web/CSS/order), [align-content](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content), [align-items](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items), [align-self](https://developer.mozilla.org/en-US/docs/Web/CSS/align-self). 
- [Viewport and Media Queries](css/viewport-media-queries.md) 
- Example: [4-column layout with CSS flexbox](http://revitalk.com/mmp200/css/flex/simple-flex-layout.html) [(code)](https://github.com/revitalk/mmp200/blob/master/css/flex/simple-flex-layout.html)


**Assignment:** [Midterm project](assignments/midterm.md) step 4

**Read:** [What is Responsive Design](http://cdn.oreillystatic.com/oreilly/booksamplers/9781449362942_sampler.pdf)

**Assignment:** [Midterm project](assignments/midterm.md) step 4

--------------------------

### Week 7
**CSS Responsive Design**
- Mobile-first web development
- CSS Dropdown Menu ([code](https://github.com/revitalk/mmp200/blob/master/css/css-dropdown-menu.html))

**Assignment:** [Midterm project](assignments/midterm.md) step 4

--------------------------

### Week 8
**Midterm Presentations**

--------------------------

### Week 9
**Bootstrap Web Development**
- Using a CSS feamework- advantages and drawbacks
- [Download and learn about Bootstrap](http://getbootstrap.com/)- the most popular CSS framework
- [Quick responsive layout with Bootstrap]({{site.url}}/mmp200/bootstrap/three-col-bs)
- [Navigation bar with Bootstrap](https://getbootstrap.com/docs/4.0/components/navbar/)
- [Dropdown menu with Bootstrap](https://getbootstrap.com/docs/4.0/components/dropdowns/)
- [Bootstrap's slideshow](https://getbootstrap.com/docs/4.0/components/carousel/)

**Assignment:** [class portfolio]({{site.url}}/mmp200/assignments/portfolio)


<!-- ### Week 10
**App Concept Development**
<iframe src="https://player.vimeo.com/video/52861634" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

- Case Study: [NY Times Cooking App](https://cooking.nytimes.com/)

**Assignment:** [pitch an app]({{site.url}}/mmp200/assignments/app-pitch) group work

 
**Class exercise:** User flows

**Assignment:** [pitch an app]({{site.url}}/mmp200/assignments/app-pitch) group work and presentations

**Read** 
- [How we really use the Web](http://www.sensible.com/chapter.html)
- [Why Users like Mindless Choices](https://www.sensible.com/downloads/DMMT-Revisited-sample-chapter.pdf)
-->

--------------------------

### Week 10
**Planning an interactive site**
- Developing project requirements: [Creative Brief]({{site.url}}//mmp200/assignments/creative-brief)
- [Information Architecture]({{site.url}}/mmp200/information-architecture/information-architecture)
- [Content Selection and Organization](https://go.gliffy.com/go/publish/5110220)
- [Organization Schemes](https://www.usability.gov/how-to-and-tools/methods/organization-schemes.html)
- [Personas]({{site.url}}/mmp200/information-architecture/personas)
- Scenarios and workflows
- [Sitemap](information-architecture/sitemap.md)
- Sketching

**Assignment:** [Final project]({{site.url}}/mmp200/assignments/final-pro)
**Read:** [Goal-Directed Design](http://media.wiley.com/product_data/excerpt/11/04700841/0470084111.pdf)

--------------------------

### Week 11-12
**Interface Design**

<iframe width="560" height="315" src="https://www.youtube.com/embed/yY96hTb8WgI?rel=0" frameborder="0" allowfullscreen></iframe>

- Visual hierarchy
- Entry Point
- [Mental Model and Conceptual Models](https://uxmag.com/articles/the-secret-to-designing-an-intuitive-user-experience)
- [Digital Affordances](http://blog.teamtreehouse.com/affordances-web-design)
     - Labels
     - Metaphors
     - Patterns
- Providing feedback

----------------------------------

### Week 13
**CSS & Bootstrap Production Lab**
- [Complex Bootstrap layout]({{site.url}}/mmp200/bootstrap/complex-layout-bs)
- bring your questions to class!

**Visual enhancement**
- Creating a [style tile](http://styletil.es/)
- [Simple template for a style tile](https://github.com/revitalk/mmp200/blob/master/graphic-design/style-tile.ai)

**Assignment:** [Final project]({{site.url}}/mmp200/assignments/final-pro) prototyping

--------------------------

### Week 14
**Critiques**
- Testing and assessment
- Revisions

**Assignment:** [Final project]({{site.url}}/mmp200/assignments/final-pro) production

--------------------------

### Week 15: Exam Week
**Final presentations**
**Submission of final portolios**

**Assignment:** [Final project]({{site.url}}/mmp200/assignments/final-pro) production



