---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

__Biography__

I am Shuolin Xiao. I received my Ph.D. in Mechanical Engineering from the University of Houston in 2020 and a B.A. in Electrical Engineering from Beijing Institute of Technology, China, in 2011. During my graduate studies, I developed numerical simulations for oil spills and wind turbine wake flows, with a primary objective of enhancing offshore environmental sustainability. After my Ph.D., I joined the School of Civil and Environmental Engineering at Cornell University as a Postdoctoral Associate. There, my research focused on the transport and fate of microplastics across urban, atmospheric, and oceanic environments. I am currently a Postdoctoral Fellow at the Ralph S. O’Connor Sustainable Energy Institute at Johns Hopkins University, where I specialize in coarse-grained large-eddy simulations of wind farms and the buidlup of the web-service accessible public database. Also, very recently, I started with another project on very coarse large-eddy simulation with a closure model discovered by a reinforcement learning approach, aiming to capture the long-term behavior of a chaotic system.

__Research Interests__

My research focuses on the long-term dynamics of turbulent flows, characterized by rapid state transitions between meta-stable states, are particularly relevant in carbon capture and storage, denotation engine, and single or hybrid energy systems. These transitions are triggered by the non-equilibrium nature of turbulence, where various mechanisms can contribute to state changes. One such mechanism is the cumulative effect of small-scale fluctuations, which evolve and amplify over extended periods, eventually influencing larger scales and inducing gradual shifts in the turbulent flow's energy distribution, thereby triggering rapid transitions between meta-stable states. These transitions can significantly impact the stability and performance of carbon capture and storage, denotation engine, and single or hybrid energy systems.

However, traditional high-fidelity simulations of turbulent flows are limited to capturing short-term behaviors due to their high computational cost requirements. To achieve high-fidelity simulations of turbulent flows over hundreds of eddy turnover times and beyond, my methodology adopts coarse-grained high-fidelity simulations and leverages AI tools as well as theoretical derivations to preserve detailed physics and maintain accuracy while minimizing the demand for extensive computational resources. Today, most, if not all, data-driven turbulence models rely on a one-step cost function, without accounting for the cumulative effects of the cost function. This often leads to the accumulation of high-spatial-frequency errors and divergence from the ground truth during long-term simulations. To address the aforementioned issues, a multi-agent reinforcement learning approach will be leveraged to optimize long-term rewards based on multi-point and multi-time statistics. To reduce the computational cost associated with optimizing multi-agent systems, a decentralized scheme is adopted instead of a centralized one. This approach significantly reduces computational demands by using a coarse mesh and utilizing a decentralized scheme for the multi-agent reinforcement learning, which allows agents to operate independently while coordinating through localized interactions, thereby ensuring efficiency for long-term simulations. Subsequently, the generated datasets will be integrated into web-service-accessible public databases, enabling researchers worldwide to efficiently access large volumes of data and accelerate the development of data-driven surrogate models.
![test](./images/Application_graphical_abstract.jpg)

