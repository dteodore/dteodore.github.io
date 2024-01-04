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

Cree Corpus: A Collection of nêhiyawêwin Resources

venue: 'Association for Computational Linguistics'

citation: 'Teodorescu, D., Matalski, J., Lothian, D., Barbosa, D., & Demmans Epp, C. (2022). Cree corpus: A Collection of nêhiyawêwin Resources. Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers).https://doi.org/10.18653/v1/2022.acl-long.440'

## Journal Papers

Quantifying Depression-Related Language on Social Media During the COVID-19 Pandemic

venue: 'International Journal of Population Data Science'

citation: 'Davis, B., McKnight, D. E., Teodorescu, D., Quan-Haase, A., Chunara, R., Fyshe, A. and Lizotte, D. J. (2022) “Quantifying Depression-Related Language on Social Media During the COVID-19 Pandemic”, International Journal of Population Data Science, 5(4). doi: 10.23889/ijpds.v5i4.1716.'

## Workshop Papers

Utterance Emotion Dynamics in Children’s Poems: Emotional Changes Across Age

venue: 'Proceedings of the 13th Workshop on Computational Approaches to Subjectivity, Sentiment, & Social Media Analysis'

citation: 'Teodorescu, D., Fyshe, A., Mohammad, S. (2023). Utterance Emotion Dynamics in Children’s Poems: Emotional Changes Across Age. Proceedings of the 13th Workshop on Computational Approaches to Subjectivity, Sentiment, & Social Media Analysis. DOI: 10.18653/v1/2023.wassa-1.35'

UAlberta at LSCDiscovery: Lexical Semantic Change Detection via Word Sense Disambiguation

venue: 'Proceedings of the 3rd Workshop on Computational Approaches to Historical Language Change'

citation: 'Teodorescu, D., von der Ohe, S., & Kondrak, G. (2022). UAlberta at LSCDiscovery: Lexical Semantic Change Detection via Word Sense Disambiguation. Proceedings of the 3rd Workshop on Computational Approaches to Historical Language Change. https://doi.org/10.18653/v1/2022.lchange-1.19'
