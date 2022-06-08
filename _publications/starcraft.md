---
title: "Leveraging Transformers for StarCraft Macromanagement Prediction"
collection: publications
permalink: /publication/HPESurvey
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
date: 2020-12-24
paperurl: "https://ieeexplore.ieee.org/abstract/document/9680028"
citation: 'Muhammad Junaid Khan, <b>Shah Hassan</b>, Gita Sukthankar.  "Leveraging Transformers for StarCraft Macromanagement Prediction".<i>(ICMLA 2021)</i>. '
---
# Leveraging Transformers for StarCraft Macromanagement Prediction

[<a href="https://ieeexplore.ieee.org/abstract/document/9680028">Paper</a>]



## Abstract
Inspired by the recent success of transformers in natural language processing and computer vision applications, we introduce a transformer-based neural architecture for two key StarCraft II (SC2) macromanagement tasks: global state and build order prediction. Unlike recurrent neural networks which suffer from a recency bias, transformers are able to capture patterns across very long time horizons, making them well suited for full game analysis. Our model utilizes the MSC (Macromanagement in StarCraft II) dataset and improves on the top performing gated recurrent unit (GRU) architecture in predicting global state and build order as measured by mean accuracy over multiple time horizons. We present ablation studies on our proposed architecture that support our design decisions.One key advantage of transformers is their ability to generalize well, and we demonstrate that our model achieves an even better accuracy when used in a transfer learning setting in which models trained on games with one racial matchup (e.g., Terran vs. Protoss) are transferred to a different one. We believe that transformers’ ability to model long games, potential for parallelization, and generalization performance make them an excellent choice for StarCraft agents.
<!--
## Citation
      @misc{zheng2020deep,
       title={Deep Learning-Based Human Pose Estimation: A Survey}, 
       author={Ce Zheng and Wenhan Wu and Taojiannan Yang and Sijie Zhu and Chen Chen and Ruixu Liu and Ju Shen and Nasser Kehtarnavaz and Mubarak Shah},
       year={2020},
       eprint={2012.13392},
       archivePrefix={arXiv},
       primaryClass={cs.CV}
      }
-->
