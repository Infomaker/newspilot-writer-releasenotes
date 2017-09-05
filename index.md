---
layout: full-width
title: Newspilot Writer release notes
---

<div class="jumbotron">
<h1>Newspilot Writer Release notes</h1>
<p class="lead">
  This site contains release notes for Newpilot Writer and accompanying projects.
  When upgrading a servuce from a version to a higher one, <strong>please consider each consecutive release note for upgrade
  instructions</strong>. The required version for each dependency is listed in the release page for the version to upgrade to.
  <strong>Note that each dependent service may have additional dependency requirements for its dependencies</strong>.
</p>
</div>    

<h2>Newspilot Writer versions</H2>

{% for note in site.writer-releasenotes %}
<a href="{{site.baseurl}}/{{note.url}}">{{note.title}}</a><br>{% endfor %}

<h2>Editor service versions</h2>
{% for note in site.editorservice-releasenotes %}
<a href="{{site.baseurl}}/{{note.url}}">{{note.title}}</a>
{% endfor %}

