---
layout: page
title: About
permalink: /about/
weight: 3
---

<h1>About Me</h1>

Hi, I am Stefan Radlwimmer, an Austrian Game Engineering Enthusiast working at <a href='https://developer.vuforia.com/home/'>Vuforia, a PTC Technology</a>.<br/><br/>
I currently work as Senior Augmented Developer responsible for <a href='https://www.ptc.com/en/products/vuforia/vuforia-expert-capture'>Vuforia Expert Capture</a> and 
a proprietary AR Framework based on Unity Engine.

<ul id="profileTabs" class="nav nav-tabs">
    <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#skills" style="font-size:20px">Skills</a></li>
    <li class="nav-item"><a class="nav-link active" data-toggle="tab" href="#work" style="font-size:20px">Work</a></li>
    <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#education" style="font-size:20px">Education</a></li>
</ul>
<div class="tab-content">
    <div class="tab-pane" id="skills">
        <h2>Languages</h2>
        <div class="row">
            {% include about/skills.html title="Programming" source=site.data.skills-programming %}
            {% include about/skills.html title="Natural" source=site.data.skills-language %}
        </div>
    </div>
    
    <div class="tab-pane active" id="work">
        <h2>Work experience</h2>
        <div class="row">
            {% include about/timeline-work.html %}
        </div>
    </div>
    
    <div class="tab-pane" id="education">
        <h2>Education</h2>
        <div class="row">
            {% include about/timeline-education.html %}
        </div>
    </div>
</div>