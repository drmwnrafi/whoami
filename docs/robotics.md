---
hide:
  - navigation
  - footer
---

# **Robotics**

## **MAP-IT : 2D Mapping Iterative Closest Point and Pose Graph on Mobile Robot**

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; align-items: start;">
  <div style="text-align: justify;">
    <div>
      <a href="https://github.com/drmwnrafi/ROS2-PLICP-POSE-GRAPH">
        <img src="https://img.shields.io/badge/Source Code-121013?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
      </a>
      <a href="https://drmwnrafi.github.io/notesonanything/robotics/slam/plicp/">
        <img src="https://img.shields.io/badge/Theoretical Explanation-526CFE?style=for-the-badge&logo=materialformkdocs&logoColor=fff" alt="MkDocs">
      </a>
      <a href="https://www.researchgate.net/publication/385438246_Implementation_of_Levenberg-Marquardt_Point_to_Line_Iterative_Closest_Point_and_Pose_Graph_Optimization_for_2D_Indoor_Mapping_on_Differential_Drive_Mobile_Robot">
        <img src="https://img.shields.io/badge/Research_Gate-00CCBB.svg?&style=for-the-badge&logo=ResearchGate&logoColor=white" alt="ResearchGate">
      </a>
    </div>
    <p>I applied the Levenberg-Marquardt algorithm for Point to Line Iterative Closest Point (PLICP) and developed occupancy grid mapping from scratch using NumPy. 
    Additionally, I built a web application for mobile robot control, integrating it seamlessly with Robot Operating System 2 (ROS2) to enhance functionality and user interaction. 
    Furthermore, I published a paper on my work at the International Conference of Advanced Technology and Multidiscipline (ICATAM 2024).</p>
    <div>
      <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff" alt="Python">
      <img src="https://img.shields.io/badge/ROS2-22314E?&logo=ROS&logoColor=white" alt="ROS">
      <img src="https://img.shields.io/badge/Gradio-ff4c00?&logoColor=white&logo=" alt="Gradio">
    </div>
  </div>
  <div style="text-align: center;">
    <video src="../assets/media/mapit.mp4" style="text-align: center; justify-content: center;" alt="Quadcopter Simulation" width="350px" type="video/mp4" controls></video>
    <img src="../assets/media/map_.gif" alt="MAP-IT" width="350px" style="text-align: center; justify-content: center;">
  </div>
</div>

---

## **WyNDA : Data-Driven Discovery for Mathematical Model**

<div style="display: grid; grid-template-columns: 3fr 1fr; gap: 20px; align-items: start;">
  <div style="text-align: justify;">
    <div>
      <a href="https://github.com/drmwnrafi/pywynda">
        <img src="https://img.shields.io/badge/Python Code-121013?style=for-the-badge&logo=github&logoColor=fff" alt="Python Code">
      </a>
      <a href="https://github.com/drmwnrafi/cwynda">
        <img src="https://img.shields.io/badge/C/C++ Code-121013?style=for-the-badge&logo=github&logoColor=white" alt="C/C++ Code">
      </a>
      <a href="https://drmwnrafi.github.io/notesonanything/robotics/sys_iden/wynda/">
        <img src="https://img.shields.io/badge/Theoretical Explanation-526CFE?style=for-the-badge&logo=materialformkdocs&logoColor=fff" alt="MkDocs">
      </a>
    </div>
    <p>I reimplemented the code from the paper “WyNDA: A Method to Discover Mathematical Models of Dynamical Systems from Data” 
    and developed both Python and C++ implementations to extract mathematical models of dynamical systems from observational data.</p>
    <div>
      <img src="https://img.shields.io/badge/C++-%2300599C.svg?logo=c%2B%2B&logoColor=white" alt="C++">
      <img src="https://img.shields.io/badge/C-00599C?logo=c&logoColor=white" alt="C">
      <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff" alt="Python">
    </div>
  </div>
  <div style="text-align: right; position: relative;">
    <img src="../assets/media/wynda_lorentz.gif" alt="WyNDA" width="350px">
  </div>
</div>

<!-- ---

## **MuJoCo Simulation of PLICP Graph SLAM Mapping**

<div style="display: grid; grid-template-columns: 3fr 1fr; gap: 20px; align-items: start;">
  <div style="text-align: justify;">
    <div>
      <a href="https://github.com/drmwnrafi/mujoco_zoo">
        <img src="https://img.shields.io/badge/Source Code-121013?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
      </a>
    </div>
    <p>I implemented minimum snap trajectory optimization for both position and orientation, as well as geometric control on \(SE(3)\) for nonlinear control in non-flat spaces. 
    Additionally, I built a 3D simulation environment using MuJoCo to test and validate these control strategies.</p>
    <div>
      <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff" alt="Python">
      <img src="https://img.shields.io/badge/MuJoCo-00599C?&logoColor=white" alt="MuJoCo">
    </div>
  </div>
  <div style="text-align: right;">
    <img src="../assets/media/geom_ctrl.gif" alt="Quadcopter Simulation" width="400px">
  </div>
</div> -->

---

## **Quadcopter Trajectory Planning and Tracking 3D Simulation**

<div style="display: grid; grid-template-columns: 3fr 1fr; gap: 20px; align-items: start;">
  <div style="text-align: justify;">
    <div>
      <a href="https://github.com/drmwnrafi/mujoco_zoo">
        <img src="https://img.shields.io/badge/Source Code-121013?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
      </a>
      <a href="https://drmwnrafi.github.io/notesonanything/robotics/nonlinear_control/geom_quadcopter/">
        <img src="https://img.shields.io/badge/Theoretical Explanation-526CFE?style=for-the-badge&logo=materialformkdocs&logoColor=fff" alt="MkDocs">
      </a>
    </div>
    <p>I implemented minimum snap trajectory optimization for both position and orientation, as well as geometric control on \(SE(3)\) for nonlinear control in non-flat spaces. 
    Additionally, I built a 3D simulation environment using MuJoCo to test and validate these control strategies.</p>
    <div>
      <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff" alt="Python">
      <img src="https://img.shields.io/badge/MuJoCo-00599C?&logoColor=white" alt="MuJoCo">
    </div>
  </div>
  <div style="text-align: right;">
    <img src="../assets/media/geom_ctrl.gif" alt="Quadcopter Simulation" width="400px">
  </div>
</div>
