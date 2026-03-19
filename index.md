---
title: Kammerchor Innsbruck
description: Aktuelle Konzerttermine des Kammerchor Innsbruck.
---

<img src="/assets/kammerchor.jpg" alt="Kammerchor Innsbruck" style="width:100%">

# Nächste Veranstaltungen

{% capture included %}
{% include_relative aktuelles.md %}
{% endcapture %}

{{ included | markdownify | replace: '<h2', '<h3' | replace: '</h2', '</h3' }}
