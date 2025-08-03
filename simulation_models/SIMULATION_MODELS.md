# 🧪 Simulation Models

This section provides an overview of the simulation studies conducted to evaluate the performance of the **compliant gripper** and the **parallel wrist articulation system**.

Each simulation was conducted using CAD-integrated tools such as **SolidWorks Simulation** and **Motion Analysis**, with accompanying video exports provided in the `/videos` directory.

---

## 📎 Directory Structure
```graphql
/simulation_models
├── gripper_stress_analysis.mp4
├── wrist_motion_analysis.mp4
└── SIMULATION_MODELS.md
```

---

## 🔧 1. Stress Analysis – Compliant Gripper

🎥 **Video**: [`gripper_stress_analysis.mp4`](./gripper_stress_analysis.mp4)

### Objective:
To evaluate the **structural integrity** and **strain distribution** within the compliant gripper during actuation.

### Methodology:
- **Static structural simulation** under input displacement at the actuator anchor.
- Applied boundary conditions replicate expected loading during object grasp.
- Material: flexible polymer (e.g., Nylon or TPU).

### Key Results:
- High-strain regions localize near the compliant hinges and four-bar pivots.
- Displacement profile confirms controlled grasping motion without material failure.
- Safety factor within acceptable limits for repeated surgical operations.

---

## 🔄 2. Motion Analysis – Wrist Articulation

🎥 **Video**: [`wrist_motion_analysis.mp4`](./wrist_motion_analysis.mp4)

### Objective:
To simulate and validate the wrist's articulation range across primary anatomical motions:
- **Radial Deviation**
- **Ulnar Deviation**
- **Flexion**
- **Extension**

### Methodology:
- **Kinematic simulation** using SolidWorks Motion Study.
- Drive motion through prismatic sliders (PUU linkage inputs).
- Measured end-effector orientation and range of motion.

### Key Results:
- Full 2-DOF spherical motion achieved without link interference.
- **Range of motion** matches target anatomical workspace.
- Smooth compliant return to neutral position after actuation.

---

## 📌 Notes

- All simulations were validated under expected microsurgical loads.
- Stress simulation uses linear material models; real-world behavior may vary with material selection and scaling.
- Future FEA iterations may include **dynamic loading** and **fatigue life analysis**.

---

