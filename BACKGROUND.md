# 📚 Background

## 🔬 What is a Micromanipulator?

A **micromanipulator** is a precision mechanical device designed to control fine-scale movements of surgical or experimental tools—often at sub-millimeter resolutions. In surgical robotics, micromanipulators allow a surgeon to interact with small, delicate structures, such as nerves or blood vessels, while filtering out hand tremors and enhancing movement precision.

These devices are core components in microsurgical systems used in:

- Neurosurgery  
- Ophthalmology  
- Endoscopic or laparoscopic procedures  
- Microassembly in research or biotech

---

## 🧲 Importance of Miniaturization

<img src="docs/images/micro_tweezer_example.jpg" alt="Micro Tweezer Example" width="400"/>

*Example: Miniaturized micro-tweezer gripper used for manipulating small biological samples.*

Miniaturization in robotic micromanipulation is critical because:

- **Space is Limited:** Surgical access is often through small incisions or narrow cavities.
- **Tissue Safety:** Reduced tool mass and size lowers the risk of unintentional tissue damage.
- **Enhanced Control:** Smaller, lighter instruments respond more precisely to input motions.
- **System Integration:** Compact designs enable easier incorporation into robotic wrists or tool changers.

---

## 🔄 What is a Compliant Mechanism?

A **compliant mechanism** is a flexible structure that achieves motion and force transmission through **elastic deformation** of its material, instead of using rigid-body joints or linkages.

### ✅ Benefits of Compliant Mechanisms:

- **Part Count Reduction**  
  Fewer moving parts = fewer potential failure points and simpler assembly.

- **Precise Motion**  
  Smooth, continuous motion paths make them ideal for delicate operations.

- **Predictability and Portability**  
  Lightweight and inherently safe; particularly well-suited for surgical applications.

- **High Force-to-Size Ratio**  
  Elastic deformation enables compact yet effective force generation.

---

## 🤖 Compliant Integration in Surgical Wrist and Gripper

This project integrates compliant mechanisms in two key areas:

### 1. **Wrist Articulation (Parallel Kinematics)**  
The wrist mechanism uses a **parallel linkage system** that maintains stiffness while offering multiple degrees of freedom. Compliant joints reduce complexity and increase robustness without relying on bulky actuators.

### 2. **Adaptive Gripper (Forceps/End-Effector)**  
The gripper is designed with one **passive compliant finger** and one **active control finger**.

#### 💡 Key Advantage:
This structure enables **simple and reliable control**:  
- First, the passive finger makes contact with the object.  
- Then, the active finger closes the grasp.  

This allows for **robust gripping** with minimal sensing and control overhead.

#### ⚠️ Trade-Off:
The grip depends heavily on **friction** at the contact point. Low-friction objects or suboptimal alignments can result in **slippage or ejection** of the target during manipulation.

---

## 🧩 Why Compliant Design Matters in Surgical Robotics

By integrating compliant elements into micromanipulation tools, we aim to:

- Improve the **safety** and **adaptability** of surgical interactions.
- Reduce **design complexity** and **actuator burden**.
- Allow **robust grasping** of variable tissues or objects with minimal sensing.
- Enhance the **natural feel** of tool control for surgeons.

---

