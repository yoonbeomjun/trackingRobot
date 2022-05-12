# Tracking Robot
***
## 피드백
* 문제점   
  젯슨나노와 라즈베리파이로 ROS통신을 하면 서로 인터넷에 연결해야하는 상황이 발생됨.

* 피드백 후 해결 방안
  인터넷 필요없이 제어 가능한 아두이노로 ROS-Serial통신으로 대체함.
***

## 1. 진행사항
* 영상처리   
  HaarCascade를 활용하여 얼굴 영역 검출 완료.   
     
  <img src="./img/얼굴영역검출.png" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="Face Detection"></img>
   
* ROS 통신   
젯슨 나노와 아두이노를 이용하여 ROS 시리얼 통신함. 현재 신호를 주고 받기를 완료함.   
   
  <img src="./img/ros통신 활용.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="ROS"></img>
  
* 기타   
  이번주 신청했던 제품들을 수령 완료함.


## 2. 블록도

<img src="./img/블록도.png" width="80%" height="60%" title="px(픽셀) 크기 설정" alt="ROS"></img>


## 3. 남은 과정들

* 영상처리   
  Face Tracking 기술을 활용하여 얼굴 추적.
   
* ROS 통신   
  젯슨 나노와 아두이노 사이에서 원하는 데이터들을 주고 받을 수 있게 해야함.

* 제어   
  주고 받는 데이터들을 활용하여 모터나 센서등 제어기기를 알맞게 조절해야함.
