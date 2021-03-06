---
layout: article
title: "Exploration of numerical hydrodynamics"
toc: false
categories: projects
excerpt: "Contains some doodlings I did in the world of hydrodynamics. At some point I became interested in how do fluids actually move so I build my own hydro code to find out."
tags: [video]
image:
  feature:
  teaser: hydro_kh.png
---

At some point I became interested in how (numerical) hydrodynamics actually works so I ended writing my own 2-dimensional hydro code.
My aim was to make the code as modular as possible and I think it turned out pretty nice.
You can get it from my github page [here](https://github.com/natj/hydro).

The initial design of the code mimicks [Christian Ott's 1D python code](https://www.tapir.caltech.edu/~cott/ay190/) pretty closely but I added an unsplitted HLLC solver based on [2D Pyro code](http://bender.astro.sunysb.edu/hydro_by_example/index.html) as I was not happy with the (Strang) splitted version.
For time integration we use second order Runge-Kutta integrator and for reconstruction a linear piecewise interpolation.

After initial design and debugging I ran some tests and was able to produce the Kelvin-Helmholtz instability between the surface of two different density fluids flowing in opposite directions:

<iframe src="//player.vimeo.com/video/95607699" width="500" height="500" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe> <p><a href="https://vimeo.com/95607699">Kelvin&ndash;Helmholtz instability</a> from <a href="https://vimeo.com/user28191808">Joonas N&auml;ttil&auml;</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

Next step is to add a magnetohydrodynamical Riemann solver like HLLB.
