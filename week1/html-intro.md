---
layout: class
site: MMP 200 Multimedia Design
title: HTML elements, tags and attributes
---
What is the difference between HTML elements and tags?

{% raw %}
<p>
{% endraw %} 
is a tag and 
{% raw %}
</p>
{% endraw %} 
is a tag too. The first is a start tag and the second is an end tag. On the other hand, the following line is an element:

{% raw %}<p>This is a great day</p>{% endraw %}

This is another element: {% raw %}<div><p>This is a great day</p></div>{% endraw %}.

An attribute is a property of an element. It is written inside the start tag in the following form: <tag attribute="value">. For example the src attribute points to a file’s name and location: {% raw %}<img src="images/flower.gif" />{% endraw %}.
