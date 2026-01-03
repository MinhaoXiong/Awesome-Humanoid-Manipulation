<div align=center>

# Awesome Humanoid Manipulation

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
![papercount](https://img.shields.io/badge/paper_count-70+-pink)
[![Maintenance](https://img.shields.io/badge/maintained%3F-yes-green.svg)](https://github.com/Naereen/StrapDown.js/graphs/commit-activity)

</div>

A curated list of awesome papers and resources on **Humanoid Manipulation**.

## News

* **`2025/12/10`** We release the repo "[Awesome-Humanoid-Manipulation](https://github.com/MinhaoXiong/Awesome-Humanoid-Manipulation)", collecting recent papers on humanoid manipulation! Contributions are welcome!

## Overview

<p align="center"> <img src="images/banner.jpg" width="800" align="center"> </p>

We use the following tags to categorize each paper:

| Tag Type     | Examples                                                                                                                                                                        |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Method**   | ![](https://img.shields.io/badge/VLA-blue) ![](https://img.shields.io/badge/RL-blue) ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Diffusion-blue) |
| **Input**    | ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Tactile-green) ![](https://img.shields.io/badge/Force--Feedback-green)                   |
| **Task**     | ![](https://img.shields.io/badge/Dexterous--Manipulation-purple) ![](https://img.shields.io/badge/Bimanual-purple) ![](https://img.shields.io/badge/Loco--Manipulation-purple)  |
| **Feature**  | ![](https://img.shields.io/badge/Force--Adaptive-orange) ![](https://img.shields.io/badge/Sim--to--Real-orange) ![](https://img.shields.io/badge/Real--World-orange)            |
| **Resource** | ![](https://img.shields.io/badge/Open--Sourced-red) ![](https://img.shields.io/badge/Dataset-red)                                                                               |

## Contents

- [Awesome Humanoid Manipulation](#awesome-humanoid-manipulation)
  - [Loco-Manipulation](#loco-manipulation)
  - [Non-Loco-Manipulation](#non-loco-manipulation)
  - [Retargeting](#retargeting)
  - [Whole-Body Controller](#whole-body-controller)
  - [Human Motion Dataset](#human-motion-dataset)

---

## Loco-Manipulation

- **[1] VIRAL: Visual Sim-to-Real at Scale for Humanoid Loco-Manipulation**, arXiv 2025.

  [[Paper](https://arxiv.org/abs/2511.15200)] ![](https://img.shields.io/badge/RL-blue) ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Loco--Manipulation-purple) ![](https://img.shields.io/badge/Sim--to--Real-orange)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{viral2025,
    title={VIRAL: Visual Sim-to-Real at Scale for Humanoid Loco-Manipulation},
    author={Authors},
    journal={arXiv preprint arXiv:2511.15200},
    year={2025}
  }
  ```

  </details>

- **[2] FALCON: Learning Force-Adaptive Humanoid Loco-Manipulation**, arXiv 2025.

  [[Paper](https://arxiv.org/abs/2505.06776)] [[Project](https://lecar-lab.github.io/falcon-humanoid/)] ![](https://img.shields.io/badge/RL-blue) ![](https://img.shields.io/badge/Loco--Manipulation-purple) ![](https://img.shields.io/badge/Force--Adaptive-orange) ![](https://img.shields.io/badge/Real--World-orange)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{falcon2025,
    title={FALCON: Learning Force-Adaptive Humanoid Loco-Manipulation},
    author={Authors},
    journal={arXiv preprint arXiv:2505.06776},
    year={2025}
  }
  ```

  </details>

- **[3] OmniH2O: Universal and Dexterous Human-to-Humanoid Whole-Body Teleoperation and Learning**, arXiv 2024.

  [[Paper](https://arxiv.org/abs/2406.08858)] [[Project](https://omni.human2humanoid.com/)] [[Code](https://github.com/LeCAR-Lab/human2humanoid)] ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Loco--Manipulation-purple) ![](https://img.shields.io/badge/Real--World-orange) ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{omnih2o2024,
    title={OmniH2O: Universal and Dexterous Human-to-Humanoid Whole-Body Teleoperation and Learning},
    author={Authors},
    journal={arXiv preprint arXiv:2406.08858},
    year={2024}
  }
  ```

  </details>

- **[4] HOMIE: Humanoid Loco-Manipulation with Isomorphic Exoskeleton Cockpit**, arXiv 2025.

  [[Paper](https://arxiv.org/abs/2502.13013)] [[Project](https://homietele.github.io/)] [[Code](https://github.com/OpenRobotLab/OpenHomie)] ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Loco--Manipulation-purple) ![](https://img.shields.io/badge/Real--World-orange) ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{homie2025,
    title={HOMIE: Humanoid Loco-Manipulation with Isomorphic Exoskeleton Cockpit},
    author={Authors},
    journal={arXiv preprint arXiv:2502.13013},
    year={2025}
  }
  ```

  </details>

- **[5] DreamControl: Human-Inspired Whole-Body Humanoid Control for Scene Interaction via Guided Diffusion**, arXiv 2025.

  *Dvij Kalaria, Sudarshan S Harithas, Pushkal Katara, Sangkyung Kwak, Sarthak Bhagat, Shankar Sastry, Srinath Sridhar, Sai Vemprala, Ashish Kapoor, Jonathan Chung-Kuan Huang.*

  [[Paper](https://arxiv.org/abs/2509.14353)] [[Project](https://genrobo.github.io/DreamControl/)] ![](https://img.shields.io/badge/Diffusion-blue) ![](https://img.shields.io/badge/Loco--Manipulation-purple)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{kalaria2025dreamcontrol,
    title={DreamControl: Human-Inspired Whole-Body Humanoid Control for Scene Interaction via Guided Diffusion},
    author={Kalaria, Dvij and Harithas, Sudarshan S and Katara, Pushkal and Kwak, Sangkyung and Bhagat, Sarthak and Sastry, Shankar and Sridhar, Srinath and Vemprala, Sai and Kapoor, Ashish and Huang, Jonathan Chung-Kuan},
    journal={arXiv preprint arXiv:2509.14353},
    year={2025}
  }
  ```

  </details>

- **[6] HAFO: A Force-Adaptive Control Framework for Humanoid Robots in Intense Interaction Environments**, arXiv 2025.

  *Chenhui Dong, Haozhe Xu, Wenhao Feng, Zhipeng Wang, Yanmin Zhou, Yifei Zhao, Bin He.*

  [[Paper](https://arxiv.org/abs/2511.20275)] ![](https://img.shields.io/badge/RL-blue) ![](https://img.shields.io/badge/Loco--Manipulation-purple) ![](https://img.shields.io/badge/Force--Adaptive-orange)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{dong2025hafo,
    title={HAFO: A Force-Adaptive Control Framework for Humanoid Robots in Intense Interaction Environments},
    author={Dong, Chenhui and Xu, Haozhe and Feng, Wenhao and Wang, Zhipeng and Zhou, Yanmin and Zhao, Yifei and He, Bin},
    journal={arXiv preprint arXiv:2511.20275},
    year={2025}
  }
  ```

  </details>

- **[7] VisualMimic: Visual Humanoid Loco-Manipulation via Motion Tracking and Generation**, arXiv 2025.

  *Shaofeng Yin, Yanjie Ze, Hong-Xing Yu, C. Karen Liu, Jiajun Wu.*

  [[Paper](https://arxiv.org/abs/2509.20322)] [[Project](https://visualmimic.github.io/)] ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Loco--Manipulation-purple)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{yin2025visualmimic,
    title={VisualMimic: Visual Humanoid Loco-Manipulation via Motion Tracking and Generation},
    author={Yin, Shaofeng and Ze, Yanjie and Yu, Hong-Xing and Liu, C. Karen and Wu, Jiajun},
    journal={arXiv preprint arXiv:2509.20322},
    year={2025}
  }
  ```

  </details>

- **[8] HDMI: Learning Interactive Humanoid Whole-Body Control from Human Videos**, arXiv 2025.

  [[Paper](https://arxiv.org/abs/2509.16757)] [[Project](http://hdmi-humanoid.github.io/)] ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Loco--Manipulation-purple)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{hdmi2025,
    title={HDMI: Learning Interactive Humanoid Whole-Body Control from Human Videos},
    journal={arXiv preprint arXiv:2509.16757},
    year={2025}
  }
  ```

  </details>

- **[9] ResMimic: From General Motion Tracking to Humanoid Whole-body Loco-Manipulation via Residual Learning**, arXiv 2025.

  [[Paper](https://arxiv.org/abs/2510.05070)] [[Project](https://resmimic.github.io/)] ![](https://img.shields.io/badge/RL-blue) ![](https://img.shields.io/badge/Loco--Manipulation-purple)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{resmimic2025,
    title={ResMimic: From General Motion Tracking to Humanoid Whole-body Loco-Manipulation via Residual Learning},
    journal={arXiv preprint arXiv:2510.05070},
    year={2025}
  }
  ```

  </details>

- **[10] HMC: Learning Heterogeneous Meta-Control for Contact-Rich Loco-Manipulation**, arXiv 2025.

  [[Paper](https://arxiv.org/abs/2511.14756)] ![](https://img.shields.io/badge/RL-blue) ![](https://img.shields.io/badge/Loco--Manipulation-purple)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{hmc2025,
    title={HMC: Learning Heterogeneous Meta-Control for Contact-Rich Loco-Manipulation},
    journal={arXiv preprint arXiv:2511.14756},
    year={2025}
  }
  ```

  </details>

- **[11] Human2LocoMan: Learning Versatile Quadrupedal Manipulation with Human Pretraining**, arXiv 2025.

  [[Paper](https://arxiv.org/pdf/2506.16475)] [[Project](https://human2bots.github.io/)] ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Loco--Manipulation-purple)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{human2locoman2025,
    title={Human2LocoMan: Learning Versatile Quadrupedal Manipulation with Human Pretraining},
    journal={arXiv preprint arXiv:2506.16475},
    year={2025}
  }
  ```

  </details>

- **[12] Guided Reinforcement Learning for Robust Multi-Contact Loco-Manipulation**, OpenReview 2025.

  [[Paper](https://openreview.net/pdf?id=9aZ4ehSTRc)] [[Project](https://leggedrobotics.github.io/guided-rl-locoma/)] ![](https://img.shields.io/badge/RL-blue) ![](https://img.shields.io/badge/Loco--Manipulation-purple)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{guidedrl2025,
    title={Guided Reinforcement Learning for Robust Multi-Contact Loco-Manipulation},
    year={2025}
  }
  ```

  </details>

- **[13] M2Diffuser: Diffusion-based Trajectory Optimization**, IEEE 2025.

  [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10937276)] [[Project](https://m2diffuser.github.io/)] ![](https://img.shields.io/badge/Diffusion-blue) ![](https://img.shields.io/badge/Loco--Manipulation-purple)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{m2diffuser2025,
    title={M2Diffuser: Diffusion-based Trajectory Optimization},
    year={2025}
  }
  ```

  </details>

- **[14] WildLMa: Long Horizon Loco-Manipulation in the Wild**, arXiv 2024.

  [[Paper](https://arxiv.org/pdf/2411.15131)] [[Project](https://wildlma.github.io/)] ![](https://img.shields.io/badge/RL-blue) ![](https://img.shields.io/badge/Loco--Manipulation-purple) ![](https://img.shields.io/badge/Real--World-orange)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{wildlma2024,
    title={WildLMa: Long Horizon Loco-Manipulation in the Wild},
    journal={arXiv preprint arXiv:2411.15131},
    year={2024}
  }
  ```

  </details>

- **[15] HERMES: Human-to-Robot Embodied Learning from Multi-Source Motion Data for Mobile Dexterous Manipulation**, arXiv 2025.

  [[Paper](https://arxiv.org/abs/2508.20085)] [[Project](https://gemcollector.github.io/HERMES/)] ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Loco--Manipulation-purple) ![](https://img.shields.io/badge/Dexterous--Manipulation-purple)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{hermes2025,
    title={HERMES: Human-to-Robot Embodied Learning from Multi-Source Motion Data for Mobile Dexterous Manipulation},
    journal={arXiv preprint arXiv:2508.20085},
    year={2025}
  }
  ```

  </details>

- **[16] In-N-On: Scaling Egocentric Manipulation with in-the-wild and on-task Data**, arXiv 2025.

  [[Paper](https://arxiv.org/abs/2511.15704)] [[Project](https://xiongyicai.github.io/In-N-On/)] ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Loco--Manipulation-purple)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{innon2025,
    title={In-N-On: Scaling Egocentric Manipulation with in-the-wild and on-task Data},
    journal={arXiv preprint arXiv:2511.15704},
    year={2025}
  }
  ```

  </details>

- **[17] ActiveUMI: Robotic Manipulation with Active Perception from Robot-Free Human Demonstrations**, arXiv 2025.

  [[Paper](https://arxiv.org/abs/2510.01607)] ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Loco--Manipulation-purple)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{activeumi2025,
    title={ActiveUMI: Robotic Manipulation with Active Perception from Robot-Free Human Demonstrations},
    journal={arXiv preprint arXiv:2510.01607},
    year={2025}
  }
  ```

  </details>

---

## Non-Loco-Manipulation

- **[1] Generalizable Humanoid Manipulation with Improved 3D Diffusion Policies**, arXiv 2024.

  [[Paper](https://arxiv.org/abs/2410.10803)] [[Project](https://humanoid-manipulation.github.io/)] [[Code](https://github.com/YanjieZe/Improved-3D-Diffusion-Policy)] ![](https://img.shields.io/badge/Diffusion-blue) ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Bimanual-purple) ![](https://img.shields.io/badge/Real--World-orange) ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{dp3_2024,
    title={Generalizable Humanoid Manipulation with Improved 3D Diffusion Policies},
    author={Authors},
    journal={arXiv preprint arXiv:2410.10803},
    year={2024}
  }
  ```

  </details>

- **[2] EgoMimic: Scaling Imitation Learning via Egocentric Video**, arXiv 2024.

  [[Paper](https://arxiv.org/abs/2410.24221)] [[Project](https://egomimic.github.io/)] [[Code](https://github.com/SimarKareer/EgoMimic)] ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Bimanual-purple) ![](https://img.shields.io/badge/Real--World-orange) ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{egomimic2024,
    title={EgoMimic: Scaling Imitation Learning via Egocentric Video},
    author={Authors},
    journal={arXiv preprint arXiv:2410.24221},
    year={2024}
  }
  ```

  </details>

- **[3] GR00T N1: An Open Foundation Model for Generalist Humanoid Robots**, arXiv 2025.

  [[Paper](https://arxiv.org/abs/2503.14734)] ![](https://img.shields.io/badge/VLA-blue) ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Bimanual-purple) ![](https://img.shields.io/badge/Real--World-orange)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{groot2025,
    title={GR00T N1: An Open Foundation Model for Generalist Humanoid Robots},
    author={Authors},
    journal={arXiv preprint arXiv:2503.14734},
    year={2025}
  }
  ```

  </details>

- **[4] Open-TeleVision: Teleoperation with Immersive Active Visual Feedback**, arXiv 2024.

  [[Paper](https://arxiv.org/abs/2407.01512)] [[Project](https://robot-tv.github.io/)] [[Code](https://github.com/OpenTeleVision/TeleVision)] ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Bimanual-purple) ![](https://img.shields.io/badge/Real--World-orange) ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{opentv2024,
    title={Open-TeleVision: Teleoperation with Immersive Active Visual Feedback},
    author={Authors},
    journal={arXiv preprint arXiv:2407.01512},
    year={2024}
  }
  ```

  </details>

- **[5] TrajBooster: Boosting Humanoid Whole-Body Manipulation via Trajectory-Centric Learning**, arXiv 2025.

  [[Paper](https://arxiv.org/abs/2509.11839)] [[Project](https://jiachengliu3.github.io/TrajBooster/)] ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Bimanual-purple)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{trajbooster2025,
    title={TrajBooster: Boosting Humanoid Whole-Body Manipulation via Trajectory-Centric Learning},
    journal={arXiv preprint arXiv:2509.11839},
    year={2025}
  }
  ```

  </details>

- **[6] Humanoid Policy ~ Human Policy**, arXiv 2025.

  [[Paper](https://arxiv.org/pdf/2503.13441)] [[Project](https://human-as-robot.github.io/)] ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Bimanual-purple) ![](https://img.shields.io/badge/Dataset-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{humanoidpolicy2025,
    title={Humanoid Policy ~ Human Policy},
    journal={arXiv preprint arXiv:2503.13441},
    year={2025}
  }
  ```

  </details>

- **[7] MotionTrans: Human VR Data Enable Motion-Level Learning for Robotic Manipulation Policies**, arXiv 2025.

  [[Paper](https://arxiv.org/abs/2509.17759)] ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Bimanual-purple)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{motiontrans2025,
    title={MotionTrans: Human VR Data Enable Motion-Level Learning for Robotic Manipulation Policies},
    journal={arXiv preprint arXiv:2509.17759},
    year={2025}
  }
  ```

  </details>

---

## Retargeting

- **[1] Retargeting Matters: General Motion Retargeting for Humanoid Motion Tracking**, arXiv 2025.

  *Joao Pedro Araujo, Yanjie Ze, Pei Xu, Jiajun Wu, C. Karen Liu.*

  [[Paper](https://arxiv.org/abs/2510.02252)] [[Code](https://github.com/YanjieZe/GMR)] ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{araujo2025retargeting,
    title={Retargeting Matters: General Motion Retargeting for Humanoid Motion Tracking},
    author={Araujo, Joao Pedro and Ze, Yanjie and Xu, Pei and Wu, Jiajun and Liu, C. Karen},
    journal={arXiv preprint arXiv:2510.02252},
    year={2025}
  }
  ```

  </details>

- **[2] SPIDER: Scalable Physics-Informed Dexterous Retargeting**, arXiv 2025.

  *Chaoyi Pan, Changhao Wang, Haozhi Qi, Zixi Liu, Homanga Bharadhwaj, Akash Sharma, Tingfan Wu, Guanya Shi, Jitendra Malik, Francois Hogan.*

  [[Paper](https://arxiv.org/abs/2511.09484)] [[Project](https://jc-bao.github.io/spider-project/)]

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{pan2025spider,
    title={SPIDER: Scalable Physics-Informed Dexterous Retargeting},
    author={Pan, Chaoyi and Wang, Changhao and Qi, Haozhi and Liu, Zixi and Bharadhwaj, Homanga and Sharma, Akash and Wu, Tingfan and Shi, Guanya and Malik, Jitendra and Hogan, Francois},
    journal={arXiv preprint arXiv:2511.09484},
    year={2025}
  }
  ```

  </details>

- **[3] OmniRetarget: Interaction-Preserving Data Generation for Humanoid Whole-Body Loco-Manipulation and Scene Interaction**, arXiv 2025.

  *Lujie Yang, Xiaoyu Huang, Zhen Wu, Angjoo Kanazawa, Pieter Abbeel, Carmelo Sferrazza, C. Karen Liu, Rocky Duan, Guanya Shi.*

  [[Paper](https://arxiv.org/abs/2509.26633)]

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{yang2025omniretarget,
    title={OmniRetarget: Interaction-Preserving Data Generation for Humanoid Whole-Body Loco-Manipulation and Scene Interaction},
    author={Yang, Lujie and Huang, Xiaoyu and Wu, Zhen and Kanazawa, Angjoo and Abbeel, Pieter and Sferrazza, Carmelo and Liu, C. Karen and Duan, Rocky and Shi, Guanya},
    journal={arXiv preprint arXiv:2509.26633},
    year={2025}
  }
  ```

  </details>

---

## Whole-Body Controller

- **[1] ULC: A Unified and Fine-Grained Controller for Humanoid Loco-Manipulation**, arXiv 2025.

  [[Paper](https://arxiv.org/abs/2507.06905)] ![](https://img.shields.io/badge/RL-blue) ![](https://img.shields.io/badge/Loco--Manipulation-purple)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{ulc2025,
    title={ULC: A Unified and Fine-Grained Controller for Humanoid Loco-Manipulation},
    journal={arXiv preprint arXiv:2507.06905},
    year={2025}
  }
  ```

  </details>

- **[2] Whole-Body End-Effector Pose Tracking**, IEEE 2025.

  [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11127964)] ![](https://img.shields.io/badge/RL-blue)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{wbeetracking2025,
    title={Whole-Body End-Effector Pose Tracking},
    year={2025}
  }
  ```

  </details>

- **[3] Humanoid Locomotion and Manipulation: Current Progress and Challenges in Control, Planning, and Learning**, arXiv 2025.

  [[Paper](https://arxiv.org/pdf/2501.02116)] ![](https://img.shields.io/badge/Survey-blue)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{humanoidsurvey2025,
    title={Humanoid Locomotion and Manipulation: Current Progress and Challenges in Control, Planning, and Learning},
    journal={arXiv preprint arXiv:2501.02116},
    year={2025}
  }
  ```

  </details>

---

## Human Motion Generation&Dataset

- **[1] Object Motion Guided Human Motion Synthesis**, arXiv 2023.

  *Jiaman Li, Jiajun Wu, C. Karen Liu.*

  [[Paper](https://arxiv.org/abs/2309.16237)] ![](https://img.shields.io/badge/Dataset-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{li2023object,
    title={Object Motion Guided Human Motion Synthesis},
    author={Li, Jiaman and Wu, Jiajun and Liu, C. Karen},
    journal={arXiv preprint arXiv:2309.16237},
    year={2023}
  }
  ```

  </details>

- **[2] GRAB: A Dataset of Whole-Body Human Grasping of Objects**, ECCV 2020.

  *Omid Taheri, Nima Ghorbani, Michael J. Black, Dimitrios Tzionas.*

  [[Paper](https://arxiv.org/abs/2008.11200)] [[Project](https://grab.is.tue.mpg.de/)] ![](https://img.shields.io/badge/Dataset-red) ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{taheri2020grab,
    title={GRAB: A Dataset of Whole-Body Human Grasping of Objects},
    author={Taheri, Omid and Ghorbani, Nima and Black, Michael J. and Tzionas, Dimitrios},
    journal={arXiv preprint arXiv:2008.11200},
    year={2020}
  }
  ```

  </details>

- **[3] HUMOTO: A 4D Dataset of Mocap Human Object Interactions**, arXiv 2025.

  *Jiaxin Lu, Chun-Hao Paul Huang, Uttaran Bhattacharya, Qixing Huang, Yi Zhou.*

  [[Paper](https://arxiv.org/abs/2504.10414)] [[Project](https://jiaxin-lu.github.io/humoto/)] ![](https://img.shields.io/badge/Dataset-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{lu2025humoto,
    title={HUMOTO: A 4D Dataset of Mocap Human Object Interactions},
    author={Lu, Jiaxin and Huang, Chun-Hao Paul and Bhattacharya, Uttaran and Huang, Qixing and Zhou, Yi},
    journal={arXiv preprint arXiv:2504.10414},
    year={2025}
  }
  ```

  </details>

- **[4] PICO: Reconstructing 3D People In Contact with Objects**, arXiv 2025.

  [[Paper](https://arxiv.org/abs/2504.17695)] [[Project](https://pico.is.tue.mpg.de/)] ![](https://img.shields.io/badge/Dataset-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{pico2025,
    title={PICO: Reconstructing 3D People In Contact with Objects},
    journal={arXiv preprint arXiv:2504.17695},
    year={2025}
  }
  ```

  </details>

- **[5] Efficient and Scalable Monocular Human-Object Interaction Motion Reconstruction**, arXiv 2025.

  [[Paper](https://arxiv.org/pdf/2512.00960)] [[Project](https://wenboran2002.github.io/open4dhoi/)] ![](https://img.shields.io/badge/Dataset-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{open4dhoi2025,
    title={Efficient and Scalable Monocular Human-Object Interaction Motion Reconstruction},
    journal={arXiv preprint arXiv:2512.00960},
    year={2025}
  }
  ```

  </details>

- **[6] OmniControl: Control Any Joint at Any Time for Human Motion Generation**, arXiv 2023.

  [[Paper](https://arxiv.org/abs/2310.08580)] [[Project](https://neu-vi.github.io/omnicontrol/)]

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{omnicontrol2023,
    title={OmniControl: Control Any Joint at Any Time for Human Motion Generation},
    journal={arXiv preprint arXiv:2310.08580},
    year={2023}
  }
  ```

  </details>

- **[7] Learning to Control Physically-simulated 3D Characters via Generating and Mimicking 2D Motions**, arXiv 2025.

  [[Paper](https://arxiv.org/pdf/2512.08500)] [[Project](https://jiann-li.github.io/mimic2dm/)]

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{mimic2dm2025,
    title={Learning to Control Physically-simulated 3D Characters via Generating and Mimicking 2D Motions},
    journal={arXiv preprint arXiv:2512.08500},
    year={2025}
  }
  ```

  </details>

- **[8] DROID: A Large-Scale In-The-Wild Robot Manipulation Dataset**, RSS 2024.

  *Khazatsky, Alexander and others.*

  [[Paper](https://arxiv.org/abs/2403.12945)] [[Project](https://droid-dataset.github.io/)] ![](https://img.shields.io/badge/Dataset-red) ![](https://img.shields.io/badge/Real--World-orange) ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @inproceedings{khazatsky2024droid,
    title={DROID: A Large-Scale In-The-Wild Robot Manipulation Dataset},
    author={Khazatsky, Alexander and others},
    booktitle={RSS},
    year={2024}
  }
  ```

  </details>

- **[9] HumanoidBench: Simulated Humanoid Benchmark for Whole-Body Locomotion and Manipulation**, arXiv 2024.

  [[Paper](https://arxiv.org/abs/2403.10506)] [[Project](https://humanoid-bench.github.io/)] [[Code](https://github.com/carlosferrazza/humanoid-bench)] ![](https://img.shields.io/badge/Dataset-red) ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{humanoidbench2024,
    title={HumanoidBench: Simulated Humanoid Benchmark for Whole-Body Locomotion and Manipulation},
    author={Authors},
    journal={arXiv preprint arXiv:2403.10506},
    year={2024}
  }
  ```

  </details>

- **[10] RoboCasa: Large-Scale Simulation of Everyday Tasks for Generalist Robots**, arXiv 2024.

  [[Paper](https://arxiv.org/abs/2406.02523)] [[Project](https://robocasa.ai/)] [[Code](https://github.com/robocasa/robocasa)] ![](https://img.shields.io/badge/Dataset-red) ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{robocasa2024,
    title={RoboCasa: Large-Scale Simulation of Everyday Tasks for Generalist Robots},
    author={Authors},
    journal={arXiv preprint arXiv:2406.02523},
    year={2024}
  }
  ```

  </details>

- **[11] Humanoid-Gym: Reinforcement Learning for Humanoid Robot with Zero-Shot Sim2Real Transfer**, arXiv 2024.

  [[Paper](https://arxiv.org/abs/2404.05695)] [[Project](https://sites.google.com/view/humanoid-gym/)] [[Code](https://github.com/roboterax/humanoid-gym)] ![](https://img.shields.io/badge/Dataset-red) ![](https://img.shields.io/badge/Sim--to--Real-orange) ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{humanoidgym2024,
    title={Humanoid-Gym: Reinforcement Learning for Humanoid Robot with Zero-Shot Sim2Real Transfer},
    author={Authors},
    journal={arXiv preprint arXiv:2404.05695},
    year={2024}
  }
  ```

  </details>

---

## Citation

If you find this repository helpful, please consider citing:

```bibtex
@misc{awesome-humanoid-manipulation,
  author = {Minhao Xiong},
  title = {Awesome Humanoid Manipulation},
  year = {2025},
  publisher = {GitHub},
  howpublished = {\url{https://github.com/MinhaoXiong/Awesome-Humanoid-Manipulation}}
}
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
