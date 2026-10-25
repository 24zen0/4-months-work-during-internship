# Robot Learning Internship at Galbot

An April 2026 progress presentation from Yitao Zeng's research internship in Galbot's Embodied Intelligence Algorithm Department, January–June 2026.

[Progress presentation (PDF)](%E6%9B%BE%E4%BA%A6%E9%99%B6%E7%9A%84%E9%93%B6%E6%B2%B3%E6%B1%87%E6%8A%A54.25%20newest.pdf) · [Current research overview](https://24zen0.github.io/#galbot) · [StereoVLA](https://shengliangd.github.io/StereoVLA-Webpage/)

## Research work

My internship combined robot-learning data engineering, depth-aware baseline support, and real-robot system integration:

- Built a parallel TFDS-to-LeRobot conversion pipeline for SynGrasp-1B trajectories and checked converted data through robot deployment tests.
- Surveyed depth-aware policies for StereoVLA reviewer-response work and adapted a DP3 baseline using a Dockerized ROS–Franka stack, ZED sensing, and ZeroMQ communication. The deployment attempt exposed target-selection and sim-to-real difficulties.
- Supported robot-control and inference integration, including initial-pose testing, for a separate foundation-model experiment.
- Explored data-curation methods, including CUPID, for robot learning.

The StereoVLA contribution was dataset conversion and baseline support. The foundation-model tests were a separate internship activity.

## About this repository

This is a presentation repository. The PDF captures work in progress as of April 2026; the linked research website summarizes the full January–June internship. Training code and internship datasets are not distributed here.

The internship took place in the research group led by He Wang, Assistant Professor at Peking University.
