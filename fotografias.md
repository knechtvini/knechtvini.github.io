---
layout: default
title: Fotografias
permalink: /fotografias/
photos:
  - url: https://lh3.googleusercontent.com/pw/AP1GczMatyaeRhcMWkXHE1oFV0rPHKQPB2G0BxWl17Ed2ThjL9rOq5cagCgzv_lFU-0GM9I5tjy5dXKkR5ad2dbcVxwFj8x_hOFqFqPjyhwgeFrxFwKWXN0v7CwuA_72Ji_ak1T59vtSj8nJfgJJsYOITxGEGQ=w1291-h968-s-no-gm?authuser=0
  - url: https://upload.wikimedia.org/wikipedia/commons/thumb/5/59/William_Garrow2.jpg/125px-William_Garrow2.jpg
  - url: https://upload.wikimedia.org/wikipedia/commons/thumb/7/76/Lithobates_sylvaticus_%28Woodfrog%29.jpg/280px-Lithobates_sylvaticus_%28Woodfrog%29.jpg
  - url: https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Conifer_forest.jpg/250px-Conifer_forest.jpg
---

### Fotografias

<div class="mosaico">

{% for photo in page.photos %}
<img src="{{ photo.url }}" alt="image" style="width:100%">
{% endfor %}

</div>

