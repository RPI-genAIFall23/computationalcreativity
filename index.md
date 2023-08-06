---
layout: home
title: 🏠 Home
nav_exclude: false
nav_order: 1
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{{ site.staffersnobio }}

{: .success } 
> The first day of class is on Monday, August 28, at 4 PM in JEC 4104.  Materials on this site are in flux until then!

Below, you find class notes from each lecture by clicking the ✏️ emojis and watch Mediasite video recordings by clicking the 🎥 emojis.

[Jump to the current week](#module-1-introduction){: .btn }

{% for module in site.modules %}
{{ module }}
{% endfor %}
