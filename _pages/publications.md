---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

### [Rethink before Releasing your Model: ML Model Extraction Attack in EDA](https://dl.acm.org/doi/abs/10.1145/3566097.3567896)
     * [Preprint](/files/ASPDAC23_Model_extraction.pdf){: .btn} 
     * **Chen-Chia Chang**, Jingyu Pan, Zhiyao Xie, Jiang Hu, and Yiran Chen
     * Proceedings of IEEE/ACM Asia and South Pacific Design Automation Conference (ASP-DAC), 2023.
