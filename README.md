# 2023년 1학기 인공지능 딥러닝 프로젝트

딥러닝과 CNN에 관해 학습하며 진행한 프로젝트입니다.

<br>
<br>
<br>

## 1. CNN_하이퍼파라미터_비교

CNN을 익히기 위해 CNN 모델의 여러 하이퍼파라미터들을 바꾸어가며 정확도를 비교했습니다.

<img width="815" alt="image" src="https://github.com/user-attachments/assets/dfe9b5a4-59f2-4f30-8e21-b58372606d1d">
<img width="815" alt="image" src="https://github.com/user-attachments/assets/636aa106-d551-4a0b-9a09-238c93047d36">

<br>
<br>
<br>

## 2. main_model

CNN_하이퍼파라미터_비교에서 가장 성능이 좋았던 3번째 모델에 대한 분석입니다.

![image](https://github.com/user-attachments/assets/0d842f8a-a0bd-4288-b3b7-f86ff868c049)


<br>
<br>
<br>

## 3. Kmeans_Loss

기존 모델(main_model) 학습 이후 Kmeans를 활용하여 정확도를 높인 버전입니다. (크로스엔트로피 + Kmeans을 활용한 Loss 함수)

히트맵을 출력하여 모델이 입력 이미지에서 어떤 부분을 중점적으로 고려했는지 확인합니다.
![image](https://github.com/user-attachments/assets/026fbd90-0c5d-4eba-88b4-ad9f6732be80)

<br>
<br>

t-SNE로 고차원 공간에서 데이터가 놓인 manifold를 찾아내어, 그 구조를 잘 유지한 채로 저차원 공간으로 "평평하게" 핀 모습을 시각적으로 확인합니다.
![image](https://github.com/user-attachments/assets/6a0ce4d9-53cf-4c94-8eb3-747136eb88be)
![image](https://github.com/user-attachments/assets/fdec8083-79a6-43ce-ac22-3c6f2157f2b6)

<br>
<br>
<br>
<br>
<br>
<br>

## 결론

인공지능, 머신러닝, 딥러닝 등을 학습하고, 특히 CNN을 깊게 학습함으로써 향후 주가 예측 프로젝트 수행 역량의 기반이 되었습니다.
