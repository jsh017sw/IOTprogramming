📂 레포지토리 구조
.
├── README.md                # 레포지토리 소개 문서
├── requirements.txt         # (선택) 사용한 파이썬 패키지 목록
├── 01_basic_python/         # 파이썬 기본 문법
│   ├── variables.py
│   ├── input_output.py
│   └── control_flow.py
├── 02_data_structure/       # 리스트, 튜플, 딕셔너리 등
│   ├── list_examples.py
│   ├── dict_examples.py
│   └── practice.py
├── 03_function_module/      # 함수, 모듈, 패키지
│   ├── functions.py
│   └── my_module.py
├── 04_file_network/         # 파일 입출력, 네트워크 기초
│   ├── file_io.py
│   └── simple_socket.py
├── 05_iot_examples/         # IOT 관련 예제
│   ├── led_control.py
│   ├── sensor_read.py
│   └── mqtt_example.py
└── assignments/             # 과제 코드 및 보고서
    ├── hw01/
    ├── hw02/
    └── ...

🧠 레포지토리 목적

파이썬 기본 문법을 배우고 실습하기 위함

IOT와 연동되는 파이썬 코드를 단계적으로 정리

수업 내용을 체계적으로 저장하여 복습 및 참고용으로 활용

나중에 포트폴리오로도 활용 가능한 깔끔한 학습용 레포지토리 구성

🛠️ 개발 환경

Python 3.x

에디터: VS Code / PyCharm / Thonny

(선택) 라즈베리파이 또는 기타 IOT 장비

OS: Windows / macOS / Linux / Raspberry Pi OS

필요한 패키지가 있다면 아래 명령어로 설치:

pip install -r requirements.txt

🚀 실행 방법

각 폴더 안에 접근하여 파이썬 파일을 실행하면 됩니다.

cd 01_basic_python
python variables.py


IOT 관련 예제를 실행할 경우
센서, GPIO, 네트워크 등 관련 환경이 정상적으로 설정되어 있는지 확인하세요.

✏️ 학습 내용 정리 방법 (추천)

주차별/주제별로 폴더를 분리

각 파일 상단에 설명 주석 작성

notes/ 폴더를 만들어 이론 정리를 저장

notes/python_basic.md

notes/iot_mqtt.md 등

✅ 커밋 메시지 규칙 (예시)

feat: LED 제어 기능 추가

fix: 센서 입력값 오류 수정

docs: README 사용법 추가

refactor: 코드 구조 개선

📌 TODO (추가 예정)

 파이썬 기본 개념 마크다운 정리

 IOT 센서/통신 예제 추가

 MQTT / HTTP 통신 정리

 과제 풀이 업로드

 에러 해결법 모음 작성

👤 작성자 정보

이름: (이름 또는 닉네임)

수업명: IOT 프로그래밍

언어: Python
