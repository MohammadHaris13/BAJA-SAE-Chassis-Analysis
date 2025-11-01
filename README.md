# BAJA SAE Chassis Analysis

This project focuses on the **structural and dynamic analysis of a BAJA SAE vehicle chassis** using **ANSYS Workbench**. The goal was to ensure the chassis design is safe, lightweight, and capable of withstanding multiple real-world impact and load conditions.

---

## Project Overview

The BAJA SAE chassis was analyzed under **various loading conditions** including frontal, side, rear, rollover, torsional, and bump impacts, as well as a modal analysis to determine natural frequencies.  
The workflow followed a systematic approach starting from beam extraction to full simulation and result interpretation.

---

## Workflow Summary

### **Step 1: Beam Extraction and Material Setup**
- Imported chassis geometry into **ANSYS SpaceClaim**.  
- Extracted **beam elements** from solid members and assigned **custom circular tube profile**  
  - Outer radius: 17.5 mm  
  - Inner radius: 16 mm  
- Used **Connect Tool** to close beam gaps (max distance: 35 mm).  
- Shared common vertices for continuity.  
- Created **custom material (Structural Steel Alloy)** with modified mechanical properties:
  - Density  
  - Young’s Modulus  
  - Yield Strength  
  - Ultimate Tensile Strength  

---

### **Step 2: Meshing & Static Structural Analyses**

Performed mesh generation and simulations for **front and side impact** tests.

#### 🔹 Frontal Impact Test
- Applied force: **33,000 N (Z-direction)**  
- Fixed firewall vertices  
- Observed max stress: **≈ 464 MPa**  
- Checked total deformation & stress flow animation  

#### 🔹 Side Impact Test
- Applied force: **13,720 N (X-direction)**  
- Fixed opposite side vertices  
- Observed lateral stress distribution and deformation patterns  

---

### **Step 3: Rollover, Rear Impact & Torsional Tests**

#### 🔹 Rollover Test
- Force: **9,625 N (Y-direction)** applied on top members  
- Max stress: **≈ 238 MPa**  

#### 🔹 Rear Impact Test
- Force: **13,750 N (Z-direction)** applied on rear members  
- Max stress: **≈ 338 MPa**

#### 🔹 Torsional Test
- Opposite vertical forces (**±6,875 N**) on front suspension mounts  
- Rear vertices simply supported  
- Evaluated torsional rigidity & deformation  

---

### **Step 4: Front Bump & Modal Analysis**

#### 🔹 Front Bump Test
- Force: **8,250 N (Y-direction)** on front right shock mount  
- Fixed left mount and firewall  
- Max stress: **≈ 257 MPa**  
- Factor of Safety ≈ **2**

#### 🔹 Modal Analysis
- Fixed firewall region  
- Extracted **6 mode shapes**  
- Frequency range: **37–115 Hz**  
- Verified chassis vibration characteristics and stability  

---

## Results Summary

| Test Type          | Applied Load (N) | Max Stress (MPa) | FOS | Key Observation |
|--------------------|------------------|------------------|-----|-----------------|
| Frontal Impact     | 33,000           | 464              | 2.0 | High stress on front rails |
| Side Impact        | 13,720           | ~400             | 2.1 | Stress on side members |
| Rear Impact        | 13,750           | 338              | 2.3 | Rear deformation localized |
| Rollover           | 9,625            | 238              | 2.5 | Top frame compression |
| Torsional          | ±6,875           | Moderate         | 2.0 | Good rigidity |
| Front Bump         | 8,250            | 257              | 2.0 | Shock mount region stress |
| Modal Analysis     | —                | —                | —   | Natural freq: 37–115 Hz |

---

## Key Learnings
- Gained hands-on experience with **beam-based modeling** in ANSYS SpaceClaim.  
- Learned **load application and boundary condition setup** for static & modal analysis.  
- Understood **stress flow and deformation behavior** in vehicle chassis systems.  
- Developed proficiency in **interpreting simulation results and optimizing design parameters**.  

---

## Tools & Technologies
- **ANSYS Workbench**  
- **ANSYS SpaceClaim**  
- **Static Structural & Modal Analysis Modules**  
- **Finite Element Analysis (FEA)**  

---

## Skills Demonstrated
- Finite Element Analysis (FEA)  
- Structural Strength Evaluation  
- Crash & Impact Simulation  
- Modal (Vibration) Analysis  
- Material and Profile Customization  
- Mesh Generation & Validation  
- Design Optimization  


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

## Side Impact Test

<img width="1625" height="634" alt="Side Impact Test" src="https://github.com/user-attachments/assets/59e6fea2-908f-470e-8e8d-1a3dc06d12d7" />


https://github.com/user-attachments/assets/bef5e636-09db-438f-8def-10ce1894fe3d



https://github.com/user-attachments/assets/8cf729f3-8311-4569-b54e-ad2b3ac48639

---

## Roll Over

<img width="1625" height="637" alt="Roll Over" src="https://github.com/user-attachments/assets/39892bdb-0743-4cd7-a67d-4879a9edf489" />


https://github.com/user-attachments/assets/7d83d236-0935-4d03-8839-6c40b823f2db



https://github.com/user-attachments/assets/cc8e83da-21c8-4db4-a8ce-6cfb8ea703e5

---

## Rear Impact Test

<img width="1629" height="633" alt="Rear Impact Test" src="https://github.com/user-attachments/assets/ed4be795-599a-4f06-81cf-c8e15207a289" />


https://github.com/user-attachments/assets/c624e588-ed78-4997-b599-4d0f9def5377



https://github.com/user-attachments/assets/193e617d-7a22-42f7-adc9-b1eb7d36face

---

## Frontal Impact Test

<img width="1629" height="640" alt="Frontal Impact Test" src="https://github.com/user-attachments/assets/292c5897-5e0f-4317-9fa0-4a5dafe0f885" />


https://github.com/user-attachments/assets/a0d4c077-cfe0-4792-b5ae-97714a12289d



https://github.com/user-attachments/assets/b1941713-6583-4be1-92a9-78b73cdda677

---


---

## Conclusion
The analysis confirmed that the **BAJA SAE chassis design is structurally safe**, with all stresses within permissible limits and a satisfactory factor of safety.  
Future improvements could involve **increasing pipe thickness** or exploring **alternate lightweight alloys** to enhance performance.

---

### Author
**Mohammad Haris**  
Final Year B.Tech – Mechanical Engineering  
VIT-AP,Amaravati   
[Linkedin Profile](https://linkedin.com/in/mohammad-haris-13032002) | [Email](mailto:mohammaddharis1303@gmail.com)

---






