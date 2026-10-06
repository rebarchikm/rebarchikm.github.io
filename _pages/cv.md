---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

{% assign cv_pdf = "/files/Rebarchik_CV.pdf" | prepend: base_path %}

<p><a class="btn" href="{{ cv_pdf }}" download>Download CV (PDF)</a></p>

<object class="cv-viewer" data="{{ cv_pdf }}#view=FitH" type="application/pdf">
  <p>Your browser cannot display the PDF here. <a href="{{ cv_pdf }}">Open the CV in a new tab</a> instead.</p>
</object>
