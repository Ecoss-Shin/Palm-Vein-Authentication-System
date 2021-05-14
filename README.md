# 적외선 정맥 인증 시스템

### 1. 이미지 얻기

정맥 속의 헤모글로빈은 적외선을 흡수한다.

그래서 적외선 LED와 적외선 카메라로 촬영한다면 정맥 이미지를 얻을 수 있다.

매번 일관된 이미지를 얻을 수 있는 설정 ( 제어해야 할 변수 )

- 조명 ( 적외선 LED가 방해받지 않도록 해야함 )
- 카메라 위 손바닥 or 손등 높이 ( 코드로 수정 가능 )
- 영상에서 손바닥의 위치/방향 ( 코드로 수정 가능 )

상자를 사용하여 적외선 LED가 방해받지 않도록 하고 ELP-USB0230X2-KV90( 적외선 LED와 적외선 카메라 )를 사용하여 기본적인 하드웨어를 구성했다.

![image03](https://user-images.githubusercontent.com/73572179/117946330-2c78d400-b34a-11eb-8b02-75752e9388ad.jpg)

### 2. 이미지 처리

이미지 처리는 아래 그림의 순서를 따른다.

![dccc](https://user-images.githubusercontent.com/73572179/117950134-d6a62b00-b34d-11eb-8c70-42695ac6c6fa.JPG)

### 3. 인증 with TensorFlow

train을 위해 데이터가 필요하며 2명의 각 왼손, 오른손 사진을 5장 ~ 10장까지 train 시켰다.

![train_image](https://user-images.githubusercontent.com/73572179/117949151-c9d50780-b34c-11eb-9dd2-0fb920da46d4.JPG)

결과가 잘 나오는 것을 확인할 수 있다.

![asddsaf](https://user-images.githubusercontent.com/73572179/117949363-03a60e00-b34d-11eb-8ab4-be930519543b.JPG)
