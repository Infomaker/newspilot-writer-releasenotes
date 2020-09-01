---
layout: full-width
title: Naviga Writer release notes
---

<div class="jumbotron">
  <h1>Naviga Writer release notes have moved!</h1>
  <p class="lead">
    This site used to contain release notes for Naviga Writer and accompanying projects. These now exist here:
    
    * [Naviga Writer Release Notes](https://docs.infomaker.io/writer/release-notes)
  </p>
  <p>
    Release notes for EditorService still live here for legacy reasons.
  </p>
</div>

<div class="release-notes">
<h3>Editor service</h3>
{% for note in site.editorservice-releasenotes reversed %}
{{note.releaseDate}} &nbsp;&nbsp;&nbsp; <a href="{{site.url}}{{site.baseurl}}{{note.url}}">{{note.title}}</a><br>{% endfor %}
</div>