<h1 align="center">Madhav Krishnamangalam Sabu</h1>

<p align="center">
  <em>RL, world models, and learned dynamics for physical systems.</em><br>
  <em>Buildings are the testbed, not the destination.</em>
</p>

<p align="center">
  <a href="https://madhavkrishnamangalams.netlify.app"><img src="https://img.shields.io/badge/Portfolio-0B0B0B?style=for-the-badge&logo=react&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/madhavkrishnamangalams/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:madhav18oct@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### About

Mechanical/systems engineer moving into machine learning. Day job is diagnosing and validating thermal and energy performance across a portfolio of large buildings — field data, physics-based models, Python. Off-hours I work on offline RL and learned dynamics for control of those same systems, under the name **Enthalpy AI**.

- 🔭 Extending an offline RL + EnergyPlus pipeline from one building to **multi-building generalization** — DOE reference archetypes, physical-parameter conditioning, zero-shot transfer to held-out building types
- 📄 Workshop paper under double-blind review — *Tackling Climate Change with ML*, NeurIPS 2026
- 🎓 MS Mechanical Engineering, Columbia · B.Tech Mechanical Engineering, NIT Tiruchirappalli
- 🧰 Comfortable at both ends of the stack: SolidWorks and a CNC mill on one, PyTorch and FastAPI on the other
- 💬 Ask me about offline RL evaluation pitfalls, building thermal dynamics, or why closed-loop rollouts humble open-loop metrics

---

### Selected work

| Project | What it is | Stack |
|---|---|---|
| **Offline RL for price-responsive HVAC** | Behavior cloning, FQI, discrete CQL, and a learned one-step dynamics model, benchmarked in closed-loop EnergyPlus rollouts against real NYISO prices. Honest headline: a fixed 24 °C setpoint beats the learned policies once the loop is closed. | PyTorch · EnergyPlus · NumPy |
| **Physics-informed hybrid surrogate** | Gray-box thermal surrogate pairing a physical model with a learned residual. ~55% MAE reduction on a single-building case study; multi-building validation in progress. | PyTorch · EnergyPlus |
| **MetaRouter** | CLI router for coding agents — git-state snapshotting, SQLite logging, keyword-based routing between models. | Python · SQLite |
| **Incentive RAG platform** | Internal chat tool answering utility and state incentive program questions with citation-backed, deterministic savings calculations. | FastAPI · React · LangChain · ChromaDB |
| **Jet-quenching test rig** | Quenching failure-analysis rig designed and built from scratch: plate-transport rail, CNC-milled nozzle, actuator control, IR camera calibration. | SolidWorks · CNC · Arduino · MATLAB |

---

### Toolkit

<table>
  <tr>
    <td><b>ML&nbsp;/&nbsp;RL</b></td>
    <td>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
      <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white">
      <img src="https://img.shields.io/badge/Weights_&_Biases-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black">
      <img src="https://img.shields.io/badge/Offline_RL-5B5B5B?style=flat-square">
      <img src="https://img.shields.io/badge/World_Models-5B5B5B?style=flat-square">
    </td>
  </tr>
  <tr>
    <td><b>Scientific&nbsp;Python</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
      <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white">
      <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white">
      <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white">
      <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square">
    </td>
  </tr>
  <tr>
    <td><b>Simulation</b></td>
    <td>
      <img src="https://img.shields.io/badge/EnergyPlus-FFB81C?style=flat-square&logoColor=black">
      <img src="https://img.shields.io/badge/OpenStudio-4A90D9?style=flat-square">
      <img src="https://img.shields.io/badge/COMSOL-0B5394?style=flat-square">
      <img src="https://img.shields.io/badge/ANSYS_Workbench-FFB71B?style=flat-square&logoColor=black">
    </td>
  </tr>
  <tr>
    <td><b>Hardware&nbsp;/&nbsp;CAD</b></td>
    <td>
      <img src="https://img.shields.io/badge/SolidWorks-E31E24?style=flat-square&logoColor=white">
      <img src="https://img.shields.io/badge/CNC_Machining-555555?style=flat-square">
      <img src="https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white">
      <img src="https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white">
    </td>
  </tr>
  <tr>
    <td><b>Build&nbsp;/&nbsp;Ship</b></td>
    <td>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
      <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black">
      <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white">
      <img src="https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat-square">
      <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white">
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
    </td>
  </tr>
</table>

---

### Currently

- Extending the offline RL pipeline toward multi-building generalization — DOE reference archetypes, physical-parameter conditioning, zero-shot transfer
- Reading into structured world models and model-based RL for control under partial observability
- Preparing **PhD applications for Fall 2027** in RL / learned dynamics for physical systems

**Open to:** PhD positions starting Fall 2027, and ML / robotics / thermal-systems engineering roles where physical modeling and learning meet. Reach me at [madhav18oct@gmail.com](mailto:madhav18oct@gmail.com).
