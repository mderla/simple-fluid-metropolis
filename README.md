# simple-fluid-metropolis
A Jupyter Notebook demonstrating drawing canonical ensemble distributed configurations for interacting fluids with Metropolis Monte Carlo simulation. From a programming point of view, it is plug-and-play with any isotropically interacting classical simple fluid, by setting the interaction potential $u(r)$ to the desired one. For now, the famous Lennard-Jones interaction potential $$u(r)=4\varepsilon\left(\frac{\sigma}{r}\right)^6\left(\left(\frac{\sigma}{r}\right)^6-1\right)$$ has been inserted and an example plot for the estimated (radial) two-body density computed; The simulation for the plot was run in three spatial dimensions with $N=50$ particles at a packing fraction of $\eta=60 \\%$ and $\varepsilon/k_{\mathrm{B}}T=1$, where $T$ is thermodynamic temperature. The (three dimensional) packing fraction has been defined via $$\eta=\frac{4}{3}\pi\left(\frac{\sigma}{2}\right)^3\cdot\rho$$ where $\rho$ is the molar density of the system and $\sigma$ the distance below which the Lennard-Jones potential is positive (start of the effective hard core)

No quantitative diagnostic like Gelman-Rubin has been employed for finding a good burn-in time or probing for convergence. In fact, the entire project is a proof of concept.
