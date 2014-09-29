---
layout: page
title: Truss Bridge Design
permalink: /projects/design/trussdesign/
---

Truss Bridge Design
====

 One of the first projects of the year in Engineering Science is the steel truss bridge design project, in which students are required to design a pedestrian truss bridge in teams of three to meet a specific set of requirements. We decided that the main stakeholders for this project were the users and the city, who contracted us to build the bridge. As a group, my team agreed that our main design values for this project would be safety and cost, hence the optimal solution would be the least expensive bridge that did not compromise the safety of the stakeholders. Analyzing the problem and applying my knowledge of truss structures, I determined that certain geometries of trusses could be modeled using series, and therefore a computer simulation could easily be run to choose the least expensive design. Through research, I was able to find the optimal ratios for these bridge geometries, and using these I compared the cost of each, eventually choosing a Pratt truss as the final geometry.

<div class="center">
    <div>
        <img src="{{ site.baseurl }}/assets/trussbridge.jpg" style="width: height:400px;">
        <p>The technical drawings detailing the design of the bridge</p>
    </div>
</div>

Using a python script I created, I was then able to optimize each of the members of the truss individually, eventually yielding a design that was 22% cheaper than any other design in the section, while exceeding the safety criteria laid out in the assignment. Design for safety does not just consist of whether it performs it's intended function correctly, but also whether it is safe for regular use by the stakeholders. In the case of a bridge, bearing load is necessary, but not sufficient. More factors have to be taken into consideration. In our truss design, for example, the minimum safe height and spacing of the handrails was researched so that it was safe for pedestrians. The structure was also designed so that resonance caused by pedestrians or wind did not cause the bridge to fail.

I consider this one of my first real exposures to engineering design, since in order to solve the problem, I had to adopt an iterative approach to concept selection. In most of my previous work, initial designs were compared and one option was chosen, following which no more comparison was done. This was not the case with this project. The first design we selected was in fact an arch, however after some preliminary calculations, we discovered that this shape was highly inefficient due to the high cost of compression members, and were forced to change designs. From this point on, we used the approach described in the paragraphs above, in which different designs were compared, optimized, then compared again, until a superior design emerged. This experience is reflected in the iterative nature of my design process, in which concepts are in constant evolution.