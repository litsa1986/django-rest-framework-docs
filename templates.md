Create the template file

To edit the template you will have to create a .html file to override the original one. Inside your templates directory create a directory named rest_framework_docs and inside this create the file docs.html. You can then extend/override the default template.

{% extends "rest_framework_docs/base.html" %}


---docs.html
% extends "rest_framework_docs/base.html" %}

{% block title %}Web Advertisement Business{% endblock %}
{% block logo %}<a class="navbar-brand" href="#">Documentation of Web Advertisemet Business</a>{% endblock %}
<div class="jumbotron">

  <h1><i><b>WAB</b></i></h1>
  <h3>Documentation of the Web Advertisement Business.</h3>
</div>


{% block footer %}<div class="footer">Copyright © 2016 Evangelia Grigoriadou & Kiakou Georgia.</div>{% endblock %}