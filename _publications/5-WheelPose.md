---
title: "WheelPose: Data Synthesis Techniques to Improve Pose Estimation Performance on Wheelchair Users"
collection: publications
permalink: /publication/WheelPose
excerpt: ''
date: 2024-05-11
venue: 'ACM CHI 2024'
paperurl: 'http://academicpages.github.io/files/WheelPose_final.pdf'
citation: '@inproceedings{10.1145/3613904.3642555,
		author = {Huang, William and Ghahremani, Sam and Pei, Siyou and Zhang, Yang},
		title = {WheelPose: Data Synthesis Techniques to Improve Pose Estimation Performance on Wheelchair Users},
		year = {2024},
		isbn = {9798400703300},
		publisher = {Association for Computing Machinery},
		address = {New York, NY, USA},
		url = {https://doi.org/10.1145/3613904.3642555},
		doi = {10.1145/3613904.3642555},
		booktitle = {Proceedings of the CHI Conference on Human Factors in Computing Systems},
		articleno = {944},
		numpages = {25},
		keywords = {Accessibility, Data Synthesis, Pose Estimation, Wheelchair Users},
		location = {, Honolulu, HI, USA, },
		series = {CHI '24}
}'
---

Existing pose estimation models perform poorly on wheelchair users due to a lack of representation in training data. We present a data synthesis pipeline to address this disparity in data collection and subsequently improve pose estimation performance for wheelchair users. Our configurable pipeline generates synthetic data of wheelchair users using motion capture data and motion generation outputs simulated in the Unity game engine. We validated our pipeline by conducting a human evaluation, investigating perceived realism, diversity, and an AI performance evaluation on a set of synthetic datasets from our pipeline that synthesized different backgrounds, models, and postures. We found our generated datasets were perceived as realistic by human evaluators, had more diversity than existing image datasets, and had improved person detection and pose estimation performance when fine-tuned on existing pose estimation models. Through this work, we hope to create a foothold for future efforts in tackling the inclusiveness of AI in a data-centric and human-centric manner with the data synthesis techniques demonstrated in this work. Finally, for future works to extend upon, we open source all code in this research and provide a fully configurable Unity Environment used to generate our datasets. In the case of any models we are unable to share due to redistribution and licensing policies, we provide detailed instructions on how to source and replace said models. 
