---
layout: splash
title: "3D Diffusion Policy"
permalink: /

excerpt: "Generalizable visuomotor policy learning via simple 3D representations."

header:
  overlay_color: "#000000"
  overlay_filter: "0.45"
  overlay_image: /assets/images/hero_dp3.jpg   # 맨 위 큰 배경 이미지

  actions:
    - label: "arXiv"
      url: "https://arxiv.org/abs/XXXX.XXXXX"
    - label: "Paper"
      url: "https://your-conf-paper-link"
    - label: "Code"
      url: "https://github.com/YOUR_ID/YOUR_REPO"
    - label: "Simulation Data"
      url: "https://your-sim-data-link"
    - label: "Real Robot Data"
      url: "https://your-real-data-link"

team:
  - image_path: /assets/images/team/member1.jpg
    alt: "Author 1"
    title: "Author 1<sup>1</sup>"
    excerpt: "Affiliation 1"
  - image_path: /assets/images/team/member2.jpg
    alt: "Author 2"
    title: "Author 2<sup>1</sup>"
    excerpt: "Affiliation 1"
  - image_path: /assets/images/team/member3.jpg
    alt: "Author 3"
    title: "Author 3<sup>2</sup>"
    excerpt: "Affiliation 2"
  # ... 필요한 만큼 추가
---

## Abstract

여기에 논문 abstract 요약 적기.  
(그대로 복붙 or 두세 문장으로 줄인 버전)

---

## Method

우리 방법론 짧게 설명:

- **Representation.** 3D representation (voxel / point cloud / SDF 등) 한 줄 설명  
- **Policy.** Diffusion policy 구조, conditioning, 입력/출력  
- **Training.** imitation learning 세팅, loss, dataset 등 키워드만

<p align="center">
  <img src="/assets/images/method_overview.png" width="80%" alt="Method overview">
</p>

---

## Benchmarks

### RoboMimic

| Task      | Baseline A | Baseline B | **Ours** |
|-----------|:----------:|:----------:|:--------:|
| Lift      | 0.xx       | 0.xx       | **0.xx** |
| Can       | 0.xx       | 0.xx       | **0.xx** |
| Square    | 0.xx       | 0.xx       | **0.xx** |
| Tool Hang | 0.xx       | 0.xx       | **0.xx** |

### Franka Kitchen

| Metric/Task        | Baseline | Diffusion Policy | **Ours** |
|--------------------|:--------:|:----------------:|:--------:|
| 4 tasks completed  | 0.xx     | 0.xx             | **0.xx** |
| 2+ tasks completed | 0.xx     | 0.xx             | **0.xx** |

(나중에 실제 숫자로 교체)

---

## Publication

<span class="label label--primary">Robotics: Science and Systems (RSS) 2024</span>

Accepted as a full paper.

- 📄 [Camera-ready PDF](https://your-camera-ready-link)  
- 📺 [Talk Video](https://youtube.com/your-talk-link)

---

## Team

{% include feature_row id="team" %}

<div style="margin-top:0.5rem">
  1 Affiliation 1 &nbsp;&nbsp;
  2 Affiliation 2
</div>

---

## Real-world Robot Results

<div class="video-grid">
  <div class="video-item">
    <video src="/assets/videos/real_world_1.mp4" controls muted loop></video>
    <p class="video-caption">Task 1</p>
  </div>
  <div class="video-item">
    <video src="/assets/videos/real_world_2.mp4" controls muted loop></video>
    <p class="video-caption">Task 2</p>
  </div>
  <div class="video-item">
    <video src="/assets/videos/real_world_3.mp4" controls muted loop></video>
    <p class="video-caption">Task 3</p>
  </div>
</div>
