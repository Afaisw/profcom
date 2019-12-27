---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<!-- Masthead -->
{% include header.html %}
<!-- Icons Grid -->
{% include iconsection.html title="minContent" data=site.data.minicontent %}

<!-- Image Showcases -->
{% include imagesection.html %}

<!-- Testimonials -->
{% include testisection.html title="Crew" data=site.data.crew %}

<!-- Call to Action -->
{% include signup.html %}