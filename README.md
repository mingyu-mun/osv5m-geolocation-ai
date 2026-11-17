# GeoGuessr AI: Image-Based Geolocation

## Project Overview

GeoGuessr AI는 **이미지 한 장을 분석하여 해당 이미지가 촬영된 지리적 위치를 예측하는 AI 프로젝트**이다.

사람이 거리 사진 속 건축물, 도로, 표지판, 식생, 지형 등의 특징을 통해 촬영 장소를 추측하는 것처럼, 딥러닝 모델이 이미지의 시각적 정보를 학습하여 국가 및 지리적 위치를 추정하는 것을 목표로 한다.

Google Street View 기반 위치 추측 게임인 GeoGuessr에서 아이디어를 얻었으며, 대규모 거리 이미지 데이터셋을 활용해 Visual Geolocation 모델을 개발하는 프로젝트이다.

## Dataset

### OpenStreetView-5M (OSV-5M)

전 세계 225개 국가 및 지역에서 수집된 약 510만 장의 거리 이미지와 지리적 위치 정보를 포함하는 대규모 Visual Geolocation 데이터셋이다.

- **Dataset:** OpenStreetView-5M
- **Scale:** 약 510만 장의 이미지
- **Data:** Street-view Images, GPS Coordinates, Geographic Metadata
- **Task:** Image-Based Geolocation
- **Publication:** CVPR 2024

### Links

- [Dataset — Hugging Face](https://huggingface.co/datasets/osv5m/osv5m)
- [Official GitHub Repository](https://github.com/gastruc/osv5m)
- [Project Website](https://osv5m.github.io/)
- [Research Paper — arXiv](https://arxiv.org/abs/2404.18873)

## Tech Stack

- Python
- PyTorch
- Computer Vision
- Deep Learning
