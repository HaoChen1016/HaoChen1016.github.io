---
permalink: /project_research/
title: "Project/Research"
---
### NSF-NRI: Safe Wind-Aware Navigation for Collaborative Autonomous Aircraft in Low Altitude Airspace (Sep 2019 – Dec 2023 (Expected))
#### Research Assistant, Control, Robotics and Automation Laboratory (CoRAL), OSU, Stillwater, OK, USA. 

The project aims to validate the hypothesis that 'in-time' gust awareness by a pilot or an autopilot, can enhance safety, efficiency and robustness of future autonomous aircraft operations in low altitude airspace. Towards this objective, the research team will investigate novel learning tools to model piloting behaviors, design safe and efficient wind aware path planning algorithms, and importantly, construct short-term gust forecast models with wind measurements. The team will develop a high-fidelity simulation framework that integrates turbulence modeling, guidance, navigation, control, and pilot-aircraft interface to demonstrate autonomous and remotely-piloted aircraft flying through urban canopies with improved predictability and increased endurance. A recommendation system that facilitates pilot-aircraft interactions will be produced and demonstrated through both simulations and experiments. My work mainly includes:
- System modeling. We build mathematical models for nonlinear quadcopter dynamics which are integrated with various drag, thrust and wind models. 
- Estimation algorithm design for single agent states and wind estimation. We develop invariant EKFs (IEKFs) by taking advantage of symmetry in the system, and IEKFs show better transient performance compared to EKFs.
- Estimation and fusion algorithm design for multi-agent system states and wind estimation. We extend EKFs/IEKFs from single quadcopter to multiple-quadcopter system and develop information fusion methods.
- Machine learning methods for states and wind estimation. We train DNN to obtain the accurate thrust model and LSTM for wind estimation.
- MATLAB/Simulink simulation validation. The MATLAB/Simulink simulation model integrates quadcopter dynamics, motor/rotor models, sensor models, wind models, estimators, controllers, and path planner.
- Indoor/outdoor experiments validation. For indoor experiments, we built a thrust stand for obtaining thrust model, a mobile robot for ground truth wind collection, and we used a motion capture system for pose feedback and small-size quadcopter for flight test. For outdoor experiments, we conducted multiples outdoor experiments by using a large-size quadcopter for hovering test and various wind sensors for collecting true wind.
