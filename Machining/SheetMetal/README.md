# 🔩 Clamp Bracket – Sheet Metal CAD Project

## 📌 Overview
This project was completed as part of a **Udemy Sheet Metal Design course** to build a **foundational understanding of sheet metal concepts, manufacturable CAD design, and flat-pattern development**.

The model is a clamp-style bracket formed from bent mild steel sheet metal. It demonstrates how a flat sheet can be transformed into a functional component using bends, cut features, and production-ready design rules.

---

## 🎯 Project Goal
The main purpose of this project was **learning-focused rather than product-specific**.

Key learning outcomes included:

- Creating base flanges and edge flanges  
- Understanding bend sequencing  
- Generating flat patterns  
- Applying bend radius rules  
- Learning **K-Factor** and **Bend Allowance**  
- Adding cutouts, slots, and mounting holes  
- Producing engineering drawings  

---

## 🧱 Model Summary

- **Part Name:** Clamp Bracket  
- **Material:** Mild Steel  
- **Thickness:** 2 mm  
- **Finish:** Powder Coat Black  
- **Manufacturing Method:** Laser Cut + Press Brake Formed  

---

## 🖼️ Preview

### Final Model
![Clamp Bracket](https://github.com/nili-yay/ProjectHub/blob/main/Machining/SheetMetal/Part%201%20Drawing%202.pdf)

### Flat Pattern
![Flat Pattern](https://github.com/nili-yay/ProjectHub/blob/main/Machining/SheetMetal/Flattened.pdf)

### STL Model
👉 [Download STL File](https://github.com/nili-yay/ProjectHub/blob/main/Machining/SheetMetal/Part%20Studio%201%20-%20Part%201.stl)

---

## ⚙️ Key Design Features

- Circular upper section designed to retain or wrap around a cylindrical object  
- Dual mounting feet with bolt holes for fastening  
- Symmetrical layout for balanced loading  
- Slots on side walls for clearance / weight reduction  
- Large central cutout to reduce material use and improve appearance  

---

## 🧠 Design Decisions (Engineering Thinking)

Even though this was a course project, I identified several practical design choices:

### 🔹 Rounded Corners & Bend Radii
Rounded transitions help:

- Reduce stress concentrations  
- Lower cracking risk during bending  
- Improve fatigue resistance  
- Improve manufacturability  

### 🔹 Symmetrical Geometry
A mirrored left/right form can help with:

- Even force distribution  
- Easier alignment during assembly  
- Cleaner and more stable support structure  

### 🔹 Material Reduction with Slots
Cutouts may serve to:

- Reduce overall weight  
- Save material cost  
- Improve flexibility during installation  
- Provide tool or fastener access  

### 🔹 Flat Mounting Tabs
The lower feet provide a stable bolting surface to secure the bracket onto another structure.

---

## 📐 Sheet Metal Concepts Applied

### 📍 K-Factor

The model uses **K-Factor = 0.45**.

K-Factor represents the position of the neutral axis through the sheet thickness during bending.

\[
K = \frac{t}{T}
\]

Where:

- **t** = neutral axis distance from inside face  
- **T** = material thickness  

This directly affects flat pattern accuracy.

👉 Learn more: https://www.thefabricator.com/thefabricator/article/shopmanagement/k-factors-y-factors-and-press-brake-bending-precision

---

### 📍 Bend Allowance

Bend allowance estimates how much material is consumed in the bend zone.

\[
BA = \theta(R + KT)
\]

Where:

- **BA** = Bend Allowance  
- **θ** = bend angle in radians  
- **R** = inside bend radius  
- **K** = K-Factor  
- **T** = thickness  

Correct values ensure the flat blank folds into the intended final part.

👉 Learn more: https://sendcutsend.com/blog/what-is-bend-allowance/

---

## 🛠️ Skills Practiced

- Sheet metal CAD workflows  
- Flat pattern generation  
- Manufacturing-aware design  
- Bend parameter control  
- Drawing creation  
- Feature sequencing  

---

## 🏭 Possible Real-World Uses

This bracket could resemble components used for:

- Pipe / tube clamps  
- Sensor holders  
- Automotive brackets  
- Cable support mounts  
- Machine frame retainers  

---

## 📚 Reflection

This project helped me understand that sheet metal design is not just modeling shapes—it requires considering **material behavior, manufacturing limits, tolerances, and bend calculations**.

It was a strong practical introduction to production-oriented CAD design.

---
