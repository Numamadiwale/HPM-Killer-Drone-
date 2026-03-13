NOTE : These are settings i used to ensure the model runs well under the 50k limit and still provide top notch results :
# HFSS Simulation Setup Guide

### 1. Mesh Assignment
Assign this to the mesh in the model tree:
![Mesh Assignment](https://github.com/user-attachments/assets/ce20db55-9fda-4ab8-8f4c-f6d303d437ba)

---

### 2. Surface Approximation
Assign surface approximation to all model elements (substrate, port, ground, etc.). Ensure they are set to **coarse**.
![Surface Approximation Settings](https://github.com/user-attachments/assets/837d9dbd-43de-4732-88be-a9a39a38b4db)

---

### 3. Solution Setup Settings
Configure the following settings when adding the solution setup:

**General Setup:**
![Solution Setup 1](https://github.com/user-attachments/assets/d448bba8-6d20-468b-91f4-1eefaef3f305)

**Advanced Options:**
![Solution Setup 2](https://github.com/user-attachments/assets/64409a6a-535f-4d2f-8585-676f8f7c6771)

**Convergence and Matrix Settings:**
![Solution Setup 3](https://github.com/user-attachments/assets/3e361c30-311e-4f28-823e-a4da5f5177e2)

**Solver and Misc Settings:**
![Solution Setup 4](https://github.com/user-attachments/assets/1a8bc945-9c9b-47ea-a349-cc48f794f45b)
