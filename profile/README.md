# 프로젝트 개요
## 기체 - 지상국 설계

edge에서 영상처리가 이루어지지 않을경우 edge는 raspberry pi로 선정될 가능성이 있음.
> wifi의 사용 가능성 (핫스팟 모듈 장착예정)  
> 하드웨어적인 메모리 충분  
> ![testcase](https://github.com/ikw-drone-project/.github/assets/71598954/1069866e-962a-48ac-8d45-3bb54fb5a9bd)

MAVLINK(Micro Air Vehicle Link)를 통하여 받아온 정보와 영상정보에 기반하여 적 위치를 특정.
![image](https://github.com/ikw-drone-project/.github/assets/71598954/756c8d8e-974f-4467-8f15-fae29f523c9d)
## 목적
### 비행중인 무인비행체가 적 장갑차, 사람을 탐지하는 경우 GCS상에 상세 좌표를 표기.
## 한계점 및 제약사항
### 비행기의 고도를 지형(Terrial)과의 거리에 기반한 
