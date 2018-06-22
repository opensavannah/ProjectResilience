---
title: Join Us
permalink: /join/

lede_markdown: We are a team of passionate, civic-minded professionals who work to bring the principles, values, and practices of the technology sector into government with one goal in mind: to improve the lives of Austin's residents.

# DON'T EDIT ANYTHING BETWEEN THE <div> TAGS BELOW!
---

<div class="hidden-md hidden-lg hidden-xl" role="menu">
{% assign new_collection = site.collections | where: "title", page.nav_from_collection | first %}
{% assign items = new_collection.docs | sort: "url" | sort: "position" %}
{% assign base_path = page.nav_from_collection | downcase | prepend: "/_" | append: "/"  %}
{% include recursive-nav.html items=items base_path=base_path  %}
</div>

We’re currently looking for [Content Strategists](/join/positions/content-strategist/) and a [Visual Designer](/join/positions/visual-designer/) to contribute to the future of austin.gov, and a [Service Designer](/join/positions/service-designer/) to lead transformation projects within our Office of Public Health.

We're also hiring [front-end](/join/positions/full-stack-developer/), [back-end](/join/positions/back-end-developer/), and [full-stack developers](/join/positions/front-end-developer/) to support austin.gov and other open-source projects.

Our terms are for 12 months of full-time work (40 hours each week), with opportunities to apply for permanent positions at the city. [Learn more about benefits](/join/information/benefits/)



--



#### Get Updates
{% include bloomfire-form.html %}
