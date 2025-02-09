---
layout: default
title: Fotografias
permalink: /fotografias/
photos:
  - url: https://lh3.googleusercontent.com/pw/AP1GczPdvWSg4F6k3uiLuSA5yND7tOV3Gqkkf3oRUDR-bvxume-vb9bT9xXV1E8hdnp3cnLIMLAxfZhFbls2kEfQZiP6hF17x5Q6qKF_-YN1LtsOGG818nRB=w2400
  - url: https://lh3.googleusercontent.com/pw/AP1GczMaOUnmPqkdyza8UnPTa_9bjH9oMR5SLbLWOUpNqkhZZyoYCcXQ7z4Q7xsez3Wb9hUNYl31VG5g4h-nDC9jlF6mO0noVtmxBZ2H5HtBVESDnWaG0y8p=w2400

---

### Fotografias

<div class="mosaico">

{% for photo in page.photos %}
<img src="{{ photo.url }}" alt="image" style="width:100%">
{% endfor %}

</div>

