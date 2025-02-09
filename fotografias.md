---
layout: default
title: Fotografias
permalink: /fotografias/
photos:
  - url: https://lh3.googleusercontent.com/pw/AP1GczPdvWSg4F6k3uiLuSA5yND7tOV3Gqkkf3oRUDR-bvxume-vb9bT9xXV1E8hdnp3cnLIMLAxfZhFbls2kEfQZiP6hF17x5Q6qKF_-YN1LtsOGG818nRB=w2400
  - url: https://lh3.googleusercontent.com/pw/AP1GczMaOUnmPqkdyza8UnPTa_9bjH9oMR5SLbLWOUpNqkhZZyoYCcXQ7z4Q7xsez3Wb9hUNYl31VG5g4h-nDC9jlF6mO0noVtmxBZ2H5HtBVESDnWaG0y8p=w2400
  - url: https://lh3.googleusercontent.com/pw/AP1GczOzUEYKQ7zj052qYtFz6Dhl2rkR0cZ4I3plXQzvdH5VY8mqc0dkz9M6GB9Fmbxlto92UB01_5SmbvX3kj6RdS71FAlKBxcLTsO4Zjyi_kdaQbotwtlR=w2400
AP1GczMRWDhTxbwLBLHxQ1NuCJgorthfgYVtxnJxa7j0U9ovaZRuivr4b_Fmf0brkkGrBLvMFNVKKCnECRYi1ICPWzCkE0uOo9lXuU9uL7QiU8VDD60sMROK=w2400

---

### Fotografias

<div class="mosaico">

{% for photo in page.photos %}
<img src="{{ photo.url }}" alt="image" style="width:100%">
{% endfor %}

</div>

