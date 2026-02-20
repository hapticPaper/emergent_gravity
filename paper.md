# The Informational Mechanics of Spacetime: Gravity and Dilation as Emergent Properties of Entanglement Overlap and Discrete Causality

### Ian Rubenstein
##### 19 Feb, 2026
###### Gemini 3.1, Claude 4.6

### **Abstract**

This paper formally redefines spacetime locality, time dilation, and gravitational attraction as emergent phenomena arising from the finite propagation rate of quantum mutual information. By abandoning the geometric continuous manifold of General Relativity, we model the universe as a bipartite tensor network where spatial distance is a measure of interaction adjacency, and the speed of light ($c$) is recontextualized as $R_c$: the absolute, discrete interaction rate limit of causality. In this framework, time is the sequential completion of a localized update cycle ("now"). Gravitational time dilation emerges naturally: entangled particles continuously cycle through mutually conforming states, and denser entanglement overlap means consecutive interactions propagate slower through the network, lengthening each update cycle at the fixed rate $R_c$. Velocity-dependent time dilation arises from the same mechanism: a moving subsystem expends causal bandwidth traversing the network, reducing the rate of local state updates by the Lorentz factor — recovering special relativity without geometric Minkowski space. Gravity follows from the same structure: a subsystem's degrees of freedom are shared with the local entanglement network in proportion to the overlap. The greater the overlap with a massive body, the more a subsystem's reference frame and vector are defined through that body's — manifesting macroscopically as gravitational attraction.

---

### 1. The Observer Subsystem and Discrete Causality
We begin by defining the universe not as a spatial container, but as a pure, static quantum state $|\Psi\rangle$ in a total Hilbert space $\mathcal{H}_{total}$, governed by the Wheeler-DeWitt equation $\hat{H}|\Psi\rangle = 0$.

To recover local dynamics, we partition the universe into an interaction-bound observer subsystem ($A$) and its environment ($E$):

$$\mathcal{H}_{total} = \mathcal{H}_A \otimes \mathcal{H}_E$$

The state of the observer is given by the reduced density matrix:

$$\rho_A = \text{Tr}_E(|\Psi\rangle\langle\Psi|)$$

Standard models treat the propagation of causality ($c$) as a velocity through vacuum geometry. We formalize it as $R_c$, the maximum allowable rate of state updates (interactions) per fundamental causal interval ($\tau_{univ}$). A localized "now" is the discrete execution of a state update—an exchange of mutual information between $\mathcal{H}_A$ and $\mathcal{H}_E$.

### 2. The Entanglement Overlap Field ($\Omega$)
Spatial locality is redefined as the adjacency of nodes in the entanglement network. Physical distance is equivalent to the number of intermediate interactions required to correlate two disjoint subsystems.

We introduce the scalar field $\Omega(x)$, representing the localized density of overlapping entanglement radii at coordinate $x$. This defines the depth of the local conformance network—the number of entangled particles whose states must mutually conform for a single update cycle to complete.

A massive body is defined as a system with extreme internal entanglement density. Let $\rho_e(x)$ denote the volumetric entanglement density distribution. This density sources the overlap field, governed by the informational Poisson equation:

$$\nabla^2 \Omega(x) = -4\pi \kappa \rho_e(x)$$

where $\kappa$ is the fundamental informational coupling constant mapping entanglement density to environmental conformance burden. The sign convention ensures that $\Omega$ increases in the vicinity of entanglement-dense regions, consistent with its interpretation as conformance depth.

**Why Poisson?** The choice of field equation is not arbitrary. If entanglement from a localized source spreads isotropically, and the total entanglement overlap integrated over any enclosing surface is conserved (entanglement is neither created nor destroyed by the field), then by Gauss's law:

$$\oint \nabla\Omega \cdot d\mathbf{S} = -4\pi\kappa M_{enclosed}$$

The divergence theorem immediately gives the Poisson equation. The only physical assumptions are isotropy and conservation of entanglement overlap — no geometric or thermodynamic postulates are needed.

Alternative field equations carry specific physical consequences:

- **Helmholtz** ($\nabla^2\Omega + k^2\Omega = -4\pi\kappa\rho_e$): yields a Yukawa potential $\Omega \sim e^{-kr}/r$, predicting screened gravity that weakens exponentially beyond scale $1/k$. This is experimentally excluded at solar system scales.
- **Nonlinear Poisson** ($\nabla^2\Omega + f(\Omega) = -4\pi\kappa\rho_e$ for some $f$): could produce MOND-like modifications at low accelerations while preserving $1/r$ behavior at short range. This remains a viable extension if galactic rotation curves are to be addressed within the framework.
- **Wave equation** ($\nabla^2\Omega - R_c^{-2}\partial_t^2\Omega = -4\pi\kappa\rho_e$): introduces propagating disturbances in the overlap field at speed $R_c$ — a natural candidate for gravitational waves within this framework. If the overlap field is dynamic rather than static, the wave equation is the minimal causal extension of Poisson.

The static Poisson equation is therefore the minimal choice consistent with known gravitational phenomenology. Whether dynamical extensions (wave equation) or nonlinear corrections arise from the microscopic entanglement dynamics is an open question addressed in Section 10.

For an isolated system of total entanglement content $M$ localized at the origin ( $\rho_e = M\delta^3(\mathbf{x})$ ), the spherically symmetric solution is:

$$\Omega(r) = \Omega_0 + \frac{\kappa M}{r}$$

where $\Omega_0$ is the background conformance depth of free space—the irreducible entanglement overlap of the vacuum. The overlap field diverges as $r \to 0$, reflecting unbounded conformance depth at the core of a maximally entangled system.

### 3. Derivation of Informational Time Dilation
Time ($\tau_{local}$) is not a background dimension; it is the subjective sequence of discrete update cycles experienced by subsystem $A$.

Because the universal interaction rate $R_c$ is strictly conserved, a deeper conformance network ($\Omega$) means consecutive interactions propagate slower — each interaction still occurs at rate $R_c$, but there are more entangled states in the path, stretching the duration of each local update cycle. The differential of local proper time is the ratio of the fundamental interaction rate to the local conformance depth:

$$d\tau_{local} = \frac{R_c}{\Omega(x)} d\tau_{univ}$$

We define the **informational clock rate** $\phi(x)$ as the local rate of proper time advance per causal interval:

$$\phi(x) \equiv \frac{R_c}{\Omega(x)}$$

For the spherically symmetric solution $\Omega(r) = \Omega_0 + \kappa M/r$:

$$\phi(r) = \frac{R_c}{\Omega_0 + \kappa M/r} = \phi_\infty \cdot \frac{1}{1 + \dfrac{r_\Omega}{2r}}$$

where $\phi_\infty \equiv R_c / \Omega_0$ is the clock rate at spatial infinity and $r_\Omega \equiv 2\kappa M / \Omega_0$ is the **informational radius**—the scale at which the entanglement overlap field doubles the vacuum conformance depth.

In the weak-field regime ($r_\Omega / r \ll 1$):

$$\phi(r) \approx \phi_\infty \left(1 - \frac{r_\Omega}{2r}\right)$$

This is structurally identical to the Schwarzschild weak-field limit:

$$\frac{d\tau}{dt} \approx 1 - \frac{r_s}{2r}$$

where $r_s = 2GM/c^2$ is the Schwarzschild radius. The correspondence demands $r_\Omega = r_s$, yielding:

$$\frac{\kappa}{\Omega_0} = \frac{G}{R_c^2}$$

This constrains the informational coupling constant entirely in terms of known physical constants, eliminating one free parameter from the framework.

As a subsystem approaches a dense entanglement network, $\Omega(x) \to \infty$ and $\phi(x) \to 0$. Gravitational time dilation is thus a direct consequence of conformance depth: consecutive interactions propagate slower through denser entanglement overlap, and each update cycle takes longer. No geometric spacetime curvature is required.

**Strong-field departure.** In the strong-field regime, the frameworks diverge. The Schwarzschild metric predicts a coordinate singularity at $r = r_s$ where $d\tau/dt = 0$. The informational clock rate $\phi(r) = \phi_\infty / (1 + r_\Omega/2r)$ is strictly positive for all $r > 0$, approaching zero only asymptotically as $r \to 0$. This framework therefore predicts no sharp event horizon—only asymptotically increasing time dilation. The observational consequences are discussed in Section 9.

**Velocity-dependent time dilation.** The same mechanism accounts for special-relativistic time dilation. A subsystem at rest devotes its full causal bandwidth $R_c$ to propagating through the local conformance network, yielding clock rate $\phi = R_c/\Omega$. A subsystem moving at velocity $v$ through the entanglement network expends part of that bandwidth on spatial displacement — each interaction encountered along the trajectory is an additional exchange that causality must propagate through at rate $R_c$, leaving less bandwidth for the local update cycle. The physical picture is direct: imagine the entanglement network as a field of interactions occurring at rate $R_c$. A stationary subsystem encounters only the local density. A fast-moving subsystem sweeps through the network ahead of it, each encounter consuming causal bandwidth — like running through rain, where each drop to the face is an interaction that must be processed before the next local update can complete.

Since spatial displacement and temporal evolution both draw on the same finite bandwidth $R_c$, the available rate for local updates is:

$$R_c^{(local)} = \sqrt{R_c^2 - v^2}$$

The conformance depth is unchanged, but the bandwidth available to propagate through it is reduced:

$$\phi(v) = \frac{R_c^{(local)}}{\Omega} = \frac{R_c}{\Omega}\sqrt{1 - \frac{v^2}{R_c^2}} = \phi_{rest}\sqrt{1 - \frac{v^2}{R_c^2}}$$

This recovers the Lorentz factor exactly. At $v = R_c$, all interaction bandwidth is consumed by spatial traversal — none remains for local updates, and $\phi \to 0$: time stops. The speed of light is not merely a velocity bound; it is the point at which traversing the entanglement network exhausts the causal bandwidth available for temporal evolution.

**Combined dilation.** For a subsystem moving at velocity $v$ in a gravitational overlap field $\Omega(r)$:

$$\phi(r, v) = \frac{\sqrt{R_c^2 - v^2}}{\Omega(r)} = \phi_\infty \cdot \frac{\sqrt{1 - v^2/R_c^2}}{1 + r_\Omega/2r}$$

In the weak-field, low-velocity limit:

$$\phi \approx \phi_\infty\left(1 - \frac{r_s}{2r} - \frac{v^2}{2R_c^2}\right)$$

reproducing the standard weak-field result of General Relativity. Gravitational and velocity-dependent dilation are not separate phenomena requiring distinct explanations — they are both consequences of the finite causal bandwidth $R_c$: mass increases the conformance depth the bandwidth must propagate through; motion diverts the bandwidth into spatial displacement. Both reduce the rate of local state updates.

### 4. Mass-Energy as Interaction Capacity
Under this framework, Einstein's mass-energy equivalence transitions from a kinematic description to a statement of latent informational capacity. The total energy $E$ of a localized subsystem is its intrinsic entanglement density ($M$) constrained by the square of the universal interaction rate:

$$E = M R_c^2$$

Energy represents the absolute maximum interaction rate a subsystem could sustain if its degrees of freedom were entirely independent of the environmental entanglement network.

### 5. Gravity as Shared Degrees of Freedom
A subsystem's degrees of freedom are shared with the local entanglement network in proportion to the overlap of their entanglement radii. Near a massive body, a subsystem's entanglement overlaps extensively with the mass — and to the extent that degrees of freedom are shared, the subsystem's reference frame and vector are defined through the mass's.

Consider the limiting case: a particle fully absorbed into a Bose-Einstein condensate has zero independent degrees of freedom. Its next spacetime reference frame and vector are the condensate's, completely. This is not a force acting on the particle — the particle's state simply IS the condensate's state.

Macroscopic gravity is the partial version of this. We share entanglement overlap with the Earth, and to that degree our reference frame is defined through Earth's. What we experience as gravitational attraction is the proportion of our degrees of freedom that are not independently determined but are instead inherited from the dominant local entanglement network. To maintain a trajectory independent of the mass requires retaining degrees of freedom against the overlap — demanding interaction bandwidth that exceeds $R_c$.

In the macroscopic limit, this manifests as an effective force derived from the gradient of $\phi(x)$:

$$\mathbf{F}_g = -\alpha \nabla \phi(x)$$

where $\alpha > 0$ encodes the test subsystem's coupling to the overlap field. Since $\phi(x)$ decreases toward entanglement-dense regions, $\nabla\phi$ points away from mass, and $-\nabla\phi$ points inward — the macroscopic signature of shared degrees of freedom.

**Recovery of Newton's law.** In the weak-field limit, using $\phi(r) \approx \phi_\infty(1 - \kappa M/(\Omega_0 r))$:

$$\nabla\phi = \phi_\infty \frac{\kappa M}{\Omega_0 r^2}\hat{r}$$

$$\mathbf{F}_g = -\frac{\alpha \phi_\infty \kappa M}{\Omega_0 r^2}\hat{r}$$

Identifying $\alpha \phi_\infty \kappa / \Omega_0 = G$ for a unit test mass:

$$\mathbf{F}_g = -\frac{GM}{r^2}\hat{r}$$

Newton's inverse-square law is recovered exactly. The gravitational constant is expressed in terms of fundamental informational quantities:

$$G = \frac{\alpha R_c \kappa}{\Omega_0^2}$$

**Singularity regularization.** The full non-linearized force magnitude:

$$|\mathbf{F}_g| = \frac{\alpha R_c \kappa M}{r^2\left(\Omega_0 + \kappa M/r\right)^2}$$

approaches a finite constant $\alpha R_c / (\kappa M)$ as $r \to 0$, rather than diverging. The informational framework naturally regularizes the Newtonian gravitational singularity: the force saturates when the local conformance depth dominates the vacuum background. This provides a resolution to the classical point-mass divergence without requiring spacetime quantization or dimensional regularization.

### 6. Multi-Body Systems

The linearity of the informational Poisson equation ensures that the overlap field generated by multiple massive bodies superposes:

$$\Omega(\mathbf{x}) = \Omega_0 + \sum_i \frac{\kappa M_i}{|\mathbf{x} - \mathbf{x}_i|}$$

A test subsystem at position $\mathbf{x}$ has its degrees of freedom shared with the combined entanglement network of all nearby masses, weighted by the local overlap contribution of each. Its reference frame is not defined through any single body but through the composite field — the proportion of shared degrees of freedom with each mass determines the effective trajectory.

**Lagrange points.** At locations where $\nabla\phi = 0$, the overlap gradients from competing masses balance. A subsystem at such a point has its degrees of freedom shared symmetrically among the sources, and no net drift toward any single body emerges. These are the Lagrange points of the standard two-body problem, recovered here without invoking inertial frames or fictitious forces — they are simply the nodes where no single mass dominates the entanglement overlap.

**Tidal forces.** The second derivative $\nabla\nabla\phi$ encodes the differential sharing of degrees of freedom across an extended body. A subsystem's near edge shares more degrees of freedom with the dominant mass than its far edge, producing the gradient of trajectory we identify as tidal stress. In the weak-field limit, $\nabla\nabla\phi$ reproduces the Newtonian tidal tensor exactly.

**Hierarchical binding.** In a system with well-separated mass scales — a moon orbiting a planet orbiting a star — the overlap field naturally produces hierarchical binding. The moon's degrees of freedom are shared predominantly with the planet (nearest, densest local overlap), while the planet-moon system's combined degrees of freedom are shared predominantly with the star. Each level of the hierarchy emerges from the local dominance of the nearest entanglement source, without requiring separate treatment. The transition between regimes — the Hill sphere in classical mechanics — corresponds to the radius at which the overlap contributions from two bodies are equal: $\kappa M_1/r_1 = \kappa M_2/r_2$.

### 7. Resolution of Spatially Separated Entanglement
By defining space strictly as an adjacency matrix of mutual information, the EPR paradox and non-locality are trivially resolved.

Two maximally entangled, isolated particles share a direct informational edge. Regardless of their apparent separation in the emergent macroscopic geometry, their intermediate interaction field is zero ($\Omega_{intermediate} = 0$).

When an interaction forces an update to their shared state, the absence of intermediate interactions means the update requires exactly one causal interval:

$$d\tau_{update} = \frac{1}{R_c}$$

No causal speed limit is violated; the particles execute a single adjacent interaction, exposing geometric distance as an emergent property of the macroscopic observer's own entanglement structure.

### 8. Correspondence with Existing Frameworks
This framework intersects with several independent research programs that have approached the geometry-information interface from distinct starting points.

**Jacobson's thermodynamic gravity (1995).** Jacobson derived the Einstein field equations by treating the Clausius relation $\delta Q = TdS$ as fundamental, applied to local Rindler horizons with entropy proportional to area [1]. Our framework shares the premise that gravity is not a fundamental force but an emergent consequence of information-theoretic constraints. The key distinction: Jacobson requires the Bekenstein-Hawking entropy-area relation as input; we derive the gravitational gradient directly from the interaction structure of the overlap field, without invoking thermodynamic entropy.

**Verlinde's entropic gravity (2011).** Verlinde proposed gravity as an entropic force arising from changes in information associated with the positions of material bodies, deriving Newton's law from holographic screen arguments [2]. Our Section 5 arrives at a structurally similar result—gravity emerging from informational structure—but replaces the holographic screen with the overlap field $\Omega(x)$ and identifies a microscopic mechanism (shared degrees of freedom through entanglement overlap) rather than a thermodynamic postulate.

**ER=EPR (Maldacena & Susskind, 2013).** The conjecture that entangled particles are connected by non-traversable Einstein-Rosen bridges [3] resonates directly with Section 7: two entangled particles share a direct informational edge regardless of macroscopic geometric separation. The ER=EPR framework is couched in AdS/CFT; we arrive at the same conclusion from the entanglement adjacency structure. Both approaches dissolve the paradox of non-locality by asserting that the entanglement connection is topologically prior to the emergent spatial geometry.

**Causal set theory (Bombelli, Lee, Meyer & Sorkin, 1987).** Causal set theory discretizes spacetime into a partially ordered set of events, with the order relation encoding causal structure [4]. Our fundamental causal interval $\tau_{univ}$ and the discrete execution of state updates share this commitment to fundamentally discrete causality. However, causal sets derive geometry from the order relation alone; we derive it from the entanglement adjacency structure, which carries richer informational content—specifically, the bond dimensions of the tensor network.

**Wolfram's computational universe (2020).** Wolfram's physics project models the universe as a hypergraph evolving by local rewrite rules, with space, time, and gravity emerging from the graph's large-scale structure [5]. The convergence is striking: both frameworks treat space as emergent from a network, time as discrete sequential computation, and the speed of light as a computational rate limit. The principal divergence lies in the substrate: Wolfram postulates classical rewrite rules on a hypergraph; we ground the dynamics in quantum entanglement and the Hilbert space structure of $|\Psi\rangle$.

**Tensor networks and It from Qubit.** The ongoing program connecting quantum information to spacetime geometry—particularly the Ryu-Takayanagi formula relating entanglement entropy to minimal surface area [6] and the identification of spacetime geometry with tensor network structure [7]—provides the closest existing formalism to this work. Our overlap field $\Omega(x)$ admits a natural interpretation as the bond dimension density in a MERA-like tensor network representation of the vacuum state, and the informational clock rate $\phi(x)$ as the local propagation rate through the network. Van Raamsdonk's observation that reducing entanglement between subsystems increases their spatial separation [8] is precisely the mechanism underlying our definition of distance as interaction adjacency.

**Susskind's computational complexity (2014).** Susskind's proposal that the interior volume of a black hole grows with the quantum computational complexity of the boundary state [9] provides a complementary perspective. Where Susskind measures the growth of the wormhole interior, our framework measures the conformance depth that each local state update must propagate through. Both identify a deep connection between gravity and the structure of quantum information.

### 9. Experimental Predictions and Falsifiability
A framework that claims to replace geometric spacetime must generate predictions distinguishable from General Relativity. We identify three classes of observable consequence, ranging from near-term to aspirational.

**Prediction 1: Entanglement-dependent self-dilation.** In GR, the stress-energy tensor sources curvature and depends on mass-energy content alone, not on the quantum coherence structure of the source. In this framework, $\Omega$ is sourced by entanglement density $\rho_e$, which depends on the internal quantum correlations of a system—not merely its rest mass. A system's own entanglement contributes to its local overlap field, modifying the rate at which its internal processes evolve.

Consider a Bose-Einstein condensate of $N$ atoms in a state of near-maximal entanglement. The condensate's internal entanglement raises its local conformance depth:

$$\Omega_{local} = \Omega_{ext} + \frac{\kappa_E S_E}{l_c}$$

where $\Omega_{ext}$ is the external overlap field (dominated by Earth), $S_E$ is the entanglement entropy of the condensate, $\kappa_E$ parameterizes the entanglement-specific coupling, and $l_c$ is the coherence length of the condensate. A thermal gas of equal mass and species, with $S_E \approx 0$ (no long-range entanglement), experiences only $\Omega_{ext}$. The framework predicts that the entangled system's internal clock rate is reduced relative to the thermal system:

$$\frac{\delta\phi}{\phi} \sim \frac{\kappa_E S_E}{\Omega_{ext} \, l_c}$$

*Experimental protocol (spectroscopic):* Compare atomic transition frequencies of atoms within a macroscopic BEC ($\sim 10^6$ atoms, $S_E \sim N\log 2$) against atoms in a decoherent thermal sample of equal mass and species, after subtracting known mean-field and density shifts. The framework predicts a residual redshift of the BEC transitions proportional to $S_E$. Current spectroscopic precision ($\Delta f/f \sim 10^{-19}$, [10]) is sufficient to detect or exclude this effect, contingent on the magnitude of $\kappa_E$.

*Experimental protocol (free fall):* If the coupling constant $\alpha$ in $\mathbf{F}_g = -\alpha\nabla\phi$ depends on a test system's internal entanglement structure, a BEC and a thermal gas of equal mass should fall at measurably different rates—a violation of the weak equivalence principle specific to quantum-coherent matter. Atom interferometry experiments already constrain equivalence principle violations at the $10^{-12}$ level; a differential between coherent and decoherent samples would constitute direct evidence for entanglement-sourced gravity.

**Prediction 2: Absence of a sharp event horizon.** As derived in Section 3, the informational clock rate $\phi(r)$ is strictly positive for all $r > 0$. The framework predicts no event horizon at the Schwarzschild radius—only asymptotic time dilation. For astrophysical black holes, infalling matter never crosses a causal boundary; it accumulates in an ultra-dilated shell.

The strong-field deviation is quantifiable. Although the weak-field matching sets $r_\Omega = r_s$, the functional forms diverge at small $r$. The Schwarzschild metric gives $d\tau/dt = \sqrt{1 - r_s/r}$; this framework gives $\phi(r)/\phi_\infty = 1/(1 + r_s/2r)$. At the photon sphere ($r = 3r_s/2$):

$$\sqrt{1 - \frac{2}{3}} \approx 0.577 \quad \text{vs.} \quad \frac{1}{1 + \frac{1}{3}} = 0.750$$

a $\sim 30\%$ deviation in the static time dilation component. Two caveats bear on this figure. First, the Poisson equation is the minimal ansatz for $\Omega$ (Section 2); nonlinear corrections from the microscopic entanglement dynamics could modify the strong-field form of $\phi(r)$ and bring it closer to — or further from — the Schwarzschild prediction. Second, the photon sphere involves matter moving at $v = R_c$, where velocity-dependent dilation (Section 3) contributes maximally. A full strong-field prediction requires combining the gravitational and velocity-dependent overlap in a self-consistent effective potential, which remains open.

Quasi-normal mode frequencies, determined by this effective potential near the photon sphere, would reflect any residual deviation. LIGO/Virgo/KAGRA currently constrain deviations from Kerr ringdown at the $\sim 10$–$20\%$ level [11]. The Event Horizon Telescope's shadow observations [12] provide a complementary geometric constraint. A precise QNM calculation requires extending the framework to a full metric structure (including spatial components and the combined dilation), which is a priority for future work.

**Prediction 3: Discrete time noise floor.** If time is fundamentally discrete with fundamental interval $\tau_{univ}$, the most precise clocks should encounter an irreducible noise floor uncorrelated between independent clocks, with a white spectrum up to frequency $\nu_{max} = 1/\tau_{univ}$ and a hard cutoff above. If $\tau_{univ} \sim t_P \approx 5.4 \times 10^{-44}$ s, the effect lies far below current sensitivity. However, this framework does not mandate $\tau_{univ} = t_P$; the causal interval is a free parameter that experiment can constrain from above. Cross-correlation analysis of geographically separated optical lattice clocks could place progressively tighter upper bounds on $\tau_{univ}$, testing the discrete-time hypothesis without requiring Planck-scale resolution.

### 10. Limitations and Open Questions

**Entanglement radii.** The framework invokes entanglement radii as the mechanism generating spatial overlap, but does not specify what determines their scale. A particle's entanglement radius should be a function of its mass-energy and its existing entanglement structure — heavier particles source larger overlap radii, and a system's entanglement history modifies its effective reach into the network. Deriving the functional dependence $r_{ent}(M, S_E, ...)$ from the microscopic dynamics of the tensor network would constrain $\kappa$ and potentially the form of the field equation itself. This is among the most important open problems for the framework.

**Frame dragging.** A rotating massive body should impart angular structure to the overlap field, producing the frame-dragging effects observed by Gravity Probe B and encoded in the Kerr metric's off-diagonal components. The scalar overlap field $\Omega(x)$ as currently defined cannot capture this — an extension to a vector or tensor overlap field, or a flow structure on the entanglement network, is required. The degrees-of-freedom mechanism (Section 5) suggests a natural path: a subsystem sharing degrees of freedom with a rotating mass should inherit not only its radial reference frame but also its angular momentum, producing Lense-Thirring precession. Developing this extension is a priority for reaching full GR correspondence.

**Dark energy.** This framework is built on interactions — entanglement overlap, conformance cycling, shared degrees of freedom. A phenomenon that does not interact with local structure, or interacts uniformly with everything, falls outside its current explanatory scope. Dark energy, which drives cosmological expansion without coupling to local systems in any detected way, cannot be addressed until its interaction properties are understood. If dark energy proves to be a property of the vacuum entanglement network — for instance, a cosmological evolution of $\Omega_0$ — the framework may accommodate it, but this remains speculative.

**The coupling constant $\alpha$.** The macroscopic force law $\mathbf{F}_g = -\alpha\nabla\phi$ requires $\alpha$ to be proportional to the test mass to recover the equivalence principle ($\mathbf{F}_g \propto m$). In the degrees-of-freedom picture this is natural: a more massive test subsystem shares more degrees of freedom with the local network, and thus a larger proportion of its state is defined through the dominant mass. But the precise dependence — and whether the proportionality is exact or approximate for quantum-coherent matter — needs to be derived from the microscopic theory. The BEC free-fall experiment (Section 9, Prediction 1) directly tests this question.

**Full General Relativity.** The framework currently recovers Newtonian gravity, weak-field Schwarzschild time dilation, and special-relativistic time dilation, but not the full Einstein field equations. The strong-field regime shows structural differences (Section 3), and the spatial components of the metric have not been derived. Recovering frame dragging, gravitational waves (potentially via the wave equation extension discussed in Section 2), and the correct strong-field behavior around compact objects are necessary milestones. The velocity-dependent dilation derived in Section 3 is encouraging — it unifies gravitational and inertial effects under a single mechanism — but a covariant formulation remains to be developed.

---

### Acknowledgments
The authors acknowledge foundational contributions from the quantum information, holography, and emergent gravity communities whose work informed this framework. Particular thanks are owed to the experimental atomic clock and BEC communities whose precision measurements may ultimately arbitrate between geometric and informational models of spacetime.

---

### References

[1] T. Jacobson, "Thermodynamics of spacetime: The Einstein equation of state," *Phys. Rev. Lett.* **75**, 1260 (1995). [arXiv:gr-qc/9504004]

[2] E. Verlinde, "On the origin of gravity and the laws of Newton," *JHEP* **2011**, 29 (2011). [arXiv:1001.0785]

[3] J. Maldacena and L. Susskind, "Cool horizons for entangled black holes," *Fortschr. Phys.* **61**, 781 (2013). [arXiv:1306.0533]

[4] L. Bombelli, J. Lee, D. Meyer, and R. D. Sorkin, "Space-time as a causal set," *Phys. Rev. Lett.* **59**, 521 (1987).

[5] S. Wolfram, "A class of models with the potential to represent fundamental physics," *Complex Systems* **29**, 107 (2020). [arXiv:2004.08210]

[6] S. Ryu and T. Takayanagi, "Holographic derivation of entanglement entropy from the anti-de Sitter space/conformal field theory correspondence," *Phys. Rev. Lett.* **96**, 181602 (2006). [arXiv:hep-th/0603001]

[7] B. Swingle, "Entanglement renormalization and holography," *Phys. Rev. D* **86**, 065007 (2012). [arXiv:0905.1317]

[8] M. Van Raamsdonk, "Building up spacetime with quantum entanglement," *Gen. Rel. Grav.* **42**, 2323 (2010). [arXiv:1005.3035]

[9] L. Susskind, "Computational complexity and black hole horizons," *Fortschr. Phys.* **64**, 24 (2016). [arXiv:1403.5695]

[10] T. Bothwell *et al.*, "Resolving the gravitational redshift across a millimetre-scale atomic sample," *Nature* **602**, 420 (2022).

[11] LIGO Scientific Collaboration and Virgo Collaboration, "Tests of general relativity with binary black holes from the second LIGO-Virgo gravitational-wave transient catalog," *Phys. Rev. D* **103**, 122002 (2021). [arXiv:2010.14529]

[12] Event Horizon Telescope Collaboration, "First M87 Event Horizon Telescope results. I. The shadow of the supermassive black hole," *Astrophys. J. Lett.* **875**, L1 (2019). [arXiv:1906.11238]
