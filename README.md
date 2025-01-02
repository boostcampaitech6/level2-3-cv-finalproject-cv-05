# 🏠 보여줘, 홈즈 - 맞춤형 주거 공간 시뮬레이터 서비스
![Untitled (1)](https://github.com/boostcampaitech6/level2-3-cv-finalproject-cv-05/assets/68053155/55691cec-b71c-4df3-b09a-39aeebbcfecb)

### [보여줘 홈즈 홈페이지](https://zzimkong.ggm.kr/) 
(현재 서비스는 GPU 비용 문제로 동작하지 않습니다. 더 나은 서비스로 돌아오겠습니다👏)

## 🗂️ 목차
- [🌈 프로젝트 소개](https://github.com/boostcampaitech6/level2-3-cv-finalproject-cv-05/blob/main/README.md#-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%86%8C%EA%B0%9C)<br>
- [💡 주요 기능](https://github.com/boostcampaitech6/level2-3-cv-finalproject-cv-05/blob/main/README.md#-%EC%A3%BC%EC%9A%94-%EA%B8%B0%EB%8A%A5)<br>
- [👥 팀 소개](https://github.com/boostcampaitech6/level2-3-cv-finalproject-cv-05/blob/main/README.md#-%ED%8C%80-%EC%86%8C%EA%B0%9C)<br>
- [🍀 시연영상](https://github.com/boostcampaitech6/level2-3-cv-finalproject-cv-05/blob/main/README.md#-%EC%8B%9C%EC%97%B0%EC%98%81%EC%83%81)<br>
- [🛠 사용 기술](https://github.com/boostcampaitech6/level2-3-cv-finalproject-cv-05/blob/main/README.md#-%EC%82%AC%EC%9A%A9-%EA%B8%B0%EC%88%A0)<br>
- [🏛️ 전체 서비스 아키텍처](https://github.com/boostcampaitech6/level2-3-cv-finalproject-cv-05/blob/main/README.md#%EF%B8%8F-%EC%A0%84%EC%B2%B4-%EC%84%9C%EB%B9%84%EC%8A%A4-%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98)<br>
- [🗓️ 프로젝트 타임라인](https://github.com/boostcampaitech6/level2-3-cv-finalproject-cv-05/blob/main/README.md#%EF%B8%8F-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%ED%83%80%EC%9E%84%EB%9D%BC%EC%9D%B8)<br>
- [⚙️ 유용한 링크](https://github.com/boostcampaitech6/level2-3-cv-finalproject-cv-05?tab=readme-ov-file#%EF%B8%8F-%EC%9C%A0%EC%9A%A9%ED%95%9C-%EB%A7%81%ED%81%AC)<br>
- [📞 연락처](https://github.com/boostcampaitech6/level2-3-cv-finalproject-cv-05/blob/main/README.md#-%EC%97%B0%EB%9D%BD%EC%B2%98)<br>

## 🌈 프로젝트 소개
"보여줘, 홈즈"는 사용자의 생활 패턴과 취향을 반영한 맞춤형 주거 공간 디자인을 구현해주는 서비스입니다. 사용자가 꿈꾸는 이상적인 생활 공간을 실현할 수 있도록, AI 기반의 3D 재구성 알고리즘을 통해 사용자 개인의 취향과 요구에 맞는 인테리어 시뮬레이션을 할 수 있습니다.

### 사용자가 원하는 그 어떠한 공간도 3D 입체화할 수 있습니다.
기존에 출시된 인테리어 서비스들은 해당 주거 공간의 부동산에서 제공하는 도면을 기반으로 공간을 입체화힙니다. 이는 실제 사용자가 생활하는 공간을 반영할 수 없고 제품 구매 후 원하는 분위기가 아닌 경우가 많습니다. [보여줘, 홈즈]는 사용자가 직접 촬영한 영상을 기반으로 공간과 가구를 입체화하여 ```제품 구매 전에 내 공간에 원하는 가구가 얼마나 잘 어울리는 지를 직접적으로 경험```할 수 있습니다.

### 최적의 촬영 가이드를 제공합니다.
3D AI 모델 재구성 결과는 입력 영상 퀄리티에 영향을 받습니다. 이를 위해, 저희 팀원들이 테스트한 ```사용자 입장에서 가장 편리하고 간단한 방식```의 공간, 가구 촬영 가이드를 제공합니다. 또한 모바일로 촬영하여 네이티브 앱 환경으로 편리하게 업로드할 수 있습니다.

### 갤러리로 다른 사용자들과 결과를 공유합니다.
공간이 재구성되는 동안, 지루하지 않도록 ```다른 사용자들의 인테리어 결과를 갤러리에서 확인하고 3D 입체화```해볼 수 있습니다. 다른 사용자들은 어떠한 위치에 가구를 배치하는지, 어떠한 분위기의 공간과 가구를 매치하는지 인사이트를 얻어 인테리어의 퀄리티를 높일 수 있습니다. 회원가입 전에 서비스를 탐색할 수 있는 데모 체험도 제공합니다.

### 모델 진행 과정 모니터링과 재구성 완료 여부을 제공합니다.
공간이 재구성되는 과정을 실시간으로 사용자가 확인할 수 있도록 하여, 대화형으로 서비스를 이용할 수 있습니다. 재구성 완료 시 이메일로 알림을 통해, ```만약 재구성이 실패한다면 실패 원인을 분석하여 사용자는 본인의 촬영 방식을 개선```할 수 있습니다.

## 💡 주요 기능
| 공간 재구성 |
| --- |
|<img src = "https://github.com/SangBeom-Hahn/Sketch2Fashion/assets/90328527/1a37c5df-612a-46fc-982a-00e557ad590e">|
| 재구성 효율이 높은 최적의 공간 영상 촬영 가이드 제공 |
|<img src = "https://github.com/SangBeom-Hahn/Sketch2Fashion/assets/90328527/ca40cfc6-49a5-4725-84bc-8e9baa1072ef">|
|최적의 가구 영상 촬영 가이드 제공|
|<img src = "https://github.com/SangBeom-Hahn/Sketch2Fashion/assets/90328527/3513d91d-9854-4de8-b705-6b95701474b6">|
|모바일 업로드 기능 제공|

| 모델 추론 과정 모니터링 |
| --- |
|<img src = "https://github.com/SangBeom-Hahn/Sketch2Fashion/assets/90328527/03736dd1-ea31-4c16-b617-1a38c7df20ad">|
| 모델 인퍼런스 실시간 진행 상황 모니터링 |
|<img src = "https://github.com/SangBeom-Hahn/Sketch2Fashion/assets/90328527/2e38166b-8a15-4eae-b5f1-92ac641de43e">|
| 공간 및 가구 재구성 리스트 조회 |
|<img src = "https://github.com/SangBeom-Hahn/Sketch2Fashion/assets/90328527/3832441b-f0f0-4ba5-9afb-803493809f06">|
| 모델 재구성 성공 및 실패 여부 이메일 알림 |

| 인테리어 배치 시뮬레이터 |
| --- |
|<img src = "https://github.com/SangBeom-Hahn/Sketch2Fashion/assets/90328527/b4f79442-5b00-4aa2-9606-3a9feea17755">|
| 가구 선택 후 배치, 회전, 크기 조절, 위치 이동, 복제 및 다른 종류 가구 배치 |
|<img src = "https://github.com/user-attachments/assets/50795b12-2c66-4d04-a3e6-a2f4aa883696">|
| 회원가입 전 가능한, Demo 기능 |

| 인테리어 갤러리 |
| --- |
|<img src = "https://github.com/SangBeom-Hahn/Sketch2Fashion/assets/90328527/117f5780-7240-424a-9ac0-5331108c6bb7">|
| 다른 사용자들의 인테리어 결과 조회 |
|<img src = "https://github.com/SangBeom-Hahn/Sketch2Fashion/assets/90328527/81ad2955-8678-470c-8071-85198cfbc29b">|
| 내 결과 공유, 가구 재구성 만족도 평가 |

> ## 👥 팀 소개
<table>
    <tr height="160px">
        <td align="center" width="150px">
            <a href="https://github.com/woohee-yang"><img height="120px" width="120px" src="https://github.com/boostcampaitech6/level2-objectdetection-cv-05/assets/78292486/a1e74529-0abf-4d80-9716-4e8ae5ec8e72"/></a>
            <br/>
            <a href="https://github.com/woohee-yang"><strong>양우희</strong></a>
            <br />
        </td>
        <td align="center" width="150px">
            <a href="https://github.com/jinida"><img height="120px" width="120px" src="https://github.com/boostcampaitech6/level2-objectdetection-cv-05/assets/78292486/28955c1d-fa4e-46b1-9d70-f98eb54109b2"/></a>
            <br />
            <a href="https://github.com/jinida"><strong>이영진</strong></a>
            <br />
        </td>
        <td align="center" width="150px">
            <a href="https://github.com/cmj5064"><img height="120px" width="120px" src="https://github.com/boostcampaitech6/level2-objectdetection-cv-05/assets/78292486/6388976d-d0bd-4ba6-bae8-6c7e6c5b3352"></a>
            <br/>
            <a href="https://github.com/cmj5064"><strong>조민지</strong></a>
            <br />
        </td>
        <td align="center" width="150px">
            <a href="https://github.com/ccsum19"><img height="120px" width="120px" src="https://github.com/boostcampaitech6/level2-objectdetection-cv-05/assets/78292486/9ad5ecc3-e5be-4738-99c2-cc6e7f3931cb"/></a>
            <br/>
            <a href="https://github.com/ccsum19"><strong>조수민</strong></a>
            <br />
        </td>
        <td align="center" width="150px">
            <a href="https://github.com/hee000"><img height="120px" width="120px" src="https://github.com/boostcampaitech6/level2-objectdetection-cv-05/assets/78292486/cde48fcd-8099-472b-9877-b2644954ec68"/></a>
            <br />
            <a href="https://github.com/hee000"><strong>조창희</strong></a>
            <br />
        </td>
        <td align="center" width="150px">
              <a href="https://github.com/SangBeom-Hahn"><img height="120px" width="120px" src="https://github.com/boostcampaitech6/level2-objectdetection-cv-05/assets/78292486/1f7ed5a5-5e0f-46e4-85c6-31b9767dce41"/></a>
              <br />
              <a href="https://github.com/SangBeom-Hahn"><strong>한상범</strong></a>
              <br />
          </td>
    </tr>
</table>
<br/>

![image](https://github.com/boostcampaitech6/level2-3-cv-finalproject-cv-05/assets/68053155/81bafd11-dddf-403f-a85b-6f1e12c988fe)

## 🍀 시연영상
[![Watch the video](https://img.youtube.com/vi/dQB0vjDiycg/maxresdefault.jpg)](https://www.youtube.com/watch?v=dQB0vjDiycg&t=542s)


## 🛠 사용 기술
- **Frontend**: React.js, Three.js
- **Backend**: Spring Boot, JPA, MYSQL
- **AI & Machine Learning**: Pytorch
- **Deployment**: AI-NCP, APP-GCP, Docker, Redis
- **Collaborative Tool** : Git, GitHub, Notion, Jira

## 🏛️ 전체 서비스 아키텍처
#### 1. Application
![image](https://github.com/boostcampaitech6/level2-3-cv-finalproject-cv-05/assets/68053155/20c0cee9-6e56-4194-ba0b-66fcf0efbf1e)

#### 2. Inference
![image](https://github.com/boostcampaitech6/level2-3-cv-finalproject-cv-05/blob/main/assets/infer.JPG)

## 🗓️ 프로젝트 타임라인
![image](https://github.com/boostcampaitech6/level2-3-cv-finalproject-cv-05/assets/68053155/f2b622b0-bd39-40e3-a8bc-20329785c596)

## ⚙️ 유용한 링크
 - [📚 발표 자료](https://github.com/boostcampaitech6/level2-3-cv-finalproject-cv-05/blob/main/boostcamp-cv05-semi-final.pdf)
 - [🍀Notion](https://www.notion.so/woohee-yang/Boostcamp-AI-Tech-6-zzimkkong-ae64c6924e10414a83e66a8b4d871cda)
   
## 📞 연락처
- 프로젝트에 대한 궁금한 점이 있으시면 이메일로 문의해 주세요: bcatcv5@gmail.com
