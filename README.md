# 🛸 Compact Drone – Design, Simulation, and Aerodynamic Evaluation

This repository showcases a comprehensive workflow for designing, simulating, and analyzing a compact drone using **SolidWorks**. The project integrates mechanical modeling, dynamic motion simulation, and aerodynamic testing to validate the drone’s performance and stability.

## 🎯 Project Goals

- Develop a 3D CAD model of a drone featuring impeller blades, gear systems, and a structural frame.
- Simulate motor-driven mechanical motion using SolidWorks Motion Study.
- Conduct CFD analysis to assess airflow behavior, thrust generation, and pressure distribution.
- Visualize mechanical and aerodynamic performance through animated outputs.

## 🧰 Tools and Technologies

- **SolidWorks CAD** – Used for precise 3D modeling and full assembly integration.
- **SolidWorks Motion Study** – Simulated dynamic rotation and gear interactions.
- **SolidWorks Flow Simulation** – Performed aerodynamic analysis using CFD techniques.

## 📁 Repository Contents

- `Assembly.SLDASM` – Complete drone assembly file
- `1-Impeller Blades.SLDPRT`, `2-Arm Gear.SLDPRT`, `3-Gearing.SLDPRT`, `4-Legs.SLDPRT`, `5-Main Structure.SLDPRT`, `6-Camera.SLDPRT` – Individual component models
- `Motion.mp4` – Animation of mechanical motion simulation
- `Flow Simulation.mp4` – Visualization of airflow and aerodynamic behavior
- `Final_Report.pdf` – Detailed technical report covering design, simulation, and analysis

## 🔄 Mechanical Simulation Overview

- The impeller system was driven by a virtual motor rotating at **100 RPM**.
- Motion was transmitted through a gear and belt mechanism to the impeller blades.
- The simulation confirmed proper gear alignment, smooth rotation, and stable mechanical behavior.

> ⚠️ *Note:* A minor angular mismatch was observed in the motion setup, but it does not affect the overall accuracy or conceptual validation of the mechanism.

## 🌬️ Aerodynamic Analysis (CFD)

- The impeller was set to rotate at **150 RPM** for aerodynamic testing.
- A rotating reference frame was used to simulate airflow without distorting the mesh.
- Flow trajectories and pressure contours were generated to evaluate thrust and stability.
- Mesh size: **4,018 cells**  
- Solver iterations: **140** (fully converged)

**Results:**
- Downward thrust was successfully generated.
- Pressure distribution remained balanced across components.
- No significant turbulence or flow separation was detected, indicating aerodynamic efficiency.

## 📊 Key Findings

- The drone design demonstrates strong mechanical integrity and aerodynamic performance.
- Integration of CAD, motion, and CFD within SolidWorks enabled a streamlined development process.
- The simulation results support the drone’s capability for stable hovering and efficient thrust generation.

## 👨‍💻 Author

**KONDRU CHARWICK HAMESH**

## 📬 Contact

For questions, feedback, or collaboration inquiries, feel free to reach out via email:  
📧 **charwick14@gmail.com**

---
