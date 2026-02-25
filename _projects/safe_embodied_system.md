---
layout: page
title: Safe and Robust Embodied Agent Systems
description: 
img: assets/img/project-placeholder.svg
importance: 1
category: Active Projects
related_publications: true
---
This research develops theoretically grounded and practically deployable methods for safe, robust, and verifiable embodied agent systems. We combine insights from formal verification and data-centric control approaches to scale systems' performance without sacrificing theoretical guarantees.

**Safe Reinforcement Learning.** Deploying AI systems in safety-critical applications like autonomous vehicles or medical robotics requires guarantees that they won't cause harm—yet traditional learning approaches lack formal safety assurances. We develop methods that enable AI agents to learn effectively while provably avoiding unsafe situations. Our work introduced barrier functions that mathematically certify safety during learning ([ICML 2023](https://arxiv.org/abs/2209.15090)), extended these guarantees to work with image inputs ([L4DC 2024](https://arxiv.org/abs/2311.02227)), and created frameworks that jointly optimize both performance and safety certificates ([ICCPS 2023](https://arxiv.org/abs/2201.12243), [RV 2024](https://link.springer.com/chapter/10.1007/978-3-031-74234-7_13)). These contributions establish new standards for trustworthy autonomous systems in robotics and cyber-physical applications.

**Delay-Aware Decision Making.** Real-world robots and autonomous systems face inevitable delays—cameras take time to process images, motors need time to respond, and wireless signals experience latency. These delays break standard AI assumptions and can cause dangerous failures. We developed novel approaches that explicitly account for delays during learning, including methods that reformulate the problem as probabilistic inference ([NeurIPS 2024 Spotlight](https://arxiv.org/pdf/2405.14226)), predict future states to compensate for delays ([ICML 2025](https://arxiv.org/pdf/2505.00546)), and leverage auxiliary tasks to accelerate learning in high-delay environments ([ICML 2024](https://arxiv.org/abs/2402.03141)). Our methods significantly improve performance in networked robots, cloud-based control systems, and remote operations where delays are unavoidable.

**Formal Evaluation for Embodied AI.** As AI systems become more complex, we need better ways to evaluate whether they're truly ready for deployment with proper safety consideration beyond just measuring task success. We develop comprehensive evaluation frameworks that assess physical consistency, interpretability, and alignment with human expectations. Our work ensures generated robot motions respect physical laws ([IROS 2024](https://arxiv.org/abs/2309.09317)), integrates common-sense reasoning to handle rare edge cases in autonomous driving ([ICLR 2024 Workshop](https://arxiv.org/pdf/2312.00812)), and establishes neural symbolic approaches to verify high-dimensional complex embodied agents behaviors in terms of safety([SENTINEL](https://nu-ideas-lab.github.io/SENTINEL/)). These tools enable more rigorous certification and broader acceptance of embodied AI systems.
