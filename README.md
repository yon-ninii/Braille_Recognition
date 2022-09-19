# Braille_Recognition

2022.01 ~ 2022.06까지 진행한 '딥러닝 기반 전이학습을 이용한 점자인식' 프로젝트입니다.

---

## Introduction

1. 점자 데이터 셋을 직접 구성
	- 약 200장의 디지털 점자 데이터 셋
	- 520장의 실물 점자 데이터 셋
		- 거리와 점자의 개수, 위치 등 여러 변수 통제
2. CLAHE, Erosion, Dilation 등을 적용해 이미지 전처리를 진행
3. Pytorch에서 제공하는 모델인 Faster-RCNN-FPN-ResNet50 사용 (Pretrained = True)
4. mAP50가 약 94%가 나오며 전처리를 이용해 많은 성능 향상을 이뤄냄

---

## Paper

GEP-133 대한전자공학회 2022 하계종합학술대회, ‘딥러닝 기반 전이학습을 이용한 점자 인식’, pp.1060