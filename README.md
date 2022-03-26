# 2022_1st_StepUpChallenge
1차 AI 실무교육과정 Award  
Project: Mirror Picker
***
### Introduce
Real-Time 카메라와 Input과 마음에 드는 포즈의 사진을 Input으로
두 포즈가 비슷해졌을때 사진을 찍어주는 프로그램

### Description
Google의 딥러닝 프레임워크 Mediapipe를 이용하여 구현  
본래 계획은 Pycharm 환경에서의 구현까지였으나, 주제에 맞춰 앱 제작까지 시도

### Principle


### Run Code
![Minimize_Runcode](https://user-images.githubusercontent.com/62230550/160237244-3c7f3aa0-02ff-4dbc-a5ca-882cb2a874d2.gif)

아래 화면에는 Pose Similarity가 실시간으로 출력되고 있습니다.  
처음 원하는 Target사진 (Faker선수)의 포즈와 반대되는 포즈를 취했을때와,  
비슷한 포즈를 취했을때의 Pose Similarity를 확인해 보았을때 높은 결과값을 확인할 수 있습니다.

### 한계
해당 프로젝트에서는 노트북 웹캠의 성능 문제로 깊이(z)값을 제외한 단순 x, y값만을 사용하여 진행하였습니다.
