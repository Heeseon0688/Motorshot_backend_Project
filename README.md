# Motorshot: 오토바이 헬멧 미착용 및 위협운전 탐지 컴퓨터비전 프로젝트

### 개요

이 프로젝트는 오토바이의 교통법 위반으로 인해 발생하는 사고 문제를 해결하기 위한 목적으로 설계되었습니다. 다양한 뉴스 기사와 데이터를 통해 볼 수 있듯이, 횡단보도에서의 사고, 인도 및 횡단보도 침범, 과속 및 난폭 운전 등 교통법을 위반하는 오토바이 운전으로 인해 심각한 사고들이 빈번하게 발생하고 있습니다. 이러한 문제는 보행자와 다른 운전자들의 안전을 심각하게 위협하고 있습니다.
프로젝트는 이러한 교통법 위반 행위의 심각성을 인식시키고, 법규 준수의 중요성을 강조하기 위한 캠페인이나 솔루션을 개발하는 것을 목표로 합니다. 궁극적으로는 오토바이 운전자들의 법규 준수율을 높이고, 이를 통해 사고를 줄여 보다 안전한 도로 환경을 조성하는 데 기여하고자 합니다.

### 주요 기능

* 헬멧 착용 여부 감지: Yolov8s 모델을 활용하여 오토바이 운전자의 헬멧 착용 상태를 실시간으로 감지합니다. 이를 통해 헬멧 미착용으로 인한 사고 위험을 줄이는 데 기여할 수 있습니다.
* 위험 운전 감지: Yolov8s 모델을 통해 오토바이의 앞바퀴 들기(윌리)와 지그재그 운전 등 위험한 운전 행위를 실시간으로 감지하여 경고합니다. 이 기능은 도로 안전을 향상시키는 데 중요한 역할을 합니다.
* 횡단보도 침범 감지: 오토바이가 횡단보도를 일정 시간 이상 침범했을 때 이를 실시간으로 감지하고 경고를 제공합니다. 이는 보행자의 안전을 보호하고 교통법규 준수를 강화하는 데 도움을 줍니다.

### 특징

* 실시간 감지: 오토바이의 헬멧 착용 여부와 위험 운전 행위를 실시간으로 감지하여 즉각적인 경고를 제공합니다.
* 다양한 위험 행위 감지: 헬멧 미착용뿐만 아니라 앞바퀴 들기, 지그재그 운전, 횡단보도 침범 등 다양한 위험 운전 패턴을 감지할 수 있습니다.
* 적응형 데이터 증강: 다양한 환경과 조건에서 정확한 감지를 위해 데이터 증강 기법을 적용하여 모델의 신뢰성을 높였습니다.

### 요구 사항

- Python 3.7 이상
- MongoDB 인스턴스

### 사용

* 프론트엔드

```bash
# 깃 클론
git clone https://github.com/Heeseon06/Motorshot_frontend_Project

# 프로젝트 루트 폴더에서 아래 실행(패키지 설치)
npm install

# 실행
npm start
```
* 백엔드

```bash
# 깃 클론
git clone https://github.com/Heeseon06/Motorshot_backend_Project

# 실행
uvicorn main:app --host 0.0.0.0 --port 8080 --reload

```


# 포트폴리오

![ad232c61dc0742c70f48c5f77114c301-0](https://github.com/user-attachments/assets/dbe6ad9d-3a25-4e81-96e6-eda369a1c3eb)

<details>
  <summary>펼치기/접기</summary>

<!-- ![ad232c61dc0742c70f48c5f77114c301-0](https://github.com/user-attachments/assets/dbe6ad9d-3a25-4e81-96e6-eda369a1c3eb) -->
![ad232c61dc0742c70f48c5f77114c301-1](https://github.com/user-attachments/assets/e61d6d05-e5a2-4581-a84a-edbe791e1b43)
![ad232c61dc0742c70f48c5f77114c301-2](https://github.com/user-attachments/assets/e87637dc-0b5f-4565-b3de-95cf838bc008)
![ad232c61dc0742c70f48c5f77114c301-3](https://github.com/user-attachments/assets/01a714c8-d4b5-4a71-8623-7b94fd9f9e0a)
![ad232c61dc0742c70f48c5f77114c301-4](https://github.com/user-attachments/assets/dbce7d02-bead-4ff5-9475-46977df845a2)
![ad232c61dc0742c70f48c5f77114c301-5](https://github.com/user-attachments/assets/99ac4225-7048-4cab-af3b-c1daa095c79e)
![ad232c61dc0742c70f48c5f77114c301-6](https://github.com/user-attachments/assets/0a38604e-1b42-481b-9463-a95b5263eba3)
![ad232c61dc0742c70f48c5f77114c301-7](https://github.com/user-attachments/assets/369d2c3d-574a-470e-82ce-ed029a5708a1)
![ad232c61dc0742c70f48c5f77114c301-8](https://github.com/user-attachments/assets/bb7cb54a-c997-46d6-9729-44309be0bf81)
![ad232c61dc0742c70f48c5f77114c301-9](https://github.com/user-attachments/assets/4b1d1b7a-cb88-450c-8bb3-9e149986c055)
![ad232c61dc0742c70f48c5f77114c301-10](https://github.com/user-attachments/assets/8a6e067f-85f1-424c-ab34-d1ec43504761)
![ad232c61dc0742c70f48c5f77114c301-11](https://github.com/user-attachments/assets/9247f8df-9342-44a6-8055-c3771ba132eb)
![ad232c61dc0742c70f48c5f77114c301-12](https://github.com/user-attachments/assets/1ac08f2a-b483-4684-aa6a-ca8adbc1f43e)
![ad232c61dc0742c70f48c5f77114c301-13](https://github.com/user-attachments/assets/d5496346-c012-4ca4-9997-bc3d92613f67)
![ad232c61dc0742c70f48c5f77114c301-14](https://github.com/user-attachments/assets/1fcbffbb-90fd-4713-89bc-76d5e851093c)
![ad232c61dc0742c70f48c5f77114c301-15](https://github.com/user-attachments/assets/3a5d9105-dbf1-4d41-ad25-10989782e5d8)
![ad232c61dc0742c70f48c5f77114c301-16](https://github.com/user-attachments/assets/b416d88a-3681-491b-b425-a0e70d87a4fd)
![ad232c61dc0742c70f48c5f77114c301-17](https://github.com/user-attachments/assets/a19a76da-ed17-4ee8-a29f-d8d9a06899bd)
![ad232c61dc0742c70f48c5f77114c301-18](https://github.com/user-attachments/assets/e7e3f9a4-a50a-41ec-9f8c-954731528404)
 
 </details>

<br>

# 사용 기술

* 프론트엔드
   * JavaScript
   * React

* 백엔드
   * FastAPI
   * Python

* 모델
   * YOLOv8
   * Pytorch

* 데이터베이스
  * MongoDB

* 협업
   * GitHub
   * Figma

## 파일 구조
```
Backend/
├── src/
│   ├── config/                 # 설정 파일
│   ├── controllers/            # 컨트롤러
│   ├── middleware/             # 미들웨어
│   ├── models/                 # 데이터베이스 모델 및 AI 모델
│   ├── routers/                # 라우트
│   ├── main.py                 # FastAPI 애플리케이션 진입점 파일
├── .env                        # 환경 변수 설정 파일
├── README.md                   # 프로젝트 설명 파일
```

# 작성자의 기여
