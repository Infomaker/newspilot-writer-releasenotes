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

<h2>Newspilot Writer versions</H2>

{% for note in site.writer-releasenotes %}
<a href="{{site.url}}{{site.baseurl}}{{note.url}}">{{note.title}}</a><br>{% endfor %}

<h2>Editor service versions</h2>
{% for note in site.editorservice-releasenotes %}
<a href="{{site.url}}{{site.baseurl}}{{note.url}}">{{note.title}}</a>
{% endfor %}

