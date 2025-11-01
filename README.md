# 🏎️ BAJA SAE Chassis Analysis

**Duration:** Oct 2025
**Domain:** Finite Element Analysis (FEA) | Vehicle Dynamics | Structural Design
**Tools Used:** ANSYS SpaceClaim, ANSYS Mechanical

---

## 📘 Overview

This project focuses on performing a **comprehensive Finite Element Analysis (FEA)** of a **BAJA SAE off-road vehicle chassis** to evaluate its **strength, stiffness, and vibration behavior** under various static and dynamic loading conditions.

The primary objective was to ensure **safety, rigidity, and durability** while maintaining compliance with **BAJA SAE design standards**.

---

## ⚙️ Methodology

### 1. Geometry Preparation

* Imported solid chassis model into **ANSYS SpaceClaim**.
* Extracted **beam geometry** and assigned a **custom circular tube profile** (OD: 17.5 mm, ID: 16 mm).
* Used **Connect** and **Merge** tools to close geometric gaps and ensure structural continuity.

### 2. Material Definition

* Created a **custom Structural Steel Alloy** with modified:

  * Density
  * Young’s Modulus
  * Yield Strength

### 3. Meshing

* Performed **mesh generation and refinement** in ANSYS Mechanical.
* Conducted a **mesh independence study** to validate element size for accuracy and computational efficiency.

### 4. Static Structural Simulations

Simulated key load cases to evaluate chassis response:

| Test Type      | Load (N) | Purpose                          |
| -------------- | -------- | -------------------------------- |
| Frontal Impact | 33,000   | Assess frontal crash deformation |
| Side Impact    | 13,720   | Evaluate lateral resistance      |
| Rear Impact    | 13,750   | Check rear collision safety      |
| Rollover       | 9,625    | Verify top load stability        |
| Torsional      | Variable | Study twist under uneven loading |
| Frontal Bump   | 8,250    | Assess shock mount deformation   |

---

## 📊 Results

* **Stress Range:** 238 – 464 MPa
* **Factor of Safety (FOS):** ≈ 2
* **Natural Frequencies:** 37 – 115 Hz (from modal analysis)
* Design validated for **strength, stiffness, and vibration safety**.

---

## 💡 Design Insights

* Suggested increasing **pipe wall thickness** or exploring **alternate materials** for improved fatigue life.
* Identified critical stress regions near **suspension mounts** and **joint nodes**.

---

## 🏁 Outcome

Successfully validated the BAJA SAE chassis design through a detailed **FEA-based structural assessment**, ensuring compliance with **safety and performance standards**.

The optimized chassis demonstrated **high strength-to-weight efficiency**, **vibration stability**, and **crashworthiness** under all tested conditions.

---

