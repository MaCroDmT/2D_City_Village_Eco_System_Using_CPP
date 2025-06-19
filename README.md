# 2D_City_Village_Eco_System_Using_CPP
---

## 🌆🌄 2D City-Village Ecosystem using OpenGL & C++

### 🚀 Project Overview

This is a visually rich and interactive 2D graphical simulation of a **City-Village Ecosystem** developed using **OpenGL and C++**. It beautifully combines modern urban landscapes with rural charm, blending natural elements with man-made infrastructure.

---

### 🎯 Key Features

* **City Area:**

  * High-rise skyscraper buildings with dynamic lighting.
  * Moving cars on a 2-lane road and a bridge.
  * A moving train across a rail bridge above the river.
  * Day and Night transitions with proper color and ambiance.
  * Night-mode lighting for windows and streets.

* **Village Area:**

  * Huts and windmills with rotating blades.
  * Trees, mountains, and a natural rural vibe.
  * A scenic river formed from a waterfall coming down a hill.
  * Boats moving along the river with animated waves.
  * A dam that can open and close on command.
  * Small islands in the river.

* **Natural Environment:**

  * Day/Night toggle with sun and moon animations.
  * Starry night sky in night mode.
  * Waterfall with continuous flowing animation.
  * Mountains forming the backdrop of the ecosystem.

* **Bridge:**

  * Connects both city and village across the river.
  * Carries both road and rail traffic (cars and train move over it).
  * Boats pass under the bridge.

* **Interactive Controls:**

  * Press **`D`**: Switch to **Day Mode**.
  * Press **`N`**: Switch to **Night Mode**.
  * Press **`W`**: Increase **speed** of the train and boats.
  * Press **`S`**: Decrease **speed**.
  * Press **`C`**: **Open/Close** the dam gate.

---

### 🛠️ How to Build and Run

#### ✅ Requirements

* **C++ Compiler** (e.g., g++, clang++)
* **OpenGL Utility Toolkit (GLUT)** — install via:

  * **Windows**: Install [FreeGLUT](http://freeglut.sourceforge.net/)
  * **Linux**: `sudo apt install freeglut3-dev`
  * **Mac**: Use `brew install freeglut` (ensure XQuartz is set up)

#### 🖥️ Build Instructions

##### On Windows (e.g., with Code::Blocks / Visual Studio)

1. Create a new C++ OpenGL project.
2. Add the `main.cpp` file.
3. Link OpenGL libraries:

   * `opengl32.lib`
   * `glu32.lib`
   * `freeglut.lib`
4. Compile and run.

##### On Linux (e.g., Ubuntu)

```bash
g++ main.cpp -o ecosystem -lGL -lGLU -lglut
./ecosystem
```

##### On macOS

```bash
g++ main.cpp -o ecosystem -framework OpenGL -framework GLUT
./ecosystem
```

---

### 📸 Screenshots 
**Day TIme Scenario**
![image](https://github.com/user-attachments/assets/efcf96bd-bcac-45f4-8005-22b334051357)
**Night Time Scenario**
![image](https://github.com/user-attachments/assets/820a2325-f216-4b2f-ade9-ee2c53f04a54)




---

### 👨‍💻 Developed By

> **PROTTOY SAHA**
> \[AIUB]
> Department of Computer Science
> Acomplihed Year: 2023

---

### 📜 License

This project is open-source and free to use for educational and non-commercial purposes.

---


