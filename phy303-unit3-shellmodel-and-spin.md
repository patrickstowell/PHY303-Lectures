## Unit 3 : Shell Model

We've seen how study of the binding energy curve for nuclei and basic features like the chart of stability has led to an empirical formula for the binding energy and the mass of nuclei through the semi empirical mass formular.

However notice how this derivation was only possible by merging two different concepts for nuclei. Firstly, regarding the nucleus as a single drop of Nuclear Material which acts as a Collective Body.  Secondly a concept that starts at to look at the quantum beehaviour of individual nucleonts and that they somehow lie in specific (and restricted) Energy Levels. So we have two sorts of model, a Collective Body Model, and an Individual particle Model coming together. They Assymetry Term and Pairing Term in the SEMF can only be explained assuming this second concept.

We find evidence not only that we need to account for the preference for pairing and balance between neutrons and protons, but also that specific numerical N and Z combinations have very different properties.

This results in the observation of Magic Number Nuclei, 
Magic Nuclei - **Z or N=2, 8, 20, 28, 50, 82, 126...**

These nuclei have particularly stable properties, and mark a transition point for nuclei such that those with $Z$ or $N$ below a given Magic Number have very different behaviour to those above. This leads to the idea that nucleons in nuclei somehow lie in **Concentric Shells**, analogous (but very different) to the way electrons lie in shells in atoms and similarly that a "filled" outer shell produces a more stable configuration

This shell model idea is of course tied up with introducing Quantum Mechanics to our nucleus. The basis of QM here as seen before, is that we introduce a nuclear potential well. It is the QM treatment of this Well that will determine (1) the energy levels (shells) that nucleons are allowed to occupy, and (2) how many nucleons can occupy each level.

As an example the simplest model for the Nuclear Well might be that associated with a Harmonic Oscillator, resulting in equally spaced energy levels throughout the well.

![Alt text](image-19.png)

But first notice how off the idea is. In atomic physics the well that binds the electrons is the positively charged nucleus. But in this case, the nucleons are somehow orbiting in a potential of their own making. Can this reaelly work? The nucleons are tightly bound in the nucleus with a radius much smaller than the case for electron orbitals. Why don't they collide if they are orbiting in shells? 

This looks like big step to take away from our SEMF so first let's start by looking at what real evidence we have for a shell-like structure anyway. In fact we can list 8 things starting with a few charts we have already covered.


#### 5.2 Shell Model Evidence

##### 5.2.1 Binding Energy Shape
The SEMF does a good job oon the basic shape, but a closer look reveals certain nuclei have much higher, or lower B/A than predicted even after our assymetry and pairing terms are included. These are most obvious at low A where peaks appear in multiples of 4 nucleons (e.g. 12C, 18O).

In general nuclei with Magic Number N and/or Z have a higher B/A indicating they are more tightly bound.

![Alt text](figures/semf_goodness_withpairing_ratio.png)

##### 5.2.2 Odd-Even Parabolas
A closer look at the chart of Nuclides shows that nuclei with N and Z away from the major numbers are more likely to be unstable. If we plot nuclei that lie on a line of a constant A, for example A=121 we find that odd and even A nuclei sit on two seperate parabola. Whilst our delta term in the SEMF can account for some of this it cannot account for the difference across all nuclei.

![Alt text](image-21.png)

Based on this we can make a prediction of which isotope of the given A is most stable against Nuclear Decay. From a parabola fit to the data shown of the form

$$
M(A,Z) = aA + bZ + cZ^{2}
$$
where $a$, $b$, and $c$ are free parameters that are nuclei dependent. We can determine the minima by finding the case where
$$
\frac{dM(A,Z)}{dZ} \rightarrow 0\\
$$

Whatever the nearest integer value of Z is at the minimum will be the isotope we are after. Notice hw the curves are symmetric about the minimum. This leads to the concept of **Mirror Nuclei**. This refers to a pair of nuclei that have the same $A$ but where the $N$ and $Z$ values are ereversed. An example is nitrogen-15 (7 protons and 8 neutrons) and oxygen-15 (8 protons and 7 neutrons).

The nuclear properties of a given Mirror Nuclei pair like this are similar. The chemical propereties of the associated neutral atoms (dicated by the electrons determinede by the number of protons only) will be very different of course.


##### 5.2.3 The Relative Abundance of Nuclei in Nature

A very important piece of evience for the Shell Model comes from a plot of the Relative Abundance of nuclei in nature vs A. Again we see peaeks of high abundance for nuclei with Magic Number values of N, Z, or both. There are a larger number of isotopes and isotones at particular values of Z, N.

**The Magic Numbers**
$$
2, 8, (14), 20, 28, 50, 82, 126
$$

![Alt text](image-22.png)


##### 5.2.4 The Neutron Binding Energy

Apart from the basic binding energy curve, we can look at for instance, the energy required to remove a single neutron from the nucleus vs the neutron number. The plot below shows by how much this differs from the SEMF preediction in MeV. What we see are  discontinuities up to 2 MeV at the Magic Numbers. This dependence of the energy to remove the outer neutron is strong evidence for a shell structure. A neutron just above a closed shell looks to be less tighty bound, reminisicent of the alkali metals in the chemical shell structure. This behaviour is  believed to be due to Shell Closures - it is harder to remove a neutron from a closed shell.

![Alt text](image-23.png)

##### 5.2.5 Neutron Capture Energy

Opposite to the Neutron Binding Energy plot just shown is the Neutron Capture Cross-section of nuclei vs Neutron Number. This measures how likly a given nuceus is to absorb an extra neutron fired at it. Again we see peaks and troughs in the distribution. The lowest values of these are at the Magic Numbers corresponding to filled shells in our model - it is harder to add a neutron when the outer shell is already full.


```{note}
Note how the cross section is highest for nuclei well away from the Magic Numbers. An example is Cd, which is used widely as a Neutron Sheild in nuclear experiments.
```
![Alt text](image-24.png)


##### 5.2.6 Electric Quadrupole Moments

As nuclei are charged then if this charge is not spherically distributed we might expect to measure a non-zero Electric Quadrupole Moment (we cover EQM later). For a shell model those nuclei with closed shells should be spherically symmetric and have no EQM. For nuclei that do not have a closed shell we indeed see large EQM.

In the ploot below the EQM have been normalized to the size and charge of each nucleus and these so called Reduced Quadrupole Moments are plototeeed agains the number of protnos or neutrons - depending upon which is odd. Some EQM are very large, suggesting shapes which are strongly non-spherical.



![Alt text](image-25.png)


##### 5.2.7 Nuclear Excitation Energy

The relative stability of closed shell nuclei is also indiciated by measuring the energy required tto take a nucleus from the Ground State to its First Excited State.

Here is an example plot for the excitationo energies for the even-A isotopes of lead. The requried energy is dramatically larger for the isotope with a Magic Number of neutrons. This is strong evidence for a shell model of the nucleus.

The isotope leead-208 is particularly unique in beind Doubly Magic Z=82 and N=126. This is a Double Closed Shell Nucleus and it takeese more than 2MeV to raise it to the first excited state.

![Alt text](image-26.png)


##### 5.2.8 The existince of double magic nuclei
So nuclei which have both neutron number and proton number equal to one of the Magic Numbers can be called Doubl eMagic, and are found to be particularly stable.

An example is calcium. It has exceptionally stable Doubly Magic Nuclei - two of them. Compared to the binding energy calcualted from the SEMF, they both have much moore than the expected binding eneregy.

These isotopes have Z=20 and N = 20 and 28, all three being magic numbers.

![Alt text](image-27.png)


##### 5.2.9 Decay Chains End with Magic Number Nuclei

Finally, there are several decay chain sequences in nature, particularly that starting U-235. Stable isotpoes come at the end of all these principle radiaoctive series, and all end pooints have a magic number of protons or neutrons.

Here is the example Dcay Chain of U-238 which ends in Pb-206 (which has a magic number of proton 82)

Note how from the start to finish of this chain results in emission of a total of 8 alpha particles.

There is a similar Decay Chain starting with Thorium.

![Alt text](image-28.png)


#### 5.3 Shell Model Challenge

All these observatioons strongly point to a shell Like arrangement of nucleons in the nucleus, whereby we envisage Energy Levels in which the nucleonos sit, sepereatede by gaps corresponding to the Magic Numbers for both Z and N given by : 2,8,(14),20,28,50,82,128.

![Alt text](image-29.png)


Our shell model will need to explain these characteristic numbers using QM to produce the quantised energy levels (shells), filling them with the correct number of states (nucleons) to reprduce the Magic Numbers.

So oour basic aim is to explain the Magic Numbers, i.e. all the Nuclear Energy LEvels, and then hopefully make new predictions that can be testde.

So there is strong evidence for shell structurte in Nuclei. This is compatible with a QM descriptioon with Nucleons occupying Energy Levels determined by a Central Nuclear Potential Well. We will discuss the form of this potential and the Nuclear Force between nucleons that determines its nature later. 


To deetermine the enrgy levels in the shell modeel we need to solve the full time-independent 3D Schrodingeer Equatin for particle mass $m$ and wavfunction $\psi$ which has the form:

$$
\frac{-\hbar^{2}}{2m} \nabla^{2} \psi(r,\theta,\phi) + V(r,\theta,\phi) \psi(r,\theta,\phi) = E \psi(r,\theta,\phi)
$$

For a given nucleeon, the forces acting on it by all the other nucleeons in thee nucleeus can be presented to firsst approximation by an average potential $V(r)$ whhich only depends on distancee frmo the core. We call this the Shell Theory Potential.


The origin of this potential $V(r)$ lise in the force that holds individual nucleeons toogether, the Nucleaer Force or N-N potential. So it is rasonabl to assum that the form and depth of $V(r)$ should reflecet the oveerall density distribution of the nucleons in the nucleus.



Right now we take the mass distribution given previously from the Saxon Woods

$$
\rho(r) = \frac{\rho(0)}{1+\textnormal{exp}(\frac{r-b}{a})}
$$

and invert it to get the potential $V(r)$. It is this function that goes into the Schrodinger equation to get the Eneregy Levels.


$$
V(r) = \frac{-V_{0}}{1+\textnormal{exp}(\frac{r-b}{a})}
$$

![Alt text](image-31.png)


The basis of this nuclear potential shape, for instance its spatial radius, is the force between nucleonos, the Nucleaer Force, that keeps nucleoons bound together. The "average" potential has a radius of the nucleus ($A^{1/3}$), which is much bigger in general than the range of the Nuclear Force, about $1.4~\textnormal{fm}$. Anyway for now we will just start to describe the QM result, the Shell Model in more detail, and how this helps explain many of the observed properties of Nuclei.


This guves us our **Average Potential** with radius sof the nucleus ($A^{1/3}$), much bigger than the rangee of the NUclear Force (aboutt 1.4 or so fm...)

In the shell model now since we are assuming spherical symmetry in our potential and the nuclus, we can simplify the spherical coordinates, splitting $\psi(r,\theta,\phi) = \Psi(r)\Theta(\theta)\Phi(\phi)$, means we can consider different possible spherical harmonics.

$$
\frac{-\hbar^{2}}{2m} \frac{d^{2}\Psi(r)}{dr^{2}} + V(r) \Psi(r) = E \Psi(r)
$$

We will avoid fully deriving this for now as the focus on this course is the implications that a full QM approach has on the behaviour of our nucleons.


##### 5.4 Shell Model Quantum Mechanics


A Major point is to realise that although Nuclei are composed of Nucleons they largely act as an isolated single entity. In particular they have a well defined Total Angular Momentum called Nuclear Spin, $I$. Nucleons themsleves also have Angular Momentum ($l$) and Intrinsic Spin ($s$). The vital point in our QM shell model is that the $l$ and $s$ of all the nucleons together determines the Total Nuclear Spin $I$ of a nucleus.



The result of treating the nucleus in this way we will see is the ability to now predict
- Nuclear Magic Numbers
- Nuclear Spin $I$
- Nuclear Parity $\pi$
  
And quite good, but not prefect, predictions of
- Nuclear Magnetic Moments
- Nuclear Electric Quadrupole Moments
- Excited States

The key to this is to work out the Shell Energy Levels and then determine how many nucleons are allowed to occupy each level as determined by QM and the Exclusion Principle.


#### 5.4 Shell Model Quantum Mechanics

We start by considering the QM behaviour of an individual nucleon (p or n) in the Central Potential Well of the nucleus. When we invoke QM, by applying the Schrodinger equation to solve the three dimensional system we end up with an Angular Momentum Quantum Number, $l$, that tells us about the spatial behaviour of wave function of each nucleon and defines the energy levels oof the nucleons as a result. In our simple central potential model all nucleons with the same $l$ have the same energy but we will see that it is a new quantum number $j$ that defines the actual number of states at a specific energy.

The magnitude of $l$ is given by 
$$
\langle l^{2} \rangle  = \hbar^{2}(l+1)
$$

The angular motion is a constant of the mition and the uncerttainty principle gives us certain allowed "substates" of $l$ which we will label $m_{z}$.

$$
\langle l_{z} \rangle = \hbar m_{z} ~~~~\textnormal{where}~~~~ m_z=0,\pm1,\pm2,...,\pm l
$$

Nucleons **also** have an Intrinsic Angular Momemntum called Spin $s$ such that

$$
\langle s^{2} \rangle = \hbar^{2} s(s+1)
$$

We find that similar to the angular momentum case this also has certain allowed spin substates, however these can only correspond to spin-up, or spin-dwn.

$$
\langle s_z\rangle  = \hbar m_{s} ~~~~\textnormal{where}~~~~ m_{s} = \pm \frac{1}{2}.
$$


The two quantum numbers $l$ and $s$ can vector couple to give a new quantum number $j$, known as the Total Angular Momentum Quantum Number for the nucleon. In nuclear systems it is the $j$ that is regarded as the "good" quantum number. The vector addition in this case is simply obtained from the possible combinations of $m_{z}$ and $m_{s}$ given what we know about possible values for $l,s,j$. In the figure below we can see the calculation of the quantum number $j$ represented as a combination of different arrows for $l$ and $s$. If $l$ and $s$ are parrallel (both positive) then we get higher values of $j$ than if they are anti-parrallel.

:::{figure-md} semf1
<img src='figures/FiguresSlides.012.png' width="100%" alt="Rutherford Form">
:::




```{note}
Remember a good quantum number is a quantity that remains constant and is conserved during a particular physical process or set of operations. 
```


We have seen that $m_{z}$ is always integer and $m_{s}$ is always half-integer +1/2 or -1/2. The same is true for the $l$ and $s$ quantum numbers. When we vector couple $l$ and $s$ together to make $j$ we simply add the possibilities, so this means $j$ is also always going to be half-integer. A summary of this is below.


- $l$ - from orbital angular momentum number *[Integer]*
- $s$ - from orbital angular momentum number *[Half-Integer]*
- $j$ - from orbital angular momentum number *[Half-Integer]*
  



#### 5.5 Simple Potential Example
Let's consider a simple case below by calculating the number of states in the $l=0$ and $l=1$ case to see if it makes sense based on the Magic Number shell information we are aware off. 

In the case of the ground shell we just have $l=0$, this means $m_{z}$ can only be $0$, and $m_{s}$ can only be $\pm \frac{1}{2}$. The result is we have two allowed states for the $j=\frac{1}{2}$ case as shown in the figure below.


![Alt text](image-33.png)

Now as we increase the possible $l$ state it is the $j$ value for a specific shell that is going to tell us how to fill up the Shell Energy Levels.  For instance, in the new example shown below we choose level $l=1$ and we find we are allowed total $j$ values = $\pm\frac{1}{2}$ and $\pm\frac{3}{2}$. This is because in our new shell we have the two similar $m_{z}=0$ cases as before (states 5 and 6), but also four new ones, corresponding to the case where $m_{z}=1$.


:::{figure-md} semf1
<img src='figures/FiguresSlides.011.png' width="100%" alt="Rutherford Form">
:::


Each nucleon must have its own allowed state of $m_z$ and $m_s$ when considering possible values of $j$. As shown in the figure  this results in six possible states $3/2, 1/2, -1/2, -3/2$ for $j=3/2$, and $1/2, -1/2$ for $j=1/2$. he cases where the angular momentum is parrallel ro anti-parrallel are sometimes referred to as *stretched* and *jacknife* states respectively.


Similarly if we repeated the same process for $l=2$, would have possible $j$ values of $5/2, 3/2, 1/2$ implying a total of 10 nucleon states allowed.

The sequence can be expressed as 
$$
n_{\textnormal{states}} = 2(2l+1)
$$

It is importtant to remember when calculating these state that protons and neutrons are counted seperately here. So for intance the $l=2$ level can have up to 10 protons **AND** 10 neutrons inside the shell.



### Nucleon and Level Notation

Based on this a notation for labelling levels has been developed in Nuclear Physics as below. This is annoyingly similar looking to that used for electrons in atomic orbits but is actually very different so be careful not to mix them up.


:::{figure-md} semf1
<img src='figures/FiguresSlides.013.png' width="100%" alt="Rutherford Form">
SESMF
:::


Note that we just state here a futher label n fr the basic energy level. Details of thiss are outside our scope here. However we can now easily label each of our states. For example for $n=2$, $l=1$ we have $2\textnormal{p}_{3/2}$ (4 nucleon states) and $2\textnormal{p}_{1/2}$ (2 nucleon states).


### First Model Predictions

We can now attempt a first prediction with this model, i.e. can we account for the Magic Numbers? The result is here:




A plot of the energy level positions when we carry on with this model is below. See how for a given n value, e.g. n=1, the s, p, d, f values for l go in order of increasing energy. However, there is overlap between high n values with lw l and low n values with high l. e.g. 1f is below 2p.

The exact position of the levels is oouotside out scroopoe. What is important here is how they get filled with nucleons, in relation to the main gaps. This determines the Magic Numbers.

We find: $2, 8, 20, 40, 58, 92...!!$

What we find is that although we get the first few Magic Numbers correct $(2, 8,$ and $20)$, the higher levels are completely wrong. The next two shells suggested by nature are actually at $28$ and $50$. The nuclear potential well used as the basis appears reasonable though. Trying modifications to the potential can help a bit but not enough to makee new shells so low, instead an extra term is needed in our model.

### Spin Orbit Corrections
The answer turns out to be a so-called **Spin orbit Coupling** term. The propoosal of this critical extra term in the Nuclear Potential was made in 1949 by Maria Goeppert Mayer and Johannes Jense, recognised by award of the Nobel Prize in 1963 - together with Eugene Wigner.

The basis is to introduce a further contribution to the internuclear force and hence the potential $V(r)$ that depends on the orientation of the spin $s$ and angular momentum $l$. I.e. it turns out this extra factor causes a re-ording of the energy levels 
$$
V=V(r)l\cdot s.
$$

The effect of this term is illustarted below. Recall how the Nuclear Potential Well shape (we said it comes from the Saxon Woods distribution of matter above) determines the energy levels. The Spin Orbit Correction changes this shape. The potential is deeper (nucleons are more strongly attracted) if the $l$ and $s$ are aligned parallel, and less deep (nucleons repulsed more) if they are aligned anti-parallel.

Insert figuree efor spin orbit correction.


If the nucleon is deep inside the nucleus then it also encounters many other nucleons with **Spin-Up** as **Spin-Down** and so the effect will average out, but it does not average everywhere, particularly close to the edges of the nucleus. The effect of this is to break the Degeneracy in the assignment of nucleons t energy levels by introducing new energy levels depending on the $j$ value.

For instance, considere the l=1 level. Previusly this had 6 nuclenos, 3/2, 1/2, -1/2, -3/2 (for the j=3/2) and 1/2, -1/2 (for the j=1/2) all in the same level. Now the j=3/2 nuclenos (parrallel l and s) geet their own new, lower, energy level. The j=1/2 nucleonss (anti-parallel $l$ and $s$) get their own neew, higher, energy level.


So the former degeneracy in which we had to consider all these 6 nucleons in one level is broken, and the previus single energy level becomes two, at different levels.

:::{figure-md} semf1
<img src='figures/FiguresSlides.016.png' width="100%" alt="Rutherford Form">
SESMF
:::

This effeect applies for all the $l$ levels, they all get split into two levels, except for $l$=0 (the $\textnormal{s}$ sharp) one becaue that only has one $j$ assignmeent, $j=1/2$ $($with values $1/2, -1/2$$)$.

### Modified Shell Model

The effect of the Energy Levels splitting is dramatic. As shown below it changes the position of the gaps, and can also makes neighburing $j$ states jump over one another. To calculate this what we need to do is work our way successively up the shells, first figuring out how many energy states there are given $j$, and then figuring out which correspond to parrallel anti-parrallel combinations.

![Alt text](image-34.png)

Importantly this one small change to the model now gives us the right Magic Number squence: 

**2, 8, 20, 28, 50, 82, 126**.

Seee how this gives the necessary extra splitting in the figure below. THe enumbere of states for each $l$ remains, we ejust break the degeneracy, creaeting more levels. We see a different clustering of levels, and different majoor "gaps" correspoonding to our magic numbers. Notice for instance how the $1\textnormal{g}$ level splits. All the $1g_{1/2}$ nucleons get moved down and the $1\textnormal{g}_{7/2}$ ones go up, creating a new gap when the total of 50 nucleons is reached.


#### Conclusions

So we now have a way to explain how protons and nucleons structure themselves inside our nucleus.

