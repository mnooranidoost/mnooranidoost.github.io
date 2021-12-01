---
layout: page
title: Deposition of cell-loaded droplets in droplet-based bio-printing systems
permalink: /miscellany/item-2/
---

Using a front-tracking method to solve multi-phase flow equations and a FENE-CR model to model polymers inside the bio-ink solution and the cell, I studied deposition of cell-loaded droplets on a flat surface during a bio-printing process \cite{nooranidoost2020improving}. A slip-contact line model was used to treat the dynamic contact line between the droplet interface and the flat surface. The Kistler's correlation~\cite{kistler1993hydrodynamics} was used to relate the dynamic contact angle to the static contact angle ($\theta_e$) and the capillary number $Ca_{cl} = \mu_d |V_{cl}|/\sigma_{o}$, where $\mu_{d}$, $V_{cl}$ and $\sigma_{o}$ are viscosity of the cell-laden droplet, velocity of the contact line and interfacial tension of the outer interface, respectively. First, the apparent dynamic contact angle was calculated as:
\begin{eqnarray}
\theta_{D_i} = f_{\rm Hoff}\left(Ca_{cl} + f_{\rm Hoff}^{-1}(\theta_e)\right),
\end{eqnarray}
where $f_{\rm Hoff}$ is the Hoffman function defined as
\begin{eqnarray}
f_{\rm Hoff}(\xi) = \arccos\left\{1 - 2\tanh\left[ 5.16\left(\frac{\xi}{1 + 1.31\xi^{0.99}}\right)^{0.706}\right] \right\}.
\end{eqnarray}
Then, the dynamic contact angle was computed as
\begin{eqnarray}
\theta_D = \left\{\begin{array}{cc} \theta_{D_i} & {\rm if\;} V_{cl} \ge 0 \quad ({\rm advancing}) , \\ 2\theta_e - \theta_{D_i} & {\rm if\;} V_{cl} < 0 \quad ({\rm receding}).
\end{array} \right.
\end{eqnarray}

Simulations with different viscoelastic bio-inks showed that during the deposition, the polymers inside the bio-ink extends rapidly and creates a thin viscoelastic boundary layer near the surface and the encapsulating droplet spread on the solid surface. The mechanical deformation of the cell was quantified by $\gamma=A/A_0$, where $A$  and $A_0$ are the surface areas of the deformed and the undeformed cells, respectively. Then a cell viability model proposed by Takamatsu and Rubinsky \cite{takamatsu1999viability} was used to compute the cell viability as a function of maximum instantaneous cell deformation. High cell viability was found to be achieved for bio-inks with high polymeric viscosity ratios and Weissenberg numbers. Above a critical Weissenberg number $(\approx 10)$, cell viability remained constant and further increasing of viscoelasticity did not improve cell viability (Fig. \ref{fig:3b}).


Droplet-based bio-printing systems is a state-of-art technology in creating artificial organs and this work can guide researchers in biomedical clinics to design the proper bio-ink for these systems in order to improve the cell survival during printing process. This work was supported by the Scientific and Technical Research Council of Turkey (TUBITAK), Grant No. 112M181, and the COST Action Grant No. MP1106.

