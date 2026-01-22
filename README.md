# HoloIsland: Plant Genetics (FYP) 🌿🥽
**An Immersive XR Experience exploring Procedural Botany and Genetic Inheritance**

[![Unity](https://img.shields.io/badge/Unity-2021.3+-black?logo=unity&logoColor=white)](https://unity.com/)
[![C#](https://img.shields.io/badge/Language-C%23-blue?logo=c-sharp&logoColor=white)](https://docs.microsoft.com/en-us/dotnet/csharp/)
[![Platform](https://img.shields.io/badge/Platform-MR%20%7C%20VR-lightgrey)](#)

---

## 📌 Overview
**HoloIsland** is my Final Year Project (FYP) developed at **TAR UMT**. It is a Mixed Reality (MR) / Virtual Reality (VR) simulation that allows users to step into a digital laboratory to study, breed, and grow plant species using a custom-built genetic engine. 

This project demonstrates the intersection of **Interactive Software Technology** and **Bio-simulation**, focusing on how complex scientific data (Genetics) can be visualized through immersive 3D interfaces.

---

## ✨ Key Features

* **Genetic Breeding System:** Implemented Mendelian inheritance logic. Users can cross-pollinate different plants to produce offspring with unique DNA combinations.
* **Procedural Trait Expression:** Plant height, color, and leaf patterns are not pre-set; they are generated dynamically based on the plant's genotype.
* **Diegetic XR Interface:** Designed a "floating lab" UI that exists within the 3D world, ensuring user immersion remains unbroken during the simulation.
* **Interactive Gardening:** Physics-based interactions for handling seeds, tools, and environmental controls.

---

## 🛠️ Technical Architecture

### Genetic Engine Logic
The core system uses a **Genotype-to-Phenotype** mapping. Each plant carries a digital "chromosome" (ScriptableObject) that stores dominant and recessive alleles.



* **Genotype:** A data structure containing the trait codes.
* **Phenotype Engine:** Interprets the genotype to modify Mesh renderers, Material properties, and Transform scales in real-time.

### Development Stack
* **Engine:** Unity 2021.3 LTS
* **XR Integration:** OpenXR & MRTK (Mixed Reality Toolkit)
* **Version Control:** Git

---

## 📸 Project Gallery
*(Replace these placeholders with your actual screenshots from the AWD folder or screenshots folder)*

<div align="center">
  <img src="https://via.placeholder.com/400x250.png?text=VR+Environment+Preview" width="48%" />
  <img src="https://via.placeholder.com/400x250.png?text=Genetics+UI+Preview" width="48%" />
</div>

---

## 🚀 Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/shiiyoruxz/FYP-holoisland-plant-genetics.git](https://github.com/shiiyoruxz/FYP-holoisland-plant-genetics.git)
