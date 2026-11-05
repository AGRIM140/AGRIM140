<a id="top"></a>

<!-- ======================================================================= -->
<!-- SECTION 01: BOOT SCREEN / BIOS HEADER                                   -->
<!-- ======================================================================= -->
<div align="center">
  <img src="./assets/boot-header.svg" width="100%" alt="DELL DIMENSION // AGRIM SINGH WORKSTATION BIOS v2026.X" />
</div>

<table width="100%">
  <tr>
    <td width="68%" valign="top">
      <pre>
SYS_BIOS // ROM_REV_2026.11    HOST: AGRIM140-WKSTN
==================================================================
> INIT_KERNEL: Perception, Robotics & Backend Architecture... [OK]
> MOUNT_VOL  : Pentagon Rugged Systems // A-IMCS & AGVS...... [OK]
> ALLOC_MEM  : B.Tech CSE (AI & Data Science) @ SMIT......... [OK]
> NET_NODE   : [github.com/AGRIM140](https://github.com/AGRIM140) // SYS_USER_VERIFIED...... [OK]
------------------------------------------------------------------
Engineering autonomous ground vehicle systems, computer vision 
pipelines, and distributed backend microservices. Focused on how 
software perceives physical environments and scales under load.</pre>
    </td>
    <td width="32%" valign="top">
      <pre>
+----------------------------+
|   SYSTEM DIAGNOSTICS       |
+----------------------------+
| USER_ID : AGRIM140         |
| STATUS  : [ONLINE]         |
| VERSION : 2026.11          |
| ARCH    : x86_64 / ROS2    |
| COMPUTE : CUDA / PYTORCH   |
| SIM_ENG : GAZEBO / MUJOCO  |
+----------------------------+</pre>
    </td>
  </tr>
</table>

<!-- ======================================================================= -->
<!-- SECTION 02: MAIN CONTROL PANEL (NAVIGATION BUS)                         -->
<!-- ======================================================================= -->
<table width="100%">
  <thead>
    <tr>
      <th colspan="5" align="left">
        <code>[SYS_BUS_00] // WORKSTATION_CONTROL_PANEL — SELECT_INTERRUPT_VECTOR</code>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center" width="20%">
        <a href="#system-info"><kbd>&nbsp;[F1] ABOUT_SYS&nbsp;</kbd></a><br/>
        <sub><code>0x01 // IDENTITY</code></sub>
      </td>
      <td align="center" width="20%">
        <a href="#project-directory"><kbd>&nbsp;[F2] PROJ_DIR&nbsp;</kbd></a><br/>
        <sub><code>0x02 // MNT_VOLS</code></sub>
      </td>
      <td align="center" width="20%">
        <a href="#tech-specs"><kbd>&nbsp;[F3] TECH_SPEC&nbsp;</kbd></a><br/>
        <sub><code>0x03 // MODULES</code></sub>
      </td>
      <td align="center" width="20%">
        <a href="#telemetry"><kbd>&nbsp;[F4] TELEMETRY&nbsp;</kbd></a><br/>
        <sub><code>0x04 // METRICS</code></sub>
      </td>
      <td align="center" width="20%">
        <a href="#com-ports"><kbd>&nbsp;[F5] COM_PORTS&nbsp;</kbd></a><br/>
        <sub><code>0x05 // I/O_LINK</code></sub>
      </td>
    </tr>
  </tbody>
</table>

<br/>

<!-- ======================================================================= -->
<!-- SECTION 03: ABOUT / SYSTEM INFORMATION                                  -->
<!-- ======================================================================= -->
<a id="system-info"></a>
<img src="./assets/section-about.svg" width="100%" alt="SECTION 03 // SYSTEM INFORMATION & ARCHITECTURE" />

<table width="100%">
  <tr>
    <td width="52%" valign="top">
      <h4><code>[0x03A] // HARDWARE_AND_OPERATOR_MANIFEST</code></h4>
      <pre lang="yaml">
OPERATOR_SPEC:
  identifier: "Agrim Singh (AGRIM140)"
  education:
    degree: "B.Tech in Computer Science & Engineering"
    specialization: "Data Science / AI & DS"
    institution: "Sikkim Manipal Institute of Technology (SMIT)"
  current_deployment:
    organization: "Pentagon Rugged Systems Pvt. Ltd."
    systems:
      - "A-IMCS (Autonomous Integrated Mobile Camouflage & Signature Management System)"
      - "AGVS (Autonomous Ground Vehicle Systems)"
  leadership_and_community:
    - "Founder // Recursion (Coding & GATE Prep Club @ SMIT)"
    - "Google Campus Ambassador @ SMIT"
  core_subsystems:
    - "Robotics, UGV Perception & Autonomous Systems"
    - "Computer Vision, Semantic Segmentation & GANs"
    - "Explainable AI (SHAP) & Machine Learning"
    - "Distributed Backend Systems (Django, FastAPI, Spring Boot)"</pre>
    </td>
    <td width="48%" valign="top">
      <h4><code>[0x03B] // OPERATIONAL_DOCTRINE</code></h4>
      <p>
        I build software that perceives, decides, and executes—whether that involves processing real-time multi-modal sensor feeds for an autonomous ground vehicle or architecting asynchronous microservice pipelines capable of handling heavy computational workloads.
      </p>
      <p>
        At <strong>Pentagon Rugged Systems Pvt. Ltd.</strong>, my work centers on <strong>A-IMCS</strong> and <strong>AGVS</strong> development: investigating how unstructured off-road environments are segmented using deep vision models, how LiDAR and camera feeds fuse within <strong>ROS 2</strong>, <strong>Gazebo</strong>, and <strong>MuJoCo</strong>, and how active camouflage patterns adapt to spatial frequency and color distribution in the field.
      </p>
      <hr/>
      <pre>
ACTIVE_R&D_THREADS:
├── [01] Off-Road Scene Perception (RUGD / RELLIS-3D / PSP-MobileNet)
├── [02] UGV Traversability & Active Camouflage (ROS 2 / Gazebo / MuJoCo)
├── [03] Explainable Clinical & Agricultural AI (Random Forest + SHAP)
└── [04] High-Throughput Async Backends (DRF / FastAPI / Spring Boot / Cloud Run)</pre>
    </td>
  </tr>
</table>

<p align="right"><sub><a href="#top"><kbd>^ RETURN_TO_BIOS</kbd></a></sub></p>

<!-- ======================================================================= -->
<!-- SECTION 04: PROJECT DIRECTORY                                           -->
<!-- ======================================================================= -->
<a id="project-directory"></a>
<img src="./assets/section-projects.svg" width="100%" alt="SECTION 04 // MOUNTED PROJECT VOLUMES (/DEV/SDA1)" />

<h4><code>[0x04A] // PRIMARY_PARTITION (/dev/sda1) — FLAGSHIP_SYSTEMS</code></h4>

<table width="100%">
  <thead>
    <tr>
      <th width="8%" align="left"><code>PID</code></th>
      <th width="28%" align="left"><code>EXECUTABLE / DIRECTORY</code></th>
      <th width="36%" align="left"><code>CORE_STACK_PARAMETERS</code></th>
      <th width="14%" align="center"><code>STATUS</code></th>
      <th width="14%" align="center"><code>MOUNT_LINK</code></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>0x01</code></td>
      <td><strong>A-IMCS</strong><br/><sub>Autonomous Camouflage & UGV Perception</sub></td>
      <td><code>PSP-MobileNet</code> <code>ROS 2</code> <code>LiDAR</code> <code>Gazebo</code> <code>MuJoCo</code> <code>RUGD</code> <code>RELLIS-3D</code></td>
      <td align="center"><img src="https://img.shields.io/badge/ACTIVE-78966B?style=flat-square" alt="ACTIVE" /></td>
      <td align="center"><a href="https://github.com/AGRIM140"><kbd>[OPEN_DIR]</kbd></a></td>
    </tr>
    <tr>
      <td><code>0x02</code></td>
      <td><strong>AEREO</strong><br/><sub>Bulk Certificate Generation System</sub></td>
      <td><code>Django REST</code> <code>PostgreSQL</code> <code>Celery</code> <code>Redis</code> <code>ReportLab</code> <code>UUID</code></td>
      <td align="center"><img src="https://img.shields.io/badge/STABLE-607D8B?style=flat-square" alt="STABLE" /></td>
      <td align="center"><a href="https://github.com/AGRIM140/aereo-certificate-bulk-generator"><kbd>[OPEN_DIR]</kbd></a></td>
    </tr>
    <tr>
      <td><code>0x03</code></td>
      <td><strong>SMART_CROP_ENGINE</strong><br/><sub>Profit & Risk Prediction System</sub></td>
      <td><code>Random Forest</code> <code>SHAP</code> <code>Weather API</code> <code>Scikit-learn</code></td>
      <td align="center"><img src="https://img.shields.io/badge/STABLE-607D8B?style=flat-square" alt="STABLE" /></td>
      <td align="center"><a href="https://github.com/AGRIM140/Smart-crop-profit-and-risk-prediction-system"><kbd>[OPEN_DIR]</kbd></a></td>
    </tr>
    <tr>
      <td><code>0x04</code></td>
      <td><strong>GAN_IMG_RESTORE</strong><br/><sub>Image Enhancement Using GANs</sub></td>
      <td><code>PyTorch</code> <code>CycleGAN</code> <code>SRGAN</code> <code>Noise2Noise</code> <code>DeblurGAN</code></td>
      <td align="center"><img src="https://img.shields.io/badge/VERIFIED-607D8B?style=flat-square" alt="VERIFIED" /></td>
      <td align="center"><a href="https://github.com/AGRIM140?tab=repositories"><kbd>[OPEN_DIR]</kbd></a></td>
    </tr>
    <tr>
      <td><code>0x05</code></td>
      <td><strong>DRUG_RATING_PRED</strong><br/><sub>Pharmaceutical Rating & Side-Effect Analysis</sub></td>
      <td><code>Random Forest Regressor</code> <code>Streamlit</code> <code>Python</code> <code>ML</code></td>
      <td align="center"><img src="https://img.shields.io/badge/STABLE-607D8B?style=flat-square" alt="STABLE" /></td>
      <td align="center"><a href="https://github.com/AGRIM140?tab=repositories"><kbd>[OPEN_DIR]</kbd></a></td>
    </tr>
    <tr>
      <td><code>0x06</code></td>
      <td><strong>HEALSYNC_XAI</strong><br/><sub>Hospital Decision Support Microservice</sub></td>
      <td><code>Spring Boot</code> <code>FastAPI</code> <code>Random Forest</code> <code>SHAP</code></td>
      <td align="center"><img src="https://img.shields.io/badge/VERIFIED-78966B?style=flat-square" alt="VERIFIED" /></td>
      <td align="center"><a href="https://github.com/AGRIM140?tab=repositories"><kbd>[OPEN_DIR]</kbd></a></td>
    </tr>
    <tr>
      <td><code>0x07</code></td>
      <td><strong>WEATHER_INTEL_CLOUD</strong><br/><sub>Full-Stack Weather Intelligence Platform</sub></td>
      <td><code>FastAPI</code> <code>Next.js</code> <code>Docker</code> <code>Google Cloud Run</code></td>
      <td align="center"><img src="https://img.shields.io/badge/DEPLOYED-607D8B?style=flat-square" alt="DEPLOYED" /></td>
      <td align="center"><a href="https://github.com/AGRIM140?tab=repositories"><kbd>[OPEN_DIR]</kbd></a></td>
    </tr>
  </tbody>
</table>

<h4><code>[0x04B] // INTERACTIVE_FILE_INSPECTOR (CLICK TO EXPAND SYSTEM SCHEMATICS &amp; LOGS)</code></h4>

<details open>
  <summary><kbd>DIR_01</kbd> <strong><code>/opt/pentagon/a-imcs</code> — A-IMCS: Autonomous Integrated Mobile Camouflage &amp; Signature Management System</strong></summary>
  <br/>
  <img src="./assets/proj-aimcs.svg" width="100%" alt="A-IMCS System Schematic" />
  <table width="100%">
    <tr>
      <td>
        <pre>
[FILE_ID]      : PROJ_01 // A-IMCS &amp; AGVS
[STATUS]       : ACTIVE_R&amp;D (Pentagon Rugged Systems Pvt. Ltd.)
[REPOSITORY]   : <a href="https://github.com/AGRIM140">https://github.com/AGRIM140</a>
--------------------------------------------------------------------------------
TECHNICAL_SPECIFICATION:
  * Environmental Perception : Semantic segmentation of complex unstructured terrains
                               utilizing the PSP-MobileNet architecture.
  * Dataset Benchmarking     : Trained and evaluated on off-road field datasets
                               including RUGD and RELLIS-3D.
  * Robotics &amp; Simulation    : Multi-sensor LiDAR fusion, ROS 2 node integration,
                               Gazebo simulation planning, and MuJoCo traversability mapping.
  * Signature Management     : Researching adaptive camouflage, thermochromic liquid crystal
                               (TLC) skin control, and spatial-frequency pattern synthesis.</pre>
      </td>
    </tr>
  </table>
</details>

<details open>
  <summary><kbd>DIR_02</kbd> <strong><code>/srv/backend/aereo</code> — Aereo: Bulk Certificate Generation System</strong></summary>
  <br/>
  <img src="./assets/proj-aereo.svg" width="100%" alt="Aereo System Schematic" />
  <table width="100%">
    <tr>
      <td>
        <pre>
[FILE_ID]      : PROJ_02 // AEREO_ENGINE
[STATUS]       : DEPLOYED_STABLE
[REPOSITORY]   : <a href="https://github.com/AGRIM140/aereo-certificate-bulk-generator">https://github.com/AGRIM140/aereo-certificate-bulk-generator</a>
--------------------------------------------------------------------------------
TECHNICAL_SPECIFICATION:
  * Core Architecture        : Backend service built on Django REST Framework (DRF)
                               with PostgreSQL for relational persistence.
  * Asynchronous Queueing    : Offloads high-volume PDF rendering via Celery workers
                               backed by a Redis message broker.
  * Document Synthesis       : Programmatic certificate generation powered by ReportLab.
  * Lifecycle Tracking       : UUID-indexed job management with dedicated REST APIs
                               for batch triggering, real-time status polling, and retrieval.</pre>
      </td>
    </tr>
  </table>
</details>

<details open>
  <summary><kbd>DIR_03</kbd> <strong><code>/usr/ml/smart-crop</code> — Smart Crop Profit &amp; Risk Prediction System</strong></summary>
  <br/>
  <img src="./assets/proj-smart-crop.svg" width="100%" alt="Smart Crop System Schematic" />
  <table width="100%">
    <tr>
      <td>
        <pre>
[FILE_ID]      : PROJ_03 // SMART_CROP_PRED
[STATUS]       : VERIFIED_BUILD
[REPOSITORY]   : <a href="https://github.com/AGRIM140/Smart-crop-profit-and-risk-prediction-system">https://github.com/AGRIM140/Smart-crop-profit-and-risk-prediction-system</a>
--------------------------------------------------------------------------------
TECHNICAL_SPECIFICATION:
  * Predictive Modeling      : Random Forest ensemble pipelines predicting agricultural
                               crop yield, input cost, and net profitability.
  * Explainable AI (XAI)     : Integrated SHAP (SHapley Additive exPlanations) to expose
                               feature importance and risk drivers for transparent decisions.
  * External Telemetry       : Live Weather API integration for environmental conditioning.</pre>
      </td>
    </tr>
  </table>
</details>

<details>
  <summary><kbd>DIR_04</kbd> <strong><code>/usr/vision/gan-restore</code> — Image Enhancement Using GANs</strong></summary>
  <br/>
  <img src="./assets/proj-gan-restore.svg" width="100%" alt="GAN Image Restoration Schematic" />
  <table width="100%">
    <tr>
      <td>
        <pre>
[FILE_ID]      : PROJ_04 // GAN_RESTORATION_SUITE
[STATUS]       : RESEARCH_BUILD
[REPOSITORY]   : <a href="https://github.com/AGRIM140?tab=repositories">https://github.com/AGRIM140?tab=repositories</a>
--------------------------------------------------------------------------------
TECHNICAL_SPECIFICATION:
  * Deep Learning Framework  : Implemented in PyTorch for image restoration &amp; enhancement.
  * Multi-Model Pipeline     : Comparative and modular implementation of:
                               - CycleGAN (unpaired domain translation)
                               - SRGAN (super-resolution upscaling)
                               - Noise2Noise GAN (blind image denoising)
                               - DeblurGAN (motion deblurring and sharpening)</pre>
      </td>
    </tr>
  </table>
</details>

<details>
  <summary><kbd>DIR_05</kbd> <strong><code>/usr/ml/drug-rating</code> — Drug Rating Predictor</strong></summary>
  <br/>
  <img src="./assets/proj-drug-predictor.svg" width="100%" alt="Drug Rating Predictor Schematic" />
  <table width="100%">
    <tr>
      <td>
        <pre>
[FILE_ID]      : PROJ_05 // DRUG_RATING_REGRESSOR
[STATUS]       : VERIFIED_BUILD
[REPOSITORY]   : <a href="https://github.com/AGRIM140?tab=repositories">https://github.com/AGRIM140?tab=repositories</a>
--------------------------------------------------------------------------------
TECHNICAL_SPECIFICATION:
  * Regression Pipeline      : Built around a Random Forest Regressor for dataset-driven
                               prediction and analysis of pharmaceutical ratings &amp; side effects.
  * Interactive Interface    : Deployed via a clean Streamlit frontend for parameter
                               testing and real-time inference inspection.</pre>
      </td>
    </tr>
  </table>
</details>

<details>
  <summary><kbd>DIR_06</kbd> <strong><code>/srv/clinical/healsync-xai</code> — HealSync XAI: Hospital Decision Support Microservice Platform</strong></summary>
  <br/>
  <img src="./assets/proj-healsync.svg" width="100%" alt="HealSync XAI System Schematic" />
  <table width="100%">
    <tr>
      <td>
        <pre>
[FILE_ID]      : PROJ_06 // HEALSYNC_XAI_PLATFORM
[STATUS]       : VERIFIED_BUILD
[REPOSITORY]   : <a href="https://github.com/AGRIM140?tab=repositories">https://github.com/AGRIM140?tab=repositories</a>
--------------------------------------------------------------------------------
TECHNICAL_SPECIFICATION:
  * Microservice Topology    : Distributed backend integrating Spring Boot enterprise
                               routing with FastAPI machine learning inference nodes.
  * Clinical Decision Engine : Random Forest classification models trained for drug
                               suitability prediction and patient risk stratification.
  * Explainable AI (XAI)     : Real-time SHAP feature attribution exposing biomarker and
                               dosage weights for transparent clinical auditing.</pre>
      </td>
    </tr>
  </table>
</details>

<details>
  <summary><kbd>DIR_07</kbd> <strong><code>/srv/cloud/weather-intel</code> — Full-Stack Weather Intelligence Platform</strong></summary>
  <br/>
  <img src="./assets/proj-weather.svg" width="100%" alt="Weather Intelligence Platform Schematic" />
  <table width="100%">
    <tr>
      <td>
        <pre>
[FILE_ID]      : PROJ_07 // WEATHER_INTELLIGENCE_CLOUD
[STATUS]       : DEPLOYED_CLOUD_RUN
[REPOSITORY]   : <a href="https://github.com/AGRIM140?tab=repositories">https://github.com/AGRIM140?tab=repositories</a>
--------------------------------------------------------------------------------
TECHNICAL_SPECIFICATION:
  * Full-Stack Architecture  : High-concurrency FastAPI backend paired with a reactive
                               Next.js, TypeScript, and Tailwind CSS telemetry dashboard.
  * Forecasting Pipeline     : Multivariate weather trend analysis and environmental
                               time-series modeling.
  * Cloud Infrastructure     : Containerized via Docker and deployed serverlessly on
                               Google Cloud Run for automated horizontal scaling.</pre>
      </td>
    </tr>
  </table>
</details>

<details>
  <summary><kbd>EXT_VOL</kbd> <strong><code>/dev/sdb1/extended-modules</code> — Additional Engineered Repositories (Review Analyzer, Financial OCR ETL, CNN &amp; BERT NLP)</strong></summary>
  <br/>
  <table width="100%">
    <thead>
      <tr>
        <th width="10%" align="left"><code>MOD_ID</code></th>
        <th width="28%" align="left"><code>SYSTEM_NAME</code></th>
        <th width="46%" align="left"><code>ARCHITECTURE_&_CAPABILITIES</code></th>
        <th width="16%" align="center"><code>REPO_INDEX</code></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><code>0x08</code></td>
        <td><strong>Review Quality Analyzer</strong><br/><sub>Automated Text Evaluation</sub></td>
        <td>NLP &amp; feature-driven pipeline analyzing review authenticity, sentiment structure, and information density.</td>
        <td align="center"><a href="https://github.com/AGRIM140/review-quality-analyzer"><kbd>[OPEN_REPO]</kbd></a></td>
      </tr>
      <tr>
        <td><code>0x09</code></td>
        <td><strong>Financial OCR &amp; ETL</strong><br/><sub>Document Ingestion Pipeline</sub></td>
        <td>Automated optical character recognition and structured data extraction pipeline for financial statements and invoices.</td>
        <td align="center"><a href="https://github.com/AGRIM140?tab=repositories"><kbd>[VIEW_MOD]</kbd></a></td>
      </tr>
      <tr>
        <td><code>0x0A</code></td>
        <td><strong>CNN Auto-Colorization &amp; BERT NLP</strong><br/><sub>Deep Vision &amp; Hindi Homonym NLP</sub></td>
        <td>Deep Convolutional auto-colorization network and fine-tuned <code>BERT</code> transformer models for Hindi homonym classification.</td>
        <td align="center"><a href="https://github.com/AGRIM140?tab=repositories"><kbd>[VIEW_MOD]</kbd></a></td>
      </tr>
    </tbody>
  </table>
</details>

<p align="right"><sub><a href="#top"><kbd>^ RETURN_TO_BIOS</kbd></a></sub></p>

<!-- ======================================================================= -->
<!-- SECTION 05: TECHNICAL SPECIFICATIONS                                    -->
<!-- ======================================================================= -->
<a id="tech-specs"></a>
<img src="./assets/section-specs.svg" width="100%" alt="SECTION 05 // SYSTEM CONFIGURATION & LOADED MODULES" />

<table width="100%">
  <thead>
    <tr>
      <th width="26%" align="left"><code>SUBSYSTEM_BUS</code></th>
      <th width="74%" align="left"><code>LOADED_DRIVERS_AND_MODULES (CLICKABLE_SPECS)</code></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <strong><code>[BUS_01]</code> PROGRAMMING</strong><br/>
        <sub>Core Languages &amp; Compilers</sub>
      </td>
      <td>
        <a href="https://www.python.org/"><img src="https://img.shields.io/badge/LANG-PYTHON-607D8B?style=flat-square&labelColor=242424&logo=python&logoColor=EAE6DC" alt="Python" /></a>
        <a href="https://en.cppreference.com/w/c"><img src="https://img.shields.io/badge/LANG-C-77766F?style=flat-square&labelColor=242424&logo=c&logoColor=EAE6DC" alt="C" /></a>
        <a href="https://isocpp.org/"><img src="https://img.shields.io/badge/LANG-C++-607D8B?style=flat-square&labelColor=242424&logo=cplusplus&logoColor=EAE6DC" alt="C++" /></a>
        <a href="https://dev.java/"><img src="https://img.shields.io/badge/LANG-JAVA-77766F?style=flat-square&labelColor=242424" alt="Java" /></a>
        <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"><img src="https://img.shields.io/badge/LANG-JAVASCRIPT-607D8B?style=flat-square&labelColor=242424&logo=javascript&logoColor=EAE6DC" alt="JavaScript" /></a>
        <a href="https://www.typescriptlang.org/"><img src="https://img.shields.io/badge/LANG-TYPESCRIPT-77766F?style=flat-square&labelColor=242424&logo=typescript&logoColor=EAE6DC" alt="TypeScript" /></a>
      </td>
    </tr>
    <tr>
      <td>
        <strong><code>[BUS_02]</code> AI_ML_VISION</strong><br/>
        <sub>Neural &amp; Perception Engines</sub>
      </td>
      <td>
        <a href="https://pytorch.org/"><img src="https://img.shields.io/badge/AI-PYTORCH-607D8B?style=flat-square&labelColor=242424&logo=pytorch&logoColor=EAE6DC" alt="PyTorch" /></a>
        <a href="https://www.tensorflow.org/"><img src="https://img.shields.io/badge/AI-TENSORFLOW-77766F?style=flat-square&labelColor=242424&logo=tensorflow&logoColor=EAE6DC" alt="TensorFlow" /></a>
        <a href="https://scikit-learn.org/"><img src="https://img.shields.io/badge/ML-SCIKIT_LEARN-607D8B?style=flat-square&labelColor=242424&logo=scikitlearn&logoColor=EAE6DC" alt="Scikit-Learn" /></a>
        <a href="https://huggingface.co/"><img src="https://img.shields.io/badge/NLP-HUGGING_FACE-77766F?style=flat-square&labelColor=242424&logo=huggingface&logoColor=EAE6DC" alt="Hugging Face" /></a>
        <a href="https://huggingface.co/docs/transformers/"><img src="https://img.shields.io/badge/ARCH-TRANSFORMERS-607D8B?style=flat-square&labelColor=242424" alt="Transformers" /></a>
        <a href="https://opencv.org/"><img src="https://img.shields.io/badge/CV-OPENCV-78966B?style=flat-square&labelColor=242424&logo=opencv&logoColor=EAE6DC" alt="OpenCV" /></a>
        <a href="https://shap.readthedocs.io/"><img src="https://img.shields.io/badge/XAI-SHAP-77766F?style=flat-square&labelColor=242424" alt="SHAP" /></a>
      </td>
    </tr>
    <tr>
      <td>
        <strong><code>[BUS_03]</code> ROBOTICS_AUTONOMY</strong><br/>
        <sub>Field Perception &amp; Simulation</sub>
      </td>
      <td>
        <a href="https://docs.ros.org/en/rolling/"><img src="https://img.shields.io/badge/ROBOTICS-ROS_2-78966B?style=flat-square&labelColor=242424&logo=ros&logoColor=EAE6DC" alt="ROS 2" /></a>
        <a href="https://gazebosim.org/"><img src="https://img.shields.io/badge/SIM-GAZEBO-607D8B?style=flat-square&labelColor=242424&logo=gazebo&logoColor=EAE6DC" alt="Gazebo" /></a>
        <a href="https://mujoco.org/"><img src="https://img.shields.io/badge/PHYSICS-MUJOCO-77766F?style=flat-square&labelColor=242424" alt="MuJoCo" /></a>
        <a href="#project-directory"><img src="https://img.shields.io/badge/SENSOR-LIDAR_FUSION-607D8B?style=flat-square&labelColor=242424" alt="LiDAR" /></a>
        <a href="#project-directory"><img src="https://img.shields.io/badge/PERCEPTION-COMPUTER_VISION-77766F?style=flat-square&labelColor=242424" alt="Computer Vision" /></a>
        <a href="#project-directory"><img src="https://img.shields.io/badge/VISION-SEMANTIC_SEGMENTATION-78966B?style=flat-square&labelColor=242424" alt="Semantic Segmentation" /></a>
      </td>
    </tr>
    <tr>
      <td>
        <strong><code>[BUS_04]</code> BACKEND_WEB</strong><br/>
        <sub>APIs, Services &amp; Interfaces</sub>
      </td>
      <td>
        <a href="https://www.djangoproject.com/"><img src="https://img.shields.io/badge/BACKEND-DJANGO-607D8B?style=flat-square&labelColor=242424&logo=django&logoColor=EAE6DC" alt="Django" /></a>
        <a href="https://www.django-rest-framework.org/"><img src="https://img.shields.io/badge/API-DJANGO_REST-77766F?style=flat-square&labelColor=242424" alt="Django REST Framework" /></a>
        <a href="https://fastapi.tiangolo.com/"><img src="https://img.shields.io/badge/API-FASTAPI-78966B?style=flat-square&labelColor=242424&logo=fastapi&logoColor=EAE6DC" alt="FastAPI" /></a>
        <a href="https://spring.io/projects/spring-boot"><img src="https://img.shields.io/badge/MICROSERVICE-SPRING_BOOT-607D8B?style=flat-square&labelColor=242424&logo=springboot&logoColor=EAE6DC" alt="Spring Boot" /></a>
        <a href="https://flask.palletsprojects.com/"><img src="https://img.shields.io/badge/BACKEND-FLASK-77766F?style=flat-square&labelColor=242424&logo=flask&logoColor=EAE6DC" alt="Flask" /></a>
        <a href="https://react.dev/"><img src="https://img.shields.io/badge/UI-REACT-607D8B?style=flat-square&labelColor=242424&logo=react&logoColor=EAE6DC" alt="React" /></a>
        <a href="https://nextjs.org/"><img src="https://img.shields.io/badge/SSR-NEXT.JS-77766F?style=flat-square&labelColor=242424&logo=nextdotjs&logoColor=EAE6DC" alt="Next.js" /></a>
        <a href="https://streamlit.io/"><img src="https://img.shields.io/badge/APP-STREAMLIT-607D8B?style=flat-square&labelColor=242424&logo=streamlit&logoColor=EAE6DC" alt="Streamlit" /></a>
      </td>
    </tr>
    <tr>
      <td>
        <strong><code>[BUS_05]</code> DATA_INFRA</strong><br/>
        <sub>Persistence, Queues &amp; DevOps</sub>
      </td>
      <td>
        <a href="https://www.postgresql.org/"><img src="https://img.shields.io/badge/DB-POSTGRESQL-607D8B?style=flat-square&labelColor=242424&logo=postgresql&logoColor=EAE6DC" alt="PostgreSQL" /></a>
        <a href="https://redis.io/"><img src="https://img.shields.io/badge/CACHE-REDIS-77766F?style=flat-square&labelColor=242424&logo=redis&logoColor=EAE6DC" alt="Redis" /></a>
        <a href="https://docs.celeryq.dev/"><img src="https://img.shields.io/badge/QUEUE-CELERY-78966B?style=flat-square&labelColor=242424&logo=celery&logoColor=EAE6DC" alt="Celery" /></a>
        <a href="https://www.docker.com/"><img src="https://img.shields.io/badge/CONTAINER-DOCKER-607D8B?style=flat-square&labelColor=242424&logo=docker&logoColor=EAE6DC" alt="Docker" /></a>
        <a href="https://cloud.google.com/run"><img src="https://img.shields.io/badge/CLOUD-GOOGLE_CLOUD_RUN-77766F?style=flat-square&labelColor=242424&logo=googlecloud&logoColor=EAE6DC" alt="Google Cloud Run" /></a>
        <a href="https://git-scm.com/"><img src="https://img.shields.io/badge/VCS-GIT-607D8B?style=flat-square&labelColor=242424&logo=git&logoColor=EAE6DC" alt="Git" /></a>
        <a href="https://github.com/AGRIM140"><img src="https://img.shields.io/badge/HOST-GITHUB-242424?style=flat-square&labelColor=77766F&logo=github&logoColor=EAE6DC" alt="GitHub" /></a>
      </td>
    </tr>
  </tbody>
</table>

<p align="right"><sub><a href="#top"><kbd>^ RETURN_TO_BIOS</kbd></a></sub></p>

<!-- ======================================================================= -->
<!-- SECTION 06: GITHUB ANALYTICS (SYSTEM TELEMETRY)                         -->
<!-- ======================================================================= -->
<a id="telemetry"></a>
<img src="./assets/section-telemetry.svg" width="100%" alt="SECTION 06 // SYSTEM PERFORMANCE & TELEMETRY MONITOR" />

<table width="100%">
  <tr>
    <td width="50%" align="center" valign="middle">
      <code>[MON_01] // RESOURCE_UTILIZATION_&_COMMITS (AGRIM140)</code><br/><br/>
      <a href="https://github.com/AGRIM140">
        <img src="https://github-readme-stats-anuraghazra1.vercel.app/api?username=AGRIM140&show_icons=true&bg_color=EAE6DC&title_color=242424&text_color=242424&icon_color=607D8B&border_color=242424&border_radius=0&hide_border=false" width="100%" alt="GitHub System Statistics" />
      </a>
    </td>
    <td width="50%" align="center" valign="middle">
      <code>[MON_02] // LANGUAGE_ALLOCATION_DISTRIBUTION</code><br/><br/>
      <a href="https://github.com/AGRIM140">
        <img src="https://github-readme-stats-anuraghazra1.vercel.app/api/top-langs/?username=AGRIM140&layout=compact&langs_count=6&bg_color=EAE6DC&title_color=242424&text_color=242424&border_color=242424&border_radius=0&hide_border=false" width="100%" alt="Top Languages Distribution" />
      </a>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center" valign="middle">
      <code>[MON_03] // CONTINUOUS_UPTIME_STREAK_COUNTER</code><br/><br/>
      <img src="./assets/telemetry-streak.svg" width="100%" alt="GitHub Contribution Streak Counter" />
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center" valign="middle">
      <code>[MON_04] // TEMPORAL_CONTRIBUTION_OSCILLOSCOPE</code><br/><br/>
      <img src="./assets/telemetry-oscilloscope.svg" width="100%" alt="Temporal Contribution Activity Oscilloscope" />
    </td>
  </tr>
</table>

<p align="right"><sub><a href="#top"><kbd>^ RETURN_TO_BIOS</kbd></a></sub></p>

<!-- ======================================================================= -->
<!-- SECTION 07: TERMINAL / CURRENT STATUS                                   -->
<!-- ======================================================================= -->
<a id="terminal"></a>
<div align="center">
  <img src="./assets/crt-terminal.svg" width="100%" alt="CRT Terminal Session — agrim@workstation" />
</div>

<details open>
  <summary><kbd>[TTY_RAW_BUFFER]</kbd> <code>View Plaintext Copyable Session Log (/dev/tty1)</code></summary>
  <pre lang="bash">
agrim@workstation:~$ whoami
Agrim Singh (AGRIM140) — Computer Science Engineer | AI/ML & Robotics Developer

agrim@workstation:~$ current_focus
Autonomous Ground Vehicles (A-IMCS / AGVS) | Computer Vision | Distributed Backends

agrim@workstation:~$ cat /proc/workstation/deployment
ROLE      : Contributing to A-IMCS & AGVS @ Pentagon Rugged Systems Pvt. Ltd.
PERCEPTION: Off-Road Semantic Segmentation (PSP-MobileNet, RUGD, RELLIS-3D)
ROBOTICS  : LiDAR Sensor Fusion, ROS 2 Middleware, Gazebo & MuJoCo Simulation
COMMUNITY : Founder @ Recursion (SMIT Coding & GATE Club) | Google Campus Ambassador

agrim@workstation:~$ uptime --status
STATUS: ONLINE // READY FOR COLLABORATION AND COMPLEX SYSTEMS ENGINEERING</pre>
</details>

<br/>

<!-- ======================================================================= -->
<!-- SECTION 08: CONTACT / CONNECTION TERMINAL                               -->
<!-- ======================================================================= -->
<a id="com-ports"></a>
<img src="./assets/section-contact.svg" width="100%" alt="SECTION 08 // EXTERNAL I/O & SERIAL COMMUNICATION PORTS" />

<table width="100%">
  <thead>
    <tr>
      <th width="20%" align="left"><code>PORT_ID</code></th>
      <th width="25%" align="left"><code>PROTOCOL / INTERFACE</code></th>
      <th width="30%" align="left"><code>CHANNEL_STATUS</code></th>
      <th width="25%" align="center"><code>ACTION_TRIGGER</code></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>COM1 // 0x3F8</code></td>
      <td><strong>GITHUB_VCS_BUS</strong><br/><sub><code>[github.com/AGRIM140](https://github.com/AGRIM140)</code></sub></td>
      <td><img src="https://img.shields.io/badge/LINK-ONLINE-78966B?style=flat-square&labelColor=242424&logo=github&logoColor=EAE6DC" alt="GitHub Online" /></td>
      <td align="center"><a href="https://github.com/AGRIM140"><kbd>[CONNECT_GITHUB]</kbd></a></td>
    </tr>
    <tr>
      <td><code>COM2 // 0x2F8</code></td>
      <td><strong>LINKEDIN_NET_NODE</strong><br/><sub><code>Professional Network</code></sub></td>
      <td><img src="https://img.shields.io/badge/LINK-ACTIVE-607D8B?style=flat-square&labelColor=242424&logo=linkedin&logoColor=EAE6DC" alt="LinkedIn Active" /></td>
      <td align="center"><a href="https://www.linkedin.com/in/agrim-singh/"><kbd>[CONNECT_LINKEDIN]</kbd></a></td>
    </tr>
    <tr>
      <td><code>COM3 // 0x3E8</code></td>
      <td><strong>SMTP_DIRECT_MAIL</strong><br/><sub><code>agrims.singh@gmail.com</code></sub></td>
      <td><img src="https://img.shields.io/badge/PORT-LISTENING-EAE6DC?style=flat-square&labelColor=242424&logo=minutemailer&logoColor=242424" alt="Email Listening" /></td>
      <td align="center"><a href="mailto:agrims.singh@gmail.com"><kbd>[SEND_TRANSMISSION]</kbd></a></td>
    </tr>
  </tbody>
</table>

<br/>

<!-- ======================================================================= -->
<!-- SECTION 09: FOOTER                                                      -->
<!-- ======================================================================= -->
<div align="center">
  <img src="./assets/footer.svg" width="100%" alt="END OF TRANSMISSION // BUILT WITH CURIOSITY AND TOO MUCH COFFEE." />
</div>
