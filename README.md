# Jeston_dli
<b> 구리고 진로 탐색 시간
<b> -김민겸

<b> Getting Started with AI on Jetson Nano

```
 1. Jetson Nano Setting 준비물
  
        - jetson nano 4gb


  
        - c type power adapter
  
        - 와이파이 동글
  
        - 웹캠(USB Camera), 또는 CSI Camera (라즈베리파이 V2)
  
        - 64기가 이상 마이크로sd카드
  
        - 그외 쿨링펜, lcd, 또는 모니터. hdmi
```
<b>  Jetson image
![image](https://github.com/user-attachments/assets/21b360a0-6fc1-4f4d-89df-462b2ca14ca7)
![dds](https://github.com/user-attachments/assets/8bd6e24f-b075-4008-834d-2dc7780ae573)

<b> 2. jetson nano에 대하여

 <b>    welcome 부터 따라하기

 <b>   https://learn.nvidia.com/courses/course?course_id=course-v1:DLI+S-RX-02+V2&unit=block-v1:DLI+S-RX-02+V2+type@vertical+block@aba5104413ae454c8c63a6f301925337

<b> 3. jetpack downloads 

<b>      https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit#write

<b> 4. 이미지  굽기 위해 필요한 것들.

       4-1. sd card formatter ---> download
       4-2. balenaetcher download --->  이미지 굽기
       4-3. 제슨나노에 sd넣고 우분투 설치

  #####     
     
<b> 5. 쿨링팬 설치
``` bash
sudo sh -c 'echo 128 > /sys/devices/pwm-fan/target_pwm'
```
<b>  6. usb-camera  얼굴의 코 눈 인식하는 것도 해봄, 이미지 캡쳐와 영상 녹화 cctv기능 구현 j는 이미지 캡쳐, 1은 영상 녹화 시작 0은 영상녹화 스톱
```       
       

