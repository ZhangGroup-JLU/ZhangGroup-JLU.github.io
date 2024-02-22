---
title: "吉林大学建设工程学院张文教授团队 - 科研成果"
layout: gridlay
excerpt: "建设工程学院张文教授团队 at 吉林大学（朝阳校区）."
sitemap: false
permalink: /publications/
---


# 科研成果

---

### 迄今，共发表60余篇SCI与EI检索论文，具体如下：

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="row">
 	<img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="25%" style="float: right" />
  <p><a class="pub1" href="{{ publi.link.url }}">{{ publi.title }}</a></p>
  <a class="pub2"> {{ publi.link.display }} </a>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>

---

<div>

检索论文全文，请前往 <a class="regtext" href="https://www.researchgate.net/profile/Wen-Zhang-120">ResearchGate</a>.
<br><br><br>

</div>

