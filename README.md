# Formula-1-Rear-Wing-CFD-Analysis-using-ANSYS-Fluent
This repository presents a detailed Computational Fluid Dynamics (CFD) simulation of a Formula 1 rear wing using ANSYS Fluent. The project includes all phases from geometry creation in SolidWorks to meshing, boundary condition setup, solver configuration, and post-processing for flow field analysis.

📄 Project Overview
The study simulates airflow around an F1 rear wing to evaluate aerodynamic performance and extract physical insights including pressure distribution, flow separation, and overall aerodynamic forces.

✨ Key Features
Geometry:
Designed in SolidWorks |
Includes all aerodynamic surfaces: main elements, endplates, and mounting brackets

Meshing:
Structured/unstructured meshing in ANSYS Fluent |
Local refinement around high-gradient zones |
Grid quality checked for skewness, aspect ratio, and orthogonality

Boundary Conditions:
Inlet velocity: 30 m/s |
Outlet: Pressure outlet |
Time scale factor: 1 |
Iterations: 200

Solver Settings:
Solver: Pressure-based solver with SIMPLE algorithm |
Second-order schemes for spatial discretization |
Residual convergence criteria for accuracy |
Under-relaxation tuning for steady convergence

📊 Simulation Objectives
Predict drag force acting on the wing surface |
Estimate lift generation due to downforce effect |
Visualize flow behavior and pressure zones |
Analyze impact of turbulence and boundary layer near aerodynamic surfaces


📄 Discussion_and_Conclusion.md: Aerodynamic interpretation and reflections

🧠 Learning Outcomes
Understanding of aerodynamic forces on high-performance vehicles |
Experience with meshing complex geometries |
Hands-on application of CFD solver workflows in ANSYS Fluent |
Development of post-processing and result evaluation skills

🧰 Tools Used
SolidWorks (for 3D design) |
ANSYS Fluent (for meshing and CFD) |
CFD-Post or Fluent GUI (for result visualization)
