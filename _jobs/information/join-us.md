---
title: Join Us
permalink: /join/

lede_markdown: We are looking for top talent in design, development, data analytics, user research, and product management.

# DON'T EDIT ANYTHING BETWEEN THE <div> TAGS BELOW!
---

<div class="hidden-md hidden-lg hidden-xl" role="menu">
{% assign new_collection = site.collections | where: "title", page.nav_from_collection | first %}
{% assign items = new_collection.docs | sort: "url" | sort: "position" %}
{% assign base_path = page.nav_from_collection | downcase | prepend: "/_" | append: "/"  %}
{% include recursive-nav.html items=items base_path=base_path  %}
</div>

We are a team of passionate, civic-minded professionals who work to bring the principles, values, and practices of the technology sector into government with one goal in mind: to make the lives of Austin residents’ better.

And, we are growing.

We’re currently looking for practitioners in [Content Strategy](https://cityofaustin.github.io/innovation-fellows/join/positions/content-strategist/) and and [Visual Design](https://cityofaustin.github.io/innovation-fellows/join/positions/ui-designer/) to work on the future of [austin.gov](http://alpha.austin.gov). A [Service Designer](https://cityofaustin.github.io/innovation-fellows/join/positions/service-designer/) to lead transformation projects within our Office of Public Health, and front-end, back-end, and full-stack developers to support [austin.gov](http://alpha.austin.gov) and other open-source projects.

Our terms are for 12 months of full-time work (40 hours each week), with opportunities to apply for permanent positions at the city.

If none of our current openings are the right fit for you, connect with us to be notified of future openings, or [send us your resume](https://jobs.lever.co/austintexas/7367149f-2727-4c51-82fe-124ad57f3a28).


--



#### Get Updates
{% include bloomfire-form.html %}
