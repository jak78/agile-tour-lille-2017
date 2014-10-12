---
layout: page
title: Sponsors et partenaires
permalink: /sponsors/
---

# Sponsors Platine
<div class="row">
{% for sponsor in site.data.sponsors.platinum %}
   <div class="col-md-4 col-xs-6 sponsor">
    <a href="https://github.com/{{ sponsor.url }}">
    <img src="{{sponsor.logo}}" alt="{{sponsor.name}}"/>
    {{ sponsor.name }}
    </a>
   </div>
  </li>
{% endfor %}
</div>

# Sponsors Or
<div class="row">
{% for sponsor in site.data.sponsors.gold %}
   <div class="col-md-4 col-xs-6 sponsor">
    <a href="https://github.com/{{ sponsor.url }}">
    <img src="{{sponsor.logo}}" alt="{{sponsor.name}}"/>
    {{ sponsor.name }}
    </a>
   </div>
  </li>
{% endfor %}
</div>

# Sponsors Media
<div class="row">
{% for sponsor in site.data.sponsors.media %}
   <div class="col-md-4 col-xs-6 sponsor">
    <a href="https://github.com/{{ sponsor.url }}">
    <img src="{{sponsor.logo}}" alt="{{sponsor.name}}"/>
    {{ sponsor.name }}
    </a>
   </div>
  </li>
{% endfor %}
</div>
