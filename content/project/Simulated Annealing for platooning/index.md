---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Optimization fuel-consuming in platooning of vehicles by using sophisticated meta-heuristics"
summary: "Simulated Annealing for Platooning"
authors: [Abdul Hakmeh]
tags: [Metaheuristics]
categories: []
date: 2020-04-09T13:24:16+02:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/abdulhakmeh/Simulated-Annaling-for-platooning-problem.git"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

## Abstract
Platooning of vehicles is a novel approach to reduce fuel consumption in long-distance transportation services by establishing a string of vehicles driving on the road close behind each other to reduce the aerodynamic drag. The motivation relies on the fact that the fuel costs are held accountable for the third of the total operational costs of those services, besides being the Heavy-duty vehicles one of the carbon emissions sources. 


In this study, we examine the important but complex problem of assigning optimal routes to a set of vehicles, where many platooning potentials can be offered. We use the Simulated Annealing metaheuristic approach to solve the centralized routing problem with realistic assumptions on a real-world map. A robust design method is used to tune the model parameters. Unlike the previous contributions, a restriction on the platoon size is proposed to avoid traffic congestion. For a fair evaluation, a mathematical optimization solver using Gurobi is implemented based on a mathematical formulation of the problem. An additional sensitivity analysis is made to study the impact of different model parameters on the output. 


In practice applying simulated annealing achieved approximately 5% fuel saving with an instance that has 500 trucks. For evaluating the algorithm on a real-live map the algorithm scored near 4.5% of fuel saving. The findings confirmed a satisfactory performance of the approach over the exact solver even when the restriction of the platoon size is applied, which can have a positive influence at the forefront of the platooning field, as solving the problem and enhance the solution in a reasonable time can ensure a globally optimized fuel cost-saving for the participants  besides bringing environmental benefits. 