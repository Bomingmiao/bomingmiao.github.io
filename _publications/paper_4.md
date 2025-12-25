---
title: "Towards Annotation-Free Evaluation: KPAScore for Human Keypoint Detection"
collection: publications
category: conferences
permalink: /publication/paper_4
date: 2025-10-19
venue: 'ICCV'
paperurl: 'https://openaccess.thecvf.com/content/ICCV2025/papers/Wang_Towards_Annotation-Free_Evaluation_KPAScore_for_Human_Keypoint_Detection_ICCV_2025_paper.pdf'
authors: 'Xiaoxiao Wang, Chunxiao Li, Peng Sun, Boming Miao, Yunjian Zhang, Yao Zhu'
---
Human keypoint detection is fundamental in computer vision, with applications in pose estimation and action recognition. However, existing evaluation metrics (eg, OKS, PCP, PDJ) rely on human-annotated ground truth, a labor-intensive process that increases costs, limits scalability. To address this, we propose KPAScore (KeyPoint-Answering Score), an annotation-free metric independent of ground truth. It evaluates keypoint detection using a two-stage VLM-based question-answering process: first, the VLM identifies the presence of keypoints within the image, and second, visual prompts are introduced to query the likelihood of each keypoint being accurately localized within a predefined boundary. To validate the rationale behind KPAScore, we propose KPUBench (KeyPoint Understanding Benchmark), which comprehensively evaluates the VLM's ability to determine keypoint presence and localization. Extensive experiments demonstrate KPAScore's effectiveness from three perspectives: consistency to keypoint variation, correlation with traditional metrics, alignment with human perception. We hope KPAScore will reduce reliance on manual annotations, facilitating broader adoption of keypoint detection in real-world applications.