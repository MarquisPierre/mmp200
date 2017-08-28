---
layout: class-home
site: MMP 200 Multimedia Design
title: Schedule
---
{% for i in (1..15) %}<a href="#week-{{i}}" class="week">Week {{i}}</a>{% endfor %}

--------------------

### Week 1

**Review: HTML**
* HTML Syntax
    - [Basic HTML Structure](https://github.com/revitalk/mmp200/blob/master/week1/basicHtmlStructure.html)
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
**Read:**[Build perfect website](Build perfect website)

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
    - [Designing navigation](information-architecture/nav-type.md)

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
- Layout desgin
    - [Visual Hierarchy](http://www.gdbasics.com/html/hierarchy/hierarchy.html)
    - [Grid]({{site.url}}/mmp200/graphic-design/grid)
- Creating mockups in Photoshop

**Inspiration**
- http://www.panorama.nyc/
- https://fireflyfestival.com/

**Assignment** 
- [Midterm project](assignments/midterm.md) step 3
- Mockup presentations

**Read:** [Organizing the Page: Layout of Page Elements](https://www.safaribooksonline.com/library/view/designing-interfaces/0596008031/ch04.html)

--------------------------

### Week 5
**CSS Responsive Layout**
- [CSS layout with Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes)
- [Viewport and Media Queries](css/viewport-media-queries.md) 
- Mobile-first web development
- CSS Dropdown Menu ([code](https://github.com/revitalk/mmp200/blob/master/css/css-dropdown-menu.html))

**Assignment:** [Midterm project](assignments/midterm.md) step 4
**Read:** [What is Responsive Design](http://cdn.oreillystatic.com/oreilly/booksamplers/9781449362942_sampler.pdf)

--------------------------

### Week 6
**Midterm Production**
- Embedding fonts with CSS
- CSS enhancements

**Assignment:** [Midterm project](assignments/midterm.md) step 4

--------------------------

### Week 7
**Midterm Presentations**

--------------------------

### Week 8
**Interface Design**
- Visual hierarchy
- Entry Point
- Affordances
- Providing feedback
- Mental Model and Conceptual Models

**Class exercise:** User flows
**Assignment:** [pitch an app]({{site.url}}/mmp200/assignments/app-pitch) group work and presentations
**Read** 
- [How we really use the Web](http://www.sensible.com/chapter.html)
- [Why Users like Mindless Choices](https://www.sensible.com/downloads/DMMT-Revisited-sample-chapter.pdf)

--------------------------

### Week 9
**App Concept Development**
<iframe src="https://player.vimeo.com/video/52861634" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

- Case Study: [NY Times Cooking App](https://cooking.nytimes.com/)

**Assignment:** [pitch an app]({{site.url}}/mmp200/assignments/app-pitch) group work

--------------------------

### Week 10
**Bootstrap Web Development**
- Using a CSS feamework- advantages and drawbacks
- [Download and learn about Bootstrap](http://getbootstrap.com/)- the most popular CSS framework
- [Responsive layout with Bootstrap]({{site.url}}/mmp200/bootstrap/three-col-bs)
- [Navigation bar with Bootstrap]({{site.url}}/mmp200/bootstrap/nav-bar-bs)
- [Dropdown menu with Bootstrap]({{site.url}}/mmp200/bootstrap/dropdown-bs)
- [Bootstrap's slideshow]({{site.url}}/mmp200/bootstrap/carousel-bs)
- [More Bootstrap code samples](https://github.com/revitalk/Bootstrap)

**Assignment:** [class portfolio]({{site.url}}/mmp200/assignments/portfolio)

--------------------------
<!---
### Week 11
**Planning an interactive site**
- Developing project requirements
- Personas
- Sitemaps
<!---
**Assignment:** [Final project]({{site.url}}/mmp200/assignments/final-pro)
**Read:** [Goal-Directed Design](http://media.wiley.com/product_data/excerpt/11/04700841/0470084111.pdf)

--------------------------
<!---
### Week 12
**Scenarios and workflows**
- Scenarios
- Sketching
<!---
**Assignment:** [Final project]({{site.url}}/mmp200/assignments/final-pro)

--------------------------
<!---
### Week 13
**CSS & Bootstrap Production**
<!---
**Assignment:** [Final project]({{site.url}}/mmp200/assignments/final-pro) prototyping

--------------------------
<!---
### Week 14
**Production Lab**
- bring your questions to class!
<!---
**Assignment:** [Final project]({{site.url}}/mmp200/assignments/final-pro) production

--------------------------
<!---
### Week 15
**Critiques**
- Testing and assessment
- Revisions
<!---
**Assignment:** [Final project]({{site.url}}/mmp200/assignments/final-pro) production

--------------------------
<!---
### Exam Week
**Final presentations**
**Submission of final portolios** -->
