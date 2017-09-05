---
layout: full-width
title: Newspilot Writer release notes
---

<div class="jumbotron">
<h1>Newspilot Writer Release notes</h1>
<p class="lead">
  This site contains release notes for Newpilot Writer and accompanying projects.
</p>
<p>
  Please consider each consecutive release note when upgrading a service to a newer version, there might be
  upgrade instructions for in-betweeen releases. Each dependent service may have additional dependency requirements for its dependencies.
</p>
</div>    

<div class="release-notes">
<h2>Newspilot Writer</H2>
{% for note in site.writer-releasenotes reversed %}
<a href="{{site.url}}{{site.baseurl}}{{note.url}}">{{note.title}}</a><br>{% endfor %}

<h2>Writer plugins</h2>
{% for note in site.plugins-releasenotes reversed %}
<a href="{{site.url}}{{site.baseurl}}{{note.url}}">{{note.title}}</a><br>{% endfor %}
</div>

<div class="release-notes">
<h2>Editor service</h2>
{% for note in site.editorservice-releasenotes reversed %}
<a href="{{site.url}}{{site.baseurl}}{{note.url}}">{{note.title}}</a><br>{% endfor %}
</div>

<div class="release-notes">
<h2>Concept backend</h2>
{% for note in site.conceptbackend-releasenotes reversed %}
<a href="{{site.url}}{{site.baseurl}}{{note.url}}">{{note.title}}</a><br>{% endfor %}
</div>
