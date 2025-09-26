# Exemplar-Based Image Inpainting (Criminisi et al. 2004)

This group project is a Python implementation of the **exemplar-based inpainting algorithm** introduced by Criminisi, Pérez, and Toyama (2004) as part of a final assignment for IMA201-Introduction to image Preprocessing course at Telecom Paris in october 2023.

The method fills missing regions in images by iteratively copying the most similar patches from known areas, combining **texture synthesis** with **structure propagation** to achieve realistic results.

---

## 📌 Features

- Implementation of the Criminisi et al. algorithm from scratch in Python  
- Patch extraction and matching using Sum of Squared Differences (SSD)  
- Confidence term and data term priority function  
- Iterative filling of missing regions guided by boundary pixels  
- Demonstration on custom masks (object removal / hole filling)

---

## 🖼️ Example

Original image | Mask | Inpainted result  
:---:|:---:|:---:  
![Original](assets/original.jpg) | ![Mask](assets/mask.jpg) | ![Result](assets/inpainted.png)  

---
