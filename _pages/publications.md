---
permalink: /publications/
title: "Publications"
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


## Conference Papers
- [Emotion Granularity from Text: An Aggregate-Level Indicator of Mental Health](https://arxiv.org/pdf/2403.02281). Vishnubhotla, K., **Teodorescu, D.**, Feldman, M., Lindquist, K., Mohammad, S. In *Proceedings of the Empirical Methods on Natural Language Processing (EMNLP 2024 Main)*, Miami, Florida.

- [Language and Mental Health: Measures of Emotion Dynamics from Text as Linguistic Biosocial Markers](https://aclanthology.org/2023.emnlp-main.188/). **Teodorescu, D.**, Cheng, T., Fyshe, A., Mohammad, S. In *Proceedings of the Empirical Methods on Natural Language Processing (EMNLP 2023 Main)*, Singapore.

- [Evaluating Emotion Arcs Across Languages: Bridging the Global Divide in Sentiment Analysis](https://aclanthology.org/2023.findings-emnlp.271/). **Teodorescu, D.**, Mohammad, S. In *Proceedings of the Empirical Methods on Natural Language Processing (EMNLP 2023 Findings)*, Singapore.

- [Cree Corpus: A Collection of nêhiyawêwin Resources](https://aclanthology.org/2022.acl-long.440/). **Teodorescu, D.**, Matalski, J., Lothian, D., Barbosa, D., & Demmans Epp, C. In *Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics (ACL 2022)*, Dublin, Ireland.

## Journal Papers

- [Tracking the dynamic word-by-word incremental reading through multi-measures]. (2024). Lin, C., Oralova, G., Perfetti, C., Demmans Epp, C., Fyshe, A., Clark, S., **Teodorescu, D.**, Helfrich, M. J. In *Journal of Experimental Psychology: Learning, Memory, and Cognition*.

- [Quantifying Depression-Related Language on Social Media During the COVID-19 Pandemic](https://ijpds.org/article/view/1716). (2022). Davis, B., McKnight, D. E., **Teodorescu, D.**, Quan-Haase, A., Chunara, R., Fyshe, A. and Lizotte, D. J. In *International Journal of Population Data Science*.

## Workshop Papers

- [Utterance Emotion Dynamics in Children’s Poems: Emotional Changes Across Age](https://aclanthology.org/2023.wassa-1.35/). **Teodorescu, D.**, Fyshe, A., Mohammad, S. In *Proceedings of the 13th Workshop on Computational Approaches to Subjectivity, Sentiment, & Social Media Analysis (WASSA)*, July 2023, Toronto, Canada.

- [UAlberta at LSCDiscovery: Lexical Semantic Change Detection via Word Sense Disambiguation](https://aclanthology.org/2022.lchange-1.19/). **Teodorescu, D.**, von der Ohe, S., & Kondrak, G. In *Proceedings of the 3rd Workshop on Computational Approaches to Historical Language Change (LChange’22)*, Dublin, Ireland.
