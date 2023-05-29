# deep-learning-project
2023년 1학기 인공지능 딥러닝 프로젝트

폴더 3개 설명

## CNN_하이퍼파라미터_비교

1은 기본 구조
2는 1에다가 구조 쌓을때 사이사이에 배치정규화라는 과적합 막는거 끼워넣은것
3은 2에다가 학습률 뒤로갈수록 줄인것
4는 3에다가 훈련이미지 15도 이내로 회전하거나 좌우 뒤집은거 추가한것
5랑 6은 3에다가 최적화 함수만 바꿔본것. 원래 Adam인데 다른걸로 한것

## main_model

main model은 CNN_하이퍼파라미터_비교중 3번째모델

Heatmap이랑 Tsne로 Intermediate feature space 시각화한 코드 - GPT돌리면서 오류잡기 바빠 코드 이해는 거의 되지않은상태

## Kmeans_Center_Loss

main model 구조에 Loss함수만 크로스엔트로피 방식에서 Center Loss 방식을 사용한것.

나머지 시각화는 main_model이랑 비슷
