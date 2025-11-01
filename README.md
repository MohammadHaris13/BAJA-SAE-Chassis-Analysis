# BAJA SAE Chassis Analysis

**Duration:** Oct 2025
**Domain:** Finite Element Analysis (FEA) | Vehicle Dynamics | Structural Design
**Tools Used:** ANSYS SpaceClaim, ANSYS Mechanical

---

## Overview

This project focuses on performing a **comprehensive Finite Element Analysis (FEA)** of a **BAJA SAE off-road vehicle chassis** to evaluate its **strength, stiffness, and vibration behavior** under various static and dynamic loading conditions.

The primary objective was to ensure **safety, rigidity, and durability** while maintaining compliance with **BAJA SAE design standards**.

---

## Methodology

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

## Results

* **Stress Range:** 238 – 464 MPa
* **Factor of Safety (FOS):** ≈ 2
* **Natural Frequencies:** 37 – 115 Hz (from modal analysis)
* Design validated for **strength, stiffness, and vibration safety**.

---

## Design Insights

* Suggested increasing **pipe wall thickness** or exploring **alternate materials** for improved fatigue life.
* Identified critical stress regions near **suspension mounts** and **joint nodes**.

---

## Outcome

Successfully validated the BAJA SAE chassis design through a detailed **FEA-based structural assessment**, ensuring compliance with **safety and performance standards**.
The optimized chassis demonstrated **high strength-to-weight efficiency**, **vibration stability**, and **crashworthiness** under all tested conditions.

---

<img width="634" height="420" alt="Screenshot 2025-10-31 181705" src="https://github.com/user-attachments/assets/89683a10-99f2-4dd8-a622-381813a01fee" />

---

## Mesh

<img width="1627" height="639" alt="Mesh" src="https://github.com/user-attachments/assets/512350e6-886e-45fe-a18c-f5d78c42b193" />

---

![](https://github.com/MohammadHaris13/BAJA-SAE-Chassis-Analysis/raw/refs/heads/main/Media/BAJA_SAE_TT_TD.mp4) 

## Torsion Test

<img width="1624" height="632" alt="Torsion Test" src="https://github.com/user-attachments/assets/1df29f13-a967-406c-a59c-3a44f85d4557" /> 

https://github.com/user-attachments/assets/a7a62b28-f74f-4234-b4c5-20372549c452



https://github.com/user-attachments/assets/850c67e0-eff3-41df-8b39-7db769bce78d

---

<img width="1625" height="634" alt="Side Impact Test" src="https://github.com/user-attachments/assets/59e6fea2-908f-470e-8e8d-1a3dc06d12d7" />


https://github.com/user-attachments/assets/bef5e636-09db-438f-8def-10ce1894fe3d



https://github.com/user-attachments/assets/8cf729f3-8311-4569-b54e-ad2b3ac48639

---

<img width="1625" height="637" alt="Roll Over" src="https://github.com/user-attachments/assets/39892bdb-0743-4cd7-a67d-4879a9edf489" />


https://github.com/user-attachments/assets/7d83d236-0935-4d03-8839-6c40b823f2db



https://github.com/user-attachments/assets/cc8e83da-21c8-4db4-a8ce-6cfb8ea703e5

---

<img width="1629" height="633" alt="Rear Impact Test" src="https://github.com/user-attachments/assets/ed4be795-599a-4f06-81cf-c8e15207a289" />


https://github.com/user-attachments/assets/c624e588-ed78-4997-b599-4d0f9def5377



https://github.com/user-attachments/assets/193e617d-7a22-42f7-adc9-b1eb7d36face

---

<img width="1629" height="640" alt="Frontal Impact Test" src="https://github.com/user-attachments/assets/292c5897-5e0f-4317-9fa0-4a5dafe0f885" />


https://github.com/user-attachments/assets/a0d4c077-cfe0-4792-b5ae-97714a12289d



https://github.com/user-attachments/assets/b1941713-6583-4be1-92a9-78b73cdda677





