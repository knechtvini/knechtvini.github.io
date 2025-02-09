---
layout: default
title: Fotografias
permalink: /fotografias/
photos:
  - url: https://lh3.googleusercontent.com/pw/AP1GczPdvWSg4F6k3uiLuSA5yND7tOV3Gqkkf3oRUDR-bvxume-vb9bT9xXV1E8hdnp3cnLIMLAxfZhFbls2kEfQZiP6hF17x5Q6qKF_-YN1LtsOGG818nRB=w2400
  - url: https://lh3.googleusercontent.com/pw/AP1GczMaOUnmPqkdyza8UnPTa_9bjH9oMR5SLbLWOUpNqkhZZyoYCcXQ7z4Q7xsez3Wb9hUNYl31VG5g4h-nDC9jlF6mO0noVtmxBZ2H5HtBVESDnWaG0y8p=w2400
  - url: https://lh3.googleusercontent.com/pw/AP1GczNbMqcdWlnrE1n7IcDvwr8sk9yLfdz851A711C3hnsOzzU6pUOVREaXV3KinfLc5kTfx9mgeQz4xVW4NG10rrKOJgDOZ6G13jY6F5TIRI16Gsg6Bbi_=w2400
  - url: https://lh3.googleusercontent.com/pw/AP1GczNw76LVNDQ0swd84MUo_wyBen0fY-HbM0yhebqNLy2lOu13CyLFyYZBcoHnuzhOyEehSPJoLwSgFGWmdsS0PnbAYHcgOAWSxmjRmV4HF_B8m8VtnNf8=w2400
  - url: https://lh3.googleusercontent.com/pw/AP1GczPUA3cLZSC_oB828ogM-YQbn9-zxeTGiwT5cb-XoTSf1TcpIA8c-eZLmYUCCwNVz3qOOFAysKlrSk8tQeR3Fa9LhzGU1NhAMByCCi7uPzcwWcbGeLSM=w2400

---

### Fotografias

<div class="mosaico">

{% for photo in page.photos %}
<img src="{{ photo.url }}" alt="image" style="width:100%">
{% endfor %}

</div>

