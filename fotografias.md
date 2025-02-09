---
layout: default
title: Fotografias
permalink: /fotografias/
photos:
  - url: https://drive.google.com/file/d/1_AxDiWCSx6MbMMor__EuzvZokfgc0rM8/view?usp=sharing
  - url: https://upload.wikimedia.org/wikipedia/commons/thumb/5/59/William_Garrow2.jpg/125px-William_Garrow2.jpg
  - url: https://upload.wikimedia.org/wikipedia/commons/thumb/7/76/Lithobates_sylvaticus_%28Woodfrog%29.jpg/280px-Lithobates_sylvaticus_%28Woodfrog%29.jpg
  - url: https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Conifer_forest.jpg/250px-Conifer_forest.jpg
  - url: https://lh3.googleusercontent.com/pw/AP1GczMRWDhTxbwLBLHxQ1NuCJgorthfgYVtxnJxa7j0U9ovaZRuivr4b_Fmf0brkkGrBLvMFNVKKCnECRYi1ICPWzCkE0uOo9lXuU9uL7QiU8VDD60sMROK=w2400
---

### Fotografias

<div class="mosaico">

{% for photo in page.photos %}
<img src="{{ photo.url }}" alt="image" style="width:100%">
{% endfor %}

</div>

