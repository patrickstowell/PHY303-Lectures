## Radioactive Decays

### Introduction 
As we saw in the previous unit, nuclei in excited states can emit radiation in the form of gamma rays when nucleons move between different shell levels. This explains one of our three dominant sources of radiation. What about the others, $\beta$ and $\alpha$ decay?

These become a bit trickier to solve, as both decays lead to a fundamental change in the nucleon content inside the nucleus itself. As a reminder, in all cases of radioactive decay, we characterize the process in terms of three important numbers:

- The probability of decay per unit time $\rightarrow \lambda$
- The average time a nucleus lasts before decay $\rightarrow \tau = 1/\lambda$
- The time for half the sample to decay (half-life) $\rightarrow T_{1/2} = \tau \textnormal{ln}(2) = 0.693\tau$

Radioactive decay itself is a stochastic process. That is why we define it in terms of the average times it takes bulk samples of material to decay. The main thing that governs the rate of this decay in a nucleus is actually whether the process is energetically favorable or not. In gamma radiation we saw it was almost always energetically favorable for an excited nuclear state to drop down some energy levels by emitting radiation.

What about other forms of radiation? In alpha and beta radiation the nucleus physically changes from one type to another. It turns out that a nucleus is likely to be unstable and decay through these channels if the net energy of the final products $E_{f}$ is less than that of the starting nucleus $E_{i}$. This energy deficit is defined as: 

$$
Q = M(A,Z)^{2}c^{2} - [M(A-X,Z-Y)c^{2} + M(X,Y)c^{2}] > 0 
$$

Decay is possible only if the $Q$ value is positive, and the decay is not disallowed by any other selection rule or conservation law. The energy released in the decay will come out in the kinetic energy of the release fragments in the decay. Let's consider both beta decay and alpha decay in turn to see how theoretical concepts of the nucleus help us understand their behaviour.


### 6.3 Beta Decay

In beta decay we typically see experimentally an emission of an Electron from the nucleus combined with a transmutation of a nucleus from one type into another with a lower neutron number. This is referred to as beta-minus decay and typically occurs in neutron rich nuclei which are trying to lower their energy by rebalancing their proton/neutron ratios. 

In the early years of Beta Decay studies the process observed was highly mysterious and showed very different a behaviour to Alpha Decay which was being studied at a similar time. This is illustrated by the Cloud Chamber image shown below. We see the decay of $^6$He into $^6$Li and a charged electron. We see two tracks, curving because there is a magnetic field applied. But from analysis of the plot it looks like energy, momentum and even Total Angular Momentum $J$ are not conserved if we assume the interaction:


$ ^6He \rightarrow ^6Li + e^- $

Of course the reason is that there is a Neutrino emitted as well, but this escapes the detector and we don’t see it. There are actually four things we need to consider in beta-minus(-plus) decay not just the neutrino.

1. Beta Decay is a Three-body Process, unlike alpha decay (two body). We have to account for the energies and behaviour of 3 objects - the nucleus, the beta and neutrino.
2.  The electron (positron) and neutrino produced do not exist before the decay, we need to account for their formation.
3. The electron and neutrino are relativistic, unlike the alpha in alpha decay. This makes calculations of the energies and kinematics of the decay more complicated.
4. The energy of the beta emitted by the nucleus in question is not the same in every decay. We get a continuum of energies put to a maximum. In contrast to alpha decay and gamma decays where we get one “Monoenergetic” particle depending on the energy levels or $Q$ value considered.


An example to illustrate this behaviour is:

$$
\bf
 _{83}^{210}Bi \rightarrow _{84}^{210}Po + e^- + \bar{\nu}_e 
$$

Note how with an electron emitted in beta decay we get an Anti-neutrino (this is Lepton Number conservation in particle physics)

Beta decay is a common type of radioactive decay that involves the transformation of nucleons within the nucleus, resulting in the emission of beta particles and a change in the nuclear charge. There are three main types of beta decay: electron emission (\(\beta^-\) decay), positron emission (\(\beta^+\) decay), and electron capture (EC). Each of these processes alters the nucleus in distinct ways, driven by the weak nuclear force. Here's a breakdown of their differences:

### Electron Emission (\(\beta^-\) Decay)

- **Process:** In \(\beta^-\) decay, a neutron inside the nucleus is transformed into a proton, an electron (\(e^-\)), and an electron antineutrino (\(\bar{\nu}_e\)).
  
- **Equation:** \(n \rightarrow p + e^- + \bar{\nu}_e\)

- **Result:** The atomic number (\(Z\)) of the nucleus increases by one, while the mass number (\(A\)) remains unchanged. This process leads to the element changing to its next higher neighbor in the periodic table.

- **Driving Force:** \(\beta^-\) decay occurs in neutron-rich nuclei, where the neutron-to-proton ratio is higher than that for a stable isotope of the element.

### Positron Emission (\(\beta^+\) Decay)

- **Process:** In \(\beta^+\) decay, a proton is converted into a neutron, a positron (\(e^+\)), and an electron neutrino (\(\nu_e\)).
  
- **Equation:** \(p \rightarrow n + e^+ + \nu_e\)

- **Result:** The atomic number (\(Z\)) decreases by one, but the mass number (\(A\)) remains the same. The element changes to its previous neighbor in the periodic table.

- **Driving Force:** \(\beta^+\) decay is favored in proton-rich nuclei, where the proton-to-neutron ratio is higher than the stable ratio for that element. It requires more energy than \(\beta^-\) decay, as the mass of the nucleus must compensate for the mass of the positron and the difference in mass between protons and neutrons.

### Electron Capture (EC)

- **Process:** In electron capture, an inner orbital electron is captured by a proton in the nucleus, resulting in the formation of a neutron and the emission of an electron neutrino.
  
- **Equation:** \(p + e^- \rightarrow n + \nu_e\)

- **Result:** Similar to \(\beta^+\) decay, electron capture decreases the atomic number by one without changing the mass number, shifting the element to its previous neighbor in the periodic table.

- **Driving Force:** EC also occurs in proton-rich nuclei and can be thought of as an alternative to \(\beta^+\) decay, especially in cases where the energy difference between the initial and final states does not favor positron emission. It strongly competes with e^+ decay and is the only decay available to nuclei with a Proton Excess if the mass difference between the atoms is less than 1 MeV/c^2.

### Energy Considerations and Occurrence


Note we have to be careful in Beta Decay to consider the mass of everything including the Atomic Electrons, not just the nucleons. Hence the mass used are atomic masses, not the nuclear masses. We were less careful earlier when dealing with Binding Energy calculations and the SEMF.

- **\(\beta^-\) Decay:** This process is energetically favored in neutron-rich nuclei and does not require additional energy to occur since the mass of the neutron is greater than that of the proton.

- **\(\beta^+\) Decay and EC:** Both require the nucleus to have excess energy because the mass of a neutron is less than that of a proton (when considering the mass of the positron for \(\beta^+\) decay or the binding energy of the captured electron for EC). These processes are less common than \(\beta^-\) decay due to the energy requirements and occur in proton-rich nuclei.





In beta decay, transitions between nuclear states are classified as "allowed" or "forbidden" based on certain selection rules derived from conservation laws and quantum mechanics. These rules are related to the spin (\(J\)) and parity (\(P\)) of the initial and final nuclear states, as well as the angular momentum and parity of the emitted beta particle and neutrino system. 

### Allowed Transitions

Allowed transitions are those that require the least change in angular momentum and have no change in parity between the initial and final states. The simplest case is the "superallowed" transition, which involves no change in nuclear spin and parity (\(\Delta J^P = 0^+\)) and is the most favorable in terms of transition probability.

**Equation for Superallowed Transition:**
\[ \Delta J = 0, \quad \Delta P = 0 \]

Here, \(\Delta J\) represents the change in total angular momentum quantum number, and \(\Delta P\) represents the change in parity; \(0^+\) indicates no change in either.

For "allowed" transitions (not superallowed), the changes are still minimal:
\[ \Delta J = 0 \text{ or } \pm 1, \quad \Delta P = 0 \]
except for \(0 \rightarrow 0\) transitions, which are forbidden.

These transitions are characterized by a high transition probability because they involve minimal changes in the nuclear state, making them the most common type of beta decay.

### Forbidden Transitions

Forbidden transitions occur when the change in angular momentum and/or parity does not meet the criteria for allowed transitions. They are less likely to occur due to the need for higher changes in angular momentum between the initial and final states. Forbidden transitions are categorized by the degree of "forbiddenness," which corresponds to the change in angular momentum of the emitted particles.

**First Forbidden Transition:**
\[ \Delta J = 0, \pm 1, \pm 2, \quad \Delta P = 1 \]
except for \(0 \rightarrow 0\) transitions, which are still forbidden.

In general, the "n-th forbidden" transition is characterized by:
\[ \Delta J = n, n \pm 1, n \pm 2, ..., \quad \Delta P = n \, (\text{mod} \, 2) \]

The transition probability decreases significantly with increasing order of forbiddenness, making higher-order forbidden transitions increasingly rare.

### Beta Decay Matrix Element

The probability of a beta decay occurring is proportional to the square of the matrix element, \(M\), which depends on the overlap of the initial and final nuclear wave functions and the operators involved in the transition. For allowed transitions, the matrix element involves simpler operators (e.g., Fermi and Gamow-Teller operators), while for forbidden transitions, more complex operators that include higher angular momentum components are required.

### Selection Rules Impact

- **Superallowed and Allowed Transitions:** These transitions are most likely to occur and have the shortest half-lives. They involve minimal changes in nuclear configuration and are dominated by the conservation of angular momentum and parity.
  
- **Forbidden Transitions:** These require more significant changes in the nuclear state, leading to longer half-lives and lower transition probabilities. They are crucial for understanding nuclear structure and the weak interaction, especially in nuclei far from stability.

Understanding allowed and forbidden transitions in beta decay is essential for interpreting nuclear decay patterns, predicting half-lives, and studying nuclear structure and weak interaction processes.

To determine if a beta decay transition is allowed or forbidden, we need to look at the change in angular momentum (\(\Delta J\)) and parity (\(\Delta P\)) between the initial and final states of the nucleus. Here's a step-by-step example using hypothetical nuclear states to illustrate how to calculate and classify a transition.

### Example: Beta Decay of Nucleus X to Y

Suppose we have a beta decay process where nucleus X decays to nucleus Y. Let's say:

- The initial state of nucleus X has a total angular momentum quantum number \(J_i = 2\) and positive parity (\(P_i = +1\)).
- The final state of nucleus Y has a total angular momentum quantum number \(J_f = 1\) and negative parity (\(P_f = -1\)).

### Step 1: Calculate the Change in Angular Momentum (\(\Delta J\))

\[ \Delta J = |J_f - J_i| = |1 - 2| = 1 \]

### Step 2: Determine the Change in Parity (\(\Delta P\))

Since the parity changes from positive to negative, there is a change in parity (\(\Delta P = 1\)).

### Step 3: Classify the Transition

Using the calculated \(\Delta J\) and \(\Delta P\), we can classify the transition. For allowed transitions, we expect \(\Delta J = 0\) or \(\pm 1\) (excluding \(0 \rightarrow 0\) without a change in parity), and \(\Delta P = 0\).

- In our example, \(\Delta J = 1\) fits the criterion for \(\Delta J\) in allowed transitions, but the change in parity (\(\Delta P = 1\)) indicates this is a **forbidden transition**.
- Specifically, since there's a change in parity and the \(\Delta J\) value fits within the first forbidden category (considering \(\Delta J = 0, \pm 1, \pm 2\) with a parity change), this would be a **first forbidden transition**.

### Conclusion

The transition from nucleus X to nucleus Y in our example is classified as a first forbidden transition due to the change in both angular momentum (\(\Delta J = 1\)) and parity (\(\Delta P = 1\)). Forbidden transitions are less probable than allowed transitions, meaning they typically have longer half-lives.

This example demonstrates the basic method to determine whether a beta decay transition is allowed or forbidden based on the initial and final states' angular momentum and parity. This classification helps predict the decay's likelihood and its half-life, providing insight into the nuclear structure and the weak interaction's role in nuclear processes.



For an example of an allowed transition in beta decay, let's consider the beta-minus decay of tritium (\(^3H\)) to helium-3 (\(^3He\)). This decay is interesting because it's a simple case often cited in discussions of nuclear beta decay and provides a clear illustration of an allowed transition.

### Nucleus Details:

- **Tritium (\(^3H\))** has one proton and two neutrons. Its nuclear spin and parity (\(J^P\)) are \(1/2^+\) in its ground state.
- **Helium-3 (\(^3He\))** has two protons and one neutron. Its ground state also has a nuclear spin and parity of \(1/2^+\).

### Beta-minus Decay Process:

In this decay, one of the neutrons in tritium is converted into a proton, emitting an electron (\(e^-\)) and an electron antineutrino (\(\bar{\nu}_e\)):

\[ ^3H \rightarrow \, ^3He + e^- + \bar{\nu}_e \]

### Step 1: Calculate the Change in Angular Momentum (\(\Delta J\))

Given that both the initial and final states have spins of \(1/2\), the change in angular momentum is:

\[ \Delta J = |J_f - J_i| = |1/2 - 1/2| = 0 \]

### Step 2: Determine the Change in Parity (\(\Delta P\))

Both the initial and final states have positive parity (\(+\)), so there is no change in parity:

\[ \Delta P = 0 \]

### Step 3: Classify the Transition

For the transition to be allowed:
- \(\Delta J = 0\) or \(\pm 1\) (excluding \(0 \rightarrow 0\) without a change in parity)
- \(\Delta P = 0\)

Our transition meets these criteria (\(\Delta J = 0\) and \(\Delta P = 0\)), indicating it is an **allowed transition**.

### Conclusion

The beta-minus decay of tritium (\(^3H\)) to helium-3 (\(^3He\)) is an example of an allowed transition in nuclear beta decay. Since the transition involves minimal changes in angular momentum and no change in parity, it falls into the category of allowed transitions, which are characterized by higher transition probabilities and shorter half-lives compared to forbidden transitions.

This example illustrates the criteria for allowed beta decay transitions within the context of the nuclear shell model, showing how nuclear quantum numbers play a crucial role in determining the nature and likelihood of beta decay processes.



#### 6.3.2 Applied Beta Physics
- As described earlier there are many applications of beta decay. Notable is Positron Emission Tomography.
Patients are injected with a positron emitting isotope. The positron finds an electron and Annihilates to produce two back to back gammas that can be detected and hence used to find the location of the decay, and hence image, say, the brain.
PET is an example application
$ _{9}^{18}F \rightarrow _{8}^{18}O + e^+ + $\nu_e$ $
- Often the Decay Sequence is depicted as an Energy Level Diagramme as in this example:
  
For beta decay we should have a diagram showing how the shell orbitals can change.

![Alt text](image-112.png)


### 6.4 Fermi Theory
- Fermi Theory results in an equation for dn/dE given as:

$$
\frac{dn}{dE} = \frac{16 \pi^2 \nu^2 }{h^6 c^3} (T_{max} - T_e)^2 p_e dp_e 
$$

- Here we have V as the volume of the nucleus and $ T_e (p_e) $ is the energy (momentum) of the electron. $ T_{max} $ is the maximum energy that the electron can have. Note that at this energy the neutrino must have zero energy and that $ T_{max} $ is equivalent to the Q of the reaction.
- Putting this into the equation for $ W_{fi} $ and just noting that $ P(p_e) $ is equivalent to the number rate of events or intensity $ N(P_e) $ we see most things are constants and we can say:
  
$$
 P(p_e) = N(p_e) \propto \frac{(T_{max} - T_e)^2}{p_e^2} 
$$

- Note here how the function vanishes at the point when $ T_e = T_{max} $. This is called the Beta Decay Endpoint. This Endpoint is the subject of much research in physics because everything we have stated so far assumes the neutrino has no mass. If this is not the case then the Endpoint will shift slightly.

A better way to study this Endpoint has been developed, called the Fermi-Kurie Plot. This simply rearranges the equation noting that:

$$
 (T_{max} - T_e)^{0.5} \propto \sqrt{\frac{N(p_e)}{p_e^2}} 
 $$ 

![Alt text](image-113.png)


### 6.2 Alpha Decay

First, let's start to use our newfound understanding of nuclear structure to try to understand alpha decay. There are some important questions we need to ask for this process:
- Why are the $\alpha$ particles emitted and not some other combination of nucleons?
- Why is there such a range of lifetimes and energies? What is the relationship between the two? 
- What determines the frequency of $\alpha$ decay?
- How are the $\alpha$ particles formed in the nucleus and emitted?
- Do alphas carry information on nuclear structure?

One plot that begins to answer some of these questions is a comparison of the $Q$ energy for different alpha-emitting particles separated by different radioactive decay series. This is called the Geiger-Nuttall relation, and it demonstrates that actually for many different series, there is a strong correlation between the radioactive half-life and the energy of the emitted alpha.

![Alt text](image-103.png)

Notice also how steep the relation is in the Geiger-Nuttall plot (it's a log scale). An alpha emitter that produces 8 MeV alpha particles is likely to have a half-life over 22 orders of magnitude shorter than one which produces alphas of 4 MeV kinetic energy. The Geiger-Nuttall relation is a fit to the observed data of the form:

$$
\log_{10} t_{1/2} = b_{1} \frac{Z}{Q^{1/2}} + b_{2}
$$

where Z is the number of protons, Q is the energy released, $b_{1}$ and $b_{2}$ are constants. An equivalent form is:

$$
\ln\lambda = -a_{1} \frac{Z}{Q^{1/2}} + a_2
$$

It turns out that trying to understand why the data follows this shape leads us once again to the need for a quantum mechanical treatment of Alpha Decay. To explain the relation, it turns out we need to consider that the alpha forms inside the nucleus and then escapes by Quantum Mechanical Barrier Penetration. The alpha is envisioned as a free-particle wavefunction subject to a combination of the Nuclear Potential binding it to the nucleus, and a coulomb potential that repels it from the other charged particles in the nucleus. Typically we expect a coulomb repulsion to pulse the charged alpha away from the rest of the nucleus, but in this case we are imagining that the alpha is **inside** the rest of the nucleus, therefore the remaining protons form a charged barrier that the alpha needs to tunnel through to escape. The Coulomb barrier arises because the electrostatic force is repulsive between two positively charged entities—the alpha particle and the rest of the nucleus. As the alpha particle gets closer to the nuclear surface (from within), the electrostatic potential energy increases because the repulsive force increases. At the surface of the nucleus, this potential energy reaches a maximum, forming the Coulomb barrier.

Inside the Nucleus: While inside the nucleus, the alpha particle is bound by the strong nuclear force, which is attractive and much stronger than the Coulomb force at short distances. This force keeps the nucleons (including those in the alpha particle) together.
Escape Requirement: For the alpha particle to escape, it must have enough energy to overcome the maximum potential energy at the surface created by the Coulomb repulsion. Typically, the alpha particle's kinetic energy (within the nucleus) is insufficient to overcome this barrier due to the energy binding it inside the nucleus.



![Alt text](image-130.png)

Of course, in a classical model, if the **Potential Barrier** is too high, the alpha never escapes. In Quantum Mechanics, we allow **Tunneling** with a small probability that the alpha can penetrate the barrier. Calculating the ratio of the wavefunctions inside and outside and squaring gives the probability. We can do a simple calculation of this by considering the diagram of the potential below. We assume the alpha is pre-formed in the nucleus, oscillates around, repeatedly hitting the edge inside the nucleus until at some point it escapes by **Barrier Penetration**. Once formed, the alpha particle finds itself in a potential well created by the nuclear forces. Outside this well, there's a potential energy barrier formed by the Coulomb repulsion between the positively charged alpha particle and the rest of the nucleus. Classically, the alpha particle would need to have kinetic energy greater than this barrier to escape the nucleus. However, typically, the alpha particle's kinetic energy is less than the height of this Coulomb barrier

![Alt text](image-131.png)


Notice how the Potential Barrier drops as $1/r$. Rather than try to solve this, we can make a simple approximation that the barrier has a fixed height $U_0$ and fixed length $L$, and that the alpha has energy $E$, as illustrated below. Also, the potential seen by the alpha particle is spherically symmetric, and so the quantum mechanical problem can be approached by first separating the variables into just a radial component.


![Alt text](image-135.png)
As a particle approaches the barrier, it is described by a Free Particle Wavefunction. When it reaches the barrier, it must satisfy the simplified Schrödinger Equation in the form:

$$
-\frac{\hbar^2}{2m} \frac{d^{2}}{dr^{2}} \psi(r) = [E - U_0]\psi(r) \\
$$

Solving this QM equation of simple Barrier Penetration is beyond our scope here. What is important is the result. It gives us a value for $X$, the probability of barrier penetration as:

$$
X = Ae^{-αL}
$$

where $α = \sqrt{(2m(U_0 - E))/\hbar^2}$ is called the Gamow Factor, and $A$ is a normalization constant we will call 1 for now to make the derivation simpler. Now, if we assume the alpha makes contact with the barrier once every second, then the average probability that the alpha leaves (a decay takes place) and the half-life is just related to the tunneling probability by:

$$
\lambda = \sqrt{X} \\
T_{1/2} = \ln(2)/\lambda = \ln(2)/\sqrt{X}
$$

If the alpha hits the barrier faster than 1 Hz, then we expect the probability that it leaves the nucleus to scale upwards as well. If we can work out the frequency that the alpha hits the barrier, which will be determined by its velocity and the size of the nucleus, and we know the height of the barrier $U_0$ and the width $L$ and the energy of the alpha $E$, then we can find the half-life $T_{1/2}$. We can then see if this agrees with the Geiger-Nuttall observation from data.

The way to proceed is illustrated below, where we attempt to find the half-life of 212Po, which emits an 8.78 MeV alpha.  First, we need to find the width of the barrier. For this, we need to know the Nuclear Separation $R$, i.e., the distance between the center of the nucleus and the center of the alpha. Be careful that at this point the nucleus we are talking about is not A=212, but A=208, because we have removed the alpha.


![Alt text](image-134.png)

This results in an estimate of the nuclear seperation as
$$
R= 1.2(A)^{1/3} + 1.2(208)^{1/3} = 9.01~\textnormal{fm}
$$
We now find the height of the barrier by applying Coulomb’s Law at the nuclear separation as illustrated here
$$
\frac{(k\cdot 2e \cdot (Z - 2)e)}{r} = \frac{(2\cdot (82-2) \cdot 1.44~\textnormal{MeV fm})}{9.01~\textnormal{fm}} = 26.21~\textnormal{MeV}
$$

where $k$ is equal to coulombs constant $k = 1/(4πε_0) = 8.987552 \times 10^9 N m^2/C^2$. Now the distance at which the Coulomb Potential drops to the level of energy of the observed alpha is:

$$
8.78 MeV = \frac{2(82)1.44 MeV·fm}{r} \rightarrow r = 26.9 fm
$$

So the barrier width L and gammow factor is:

$$
L = 26.90 fm - 9.01 fm = 17.9 fm \\
\alpha = \sqrt{\frac{2m(26.2-8.78)}{\hbar^{2}}} = 1.879 fm^{-1}
$$

This results in a transmission probability of 
$$
X = e^{-\alpha L} = e^{- (1.879) \cdot (17.9) } = 2.47 \times 10^{-15}
$$

The real frequency of the alpha hitting the barrier can als be estimated by determining how many times an alpha of energy $8.78 MeV$ makes contact with the walls.
$$
8.78MeV = \frac{mv^{2}}{2} \rightarrow v=2.06 \times 10^{7} ms^{-1} \\
f=\frac{v}{2R}  \rightarrow 1.14 \times 10^{21} s^{-1}
$$


For a given alpha, the combined Tunnelling Probability per second for emission is therefore the product f the barrier frequency and the transmission

$$
\lambda = f X = (2.47 \times 10^{-15})(1.14 \times 10^{21} s^{-1}) = 2.82 \times 10^6 s^{-1} 
$$



$$
 T_{1/2} = \frac{\ln 2}{\lambda} = \frac{0.693}{2.82 \times 10^6 s^{-1}} = 2.5 \times 10^{-7} s = 0.25 \mu s 
$$


<!-- ![Alt text](image-106.png) -->
The result is quite good. But note we could do better by modelling the potential as a series of decreasing barriers. As shown in the figure below we consider the decaying barrier as a combination of many fixed height barriers. The transmission probability through the entire set of barriers is simply obtained by multiplying all their individual transmission probabilities together.

![Alt text](image-132.png)

This can be written as:

$$
 X = X_1 \times X_2 \times X_3 \times ... \times X_n = A exp \left( -\frac{1}{\hbar} \sum(\sqrt{ 2m(U_{i}-Q) }) \cdot \Delta r \right)
$$

In the limit as $\Delta r \rightarrow 0$, this analysis turns into an integral from R up to $r_{2}$ based on the known form of $V(r) \propto r^{-1}$

$$
X = exp \left( -\frac{1}{\hbar} \int_{R}^{r_{2}} \sqrt{2m(V(r) - Q)} \cdot dr \right)
$$

No we can calculate the potential difference in the Gamow factor as based on the potential

$$
V(r) = \frac{2Ze^{2}}{4\pi \epsilon_{0}} \frac{1}{r}
$$

We have defined $r_{c}$ as the point where 

$$
Q = V(r_{c}) \rightarrow r_{c} = \frac{2Ze^{2}}{4\pi \epsilon_{0}} \frac{1}{Q}
$$

Now subbing this back into our potential tells us $V(r_{c})$ based only on $Q$, $r$, and $r_{c}$ results in a potential dependent on $Q$

$$
V_{c}(r) = \frac{Q r_{c}}{r}
$$

Subbing this into our integral gives us a transmission of the form

$$
X = exp \left( -\frac{1}{\hbar} \int_{R}^{r_{2}} \sqrt{2m(\frac{Q r_{c}}{r} - Q)} \cdot dr \right) \\
$$

where we can pull the $Q$ value out of the integral

$$
X = exp \left( -\frac{Q}{\hbar} \int_{R}^{r_{2}} \sqrt{2m(\frac{ r_{c}}{r} - 1)} \cdot dr \right)
$$

$$
X = exp \left( \frac{Q}{\hbar}\left[ \frac{2}{3} r \left( \frac{r_{c}-r}{r}\right)^{2/3} \right ]_{R}^{r_{2}} \right)
$$

$$
X = exp \left( \frac{Q}{\hbar}\left[ \frac{2}{3} R \left( \frac{(a/Q)-R}{R}\right)^{2/3} \right ]_{R}^{r_{2}} \right)
$$


Rearrangeing this ends up in a final form where our ttransmission factor
$$
G=\alpha L \propto \frac{Z}{Q}
$$

The alph emission rate depends upon how many times the alpha with its energy 8.78 MeV inside the nucleus will hit the walls.

Since an alpha at this energy is nonrelativistic. The frequency of hitting the walls is then as here:
$$
8.78 MeV = \frac{mv^{2}}{2} = \frac{3727 MeV v^{2}}{2c^{2}}
$$

$$
\frac{v}{c} = 0.00686; v=2.06 \times 10^{7} m/s
$$

$$
f=\frac{v}{2R} = \frac{2.06 \times 10^{7} m/s}{2(9.01 fm) (10^{-15}m/fm)} = 1.14 \times 10^{21} / s
$$

So the half-life for a single rectangular barrier with height equal to the peak of the barrier of 26.2 MeV and width 17.9 fm is: 

$$
X=Ae^{-\alpha L} = e^{-\gamma} = 2.47\times10^{-15}
$$

$$
\alpha = \sqrt{\frac{2m(U_{0} - E)}{\hbar^{2}}}
$$

Here $U_{0} = 26.2 MeV and E=8.78 MeV, and L = 17.9fm.$

So this basic Alpha Tunnelling Model allows us to predict the relationship between alpha energy and half-life of the decay, and it nicely fits with the Geiger-Nuttall relation. We had to make some assumptions, like the nucleus being spherical etc. (which is dangerous as we have seen) but it can get us very close to the data. Here is an example plot:

$ \ln \lambda = -a'\frac{Z}{Q^{1/2}} + a_2 $

$$
F=4 Z \alpha \frac{2m c^{2}}{E_{a}}^{1/2} \left( cos^{-1} \sqrt{\frac{R}{r_c}} - \sqrt{\frac{R}{r_{c}}\left( 1-\frac{R}{r_{c}}\right)} \right)
$$

$$
Last term goes to pi/2 if R << r_{c}
$$

$$
G \propto \frac{Z}{\sqrt{E_{\alpha}}}
$$

$$
t_{1/2} \propto \lambda = T w(\alpha) \frac{v_{alpha}{2R}} \propto e^{-G} e(\alpha) \frac{v}{2R}
$$

Taking the log of the equtaion gives us that belw which matches our geiger nutall foorm.
$$
log_{10} t_{1/2} = a + b Q_{\alpha}^{-1/2}
$$



Alpha decay, unlike beta decay, does not involve the transformation of nucleons from one type to another within the nucleus (such as a neutron to a proton or vice versa). Instead, alpha decay is the process by which an unstable nucleus emits an alpha particle (a \(^4He\) nucleus consisting of 2 protons and 2 neutrons) to become a more stable nucleus. The shell model and transition rules for alpha decay primarily focus on the change in the configuration of the remaining nucleus after the alpha particle is emitted.

### Shell Model and Alpha Decay

In the context of the nuclear shell model, alpha decay can be understood in terms of the rearrangement of the nucleons in the daughter nucleus and how this rearrangement affects the nuclear stability. The shell model predicts that nuclei near magic numbers (where shells are either fully filled or empty) are more stable. Thus, alpha decay often moves a nucleus closer to these magic numbers, thereby increasing its stability.

### Transition Rules for Alpha Decay

While the selection rules for alpha decay are not as strictly defined as for beta decay in terms of angular momentum and parity changes, the energy and stability considerations play a crucial role. The key factors influencing alpha decay include:

1. **Q-Value:** The energy release (\(Q\)-value) in alpha decay is a critical factor. The decay can only occur if the \(Q\)-value is positive, meaning the mass of the parent nucleus is greater than the combined mass of the daughter nucleus and the alpha particle. The \(Q\)-value is given by:

   \[ Q = [M(P) - M(D) - M(\alpha)]c^2 \]

   where \(M(P)\) is the mass of the parent nucleus, \(M(D)\) is the mass of the daughter nucleus, \(M(\alpha)\) is the mass of the alpha particle, and \(c\) is the speed of light.

2. **Nuclear Shell Effects:** The shell model predicts that nuclei with a full shell of protons or neutrons (magic numbers) are particularly stable. Alpha decay often results in a daughter nucleus that is closer to these magic numbers, making the decay more favorable if the parent nucleus is not near these numbers.

3. **Overlap and Tunneling:** The probability of alpha decay is also determined by the quantum mechanical tunneling effect. The alpha particle must overcome a potential barrier (Coulomb barrier) to escape the nucleus. The probability of tunneling depends on the height and width of the barrier and the energy of the alpha particle. This is described by the Gamow factor, which plays a significant role in determining the half-life of the alpha decay process.

### Conclusion

In summary, while the shell model and its transition rules for beta decay focus on angular momentum and parity changes, the considerations for alpha decay within the shell model framework are more about the energetics of the decay process, the stability of the daughter nucleus in terms of its proximity to magic numbers, and the quantum mechanical tunneling effect. The shell model helps explain why certain nuclei are more prone to alpha decay and how the structure of the daughter nucleus affects the decay's likelihood and rate.




### Summary
In this unit we've discussed the final dominant radioactive decay channels and the effect these can have on the nucleon content of a nucleus, and the various factors that need to be considered when trying to calculate their probability and daughter product kinetic energies.

In the next half of this course we'll start to look at different possible reactions with nuclei in more detail before looking at how knowledge of nuclear structure and decays can be used in applied physics.


