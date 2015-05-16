---
layout: page
title: PsiBot
desc: "A networked 2.5D platformer made as a class project"
thumbnail: "/assets/thumbnails/psibot.bmp"
categories : [projects, coding]
---

PsiBot
=======
Github: [github.com/A-Malone/psi-bot](https://github.com/A-Malone/psi-bot)

The culminating project in my grade 12 computer science course was, as a design team, to create and pitch a software product, completing the entire software design cycle. Many parallels can be drawn between this and the kickstarter package I completed for Praxis I in first year, however one main difference was that the product did not have to be the solution to a problem so much as as it had to fill a need. Playing to our strengths, our team selected to develop a game, which we eventually named PsiBot. Framing the problem as the need to develop a unique game, we set about brainstorming divergent concepts. In the end, we selected a multiplayer side-scrolling game, where players could place blocks, either to co-operatively navigate complex terrain, or to put their opponents further behind. A screenshot of a prototype version is shown below.

<div class="center">
    <div>
        <img src="{{ site.baseurl }}/assets/psibot1.bmp" style="width: 600px; height:450px;">
        <p>The minimum viable prototype version of PsiBot</p>
    </div>
</div>
\\
My main focus for this project was the networking aspect of the game, which I had some prior experience with. Previously, I had worked on several smaller side-projects which were networked, but never before had I taken on a project as ambitious as synchronizing hundreds of entities in real time. Doing some research, I found that there are several methods of doing this, exemplified in different games. After comparing the advantages and shortfalls of the different models, I selected a client-server model in which all of the logic is computed on the server, while the client renders the data given. This exemplifies design for user experience, since such an approach ensures that all players remain synchronized perfectly, eliminating frustrating discrepancies between clients. User experience is a multiple faceted design goal however, and usually choosing a networking model like this would limit the render rate of the game, which hinders the user's experience. Implementing a predictive motion algorithm solved this problem and overall the game was very fluid, impressing the panel of judges.

Software projects like this exemplify iterative design, since the product is constantly being tested and evaluated, refining the application until it meets all of the requirements. This project in particular is a perfect example because different sections of the game were prototyped and refined independently and then combined into a intermediate product which was then polished until a high fidelity prototype was ready. This prototype was then tested by members of the public, whose feedback went into shaping the final product. This repeated polishing and prototyping has since become one of the main characteristics of my engineering design process.

The technical experience I gained in this project has proved to be just as valuable, as I learned how to produce three-dimensional graphics, code realistic physics, accurately interpolate between data points, and keep hundreds of entities synchronized accross multiple clients. Most importantly, I dsicovered that the more you learn while making a project, the more rewarding it is to see it work  in the end. I have since strived to push myself further beyond the limits of my knowledge, whether in my side-projects, or at hackathons I've attended.
