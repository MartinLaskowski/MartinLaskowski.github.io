---
title: The Optimization Impostors' Compendium
date: 2024-03-31 01:58:59 -0500
categories: [Projects]
tags: [optimization]
mermaid: true
image:
  path: /assets/img/2023-12-05-The-Optimization-Impostors-Compendium-thumb.webp
  alt: Image by DALL·E showing text-to-image aberrations increasingly rare in early December 2023.
  lqip: /assets/img/2023-12-05-The-Optimization-Impostors-Compendium-thumb-low.webp
---
Last July, after six terrific years, I left AMPL Optimization, Inc., - the rockstar team behind the algebraic modeling language and ecosystem of the same name for large-scale mathematical optimization.

Our process for selling AMPL and solvers like Gurobi, CPLEX, etc., involved helping customer firms build and repair optimization models in energy systems, manufacturing, logistics, quantitative finance and so on. The ability to compute problems so large as would crash other toolchains and to produce solutions seemingly faster than by other means earns AMPL and these solvers their reputations in the high-performance optimization market.

Customer teams sometimes needed help building models from scratch, in the service of which my former team recently released a solid resource: the <a href="https://mo-book.ampl.com/" target="_blank">MO-Book</a> focussing especially on Python-scripted applications.

More frequently, however, practitioners needed help speeding up an existing application and to this end often threw open for debate not just their mathematical formulation but every tool in their app's toolchain, and also its runtime environment and underlying hardware. These engagements were my bliss: finding and addressing performance bottlenecks across very different deployments, each seeming to hold something new to learn.

For years now I've wanted to generalize and share certain insights relating to the speeding of optimization applications, but somehow the time never came while at AMPL. The desire remained and now, dear world, I present to you the 'The Optimization Impostors' Compendium', aka opt-models.org, live and growing at ...

## [opt-models.org](https://opt-models.org/)

I am having fun making it hope that it might be useful. Feel free to tell me there everything I am missing and getting wrong - this resource would be all the richer for your input :)
