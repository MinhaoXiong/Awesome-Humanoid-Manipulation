<div align=center>

# Awesome Humanoid Manipulation

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
![papercount](https://img.shields.io/badge/paper_count-50+-pink)
[![Maintenance](https://img.shields.io/badge/maintained%3F-yes-green.svg)](https://github.com/Naereen/StrapDown.js/graphs/commit-activity)

<!-- [![Last Commit](https://img.shields.io/github/last-commit/YOUR_USERNAME/Awesome-Humanoid-Manipulation.svg?style=flat&color=orange)](https://github.com/YOUR_USERNAME/Awesome-Humanoid-Manipulation) -->

<!-- [![GitHub](https://img.shields.io/github/stars/YOUR_USERNAME/Awesome-Humanoid-Manipulation.svg?style=social)](https://github.com/YOUR_USERNAME/Awesome-Humanoid-Manipulation)   -->

</div>

A curated list of awesome papers and resources on **Humanoid Robot Manipulation**, including dexterous manipulation, bimanual coordination, loco-manipulation, and more.

## News

* **`2025/12/10`** We release the repo "[Awesome-Humanoid-Manipulation](https://github.com/YOUR_USERNAME/Awesome-Humanoid-Manipulation)", collecting recent papers on humanoid manipulation! Contributions are welcome!

## Overview

<p align="center"> <img src="images/banner.jpg" width="800" align="center"> </p>

> **TLDR:** A comprehensive collection of papers covering humanoid robot manipulation

## Tags Explanation

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
  - [Loco-Manipulation](#dexterous-manipulation)
  - [Non-Loco-Manipulation](#loco-manipulation)
  - [Dexterous hand](#vision-language-action-vla)
  - [Datasets & Benchmark](#datasets--benchmarks)

---

## Dexterous Manipulation

- **[1] DexMV: Imitation Learning for Dexterous Manipulation from Human Videos**, ECCV 2022.

  *Qin, Yuzhe and Wu, Yueh-Hua and Liu, Shaowei and Jiang, Hanwen and Yang, Ruihan and Fu, Yang and Wang, Xiaolong.*

  [[Paper](https://arxiv.org/abs/2108.05877)] [[Code](https://github.com/yzqin/dexmv-sim)] ![](https://img.shields.io/badge/DexMV-blue) ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Dexterous--Manipulation-purple) ![](https://img.shields.io/badge/Open--Sourced-red)

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

  [[Paper](https://arxiv.org/abs/2211.15036)] [[Code](https://github.com/yzqin/dexpoint-release)] ![](https://img.shields.io/badge/DexPoint-blue) ![](https://img.shields.io/badge/RL-blue) ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Dexterous--Manipulation-purple) ![](https://img.shields.io/badge/Sim--to--Real-orange) ![](https://img.shields.io/badge/Open--Sourced-red)

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

---

## Bimanual Manipulation

- **[1] Bi-DexHands: Towards Human-Level Bimanual Dexterous Manipulation**, TPAMI 2024.

  *Chen, Yuanpei and Wang, Yaodong and others.*

  [[Paper](https://arxiv.org/abs/2206.08686)] [[Code](https://github.com/PKU-MARL/DexterousHands)] ![](https://img.shields.io/badge/Bi--DexHands-blue) ![](https://img.shields.io/badge/RL-blue) ![](https://img.shields.io/badge/Bimanual-purple) ![](https://img.shields.io/badge/Dexterous--Manipulation-purple) ![](https://img.shields.io/badge/Open--Sourced-red)

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

## Loco-Manipulation

- **[1] HumanPlus: Humanoid Shadowing and Imitation from Humans**, arXiv 2024.

  *Fu, Zipeng and Zhao, Qingqing and Wu, Qi and Wetzstein, Gordon and Finn, Chelsea.*

  [[Paper](https://arxiv.org/abs/2406.10454)] [[Project](https://humanoid-ai.github.io/)] ![](https://img.shields.io/badge/HumanPlus-blue) ![](https://img.shields.io/badge/IL-blue) ![](https://img.shields.io/badge/Visual--Input-green) ![](https://img.shields.io/badge/Loco--Manipulation-purple) ![](https://img.shields.io/badge/Real--World-orange) ![](https://img.shields.io/badge/Open--Sourced-red)

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

---

## Vision-Language-Action (VLA)

- **[1] OpenVLA: An Open-Source Vision-Language-Action Model**, arXiv 2024.

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

---

## Force-Adaptive Control

- **[1] Learning Compliant Manipulation through Tactile Feedback**, ICRA 2023.

  *Author names.*

  [[Paper](https://example.com)] ![](https://img.shields.io/badge/Force--Adaptive-orange) ![](https://img.shields.io/badge/Tactile-green) ![](https://img.shields.io/badge/Dexterous--Manipulation-purple)

  <details> <summary>BibTex</summary>

  ```bibtex
  @inproceedings{example2023,
    title={Learning Compliant Manipulation through Tactile Feedback},
    author={Author names},
    booktitle={ICRA},
    year={2023}
  }
  ```

  </details>

---

## Sim-to-Real Transfer

- **[1] Sim-to-Real Transfer for Dexterous Manipulation**, RSS 2023.

  *Author names.*

  [[Paper](https://example.com)] ![](https://img.shields.io/badge/Sim--to--Real-orange) ![](https://img.shields.io/badge/RL-blue) ![](https://img.shields.io/badge/Dexterous--Manipulation-purple)

  <details> <summary>BibTex</summary>

  ```bibtex
  @inproceedings{example2023simtoreal,
    title={Sim-to-Real Transfer for Dexterous Manipulation},
    author={Author names},
    booktitle={RSS},
    year={2023}
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

---

## Citation

If you find this repository helpful, please consider citing:

```bibtex
@misc{awesome-humanoid-manipulation,
  author = {Your Name},
  title = {Awesome Humanoid Manipulation},
  year = {2025},
  publisher = {GitHub},
  howpublished = {\url{https://github.com/YOUR_USERNAME/Awesome-Humanoid-Manipulation}}
}
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Star History

<!-- [![Star History Chart](https://api.star-history.com/svg?repos=YOUR_USERNAME/Awesome-Humanoid-Manipulation&type=Timeline)](https://www.star-history.com/#YOUR_USERNAME/Awesome-Humanoid-Manipulation&Timeline) -->
