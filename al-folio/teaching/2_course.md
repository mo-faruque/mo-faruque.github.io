<!-- ---
layout: page
title: vlsi
description: a course with no image
img:
importance: 1
category: collection

syllabus: /assets/course1-syllabus.pdf
slides: 
  - /assets/course1-lecture1.pdf  
  - /assets/course1-lecture2.pdf
---

<div class="syllabus">

  <h2>Syllabus</h2>

  <p>
    <a href="{{ page.syllabus }}" class="btn btn-primary">
      Download Course Syllabus
    </a> 
  </p>

</div>

<div class="lectures">

  <h2>Lectures & Slides</h2>

  <ul>
    {% for slide in page.slides %}
    <li>
      <a href="{{ slide | relative_url }}">Lecture Slides {{ forloop.index }}</a> 
    </li>
    {% endfor %}
  </ul>

</div> -->