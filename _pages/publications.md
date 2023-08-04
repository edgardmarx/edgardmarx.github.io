---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

*Selected Publications*

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

**Journal Papers**

* Survey on challenges of question answering in the Semantic Web <br>
  K. Höffner, S. Walter, **<u>E. Marx</u>**, R. Usbeck, J. Lehmann, A.C.N. Ngomo <br>
  Semantic Web Journal, Volume 8, 2017 \[[pdf](https://content.iospress.com/articles/semantic-web/sw247)\]  

* SINA: Semantic Interpretation of User Queries for Question Answering on Interlinked Data <br>
  S. Shekarpour, **<u>E. Marx</u>**, A.C. Ngonga Ngomo, S. Auer <br>
  Journal of Web Semantics, Volume 30, 2015 \[[pdf](https://www.sciencedirect.com/science/article/abs/pii/S1570826814000468)\]

**Conference Papers**

* RQUERY: Rewriting Natural Language Queries on Knowledge Graphs to Alleviate the Vocabulary Mismatch Problem <br>
  S. Shekarpour,  **<u>E. Marx</u>**, S. Auer <br>
  AAAI 2017 \[[pdf](https://openreview.net/forum?id=1tHAZRqftM)\] \[[code](https://github.com/jumxglhf/ParetoGNN)\]

* ROCKER: A refinement operator for key discovery <br>
  T. Soru, **<u>E. Marx</u>**, A.C. Ngonga Ngomo <br>
  WWW 2015 \[[pdf](https://openreview.net/forum?id=1tHAZRqftM)\] \[[code](https://github.com/jumxglhf/ParetoGNN)\]



# {% include base_path %}

# {% for post in site.publications reversed %}
# {% include archive-single.html %}
# {% endfor %}
