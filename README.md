# Awesome Legged Loco-Manipulation

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/Czy213hd/awesome-legged-loco-manipulation?style=social)](https://github.com/Czy213hd/awesome-legged-loco-manipulation/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Czy213hd/awesome-legged-loco-manipulation?style=social)](https://github.com/Czy213hd/awesome-legged-loco-manipulation/network/members)
[![GitHub last commit](https://img.shields.io/github/last-commit/Czy213hd/awesome-legged-loco-manipulation)](https://github.com/Czy213hd/awesome-legged-loco-manipulation/commits/main)
[![License](https://img.shields.io/github/license/Czy213hd/awesome-legged-loco-manipulation)](LICENSE)

A curated list of papers, projects, datasets, simulators, and open-source resources for reinforcement learning, whole-body control, and legged loco-manipulation.

## About

Legged loco-manipulation studies how legged robots perform locomotion and manipulation simultaneously.

Unlike fixed-base robot arms, legged manipulators must coordinate:

- Dynamic balance
- Foot-ground contacts
- Base motion
- End-effector tracking
- Whole-body posture
- Collision avoidance
- Perception and decision-making
- Sim-to-real transfer

This repository focuses on learning-based methods for legged loco-manipulation, including:

- Reinforcement learning
- Imitation learning
- Whole-body control
- Diffusion policies
- Motion imitation
- Vision-based manipulation
- Teleoperation and demonstration collection
- Sim-to-real and sim-to-sim transfer
- Quadruped, bipedal, and humanoid robots

## Contents

- [Papers and Projects](#papers-and-projects)
- [How to Add an Entry](#how-to-add-an-entry)
- [Contributing](#contributing)
- [Citation](#citation)
- [Acknowledgements](#acknowledgements)
- [License](#license)
## Papers and Projects

Entries are grouped by robot embodiment and sorted by publication year, with the newest work listed first.

---

### Quadruped Robots with Manipulator Arms

Research on quadruped robots equipped with one or more dedicated manipulator arms for mobile manipulation and whole-body loco-manipulation.

| Year | Title | Authors / Organization | Venue | Robot | Resources |
| :--: | --- | --- | :---: | --- | --- |
| 2025 | **WildLMa: Long-Horizon Loco-Manipulation in the Wild** | Ri-Zhao Qiu et al. | ICRA | Unitree B1 + Z1 Arm | [Paper](https://arxiv.org/abs/2411.15131) · [Project](https://wildlma.github.io/) · [Video](https://youtu.be/pNBMiHYn5tg) |
| 2025 | **QuadWBG: Generalizable Quadrupedal Whole-Body Grasping** | Jilong Wang et al. | ICRA | Unitree B1 + Z1 Arm | [Paper](https://arxiv.org/abs/2411.06782) · [Project](https://quadwbg.github.io/) · [Video](https://www.youtube.com/playlist?list=PLHt_fpvZmCueMLXLwx16qaJgBXRNfMSMa) |
| 2025 | **RoboDuet: Learning a Cooperative Policy for Whole-Body Legged Loco-Manipulation** | Guoping Pan et al. | RA-L | Unitree Go1 / Go2 / A1 + ARX5 | [Paper](https://arxiv.org/abs/2403.17367) · [Project](https://locomanip-duet.github.io/) · [Code](https://github.com/locomanip-duet/RoboDuet) |
| 2024 | **UMI on Legs: Making Manipulation Policies Mobile with Manipulation-Centric Whole-Body Controllers** | Huy Ha et al. | CoRL | Unitree Go2 + ARX5 | [Paper](https://arxiv.org/abs/2407.10353) · [Project](https://umi-on-legs.github.io/) · [Code](https://github.com/real-stanford/umi-on-legs) · [Video](https://youtu.be/4Bp0q3xHTxE) |
| 2024 | **Visual Whole-Body Control for Legged Loco-Manipulation** | Minghuan Liu et al. | CoRL | Unitree B1 + Z1 Arm | [Paper](https://arxiv.org/abs/2403.16967) · [Project](https://wholebody-b1.github.io/) · [Code](https://github.com/Ericonaldo/visual_wholebody) · [Video](https://youtu.be/Kfj1ImFLoqI) |
| 2024 | **LocoMan: Advancing Versatile Quadrupedal Dexterity with Lightweight Loco-Manipulators** | Changyi Lin et al. | IROS | Unitree Go1 + Dual Loco-Manipulators | [Paper](https://arxiv.org/abs/2403.18197) · [Project](https://linchangyi1.github.io/LocoMan/) · [Code](https://github.com/linchangyi1/LocoMan) · [Video](https://www.youtube.com/watch?v=d-GLiRPiHIE) |
| 2023 | **RoLoMa: Robust Loco-Manipulation for Quadruped Robots with Arms** | Henrique Ferrolho et al. | Autonomous Robots | ANYmal B + Kinova Arm | [Paper](https://arxiv.org/abs/2203.01446) · [Project](https://ferrolho.github.io/publications/ferrolho2023roloma/) · [Video](https://youtu.be/3qXNHVCagL8) |
| 2022 | **Deep Whole-Body Control: Learning a Unified Policy for Manipulation and Locomotion** | Zipeng Fu et al. | CoRL | Unitree Go1 + WidowX 250s | [Paper](https://arxiv.org/abs/2210.10044) · [Project](https://manipulation-locomotion.github.io/) · [Code](https://github.com/MarkFzp/Deep-Whole-Body-Control) · [Video](https://www.youtube.com/watch?v=4-2j3L86ZL4) |
| 2022 | **Combining Learning-Based Locomotion Policy with Model-Based Manipulation for Legged Mobile Manipulators** | Yuntao Ma et al. | RA-L | ANYmal + DynaArm | [Paper](https://arxiv.org/abs/2201.03871) · [Video](https://youtu.be/OZ9Adh0PYbw) |
| 2021 | **A Unified MPC Framework for Whole-Body Dynamic Locomotion and Manipulation** | Jean-Pierre Sleiman et al. | RA-L / ICRA | ALMA Quadruped Manipulator | [Paper](https://arxiv.org/abs/2103.00946) · [Video](https://www.youtube.com/watch?v=uT4ypNDzUvI) |

---

### Bipedal Robots with Mounted Manipulators

Research on non-humanoid bipedal robots equipped with externally mounted robotic manipulators.

| Year | Title | Authors / Organization | Venue | Robot | Resources |
| :--: | --- | --- | :---: | --- | --- |
| 2026 | **Learning Holistic Whole-Body Loco-Manipulation with a Bipedal Mobile Manipulator** | Zhongyu Chen et al. | arXiv | LimX TRON 1 + ARX L5 Arm | [Paper](https://arxiv.org/abs/2609.18930) |

---

### Humanoid Loco-Manipulation

Research on humanoid robots performing coordinated locomotion, manipulation, and whole-body interaction tasks.

| Year | Title | Authors / Organization | Venue | Robot | Resources |
| :--: | --- | --- | :---: | --- | --- |
| — | *No entries yet.* | — | — | — | — |

---

### Wheel-Legged and Hybrid Loco-Manipulation

Research on wheel-legged, wheeled-legged, transformable, and other hybrid mobile manipulators.

| Year | Title | Authors / Organization | Venue | Robot | Resources |
| :--: | --- | --- | :---: | --- | --- |
| — | *No entries yet.* | — | — | — | — |

---

### Arm-Less and Leg-as-Manipulator Loco-Manipulation

Research in which robots manipulate objects using their legs, feet, bodies, or multifunctional limbs without dedicated external manipulator arms.

| Year | Title | Authors / Organization | Venue | Robot | Resources |
| :--: | --- | --- | :---: | --- | --- |
| — | *No entries yet.* | — | — | — | — |

---

### Multi-Robot Cooperative Loco-Manipulation

Research on multiple legged or mobile robots cooperating to transport, grasp, push, pull, or manipulate objects.

| Year | Title | Authors / Organization | Venue | Robot | Resources |
| :--: | --- | --- | :---: | --- | --- |
| — | *No entries yet.* | — | — | — | — |

---

### Surveys, Benchmarks, and Datasets

Surveys, benchmarks, datasets, simulation environments, and general-purpose resources for legged loco-manipulation.

| Year | Title | Authors / Organization | Type | Resources |
| :--: | --- | --- | :---: | --- |
| — | *No entries yet.* | — | — | — |

---

## How to Add an Entry

Please place each entry under the most appropriate robot embodiment category and add new entries in reverse chronological order, with the newest work listed first.

Use the following format:

```markdown
| YEAR | **TITLE** | AUTHORS_OR_ORGANIZATION | VENUE | ROBOT | [Paper](PAPER_LINK) · [Project](PROJECT_LINK) · [Code](CODE_LINK) · [Video](VIDEO_LINK) |

## How to Add an Entry

Please add new entries in reverse chronological order, with the newest work listed first.

Use the following format:

```markdown
| YEAR | **TITLE** | AUTHORS_OR_ORGANIZATION | VENUE | ROBOT | [Paper](PAPER_LINK) · [Project](PROJECT_LINK) · [Code](CODE_LINK) · [Video](VIDEO_LINK) |
```

Only include resource links that are publicly available. Unavailable resources may be omitted.

For example:

```markdown
| 2025 | **Example Paper Title** | Author A et al. | ICRA | Unitree Go2 + Robot Arm | [Paper](PAPER_LINK) · [Project](PROJECT_LINK) · [Code](CODE_LINK) |
```

### Entry Description

A short description may be placed below the table when a paper requires additional explanation.

#### Paper or Project Title

- **Year:** 2026
- **Authors:** Author A, Author B, and Author C
- **Venue:** ICRA 2026
- **Robot:** Humanoid robot
- **Method:** Reinforcement learning and whole-body control
- **Task:** Mobile manipulation
- **Resources:** [Paper](PAPER_LINK) · [Project](PROJECT_LINK) · [Code](CODE_LINK) · [Video](VIDEO_LINK)

This work introduces a learning-based whole-body controller that enables a humanoid robot to coordinate locomotion and manipulation.

---

### Recommended Resource Links

Whenever possible, use official sources:

- Official project page
- arXiv paper
- Publisher paper page
- Official GitHub repository
- Official demonstration video
- Official dataset page

Avoid unofficial reposts when the original source is available.

### Venue Format

Use common abbreviations for conferences and journals:

- ICRA
- IROS
- RSS
- CoRL
- NeurIPS
- ICML
- RA-L
- T-RO
- IJRR
- Science Robotics
- SIGGRAPH
- arXiv

### Robot Format

Use a concise robot description, for example:

- Quadruped
- Quadruped + Arm
- Biped
- Biped + Arm
- Humanoid
- Humanoid + Dual Arms
- Wheeled-Legged Robot
- Multiple Embodiments

---

## Contributing

Contributions are welcome.

You can contribute papers, projects, datasets, simulators, robot platforms, tutorials, or other resources related to legged loco-manipulation.

### Contribution Workflow

1. Fork this repository.

2. Clone your fork:

```bash
git clone https://github.com/YOUR_USERNAME/awesome-legged-loco-manipulation.git
```

3. Enter the repository:

```bash
cd awesome-legged-loco-manipulation
```

4. Create a new branch:

```bash
git checkout -b add-new-resource
```

5. Edit `README.md` and add the resource.

6. Commit your changes:

```bash
git add README.md
git commit -m "Add paper: PAPER_TITLE"
```

7. Push the branch:

```bash
git push origin add-new-resource
```

8. Open a pull request.

### Contribution Guidelines

Please follow these guidelines:

- Add only resources related to legged locomotion, whole-body control, robot learning, or loco-manipulation.
- Use the official title of the paper or project.
- Use official paper, project, code, dataset, and video links whenever possible.
- Do not add duplicate entries.
- Sort entries by year, with the newest work first.
- Keep descriptions concise and objective.
- Do not use promotional or exaggerated language.
- Check that all links work before submitting.
- Clearly indicate whether the resource is a paper, project, dataset, simulator, or code repository.
- Keep the table format consistent.
- Use one pull request for one paper or one closely related group of resources.

### Pull Request Title

Recommended format:

```text
Add: Paper or Project Title
```

Example:

```text
Add: Learning Whole-Body Loco-Manipulation
```

### Commit Message

Recommended format:

```text
Add paper: Paper Title
```

Example:

```text
Add paper: Learning Whole-Body Loco-Manipulation
```

---

## Citation

If this repository is useful for your research, please consider citing it:

```bibtex
@misc{chen2026awesomeleggedlocomanipulation,
  author       = {Zhongyu Chen},
  title        = {Awesome Legged Loco-Manipulation},
  year         = {2026},
  howpublished = {\url{https://github.com/Czy213hd/awesome-legged-loco-manipulation}},
  note         = {A curated list of papers, projects, datasets, simulators, and open-source resources for legged loco-manipulation}
}
```

---

## Acknowledgements

Thanks to all researchers, engineers, and open-source contributors who have advanced legged locomotion, whole-body control, robot learning, and loco-manipulation.

The papers, code, videos, datasets, images, and project materials linked in this repository belong to their original authors and organizations.

This repository only collects and organizes publicly available resources for academic and educational purposes.

---

## Disclaimer

This repository is an independently maintained academic resource list.

The inclusion of a paper, project, dataset, organization, robot platform, or software framework does not imply endorsement.

If you are an author or copyright holder and would like an entry to be corrected or removed, please open an issue.

---

## License

This repository is released under the [MIT License](LICENSE).

External papers, code repositories, datasets, images, and project resources remain subject to their original licenses and copyright terms.

---
