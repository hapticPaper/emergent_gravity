# The Informational Mechanics of Spacetime: Gravity and Dilation as Emergent Properties of Entanglement Overlap and Discrete Causality

### Ian Rubenstein
##### 19 Feb, 2026
###### Gemini 3.1, Claude 4.6

### **Abstract**

This paper formally redefines spacetime locality, time dilation, and gravitational attraction as emergent phenomena arising from the finite processing rate of quantum mutual information. By abandoning the geometric continuous manifold of General Relativity, we model the universe as a bipartite tensor network where spatial distance is a measure of interaction adjacency, and the speed of light ($c$) is recontextualized as $R_c$: the absolute, discrete interaction rate limit of causality. In this framework, time is the sequential completion of a localized update cycle ("now"). Gravitational time dilation is derived as a computational processing lag caused by the exponential overlap of entanglement radii near dense quantum systems, and gravity is the emergent entropic force driving computationally bound subsystems down the gradient of least informational resistance.

---

### 1. The Computational Subsystem and Discrete Causality
We begin by defining the universe not as a spatial container, but as a pure, static quantum state $|\Psi\rangle$ in a total Hilbert space $\mathcal{H}_{total}$, governed by the Wheeler-DeWitt equation $\hat{H}|\Psi\rangle = 0$.

To recover local dynamics, we partition the universe into a computationally bound observer subsystem ($A$) and its environment ($E$):

$$\mathcal{H}_{total} = \mathcal{H}_A \otimes \mathcal{H}_E$$

The state of the observer is given by the reduced density matrix:

$$\rho_A = \text{Tr}_E(|\Psi\rangle\langle\Psi|)$$

Standard models treat the propagation of causality ($c$) as a velocity through vacuum geometry. We formalize it computationally as $R_c$, the maximum allowable rate of state updates (interactions) per fundamental causal interval ($\tau_{univ}$). A localized "now" is the discrete execution of a state update—a collapse or measurement exchanging mutual information between $\mathcal{H}_A$ and $\mathcal{H}_E$.

### 2. The Entanglement Overlap Field ($\Omega$)
Spatial locality is redefined as the adjacency of nodes in the entanglement network. Physical distance is equivalent to the number of intermediate interactions required to correlate two disjoint subsystems.

We introduce the scalar field $\Omega(x)$, representing the localized density of overlapping entanglement radii at coordinate $x$. This defines the total computational workload—the number of partial quantum interactions a localized subsystem must resolve to complete a single state update.

A massive body is defined as a system with extreme internal entanglement density. Let $\rho_e(x)$ denote the volumetric entanglement density distribution. This density sources the overlap field, governed by the informational Poisson equation:

$$\nabla^2 \Omega(x) = -4\pi \kappa \rho_e(x)$$

where $\kappa$ is the fundamental informational coupling constant mapping entanglement density to environmental interaction burden. The sign convention ensures that $\Omega$ increases in the vicinity of entanglement-dense regions, consistent with its interpretation as computational workload.

For an isolated system of total entanglement content $M$ localized at the origin ($\rho_e = M\delta^3(\mathbf{x})$), the spherically symmetric solution is:

$$\Omega(r) = \Omega_0 + \frac{\kappa M}{r}$$

where $\Omega_0$ is the background computational density of free space—the irreducible interaction workload of the vacuum. The overlap field diverges as $r \to 0$, reflecting unbounded computational congestion at the core of a maximally entangled system.

### 3. Derivation of Computational Time Dilation
Time ($\tau_{local}$) is not a background dimension; it is the subjective sequence of discrete update cycles experienced by subsystem $A$.

Because the universal interaction rate $R_c$ is strictly conserved, an increase in the required interactions ($\Omega$) stretches the duration of the local compute cycle. The differential of local proper time is the ratio of the fundamental interaction limit to the local interaction workload:

$$d\tau_{local} = \frac{R_c}{\Omega(x)} d\tau_{univ}$$

We define the **informational clock rate** $\phi(x)$ as the local rate of proper time advance per causal interval:

$$\phi(x) \equiv \frac{R_c}{\Omega(x)}$$

For the spherically symmetric solution $\Omega(r) = \Omega_0 + \kappa M/r$:

$$\phi(r) = \frac{R_c}{\Omega_0 + \kappa M/r} = \phi_\infty \cdot \frac{1}{1 + \dfrac{r_\Omega}{2r}}$$

where $\phi_\infty \equiv R_c / \Omega_0$ is the clock rate at spatial infinity and $r_\Omega \equiv 2\kappa M / \Omega_0$ is the **informational radius**—the scale at which the entanglement overlap field doubles the vacuum workload.

In the weak-field regime ($r_\Omega / r \ll 1$):

$$\phi(r) \approx \phi_\infty \left(1 - \frac{r_\Omega}{2r}\right)$$

This is structurally identical to the Schwarzschild weak-field limit:

$$\frac{d\tau}{dt} \approx 1 - \frac{r_s}{2r}$$

where $r_s = 2GM/c^2$ is the Schwarzschild radius. The correspondence demands $r_\Omega = r_s$, yielding:

$$\frac{\kappa}{\Omega_0} = \frac{G}{R_c^2}$$

This constrains the informational coupling constant entirely in terms of known physical constants, eliminating one free parameter from the framework.

As a subsystem approaches a dense entanglement network, $\Omega(x) \to \infty$ and $\phi(x) \to 0$. Gravitational time dilation is thus derived purely as localized computational lag, devoid of geometric spacetime curvature.

**Strong-field departure.** In the strong-field regime, the frameworks diverge. The Schwarzschild metric predicts a coordinate singularity at $r = r_s$ where $d\tau/dt = 0$. The informational clock rate $\phi(r) = \phi_\infty / (1 + r_\Omega/2r)$ is strictly positive for all $r > 0$, approaching zero only asymptotically as $r \to 0$. This framework therefore predicts no sharp event horizon—only asymptotically increasing time dilation. The observational consequences are discussed in Section 8.

### 4. Mass-Energy as Interaction Capacity
Under this framework, Einstein's mass-energy equivalence transitions from a kinematic description to a statement of latent informational capacity. The total energy $E$ of a localized subsystem is its intrinsic entanglement density ($M$) constrained by the square of the universal interaction rate:

$$E = M R_c^2$$

Energy represents the absolute maximum computational throughput a subsystem could execute if its complete entanglement structure were unbottlenecked by the environmental overlap field.

### 5. Gravity as the Gradient of Least Computational Action
A bound quantum system naturally evolves to advance its wave function with maximal computational efficiency. To maintain a state decoupled from a massive local environment requires breaking continuous mutual information bonds, demanding an interaction workload that exceeds $R_c$.

Gravity emerges as the entropic tendency of computationally bound subsystems toward regions of lower informational clock rate. The emergent force is derived from the gradient of $\phi(x)$:

$$\mathbf{F}_g = -\alpha \nabla \phi(x)$$

where $\alpha > 0$ is a proportionality constant encoding the test subsystem's coupling to the overlap field. Since $\phi(x)$ decreases toward entanglement-dense regions, $\nabla\phi$ points away from mass, and the force $-\nabla\phi$ points inward—attractive by construction. Subsystems are computationally entrained toward the dominant entanglement network: advancing their state in regions of lower $\phi$ requires fewer mutual information bonds to be resolved per interval, minimizing informational friction.

**Recovery of Newton's law.** In the weak-field limit, using $\phi(r) \approx \phi_\infty(1 - \kappa M/(\Omega_0 r))$:

$$\nabla\phi = \phi_\infty \frac{\kappa M}{\Omega_0 r^2}\hat{r}$$

$$\mathbf{F}_g = -\frac{\alpha \phi_\infty \kappa M}{\Omega_0 r^2}\hat{r}$$

Identifying $\alpha \phi_\infty \kappa / \Omega_0 = G$ for a unit test mass:

$$\mathbf{F}_g = -\frac{GM}{r^2}\hat{r}$$

Newton's inverse-square law is recovered exactly. The gravitational constant is expressed in terms of fundamental computational quantities:

$$G = \frac{\alpha R_c \kappa}{\Omega_0^2}$$

**Singularity regularization.** The full non-linearized force magnitude:

$$|\mathbf{F}_g| = \frac{\alpha R_c \kappa M}{r^2\left(\Omega_0 + \kappa M/r\right)^2}$$

approaches a finite constant $\alpha R_c / (\kappa M)$ as $r \to 0$, rather than diverging. The computational framework naturally regularizes the Newtonian gravitational singularity: the force saturates when the local interaction workload dominates the vacuum background. This provides a resolution to the classical point-mass divergence without requiring spacetime quantization or dimensional regularization.

### 6. Resolution of Spatially Separated Entanglement
By defining space strictly as an adjacency matrix of mutual information, the EPR paradox and non-locality are trivially resolved.

Two maximally entangled, isolated particles share a direct informational edge. Regardless of their apparent separation in the emergent macroscopic geometry, their intermediate interaction field is zero ($\Omega_{intermediate} = 0$).

When an interaction forces an update to their shared state, the absence of intermediate computational lag means the update requires exactly one causal interval:

$$d\tau_{update} = \frac{1}{R_c}$$

No causal speed limit is violated; the particles execute a single adjacent interaction, exposing geometric distance as an emergent illusion of the macroscopic observer's own processing requirements.

### 7. Correspondence with Existing Frameworks
This framework intersects with several independent research programs that have approached the geometry-information interface from distinct starting points.

**Jacobson's thermodynamic gravity (1995).** Jacobson derived the Einstein field equations by treating the Clausius relation $\delta Q = TdS$ as fundamental, applied to local Rindler horizons with entropy proportional to area [1]. Our framework shares the premise that gravity is not a fundamental force but an emergent consequence of information-theoretic constraints. The key distinction: Jacobson requires the Bekenstein-Hawking entropy-area relation as input; we derive the entropic gradient directly from the computational structure of the overlap field.

**Verlinde's entropic gravity (2011).** Verlinde proposed gravity as an entropic force arising from changes in information associated with the positions of material bodies, deriving Newton's law from holographic screen arguments [2]. Our Section 5 arrives at a structurally similar result—gravity as a gradient of informational cost—but replaces the holographic screen with the overlap field $\Omega(x)$, providing a microscopic mechanism (entanglement processing rate saturation) rather than a thermodynamic postulate.

**ER=EPR (Maldacena & Susskind, 2013).** The conjecture that entangled particles are connected by non-traversable Einstein-Rosen bridges [3] resonates directly with Section 6: two entangled particles share a direct informational edge regardless of macroscopic geometric separation. The ER=EPR framework is couched in AdS/CFT; we frame it computationally. Both approaches dissolve the paradox of non-locality by asserting that the entanglement connection is topologically prior to the emergent spatial geometry.

**Causal set theory (Bombelli, Lee, Meyer & Sorkin, 1987).** Causal set theory discretizes spacetime into a partially ordered set of events, with the order relation encoding causal structure [4]. Our fundamental causal interval $\tau_{univ}$ and the discrete execution of state updates share this commitment to fundamentally discrete causality. However, causal sets derive geometry from the order relation alone; we derive it from the entanglement adjacency structure, which carries richer informational content—specifically, the bond dimensions of the tensor network.

**Wolfram's computational universe (2020).** Wolfram's physics project models the universe as a hypergraph evolving by local rewrite rules, with space, time, and gravity emerging from the graph's large-scale structure [5]. The convergence is striking: both frameworks treat space as emergent from a network, time as discrete sequential computation, and the speed of light as a computational rate limit. The principal divergence lies in the substrate: Wolfram postulates classical rewrite rules on a hypergraph; we ground the dynamics in quantum entanglement and the Hilbert space structure of $|\Psi\rangle$.

**Tensor networks and It from Qubit.** The ongoing program connecting quantum information to spacetime geometry—particularly the Ryu-Takayanagi formula relating entanglement entropy to minimal surface area [6] and the identification of spacetime geometry with tensor network structure [7]—provides the closest existing formalism to this work. Our overlap field $\Omega(x)$ admits a natural interpretation as the bond dimension density in a MERA-like tensor network representation of the vacuum state, and the informational clock rate $\phi(x)$ as the local tensor contraction throughput. Van Raamsdonk's observation that reducing entanglement between subsystems increases their spatial separation [8] is precisely the mechanism underlying our definition of distance as interaction adjacency.

**Susskind's computational complexity (2014).** Susskind's proposal that the interior volume of a black hole grows with the quantum computational complexity of the boundary state [9] provides a complementary perspective. Where Susskind measures the growth of the wormhole interior, our framework measures the computational cost of resolving local state updates. Both identify a deep connection between gravity and the difficulty of quantum computation.

### 8. Experimental Predictions and Falsifiability
A framework that claims to replace geometric spacetime must generate predictions distinguishable from General Relativity. We identify three classes of observable consequence, ranging from near-term to aspirational.

**Prediction 1: Entanglement-dependent self-dilation.** In GR, the stress-energy tensor sources curvature and depends on mass-energy content alone, not on the quantum coherence structure of the source. In this framework, $\Omega$ is sourced by entanglement density $\rho_e$, which depends on the internal quantum correlations of a system—not merely its rest mass. A system's own entanglement contributes to its local overlap field, modifying the rate at which its internal processes evolve.

Consider a Bose-Einstein condensate of $N$ atoms in a state of near-maximal entanglement. The condensate's internal entanglement raises its local computational workload:

$$\Omega_{local} = \Omega_{ext} + \frac{\kappa_E S_E}{l_c}$$

where $\Omega_{ext}$ is the external overlap field (dominated by Earth), $S_E$ is the entanglement entropy of the condensate, $\kappa_E$ parameterizes the entanglement-specific coupling, and $l_c$ is the coherence length of the condensate. A thermal gas of equal mass and species, with $S_E \approx 0$ (no long-range entanglement), experiences only $\Omega_{ext}$. The framework predicts that the entangled system's internal clock rate is reduced relative to the thermal system:

$$\frac{\delta\phi}{\phi} \sim \frac{\kappa_E S_E}{\Omega_{ext} \, l_c}$$

*Experimental protocol (spectroscopic):* Compare atomic transition frequencies of atoms within a macroscopic BEC ($\sim 10^6$ atoms, $S_E \sim N\log 2$) against atoms in a decoherent thermal sample of equal mass and species, after subtracting known mean-field and density shifts. The framework predicts a residual redshift of the BEC transitions proportional to $S_E$. Current spectroscopic precision ($\Delta f/f \sim 10^{-19}$, [10]) is sufficient to detect or exclude this effect, contingent on the magnitude of $\kappa_E$.

*Experimental protocol (free fall):* If the coupling constant $\alpha$ in $\mathbf{F}_g = -\alpha\nabla\phi$ depends on a test system's internal entanglement structure, a BEC and a thermal gas of equal mass should fall at measurably different rates—a violation of the weak equivalence principle specific to quantum-coherent matter. Atom interferometry experiments already constrain equivalence principle violations at the $10^{-12}$ level; a differential between coherent and decoherent samples would constitute direct evidence for entanglement-sourced gravity.

**Prediction 2: Absence of a sharp event horizon.** As derived in Section 3, the informational clock rate $\phi(r)$ is strictly positive for all $r > 0$. The framework predicts no event horizon at the Schwarzschild radius—only asymptotic time dilation. For astrophysical black holes, infalling matter never crosses a causal boundary; it accumulates in an ultra-dilated shell.

This modifies the expected quasi-normal mode spectrum of black hole ringdown. The corrections to the Kerr metric prediction scale as:

$$\frac{\delta\omega}{\omega_{QNM}} \sim \mathcal{O}\left(\frac{r_\Omega^2}{r_s^2} - 1\right)$$

With LIGO/Virgo/KAGRA achieving sub-percent precision on ringdown frequencies [11], deviations at the percent level would be resolvable. The Event Horizon Telescope's shadow observations [12] provide a complementary constraint: the predicted shadow diameter differs from the Kerr prediction by a factor dependent on the strong-field form of $\phi(r)$.

**Prediction 3: Discrete time noise floor.** If time is fundamentally discrete with fundamental interval $\tau_{univ}$, the most precise clocks should encounter an irreducible noise floor uncorrelated between independent clocks, with a white spectrum up to frequency $\nu_{max} = 1/\tau_{univ}$ and a hard cutoff above. If $\tau_{univ} \sim t_P \approx 5.4 \times 10^{-44}$ s, the effect lies far below current sensitivity. However, this framework does not mandate $\tau_{univ} = t_P$; the causal interval is a free parameter that experiment can constrain from above. Cross-correlation analysis of geographically separated optical lattice clocks could place progressively tighter upper bounds on $\tau_{univ}$, testing the discrete-time hypothesis without requiring Planck-scale resolution.

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
