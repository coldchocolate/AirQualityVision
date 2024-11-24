미세먼지 농도 예측 모델

이미지를 활용하여 미세먼지(PM2.5) 농도를 예측하는 딥러닝 모델입니다. ViT(Vision Transformer), CNN(Convolutional Neural Network), ResNet을 사용하여 예측 성능을 비교하였습니다.

소개

프로젝트 목적: 이미지 데이터를 기반으로 대기 중 미세먼지 농도를 정확하게 예측하여 환경 모니터링과 공기 질 개선에 기여하고자 합니다.
사용한 모델:
ViT: Transformer 아키텍처를 이미지 처리에 적용하여 성능을 평가.
CNN: 전통적인 합성곱 신경망으로 특징 추출 및 예측.
ResNet: Residual 구조를 도입하여 딥러닝 모델의 학습 효율 향상.
데이터셋

데이터 출처: [데이터셋 링크 또는 설명]
데이터 구성:
이미지: 다양한 환경에서 촬영된 대기 이미지.
라벨: 해당 이미지 촬영 시점의 실제 미세먼지 농도 수치.
전처리 과정:
이미지 크기 조정 및 정규화.
데이터 증강(augmentation) 기법 적용.
