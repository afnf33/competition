# 프로그래머스 '2021 Dev-Matching: 머신러닝 개발자' 테스트 코드
진행: 5/23 10:00 ~ 동일 18:00

# Art Painting 이미지를 사용한 정확도 올리기 대회


## 학습
- 모델: tf_efficientnetv2_b0
- epoch: 30
- augmentation: CenterCrop, Normalize
- loss: crossentropyloss
- optimizer: Adam
- schedular: None
- batch_size: 8

## 결과 (단순 accuracy)
- Public LB: 92.857 (75/256)
- Private LB: 92.0 (79/256)
