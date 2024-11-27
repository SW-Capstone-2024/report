# report

## 과제 목적
![image](https://github.com/user-attachments/assets/85819654-41d0-475c-b42f-190ede6b4ed5)

최근 개인형 이동 수단의 사용이 증가하면서 , 전동 킥보드와 같은 이동 수간은 도시 내에서 빠르고 편리한 교통 수단으로 자리 잡았다. 그러나 이러한 이동 수단은 타이어가 작고 속도가 빠르기 때문에 작은 도로 결함에도 사고로 이어질 가능성이 크다. 이에 따라 도로의 균열과 패임, 포트홀 등의 위험 요소를 감지하여 사고를 예방할 수 있는 인공지능 기술 개발의 필요성이 대두되고 있다. 본 과제는 개인형 이동 수단에 YOLO 기반 딥러닝 알고리즘이 탑재된 라즈베리파이와 카메라를 장착하여, 도로 결함을 실시간으로 탐지하고 이를 데이터화하는 시스템을 구축하는 것을 목표로 한다. 탐지된 도로 상태 정보를 GPS를 통해 기록하고, Flask 프레임워크로 개발된 웹 페이지를 통해 대한 본부에 전달하여 도로 관리 및 유지보수를 효율적으로 수행 할 수 있도록 한다. 이를 통해 도로 관리 비용을 절감하고, 체계적인 유지보수를 실현하며 안전한 도로 환경을 조성하는데 기여하고자 한다. 또한, 사용자가 개인형 이동 수단을 타고 캠퍼스 내 특정 도로를 주행했을 때, 탐지된 위험 요소에 대해 경고 알림을 제공함으로써 사고를 예방하고 사용자의 안전성을 높이는데 기여하고자 한다.


## 과제 내용
본 과제는 전동 킥보드와 같은 개인형 이동 수단에 YOLOv8 Nano 모델을 기반으로 한 경량화된 도로 탐지 시스템을 개발하는 것을 목표로 한다. 라즈베리파이에 카메라 모듈을 장착하여 도로의 균열과 맨홀, 포트홀 등의 결함을 실시간으로 탐지하며, 탐지된 데이터를 GPS 정보와 함께 기록하고 웹사이트를 통해 시각적으로 제공한다. 데이터 수집은 크롤링과 캠퍼스 내 다양한 도로 환경에서 이루어졌으며, RoboFlow를 이용해 라벨링하고 데이터 증강 기법을 적용해 모델 훈련에 활용하였다. YOLOv8 Nano는 경량화된 구조로, 라즈베리파이와 같은 저사양 하드웨어에서도 높은 FPS를 제공하여 실시간 도로 상태 감지를 가능하게 한다. 이를 위해 모델 최적화와 하이퍼파라미터 튜닝 과정을 거쳐 놓은 탐지 성능을 확보하였다. 라즈베리파이 기반의 시스템은 웹사이트와 연동되어 탐지된 도로 결함의 위치를 지도 위에 표시하며, 학교 관계자는 이를 통해 도로 상태를 한눈에 파악하고 보수 계획을 효율적으로 수립할 수 있다. 또한, 전동 킥보드 사용자에게는 탐지된 장애물에 대해 경고음을 통해 즉각적인 대응이 가능하도록 설계하였다. 결과적으로, 이 시스템은 사용자의 주행 안전성을 향상시키는 동시에, 체계적인 도로 관리와 유지보수를 가능하게 하여 사고 예방, 안전 개선, 유지보수 비용 절감 등의 효과를 기대할 수 있다.


## 활용 방안 및 기대 효과
본 프로젝트의 결과물은 개인형 이동 수단 사용자의 안전성을 강화하는데 활용될 수 있다. 도로 위 위험 요소를 실시간으로 탐지하고 경고하는 기능을 통해 사용자에게 안전한 주행 환경을 제공하며, 이를 기반으로 전동 킥보드 제조사와 협력해 위험 탐지 솔루션을 기기에 내장하거나 공유 플랫폼과 파트너십을 통해 서비스를 확대할 수 있다. 또한, 도로 위험 데이터를 지자체나 정부 기관에 제공함으로써 도로 인프라 개선과 보수 작업을 유도할 수 있다. 이 시스템은 개인형 이동 수단의 사고 발생률을 감소시키고 안전성을 높이는 것은 물로, 데이터 기반 도로 인프라 개선으로 지역 주민의 삶의 질을 향상시키고 교통사고로 인한 사회적 비용을 절감하는데 기여할 수 있다. 또한, 개인형 이동 수단의 안전성과 편의성이 확보되면서 이용률이 증가해 대중교통과의 연계성을 강화하고, 자동차 사용 감소를 통해 교통 혼잡 문제를 완화할 수 있다. 나아가, 탄소배출량 감소와 같은 환경적 효과를 통해 스마트 시티 구현과 지속 가능한 도시 발전에도 기여할 것으로 기대된다.


