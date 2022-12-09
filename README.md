# Shoeting-AI

### 📌간단 설명
DeepFashion2 dataset을 Yolov5형식에 맞게 변형하여 
Yolov5를 train시키는 python 코드입니다.

### 📌실행 방법
해당 .ipynb 파일을 다운 받아서 구글드라이브에 업로드하여 구글코랩으로 실행시킬 수 있습니다.

이때 아직 train된 weight를 자동으로 불러오도록 연결하지 못하였으므로
해당 코드를 실행시키면 다시 train되어 결과가 나옵니다. (약 3시간 소요)
따라서 간단한 결과를 보고 싶으시면 아래 이미지 부분에서 100을 20정도로 낮추어 실행해보면
100epoch실행하는 것보다 성능은 떨어지겠지만 빠른 시간내에 결과를 확인해보실 수 있습니다.
![image](https://user-images.githubusercontent.com/90602936/206715274-535a7b3e-3e14-4fd1-9b03-4a40166cc475.png)

### 📌설명
사용자의 전신 사진으로 옷 스타일을 분석해 어울리는 신발을 추천해주는 AI아키텍처를 구현하는 것이 목표입니다.
이에 대한 기술검증을 위해 Yolov5를 DeepFashion2 데이터셋으로 학습시켜서 전신사진에서 옷을 object detection해보았습니다.

![image](https://user-images.githubusercontent.com/90602936/206716158-84c1b46c-ae43-46cb-8c1c-5d4d75eebd71.png)
![image](https://user-images.githubusercontent.com/90602936/206716197-aa7acba6-719f-419e-b454-51e55de272d1.png)
![image](https://user-images.githubusercontent.com/90602936/206716247-e915d015-9c1c-4ea6-9423-943775db1c01.png)
![image](https://user-images.githubusercontent.com/90602936/206716619-3a25b315-e2c3-40dd-8c56-4f01eb4338aa.png)
![image](https://user-images.githubusercontent.com/90602936/206716636-63335e96-891d-4253-b7f2-231173e2c1d6.png)
![image](https://user-images.githubusercontent.com/90602936/206716704-2f20e89b-fa55-4fcb-8ed6-2d136a4b0efa.png)
![image](https://user-images.githubusercontent.com/90602936/206716759-7ffdca8b-7bc4-4004-b018-6403da80efd1.png)
![image](https://user-images.githubusercontent.com/90602936/206716823-63afea38-18f1-4ad9-9d33-cf30c9ad934b.png)



