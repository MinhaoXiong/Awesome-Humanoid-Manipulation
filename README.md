<div align=center>

# Awesome Humanoid Manipulation

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
![papercount](https://img.shields.io/badge/paper_count-50+-pink)
[![Maintenance](https://img.shields.io/badge/maintained%3F-yes-green.svg)](https://github.com/Naereen/StrapDown.js/graphs/commit-activity)

</div>

A curated list of awesome papers and resources on **Humanoid Robot Manipulation**.

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
  - [Dexterous Hand](#dexterous-hand)
  - [Datasets & Benchmarks](#datasets--benchmarks)

---

## Loco-Manipulation

- **[1] VIRAL: Visual Sim-to-Real at Scale for Humanoid Loco-Manipulation**, arXiv 2025.

  *Authors.*

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

  *Authors.*

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

- **[3] HumanPlus: Humanoid Shadowing and Imitation from Humans**, arXiv 2024.

  *Fu, Zipeng and Zhao, Qingqing and Wu, Qi and Wetzstein, Gordon and Finn, Chelsea.*

  [[Paper](https://arxiv.org/abs/2406.10454)] [[Project](https://humanoid-ai.github.io/)] [[Code](https://github.com/MarkFzp/humanplus)] ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Loco--Manipulation-purple) ![](https://img.shields.io/badge/Real--World-orange) ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{fu2024humanplus,
    title={HumanPlus: Humanoid Shadowing and Imitation from Humans},
    author={Fu, Zipeng and Zhao, Qingqing and Wu, Qi and Wetzstein, Gordon and Finn, Chelsea},
    journal={arXiv preprint arXiv:2406.10454},
    year={2024}
  }
  ```

  </details>

- **[4] OmniH2O: Universal and Dexterous Human-to-Humanoid Whole-Body Teleoperation and Learning**, arXiv 2024.

  *Authors.*

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

- **[5] HOMIE: Humanoid Loco-Manipulation with Isomorphic Exoskeleton Cockpit**, arXiv 2025.

  *Authors.*

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

- **[6] HugWBC: A Unified and General Humanoid Whole-Body Controller for Fine-Grained Locomotion**, arXiv 2025.

  *Authors.*

  [[Paper](https://arxiv.org/abs/2502.03206)] [[Project](https://hugwbc.github.io/)] ![](https://img.shields.io/badge/RL-blue) ![](https://img.shields.io/badge/Loco--Manipulation-purple) ![](https://img.shields.io/badge/Real--World-orange)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{hugwbc2025,
    title={HugWBC: A Unified and General Humanoid Whole-Body Controller for Fine-Grained Locomotion},
    author={Authors},
    journal={arXiv preprint arXiv:2502.03206},
    year={2025}
  }
  ```

  </details>

- **[7] HOVER: Versatile Neural Whole-Body Controller for Humanoid Robots**, arXiv 2024.

  *Authors.*

  [[Paper](https://arxiv.org/abs/2410.21229)] [[Project](https://hover-versatile-humanoid.github.io/)] ![](https://img.shields.io/badge/RL-blue) ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Loco--Manipulation-purple) ![](https://img.shields.io/badge/Real--World-orange)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{hover2024,
    title={HOVER: Versatile Neural Whole-Body Controller for Humanoid Robots},
    author={Authors},
    journal={arXiv preprint arXiv:2410.21229},
    year={2024}
  }
  ```

  </details>

- **[8] ExBody2: Advanced Expressive Humanoid Whole-Body Control**, arXiv 2024.

  *Authors.*

  [[Paper](https://arxiv.org/abs/2412.13196)] [[Project](https://exbody2.github.io/)] ![](https://img.shields.io/badge/RL-blue) ![](https://img.shields.io/badge/Loco--Manipulation-purple) ![](https://img.shields.io/badge/Real--World-orange)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{exbody2_2024,
    title={ExBody2: Advanced Expressive Humanoid Whole-Body Control},
    author={Authors},
    journal={arXiv preprint arXiv:2412.13196},
    year={2024}
  }
  ```

  </details>

- **[9] WoCoCo: Learning Whole-Body Humanoid Control with Sequential Contacts**, arXiv 2024.

  *Authors.*

  [[Paper](https://arxiv.org/abs/2406.06005)] [[Project](https://lecar-lab.github.io/wococo/)] ![](https://img.shields.io/badge/RL-blue) ![](https://img.shields.io/badge/Loco--Manipulation-purple) ![](https://img.shields.io/badge/Sim--to--Real-orange)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{wococo2024,
    title={WoCoCo: Learning Whole-Body Humanoid Control with Sequential Contacts},
    author={Authors},
    journal={arXiv preprint arXiv:2406.06005},
    year={2024}
  }
  ```

  </details>

- **[10] Expressive Whole-Body Control for Humanoid Robots**, arXiv 2024.

  *Authors.*

  [[Paper](https://arxiv.org/abs/2402.16796)] [[Project](https://expressive-humanoid.github.io/)] [[Code](https://github.com/chengxuxin/expressive-humanoid)] ![](https://img.shields.io/badge/RL-blue) ![](https://img.shields.io/badge/Loco--Manipulation-purple) ![](https://img.shields.io/badge/Real--World-orange) ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{expressive2024,
    title={Expressive Whole-Body Control for Humanoid Robots},
    author={Authors},
    journal={arXiv preprint arXiv:2402.16796},
    year={2024}
  }
  ```

  </details>

---

## Non-Loco-Manipulation

- **[1] Generalizable Humanoid Manipulation with Improved 3D Diffusion Policies**, arXiv 2024.

  *Authors.*

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

  *Authors.*

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

  *Authors.*

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

- **[4] OpenVLA: An Open-Source Vision-Language-Action Model**, arXiv 2024.

  *Kim, Moo Jin and Pertsch, Karl and Karamcheti, Siddharth and others.*

  [[Paper](https://arxiv.org/abs/2406.09246)] [[Code](https://github.com/openvla/openvla)] ![](https://img.shields.io/badge/VLA-blue) ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{kim2024openvla,
    title={OpenVLA: An Open-Source Vision-Language-Action Model},
    author={Kim, Moo Jin and Pertsch, Karl and Karamcheti, Siddharth and others},
    journal={arXiv preprint arXiv:2406.09246},
    year={2024}
  }
  ```

  </details>

- **[5] ACE: A Cross-Platform Visual-Exoskeletons System for Low-Cost Dexterous Teleoperation**, arXiv 2024.

  *Authors.*

  [[Paper](https://arxiv.org/abs/2408.11805)] [[Project](https://ace-teleop.github.io/)] [[Code](https://github.com/ACETeleop/ACETeleop)] ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Bimanual-purple) ![](https://img.shields.io/badge/Dexterous--Manipulation-purple) ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{ace2024,
    title={ACE: A Cross-Platform Visual-Exoskeletons System for Low-Cost Dexterous Teleoperation},
    author={Authors},
    journal={arXiv preprint arXiv:2408.11805},
    year={2024}
  }
  ```

  </details>

- **[6] Open-TeleVision: Teleoperation with Immersive Active Visual Feedback**, arXiv 2024.

  *Authors.*

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

- **[7] Bunny-VisionPro: Real-Time Bimanual Dexterous Teleoperation for Imitation Learning**, arXiv 2024.

  *Authors.*

  [[Paper](https://arxiv.org/abs/2407.03162)] [[Project](https://dingry.github.io/projects/bunny_visionpro.html)] [[Code](https://github.com/Dingry/BunnyVisionPro)] ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Bimanual-purple) ![](https://img.shields.io/badge/Dexterous--Manipulation-purple) ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{bunny2024,
    title={Bunny-VisionPro: Real-Time Bimanual Dexterous Teleoperation for Imitation Learning},
    author={Authors},
    journal={arXiv preprint arXiv:2407.03162},
    year={2024}
  }
  ```

  </details>

- **[8] Bi-DexHands: Towards Human-Level Bimanual Dexterous Manipulation**, TPAMI 2024.

  *Chen, Yuanpei and Wang, Yaodong and others.*

  [[Paper](https://arxiv.org/abs/2206.08686)] [[Code](https://github.com/PKU-MARL/DexterousHands)] ![](https://img.shields.io/badge/RL-blue) ![](https://img.shields.io/badge/Bimanual-purple) ![](https://img.shields.io/badge/Dexterous--Manipulation-purple) ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{chen2022bi,
    title={Bi-DexHands: Towards Human-Level Bimanual Dexterous Manipulation},
    author={Chen, Yuanpei and Wang, Yaodong and others},
    journal={TPAMI},
    year={2024}
  }
  ```

  </details>

---

## Dexterous Hand

- **[1] DexMV: Imitation Learning for Dexterous Manipulation from Human Videos**, ECCV 2022.

  *Qin, Yuzhe and Wu, Yueh-Hua and Liu, Shaowei and Jiang, Hanwen and Yang, Ruihan and Fu, Yang and Wang, Xiaolong.*

  [[Paper](https://arxiv.org/abs/2108.05877)] [[Code](https://github.com/yzqin/dexmv-sim)] ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Dexterous--Manipulation-purple) ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @inproceedings{qin2022dexmv,
    title={DexMV: Imitation Learning for Dexterous Manipulation from Human Videos},
    author={Qin, Yuzhe and Wu, Yueh-Hua and Liu, Shaowei and Jiang, Hanwen and Yang, Ruihan and Fu, Yang and Wang, Xiaolong},
    booktitle={ECCV},
    year={2022}
  }
  ```

  </details>

- **[2] DexPoint: Generalizable Point Cloud Reinforcement Learning for Sim-to-Real Dexterous Manipulation**, CoRL 2022.

  *Qin, Yuzhe and Huang, Binghao and Yin, Zhao-Heng and Su, Hao and Wang, Xiaolong.*

  [[Paper](https://arxiv.org/abs/2211.15036)] [[Code](https://github.com/yzqin/dexpoint-release)] ![](https://img.shields.io/badge/RL-blue) ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Dexterous--Manipulation-purple) ![](https://img.shields.io/badge/Sim--to--Real-orange) ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @inproceedings{qin2022dexpoint,
    title={DexPoint: Generalizable Point Cloud Reinforcement Learning for Sim-to-Real Dexterous Manipulation},
    author={Qin, Yuzhe and Huang, Binghao and Yin, Zhao-Heng and Su, Hao and Wang, Xiaolong},
    booktitle={CoRL},
    year={2022}
  }
  ```

  </details>

- **[3] DexCap: Scalable and Portable Mocap Data Collection System for Dexterous Manipulation**, arXiv 2024.

  *Authors.*

  [[Paper](https://arxiv.org/abs/2403.07788)] [[Project](https://dex-cap.github.io/)] [[Code](https://github.com/j96w/DexCap)] ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Dexterous--Manipulation-purple) ![](https://img.shields.io/badge/Real--World-orange) ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{dexcap2024,
    title={DexCap: Scalable and Portable Mocap Data Collection System for Dexterous Manipulation},
    author={Authors},
    journal={arXiv preprint arXiv:2403.07788},
    year={2024}
  }
  ```

  </details>

- **[4] Learning Visuotactile Skills with Two Multifingered Hands**, arXiv 2024.

  *Authors.*

  [[Paper](https://arxiv.org/abs/2404.16823)] [[Project](https://toruowo.github.io/hato/)] [[Code](https://github.com/toruowo/hato)] ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Tactile-green) ![](https://img.shields.io/badge/Dexterous--Manipulation-purple) ![](https://img.shields.io/badge/Bimanual-purple) ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{hato2024,
    title={Learning Visuotactile Skills with Two Multifingered Hands},
    author={Authors},
    journal={arXiv preprint arXiv:2404.16823},
    year={2024}
  }
  ```

  </details>

- **[5] Object-Centric Dexterous Manipulation from Human Motion Data**, arXiv 2024.

  *Authors.*

  [[Paper](https://arxiv.org/abs/2411.04005)] [[Project](https://cypypccpy.github.io/obj-dex.github.io/)] ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Dexterous--Manipulation-purple)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{objdex2024,
    title={Object-Centric Dexterous Manipulation from Human Motion Data},
    author={Authors},
    journal={arXiv preprint arXiv:2411.04005},
    year={2024}
  }
  ```

  </details>

---

## Datasets & Benchmarks

- **[1] DROID: A Large-Scale In-The-Wild Robot Manipulation Dataset**, RSS 2024.

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

- **[2] HumanoidBench: Simulated Humanoid Benchmark for Whole-Body Locomotion and Manipulation**, arXiv 2024.

  *Authors.*

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

- **[3] ManiSkill3: GPU Parallelized Robotics Simulation and Rendering for Generalizable Embodied AI**, arXiv 2024.

  *Authors.*

  [[Paper](https://arxiv.org/abs/2410.00425)] [[Project](https://www.maniskill.ai/home)] [[Code](https://github.com/haosulab/ManiSkill)] ![](https://img.shields.io/badge/Dataset-red) ![](https://img.shields.io/badge/Open--Sourced-red)

  <details> <summary>BibTex</summary>

  ```bibtex
  @article{maniskill3_2024,
    title={ManiSkill3: GPU Parallelized Robotics Simulation and Rendering for Generalizable Embodied AI},
    author={Authors},
    journal={arXiv preprint arXiv:2410.00425},
    year={2024}
  }
  ```

  </details>

- **[4] RoboCasa: Large-Scale Simulation of Everyday Tasks for Generalist Robots**, arXiv 2024.

  *Authors.*

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

- **[5] Humanoid-Gym: Reinforcement Learning for Humanoid Robot with Zero-Shot Sim2Real Transfer**, arXiv 2024.

  *Authors.*

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
