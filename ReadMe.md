![Logo](https://raw.githubusercontent.com/Squidly1408/Squidly1408/refs/heads/main/images/Squidly1408%20banner%20(Black%20Button%20Background).png)

# 3D Rotating Logo

A lightweight web experiment that generates a dynamic website displaying my logo layered across different **Z-axis positions**, rotating to create a **3D depth illusion** using pure web technologies.

This project focuses on visual layering, perspective transforms, and animation timing to simulate depth without using WebGL or external 3D engines.

---

## ✨ Preview

![3D Logo Render](./3D_logo_Render.gif)

---

## 🚀 Features

- Layered logo instances positioned along the **Z-axis**
- Rotational animation to simulate 3D depth
- CSS transform-based perspective illusion
- Lightweight and dependency-free
- Fully browser-rendered (no external rendering engine)

---

## 🧠 How It Works

The illusion is created by:

1. Cloning the logo multiple times.
2. Positioning each instance along the Z-axis using `translateZ()`.
3. Applying perspective via a parent container.
4. Rotating the entire stack to create a dynamic 3D effect.
5. Adjusting opacity / blur (optional) for added depth realism.

This creates the appearance of a volumetric rotating object using only 2D elements.


\
\
\
If you have any feedback, please reach out to me at Squidly1408@Gmail.com