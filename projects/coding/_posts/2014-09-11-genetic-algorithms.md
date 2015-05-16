---
layout: page
title: Genetic Algorithms
thumbnail: /assets/thumbnails/optimizer.png
desc: A simple network optimizer using genetic algorithms created as a learning exercise
categories : [projects, coding]
---

Genetic Algorithms
=======
Github: [github.com/A-Malone/genetic-team-optimiaztion](https://github.com/A-Malone/genetic-team-optimiaztion)

In first year, one of my biggest side projects was designing genetic algorithms to solve a variety of problems. What drew me to this branch of optimization is that the computer does a lot of the work, evolving the ideal solution to the problem that it is given. The programmer need only frame the problem in a way that the desired solution is favored. This intrigued me from a biological perspective, since it is in essence using the concept of evolution on a scale that produces results in a reasonable amount of time. I had previously worked as a synthetic biology researcher, and was able to transfer my experience from that domain to understanding how these algorithms worked, and this allowed me to extend the concept to develop solutions to problems of my choosing.

I started small, first creating algorithms that could solve problems that I knew could be solve deterministically, developing algorithms to maximize the algebraic sum of a list, or sort a list. I then took what I learned from those projects and created a genetic algorithm to evolve the best possible tick-tack-toe player. While interesting conceptually, using a genetic algorithm offered no benefits over a deterministic algorithm for these problems, and produced results that were not always the optimal solution.

<div class="center">
    <div>
        <img src="{{ site.baseurl }}/assets/cross-over.png" style="width: height:400px;">
        <p>The cross-over function from my genetic team optimizer</p>
    </div>
</div>


Where I really started to see the benefits of a genetic algorithm is when I started trying to create a system to create optimal teams based on preferences of each of the members. In my design class a similar algorithm had been used to place us in teams, and dis-satisfied with the results, I set out to make my own. Using randomly generated members and preferences, the resulting algorithm was capable of producing team arrangements that granted 30-100% more preferences than the algorithm used in my class, while also maximizing the personality diversity of each team based on the simulated results of a survey. In hindsight, this project could have been solved deterministically using linear programming, however in this case, genetic algorithms have the advantage of fast and reasonable approximations. More exact results from the trial runs, and the source code can be found by following the link below the title.
