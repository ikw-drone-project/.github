# 창작기체 프로젝트
## Developers
- [김창근 ( GCS 개발 )](https://github.com/sckdrms)
- 이동현 ( 기체 가공 및 조종 )[https://github.com/Amai001]
- 박진연 ( 기체 설계 및 가공 )
- 황동혁 ( 기체 가공 및 설계 )
- 김호진 ( 기체 가공 )
- [전현배 ( 기체통신 구현 및 통합 )](https://github.com/HarryKito)
- [김찬우 ( 객체인식 모델 설계 )](https://github.com/ASDFQWERCXZZ)
- [이태경 ( 데이터베이스 관련 )](https://github.com/Tk001111)

## 기간
> 2024/04/12 ~ 2024/05/09  
> 기체 제작 04/12 ~ 05/02  
> ![first](https://github.com/ikw-drone-project/.github/assets/71598954/185cc5b6-5d1f-49aa-9d31-b80548e72c9d)

## 기체 - 지상국 설계
기체에서 수집한 정보를 지상국에 전송, 지상국 GCS상에 탐지된 적 위치 표시
![web](https://github.com/ikw-drone-project/.github/assets/71598954/ac79e100-7de8-449e-a09f-5c2f34eae1ac)
> ![image](https://github.com/ikw-drone-project/.github/assets/71598954/693133e6-0c87-499c-819a-2c16c6dca9d8)
> ![image](https://github.com/ikw-drone-project/.github/assets/71598954/cea0ab7c-00fa-4958-963d-f6e61bf42250)
> ![image](https://github.com/ikw-drone-project/.github/assets/71598954/044f9128-970e-4764-b1ea-c6a7d759008a)

> 충분한 하드웨어 메모리 필요   
> ![testcase](https://github.com/ikw-drone-project/.github/assets/71598954/1069866e-962a-48ac-8d45-3bb54fb5a9bd)

MAVLINK(Micro Air Vehicle Link)를 통하여 받아온 정보와 영상정보에 기반하여 적 위치를 특정.
![image](https://github.com/ikw-drone-project/.github/assets/71598954/756c8d8e-974f-4467-8f15-fae29f523c9d)
## Goal
### 비행중인 무인비행체가 적 장갑차, 탱크를 탐지하는 경우 GCS상 상세 좌표를 표기.
