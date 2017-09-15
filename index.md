---
layout: full-width
title: Newspilot Writer release notes
---

<div class="jumbotron">
<h1>Newspilot Writer release notes</h1>
<p class="lead">
  This site contains release notes for Newpilot Writer and accompanying projects.
</p>
<p>
  Please consider each consecutive release note when upgrading a service to a newer version, there might be
  upgrade instructions for in-betweeen releases. Each dependent service may have additional dependency requirements for its dependencies.
</p>
</div>    

<div class="release-notes">
<h3>Newspilot Writer</h3>
{% for note in site.writer-releasenotes reversed %}
{{note.releaseDate}} &nbsp;&nbsp;&nbsp; <a href="{{site.url}}{{site.baseurl}}{{note.url}}">{{note.title}}</a><br>{% endfor %}


<h3>Writer plugins</h3>
{% for note in site.plugins-releasenotes reversed %}
{{note.releaseDate}} &nbsp;&nbsp;&nbsp; <a href="{{site.url}}{{site.baseurl}}{{note.url}}">{{note.title}}</a><br>{% endfor %}
</div>


<div class="release-notes">
<h3>Editor service</h3>
{% for note in site.editorservice-releasenotes reversed %}
{{note.releaseDate}} &nbsp;&nbsp;&nbsp; <a href="{{site.url}}{{site.baseurl}}{{note.url}}">{{note.title}}</a><br>{% endfor %}
</div>


<div class="release-notes">
<h3>Concept backend</h3>
{% for note in site.conceptbackend-releasenotes reversed %}
{{note.releaseDate}} &nbsp;&nbsp;&nbsp; <a href="{{site.url}}{{site.baseurl}}{{note.url}}">{{note.title}}</a><br>{% endfor %}
</div>

<div class="release-notes">
<h3>Lambda - Image Metadata</h3>
{% for note in site.imagemetadata-releasenotes reversed %}
{{note.releaseDate}} &nbsp;&nbsp;&nbsp; <a href="{{site.url}}{{site.baseurl}}{{note.url}}">{{note.title}}</a><br>{% endfor %}

<h3>Lambda - Image Publish</h3>
{% for note in site.imagepublish-releasenotes reversed %}
{{note.releaseDate}} &nbsp;&nbsp;&nbsp; <a href="{{site.url}}{{site.baseurl}}{{note.url}}">{{note.title}}</a><br>{% endfor %}

<h3>Lambda - Image Resizing</h3>
{% for note in site.imageresizing-releasenotes reversed %}
{{note.releaseDate}} &nbsp;&nbsp;&nbsp; <a href="{{site.url}}{{site.baseurl}}{{note.url}}">{{note.title}}</a><br>{% endfor %}
</div>

<div class="release-notes">
<h3>Integration Service</h3>
{% for note in site.integrationservice-releasenotes reversed %}
{{note.releaseDate}} &nbsp;&nbsp;&nbsp; <a href="{{site.url}}{{site.baseurl}}{{note.url}}">{{note.title}}</a><br>{% endfor %}
</div>
