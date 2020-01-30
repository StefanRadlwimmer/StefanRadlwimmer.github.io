---
layout: page
title: About
permalink: /about/
weight: 3
---

<h1>About Me</h1>

Hi, I am Stefan Radlwimmer, an Austrian Game Developer working at Cyberith GmbH.<br/>
I currently work as Hardware-, Firmware-, Software- & Game-Developer on the <a href='https://www.cyberith.com/virtualizer-elite/'>Virtualizer Elite 2</a>, 
responsible for everything from hardware sensors to game engine integration. 

<ul id="profileTabs" class="nav nav-tabs">
    <li class="nav-item"><a class="nav-link active" data-toggle="tab" href="#skills" style="font-size:20px">Skills</a></li>
    <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#work" style="font-size:20px">Work</a></li>
    <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#education" style="font-size:20px">Education</a></li>
</ul>
<div class="tab-content">
    <div class="tab-pane active" id="skills">
        <h2>Skills</h2>
        <div class="row">
            {% include about/skills.html title="C++" source=site.data.cpp-skills %}
            {% include about/skills.html title="C#" source=site.data.cs-skills %}
        </div>
        
        <div class="row">
            {% include about/skills.html title="Python" source=site.data.python-skills %}
            {% include about/skills.html title="Game Engines" source=site.data.engine-skills %}
        </div>
    </div>
    
    <div class="tab-pane" id="work">
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