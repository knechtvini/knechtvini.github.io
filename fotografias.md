---
layout: default
title: Fotografias
permalink: /fotografias/
photos:
  - url: https://lh3.googleusercontent.com/pw/AP1GczPdvWSg4F6k3uiLuSA5yND7tOV3Gqkkf3oRUDR-bvxume-vb9bT9xXV1E8hdnp3cnLIMLAxfZhFbls2kEfQZiP6hF17x5Q6qKF_-YN1LtsOGG818nRB=w2400
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

