# 한국 음식 분류
## 2022년 1학기 빅데이터분석 과제
## 사용 데이터셋
한국 음식 데이터셋 : https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100
<br> 본 데이터셋은 한국지능정보사회진흥원의 사업결과 임.
<br> 반드시 위의 링크를 통해서만 데이터셋을 다운로드 받아야 함.

# 학습 결과

### ResNet50V2에서의 Accuracy가 가장 높게 측정됨.
### Test Accuracy

- test top-1 accuracy :  0.6485038995742798

- test top-2 accuracy :  0.7743449211120605

- test top-3 accuracy :  0.8329054713249207

- test top-4 accuracy :  0.8688916563987732

- test top-5 accuracy :  0.8920414447784424

## Model Train & Test
1. aihub ( https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100 ) 에서 데이터셋 다운로드 후 압축풀기
2. Image_Crop_Preprocessing_test.ipynb에서 이미지 경로 수정후 전처리
3. ResNet50V2_test_TopK-cropped_0609.ipynb 를 실행하여 학습 및 테스트
