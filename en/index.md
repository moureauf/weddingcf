---
layout: default
lang: en
ref: index
translation_link: /fr
---

<div class="home">

<div class="site-header-container {% if site.cover %}has-cover{% endif %}" {% if site.cover %}style="background-image: url({{ site.cover | prepend: site.baseurl }});"{% endif %}>
  <div class="scrim {% if site.cover %}has-cover{% endif %}">
    <header class="site-header">
      <h1 class="title">{{ site.title }}</h1>
      {% if site.subtitle %}<p class="subtitle">{{ site.subtitle }}</p>{% endif %}
    </header>
  </div>
</div>

<body>
  <div class="page-content">
    <p>
      Catherine and François will be getting married at Holm House, Penarth.
      Full details of the event can be found on this site.
      Please RSVP no later than 1 March.
    </p>
  </div>
</body>

</div>