# AP Physics 1 — Exam-Day Cram Review (May 2026)

Aligned to the College Board CED (effective Fall 2024, current for May 2026). 8 units, Fluids included.

---

## 0. Exam Mechanics

- **Format**: Hybrid digital. MCQs in Bluebook; FRQs handwritten in paper booklet.
- **Section I**: 40 MCQs, 80 min, 50% of score (≈2 min/question).
- **Section II**: 4 FRQs, 100 min, 50% of score (≈25 min/question).
- **Calculator + equation sheet provided** on both sections. The equation sheet has kinematic equations, F=ma, energy/momentum, rotational analogs, SHM, fluids, and constants. **It does NOT have**: derived results, geometry formulas you should know (volume of sphere/cylinder are there actually — check the sheet), or any conceptual rules.
- **The four FRQ types** (every exam now uses these four):
  1. **Mathematical Routines** — multi-step calculation, derive a relationship.
  2. **Translation Between Representations** — convert between graph, equation, diagram, written description.
  3. **Experimental Design and Analysis** — design a procedure, analyze data, identify error sources.
  4. **Qualitative/Quantitative Translation** — explain *why* in words, then back it up with math.

**Strategy**: Newton's 2nd Law and energy conservation alone solve a stupid number of problems. Always start with a free-body diagram (FBD) for force problems and "what's conserved?" for everything else.

---

## 1. Kinematics (10–15%)

**Core**: motion without caring about cause. 1D and 2D.

### Equations that matter
- $v = v_0 + at$
- $x = x_0 + v_0 t + \tfrac{1}{2}at^2$
- $v^2 = v_0^2 + 2a\Delta x$
- 2D: x and y are **independent**. Same time, different equations.

### Graphs (the #1 MCQ topic)
- $x$-$t$ slope = velocity. $v$-$t$ slope = acceleration. $v$-$t$ **area** = displacement. $a$-$t$ area = $\Delta v$.
- Curved $x$-$t$ → accelerating. Straight line on $v$-$t$ → constant accel.

### Projectile motion
- $a_x = 0$, $a_y = -g$. Always.
- At max height: $v_y = 0$, $v_x \ne 0$.
- Time up = time down (symmetric trajectory only).

### Traps
- **Velocity ≠ speed**. Velocity is a vector. An object turning at constant speed is accelerating.
- An object **at rest can have nonzero acceleration** (top of a vertical toss).
- "Negative acceleration" doesn't mean slowing down — it means accelerating in the −direction. Slowing down requires $\vec{a}$ opposite to $\vec{v}$.

---

## 2. Force and Translational Dynamics (18–23%) — **Highest weight, master this**

### Newton's Laws
1. $\sum \vec{F} = 0 \Leftrightarrow$ constant velocity (incl. at rest).
2. $\sum \vec{F} = m\vec{a}$.
3. Forces come in pairs: equal magnitude, opposite direction, **on different objects**.

### Common forces
- **Weight**: $W = mg$. Always down.
- **Normal**: ⊥ to surface. **Not always equal to $mg$** (incline, elevator, pushing down on object).
- **Friction**: $f_k = \mu_k N$ (kinetic, opposite motion). $f_s \le \mu_s N$ (static, ≤ because it adjusts to whatever's needed up to the limit).
- **Tension**: same throughout a massless rope. If pulley is massless/frictionless, tension same on both sides.
- **Spring**: $F = -kx$ (Hooke's law).

### Method
1. Draw FBD. Every force, labeled.
2. Pick axes (along incline if there's an incline).
3. $\sum F_x = ma_x$, $\sum F_y = ma_y$. Solve.

### Inclines
- Component of gravity **along** incline: $mg\sin\theta$.
- Component **perpendicular**: $mg\cos\theta$ → equals $N$ if no other ⊥ forces.

### Atwood / connected systems
- Both masses share $|a|$. Write $\sum F = ma$ for each, solve simultaneously.

### Circular motion (lives here)
- $a_c = v^2/r$, directed toward center.
- $\sum F_{\text{toward center}} = mv^2/r$. Centripetal force is **not a new force** — it's whatever real force(s) point inward (tension, gravity, normal, friction).

### Traps
- **Newton's 3rd Law pairs are on different objects.** "Earth pulls ball down" pairs with "ball pulls Earth up" — NOT with normal force. Normal and weight are not a 3rd-law pair.
- On an incline, $N \ne mg$. It's $mg\cos\theta$.
- Static friction is whatever it needs to be — only equals $\mu_s N$ at the slipping threshold.
- Centripetal acceleration is not zero just because speed is constant.

---

## 3. Work, Energy, and Power (18–23%) — **Tied for highest weight**

### Definitions
- $W = Fd\cos\theta$ (constant force). $\theta$ = angle between $\vec{F}$ and displacement.
- $W = $ area under $F$-$x$ graph (variable force).
- $W_{\text{net}} = \Delta KE$ (work-energy theorem).
- $KE = \tfrac{1}{2}mv^2$
- $PE_{\text{grav}} = mgh$ (near-surface)
- $PE_{\text{spring}} = \tfrac{1}{2}kx^2$
- **Conservation**: $\Delta KE + \Delta PE = W_{\text{nc}}$ (work by non-conservative forces, e.g., friction).
- If only conservative forces act: $E_{\text{mech}}$ is conserved.

### Power
- $P = W/t$ (average) or $P = \vec{F} \cdot \vec{v} = Fv\cos\theta$ (instantaneous).

### Method
1. Identify initial and final states.
2. Ask: is energy conserved? (No friction/air drag → yes.)
3. Set $E_i = E_f$ or $E_i + W_{\text{nc}} = E_f$.
4. Solve.

### Traps
- **Friction does negative work** when it opposes motion: $W_f = -f \cdot d$.
- Normal force usually does **zero work** (⊥ to motion).
- A force can do work without changing speed (lifting at constant velocity does +W on object, but $\Delta KE = 0$ because gravity does $-W$).
- $h$ in $mgh$ is **vertical** displacement, not distance traveled along incline.
- "Conservation of energy" includes thermal energy. If friction acts, mechanical energy decreases but total energy is conserved.

---

## 4. Linear Momentum (10–15%)

### Definitions
- $\vec{p} = m\vec{v}$. Vector.
- Impulse: $\vec{J} = \vec{F}\Delta t = \Delta \vec{p}$. Area under $F$-$t$ graph.
- **Conservation**: in absence of external forces, $\sum \vec{p}_i = \sum \vec{p}_f$.

### Collisions
| Type | KE? | Momentum? |
|---|---|---|
| Elastic | Conserved | Conserved |
| Inelastic | Lost | Conserved |
| Perfectly inelastic (stick together) | Lost | Conserved |

For perfectly inelastic: $m_1 v_1 + m_2 v_2 = (m_1 + m_2) v_f$.

### Center of mass
- $x_{cm} = \dfrac{\sum m_i x_i}{\sum m_i}$
- In an isolated system, the CM moves at constant velocity (or stays at rest).

### Traps
- Momentum is a **vector** — signs matter. A ball bouncing back has $\Delta p = m v_f - m v_i = m(-v) - m(v) = -2mv$, not zero.
- Momentum is conserved even when KE isn't.
- Impulse changes with **either** larger force **or** longer contact time. Crumple zones / airbags increase $\Delta t$ to reduce $F$.

---

## 5. Torque and Rotational Dynamics (10–15%)

Translational analogs: $x\to\theta$, $v\to\omega$, $a\to\alpha$, $m\to I$, $F\to\tau$.

### Equations
- $\tau = rF\sin\theta = r_\perp F$
- $\sum \tau = I\alpha$
- Rotational kinematics (constant $\alpha$): same form as linear, swap symbols.
- $v = r\omega$, $a_t = r\alpha$ (tangential), $a_c = r\omega^2 = v^2/r$ (centripetal).
- Rolling without slipping: $v_{cm} = r\omega$.

### Moments of inertia (will likely be given, but know the pattern)
- Point mass: $I = mr^2$
- Hoop / thin shell: $I = MR^2$
- Solid disk / cylinder: $I = \tfrac{1}{2}MR^2$
- Solid sphere: $I = \tfrac{2}{5}MR^2$
- Rod about end: $I = \tfrac{1}{3}ML^2$; about center: $\tfrac{1}{12}ML^2$.

### Static equilibrium
$\sum F = 0$ AND $\sum \tau = 0$. Pick a clever pivot to kill unknowns (any unknown force at the pivot has $r=0$, so $\tau = 0$).

### Traps
- Torque depends on **lever arm**, not just force. Same $F$ further out → bigger $\tau$.
- An object can have $\sum F = 0$ but still rotate ($\sum \tau \ne 0$).
- Mass distribution matters: a hoop and a solid disk of equal mass and radius have **different** $I$, so they roll down a ramp at different rates (solid disk wins).

---

## 6. Energy and Momentum of Rotating Systems (5–8%)

### Equations
- Rotational KE: $KE_{\text{rot}} = \tfrac{1}{2}I\omega^2$
- Total KE of rolling object: $\tfrac{1}{2}mv^2 + \tfrac{1}{2}I\omega^2$
- Angular momentum: $L = I\omega$ (rigid body) or $L = mvr\sin\theta$ (point particle).
- **Conservation of $L$**: if $\sum \tau_{\text{ext}} = 0$, $L$ is conserved.

### Classic problem: figure skater
- Pulls arms in → $I$ decreases → $\omega$ increases (since $I\omega$ constant). KE actually **increases** because she does work pulling her arms in.

### Rolling down an incline
- Energy conservation: $mgh = \tfrac{1}{2}mv^2 + \tfrac{1}{2}I\omega^2$.
- With $v = r\omega$: solve for $v$. Smaller $I/(mR^2)$ ratio → faster.

### Traps
- $L$ is conserved separately from $p$ — different conservation law.
- Don't forget rotational KE when energy-conserving rolling objects.

---

## 7. Oscillations (5–8%)

### Simple Harmonic Motion (SHM)
- Restoring force proportional to displacement, opposite direction.
- $x(t) = A\cos(\omega t + \phi)$, where $\omega = 2\pi f = 2\pi/T$.

### Period formulas
- **Spring**: $T = 2\pi\sqrt{m/k}$ — depends on mass and stiffness, **not amplitude**.
- **Pendulum (small angle)**: $T = 2\pi\sqrt{L/g}$ — depends on length and gravity, **not mass, not amplitude**.

### Energy in SHM
- Total: $E = \tfrac{1}{2}kA^2$ (spring).
- At amplitude: all PE, KE = 0.
- At equilibrium: all KE, PE = 0. $v_{\max} = \omega A$.

### Traps
- **Period independent of amplitude** for SHM. Doubling $A$ does NOT double $T$.
- Pendulum period is independent of mass.
- Acceleration is **maximum at endpoints** (where $x = \pm A$), zero at equilibrium. Velocity is opposite: max at equilibrium, zero at endpoints.

---

## 8. Fluids (10–15%) — **NEW unit, don't skip**

### Density and pressure
- $\rho = m/V$
- $P = F/A$ (pressure, scalar)
- $P = P_0 + \rho g h$ (pressure at depth $h$ below surface).
- Pressure depends only on **depth**, not shape of container.

### Buoyancy (Archimedes' principle)
- $F_b = \rho_{\text{fluid}} V_{\text{displaced}} g$
- Object floats if $\rho_{\text{object}} < \rho_{\text{fluid}}$.
- Floating: $F_b = W_{\text{object}}$, so $V_{\text{submerged}}/V_{\text{total}} = \rho_{\text{object}}/\rho_{\text{fluid}}$.

### Continuity (conservation of mass)
- $A_1 v_1 = A_2 v_2$ (incompressible fluid). Narrow pipe → faster flow.

### Bernoulli's equation (conservation of energy for fluids)
$$P_1 + \tfrac{1}{2}\rho v_1^2 + \rho g y_1 = P_2 + \tfrac{1}{2}\rho v_2^2 + \rho g y_2$$

- Faster flow → lower pressure (airplane wings, atomizers, narrow pipe sections).

### Traps
- Buoyant force depends on **fluid** density and **displaced** volume, not the object's density.
- Pressure scales with depth, not with volume of fluid above. A thin tall column can produce the same pressure as a wide pool of the same depth.
- Bernoulli assumes steady, incompressible, non-viscous flow.
- A submerged object that's fully submerged has constant $F_b$ regardless of depth (assuming incompressible fluid).

---

## FRQ Strategy

The four FRQ types — how to attack each:

### 1. Mathematical Routines
- Show every step. Define variables. Box final answers.
- If asked to derive, keep it symbolic until the last line.
- Units. Every. Time.

### 2. Translation Between Representations
- Label axes, units, scales on graphs.
- If converting equation → graph: identify slope and intercept meaning.
- If converting graph → description: mention shape (linear, parabolic), key points, what slope/area represents physically.

### 3. Experimental Design and Analysis
- **Procedure**: list specific measurements (what, with what tool), independent vs. dependent variable, controls, repeated trials.
- **Analysis**: usually involves linearizing data. If $T = 2\pi\sqrt{m/k}$, plot $T^2$ vs. $m$ — slope is $4\pi^2/k$.
- Always discuss sources of error and how to reduce them.

### 4. Qualitative/Quantitative Translation
- The "explain why" question. Two parts: a verbal claim, then math backing it.
- Reference physical principles by name: "By Newton's 2nd Law…", "By conservation of momentum…", "Because the buoyant force exceeds gravity…".
- Don't just calculate — explain the physical reasoning.

### General FRQ rules
- **Free body diagrams** are worth points. Always include arrows starting at the object, labeled.
- **State the physics principle** before the equation. "Using conservation of energy: $\tfrac{1}{2}mv^2 = mgh$".
- If you can't solve part (b), guess a value and use it for (c). You can earn (c) points even with wrong (b).
- Algebra errors are OK if your physics is right. Wrong physics with right algebra = zero.
- Read the question again before moving on. Did they ask for speed or velocity? Magnitude or vector?

---

## The Things to Know Cold

- **Newton's 2nd Law**: $\sum F = ma$. Direction matters.
- **Newton's 3rd Law pairs are on different objects.**
- **Energy conservation**: $E_i + W_{\text{nc}} = E_f$.
- **Momentum conservation** in collisions when no external force.
- **Angular momentum conservation** when no external torque.
- **Centripetal**: $a_c = v^2/r$, real forces provide it.
- **SHM period** doesn't depend on amplitude.
- **Buoyancy**: $F_b = \rho_f V_{\text{disp}} g$.
- **Bernoulli**: faster fluid = lower pressure.
- **FBD first, then equations**.

Good luck. Trust your training, watch your signs, and don't leave any FRQ blank.
