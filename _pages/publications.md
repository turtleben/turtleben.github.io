---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}
{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}
You can also find my articles on <a href="{{author.googlescholar}}">my Google Scholar profile</a>.
{: .notice--info}

<!---
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
-->

<br>

Conference Papers
======
* 2023
### [Rethink before Releasing your Model: ML Model Extraction Attack in EDA](https://dl.acm.org/doi/abs/10.1145/3566097.3567896)
     * [pdf](/files/ASPDAC23_Model_extraction.pdf){: .btn} 
     * **Chen-Chia Chang**, Jingyu Pan, Zhiyao Xie, Jiang Hu, and Yiran Chen
     * Proceedings of IEEE/ACM Asia and South Pacific Design Automation Conference (ASP-DAC), 2023.
