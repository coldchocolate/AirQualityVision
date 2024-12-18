## 이미지 미세먼지 농도 예측 모델

고층에서 촬영된 이미지를 활용하여 미세먼지 농도를 예측하는 딥러닝 모델


- ### 사용한 모델:
ViT16: Transformer 아키텍처를 이미지 처리에 적용하여 성능을 평가

CNN: 전통적인 합성곱 신경망으로 특징 추출 및 예측

ResNet18: Residual 구조를 도입하여 딥러닝 모델의 학습 효율 향상


- ### 데이터셋
데이터 구성: 11:00~15:00에 고층에서 촬영된 사진

이미지: 다양한 각도에서 촬영된 대기 이미지

라벨: 해당 이미지 촬영 시점의 실제 미세먼지 농도 수치

전처리 과정: 이미지 크기 조정 및 정규화


- ### 결과 및 평가
모델 성능 비교:

| Model        | Epoch | Train MAE  | Validation MAE |
| ------------ | ----- | ---------- | -------------- |
| **ViT16**    | 70    | 0.091521   | 0.095729       |
| **CNN**      | 20    | 0.065709   | 0.149738       |
| **ResNet18** | 30    | 0.189832   | 0.173581       |

