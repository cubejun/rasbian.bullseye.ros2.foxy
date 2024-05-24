# rasbian.bullseye.ros2.foxy

# 불스아이에 도커 설치
https://ban2aru.tistory.com/70

# 도커 컨테이너에 ros2 foxy 버전 설치
https://ban2aru.tistory.com/71

# gui와 네트워크 접속을 위한 컨테이너 생성 명령어 
docker pull arm64v8/ros:foxy
docker run --name ros2_net --network=host -it -v /tmp/.X11-unix:/tmp/.X11-unix -e DISPLAY=$DISPLAY arm64v8/ros:foxy /bin/bash

https://ban2aru.tistory.com/72
gui 활용 참고

https://mvje.tistory.com/171
도커 컨테이너와 code 연결


# 터틀심 노드 gui 동작 영상
https://github.com/cubejun/rasbian.bullseye.ros2.foxy/assets/133946040/817d894f-6544-4e77-97c3-c5dd698bb0b1



# 젯슨나노와의 통신
https://github.com/cubejun/rasbian.bullseye.ros2.foxy/assets/133946040/d0e8db63-38aa-41ca-b6ec-bcad6ce0ab01

