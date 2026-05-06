# AP Physics 1 — Exam-Day Cram Review (May 2026)

Aligned to the College Board CED (effective Fall 2024, current for the May 2026 exam). 8 units, Fluids included.

---

## 0. Exam Mechanics

- **Format:** Hybrid digital. MCQs in Bluebook; FRQs handwritten in paper booklet.
- **Section I:** 40 MCQs, 80 min, 50% of score (≈2 min/question).
- **Section II:** 4 FRQs, 100 min, 50% of score (≈25 min/question).
- **Calculator + equation sheet** are provided on both sections. The sheet has kinematic equations, F = ma, energy/momentum, rotational analogs, SHM, fluids, and constants. It does **not** have derived results or conceptual rules.

### The four FRQ types (every exam now uses these four)

1. **Mathematical Routines** — multi-step calculation, derive a relationship.
2. **Translation Between Representations** — convert between graph, equation, diagram, written description.
3. **Experimental Design and Analysis** — design a procedure, analyze data, identify error sources.
4. **Qualitative/Quantitative Translation** — explain *why* in words, then back it up with math.

**Strategy:** Newton's 2nd Law and energy conservation alone solve a stupid number of problems. Always start with a free-body diagram (FBD) for force problems and "what's conserved?" for everything else.

---

## 1. Kinematics (10–15%)

**Core:** motion without caring about cause. 1D and 2D.

### Equations that matter

- v = v₀ + at
- x = x₀ + v₀t + ½at²
- v² = v₀² + 2aΔx
- 2D: x and y are **independent**. Same time, different equations.

### Graphs (the #1 MCQ topic)

- **x-t slope** = velocity
- **v-t slope** = acceleration
- **v-t area** = displacement
- **a-t area** = Δv
- Curved x-t → accelerating. Straight line on v-t → constant accel.

### Projectile motion

- aₓ = 0, a_y = −g. Always.
- At max height: v_y = 0, vₓ ≠ 0.
- Time up = time down (symmetric trajectory only).

### Traps

- **Velocity ≠ speed.** Velocity is a vector. An object turning at constant speed is still accelerating.
- An object **at rest can have nonzero acceleration** (top of a vertical toss).
- "Negative acceleration" doesn't mean slowing down — it means accelerating in the −direction. Slowing down requires **a** opposite to **v**.

---

## 2. Force and Translational Dynamics (18–23%) — Highest weight, master this

### Newton's Laws

1. **ΣF = 0** ⇔ constant velocity (including at rest).
2. **ΣF = ma**
3. Forces come in pairs: equal magnitude, opposite direction, **on different objects**.

### Common forces

- **Weight:** W = mg. Always down.
- **Normal:** perpendicular to surface. **Not always equal to mg** (incline, elevator, pushing down on object).
- **Friction:**
  - Kinetic: f_k = μ_k·N (opposite motion)
  - Static: f_s ≤ μ_s·N (≤ because it adjusts to whatever's needed up to the limit)
- **Tension:** same throughout a massless rope. Massless/frictionless pulley → tension same on both sides.
- **Spring:** F = −kx (Hooke's law).

### Method

1. Draw FBD. Every force, labeled.
2. Pick axes (along incline if there's an incline).
3. ΣFₓ = maₓ, ΣF_y = ma_y. Solve.

### Inclines

- Component of gravity **along** incline: mg·sin θ
- Component **perpendicular** to incline: mg·cos θ → equals N if no other ⊥ forces.

### Atwood / connected systems

- Both masses share the same |a|. Write ΣF = ma for each, solve simultaneously.

### Circular motion (lives in this unit)

- a_c = v²/r, directed toward center.
- ΣF (toward center) = mv²/r
- Centripetal force is **not a new force** — it's whatever real force(s) point inward (tension, gravity, normal, friction).

### Traps

- **Newton's 3rd Law pairs are on different objects.** "Earth pulls ball down" pairs with "ball pulls Earth up" — **not** with normal force. Normal and weight are not a 3rd-law pair.
- On an incline, N ≠ mg. It's mg·cos θ.
- Static friction is whatever it needs to be — only equals μ_s·N at the slipping threshold.
- Centripetal acceleration is **not zero** just because speed is constant.

---

## 3. Work, Energy, and Power (18–23%) — Tied for highest weight

### Definitions

- **Work (constant force):** W = F·d·cos θ, where θ is the angle between **F** and displacement.
- **Work (variable force):** area under F-x graph.
- **Work-energy theorem:** W_net = ΔKE
- **Kinetic energy:** KE = ½mv²
- **Gravitational PE:** PE = mgh (near surface)
- **Spring PE:** PE = ½kx²
- **Conservation:** ΔKE + ΔPE = W_nc (work by non-conservative forces, e.g., friction)
- If only conservative forces act: mechanical energy is conserved.

### Power

- Average: P = W/t
- Instantaneous: P = F·v·cos θ

### Method

1. Identify initial and final states.
2. Ask: is energy conserved? (No friction/air drag → yes.)
3. Set E_i = E_f, or E_i + W_nc = E_f.
4. Solve.

### Traps

- **Friction does negative work** when it opposes motion: W_f = −f·d
- Normal force usually does **zero work** (perpendicular to motion).
- A force can do work without changing speed: lifting at constant velocity does +W on the object, but ΔKE = 0 because gravity does an equal −W.
- The h in mgh is **vertical** displacement, not distance traveled along an incline.
- "Conservation of energy" includes thermal energy. If friction acts, mechanical energy decreases but total energy is conserved.

---

## 4. Linear Momentum (10–15%)

### Definitions

- **Momentum:** p = mv (vector)
- **Impulse:** J = F·Δt = Δp. Area under F-t graph.
- **Conservation:** in absence of external forces, Σp_initial = Σp_final.

### Collisions

| Type                          | KE        | Momentum  |
| ----------------------------- | --------- | --------- |
| Elastic                       | Conserved | Conserved |
| Inelastic                     | Lost      | Conserved |
| Perfectly inelastic (stick)   | Lost      | Conserved |

For perfectly inelastic: m₁v₁ + m₂v₂ = (m₁ + m₂)v_f

### Center of mass

- x_cm = Σ(mᵢxᵢ) / Σmᵢ
- In an isolated system, the center of mass moves at constant velocity (or stays at rest).

### Traps

- Momentum is a **vector** — signs matter. A ball bouncing back at the same speed has Δp = m·v_f − m·v_i = m(−v) − m(v) = **−2mv**, not zero.
- Momentum is conserved even when KE isn't (inelastic collisions).
- Impulse changes with **either** larger force **or** longer contact time. Crumple zones / airbags increase Δt to reduce F.

---

## 5. Torque and Rotational Dynamics (10–15%)

Translational analogs: x → θ, v → ω, a → α, m → I, F → τ.

### Equations

- **Torque:** τ = r·F·sin θ = r_⊥·F
- **Newton's 2nd Law (rotational):** Στ = I·α
- Rotational kinematics (constant α): same form as linear, swap symbols.
- v = r·ω, a_t = r·α (tangential), a_c = r·ω² = v²/r (centripetal)
- **Rolling without slipping:** v_cm = r·ω

### Moments of inertia (will likely be given, but know the pattern)

- Point mass: I = mr²
- Hoop / thin shell: I = MR²
- Solid disk / cylinder: I = ½MR²
- Solid sphere: I = (2/5)MR²
- Rod about end: I = (1/3)ML²; about center: I = (1/12)ML²

### Static equilibrium

ΣF = 0 **and** Στ = 0. Pick a clever pivot to kill unknowns — any unknown force at the pivot has r = 0, so its torque is 0.

### Traps

- Torque depends on **lever arm**, not just force. Same F further out → bigger τ.
- An object can have ΣF = 0 but still rotate (if Στ ≠ 0).
- Mass distribution matters: a hoop and a solid disk of equal mass and radius have **different** I, so they roll down a ramp at different rates (solid disk wins).

---

## 6. Energy and Momentum of Rotating Systems (5–8%)

### Equations

- **Rotational KE:** KE_rot = ½·I·ω²
- **Total KE of a rolling object:** ½mv² + ½Iω²
- **Angular momentum:** L = Iω (rigid body) or L = m·v·r·sin θ (point particle)
- **Conservation of L:** if Στ_external = 0, L is conserved.

### Classic problem: figure skater

- Pulls arms in → I decreases → ω increases (since Iω stays constant).
- KE actually **increases** because she does work pulling her arms in.

### Rolling down an incline

- Energy conservation: mgh = ½mv² + ½Iω²
- With v = rω: solve for v.
- Smaller I/(mR²) ratio → faster object at the bottom.

### Traps

- L is conserved separately from p — it's a different conservation law.
- Don't forget rotational KE when energy-conserving rolling objects.

---

## 7. Oscillations (5–8%)

### Simple Harmonic Motion (SHM)

- Restoring force is proportional to displacement, opposite direction.
- x(t) = A·cos(ωt + φ), where ω = 2π/T = 2πf

### Period formulas

- **Spring:** T = 2π·√(m/k) — depends on mass and stiffness, **not amplitude**.
- **Pendulum (small angle):** T = 2π·√(L/g) — depends on length and gravity, **not mass, not amplitude**.

### Energy in SHM

- Total: E = ½kA² (spring)
- At amplitude (x = ±A): all PE, KE = 0.
- At equilibrium (x = 0): all KE, PE = 0. v_max = ω·A.

### Traps

- **Period is independent of amplitude** for SHM. Doubling A does **not** double T.
- Pendulum period is independent of mass.
- Acceleration is **maximum at the endpoints** (where x = ±A), zero at equilibrium.
- Velocity is opposite: max at equilibrium, zero at endpoints.

---

## 8. Fluids (10–15%) — NEW unit, don't skip

### Density and pressure

- **Density:** ρ = m/V
- **Pressure:** P = F/A (scalar)
- **Pressure at depth:** P = P₀ + ρ·g·h
- Pressure depends only on **depth**, not on the shape of the container.

### Buoyancy (Archimedes' principle)

- F_b = ρ_fluid · V_displaced · g
- Object floats if ρ_object < ρ_fluid.
- Floating: F_b = W_object, so V_submerged / V_total = ρ_object / ρ_fluid.

### Continuity (conservation of mass)

- A₁v₁ = A₂v₂ (incompressible fluid). Narrower pipe → faster flow.

### Bernoulli's equation (conservation of energy for fluids)

```
P₁ + ½ρv₁² + ρgy₁  =  P₂ + ½ρv₂² + ρgy₂
```

- Faster flow → lower pressure (airplane wings, atomizers, narrow pipe sections).

### Traps

- Buoyant force depends on **fluid** density and **displaced** volume — not the object's density.
- Pressure scales with depth, not with the volume of fluid above. A thin tall column produces the same pressure as a wide pool of the same depth.
- Bernoulli assumes steady, incompressible, non-viscous flow.
- A fully submerged object has constant F_b regardless of depth (assuming incompressible fluid).

---

## FRQ Strategy

How to attack each of the four FRQ types:

### 1. Mathematical Routines

- Show every step. Define variables. Box final answers.
- If asked to derive, keep it symbolic until the last line.
- Units. Every. Time.

### 2. Translation Between Representations

- Label axes, units, and scales on graphs.
- Equation → graph: identify what slope and intercept mean physically.
- Graph → description: mention shape (linear, parabolic), key points, and what slope/area represents physically.

### 3. Experimental Design and Analysis

- **Procedure:** list specific measurements (what, with what tool), independent vs. dependent variable, controls, repeated trials.
- **Analysis:** usually involves linearizing data. If T = 2π·√(m/k), plot T² vs. m — slope is 4π²/k.
- Always discuss sources of error and how to reduce them.

### 4. Qualitative/Quantitative Translation

- The "explain why" question. Two parts: a verbal claim, then math backing it.
- Reference physical principles by name: "By Newton's 2nd Law…", "By conservation of momentum…", "Because the buoyant force exceeds gravity…"
- Don't just calculate — explain the physical reasoning.

### General FRQ rules

- **Free body diagrams** are worth points. Always include arrows starting at the object, labeled.
- **State the physics principle** before the equation. Example: "Using conservation of energy: ½mv² = mgh"
- If you can't solve part (b), guess a value and use it for (c). You can earn (c) points even with a wrong (b).
- Algebra errors are usually OK if your physics is right. Wrong physics with right algebra = zero.
- Re-read the question before moving on. Did they ask for speed or velocity? Magnitude or vector?

---

## The Things to Know Cold

- **Newton's 2nd Law:** ΣF = ma. Direction matters.
- **Newton's 3rd Law pairs are on different objects.**
- **Energy conservation:** E_i + W_nc = E_f
- **Momentum conservation** in collisions when no external force acts.
- **Angular momentum conservation** when no external torque acts.
- **Centripetal acceleration:** a_c = v²/r — real forces provide it.
- **SHM period** does not depend on amplitude.
- **Buoyancy:** F_b = ρ_fluid · V_displaced · g
- **Bernoulli:** faster fluid = lower pressure.
- **FBD first, then equations.**

Good luck. Trust your training, watch your signs, and don't leave any FRQ blank.
