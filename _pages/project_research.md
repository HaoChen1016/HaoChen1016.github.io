---
permalink: /project_research/
title: "Project/Research"
gallery:
  - url: project_research/SK8_hover.jpg
    image_path: project_research/SK8_hover.jpg
    alt: "SK8_hoverTest"
    title: "SK8_hoverTest"
  - url: project_research/SK8_hover1.jpg
    image_path: project_research/SK8_hover1.jpg
    alt: "SK8_hoverTest1"
    title: "SK8_hoverTest1"
  - url: project_research/SK8.jpg
    image_path: project_research/SK8.jpg
    alt: "SK8"
    title: "SK8"
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
{% include gallery %}

### “Challenge Cup” Competition: Multi-robot collaboration system for education and experimental purpose in structured environment (Sep 2016 – May 2018)
#### Undergraduate, Special Environment Key Laboratory of Sichuan Province, Southwest University of Science and Technogy, Mianyang, Sichuan, China. 
“Challenge Cup” National College Student Curricular Academic Science and Technology Works Competition: Multi-robot collaboration system for education and experimental purpose in structured environment. We develop path planning and collision avoidance strategy based on improved A star algorithm for multi-robot system in grid space.

### The upper compter software design of XY axis drawing robot (Mar 2017 – Jul 2017)
#### Undergraduate, Special Environment Key Laboratory of Sichuan Province, Southwest University of Science and Technogy, Mianyang, Sichuan, China. 
This project uses MATLAB to design the upper computer software of the XY axis drawing robot GUI. The input of the original image is from video photography or local image input, and then the image is grayed out and binarization. Based on this, the image boundaries are obtained through the eight adjacency method, and then the boundaries are converted into images to achieve image contour extraction. Secondly, the same image is binarized according to different thresholds and divided into four images with different black and white degrees. In order to achieve a sketching effect on the drawn image, four different filling methods were used, including along the X and Y axis at 45 and -135 degrees. The designed software can achieve good drawing and sketching performance.

### 2017 (2nd) University Robot Competition of Sichuan Province
#### Undergraduate, Special Environment Key Laboratory of Sichuan Province, Southwest University of Science and Technogy, Mianyang, Sichuan, China. 
This competition requires to build a robot which can carry cylindrical building blocks to designated locations and use them to build designated shapes. The first robot to complete the construction of marked in the shape of the letter V in the middle of the competition venue will be the winner, with a competition time of 3 minutes. My work includes motion control and SLAM navigation of the robot.
