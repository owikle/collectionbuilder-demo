---
title: About
layout: about
permalink: /about.html
# Edit the markdown on in this file to describe your collection
---

{% include about/jumbotron.html %}

{% include feature/nav-menu.html sections="About the Collection;About the About Page" %}

## About the Collection

This site is generated using [`collectionbuilder-gh`](https://collectionbuilding.github.io/gh/), a project to create a free and simple digital collection using [GitHub Pages](https://pages.github.com/) from: 

- a CSV of collection metadata
- a folder of JPEG images or PDF documents

The base site features four objects from the University of Idaho Library's [Digital Collections](https://www.lib.uidaho.edu/digital). 


## About the About Page

We want to make About pages exciting again, and easy to build. 

The CollectionBuilder about page features a narrowed column with its own (optional) menu, featured content, and some technical information. 

To build one, a user writes in [Markdown](https://guides.github.com/features/mastering-markdown/) and includes  content from the site, as well as typical [Bootstrap](https://getbootstrap.com/) features like cards and modals, using code snippets like those detailed below. 

(Each included file has several options, which are documented in the files themselves. I've given the content widths of 25% and 50% to save space, but you can feature the entire image or document.) 


- Image --> {% raw %} `{% include feature/item-figure.html objectid="demo_001" width="25" %}`{% endraw %}

{% include feature/item-figure.html objectid="demo_001" width="25" %}

- PDF -- > {% raw %}  `{% include feature/item-pdf-embed.html objectid="demo_002"  width="25" %}`
  {% endraw %}

 {% include feature/item-pdf-embed.html objectid="demo_002" width="25" %}

- Video: {% raw %} `{% include feature/item-video-embed.html objectid="demo_004" %}`
 {% endraw %}

{% include feature/item-video-embed.html objectid="demo_004" %}

- Card -- >  {% raw %}`{% include feature/card.md header="This is a Card" header="The card is centered" text="The card features an image from the collection as a cap" objectid="demo_004" width="25" centered="true" %}`
 {% endraw %}

{% include feature/card.md header="This is a Card" header="The card is centered" text="The card features an image from the collection as a cap" objectid="demo_004" width="25" centered="true"  %}

- Buttons -- > {% raw %}`{% include feature/button.md text="this is button with secondary coloring" color="secondary"  %}`{% endraw %}

{% include feature/button.md text="This button has 'secondary' coloring" color="secondary" %}
  
- Alerts -- > {% raw %}`{% include feature/alert.md text="this is an alert that 'warns' a user" color="warning" align="center"  %}`
 {% endraw %}

 {% include feature/alert.md text="This is an alert that 'warns' a user with centrally aligned text." color="warning" align="center"  %}


- Modals -- > {% raw %}`{% include feature/modal.md button="This is a modal using a 'primary' colored button to invite clicking" title="when clicked:" text="A Modal will pop out a box with some more information" color="primary"  %}`{% endraw %}

{% include feature/modal.md button="This is a modal using a 'primary' colored button to invite clicking" title="When clicked:" text="A Modal will pop out a box with some more information" color="primary"  %}


We hope this makes it easier for site builders to develop the collection AND add interesting and engaging contextual information.  

