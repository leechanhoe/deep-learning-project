# deep-learning-project
2023년 1학기 인공지능 딥러닝 프로젝트

3개의 폴더에 대한 설명입니다.

## CNN_하이퍼파라미터_비교

CNN 모델의 여러 하이퍼파라미터들을 바꾸어가며 정확도를 비교했습니다.

## main_model

main model은 CNN_하이퍼파라미터_비교중 3번째모델입니다.

Intermediate feature space 및 CAM (class activation map) 가시화 코드가 있습니다.

## Kmeans_Loss

main model 구조에 Loss함수만 변경했습니다. (크로스엔트로피 + Kmeans을 활용한 Loss 함수)

Kmeans_Loss를 사용한 모델에 대한 Intermediate feature space 및 CAM (class activation map) 가시화 코드가 있습니다.