<div align="center">

# ✨Introduction

![아이콘](asset/icon.png)

# 집 꾸



</div>
<div align="center">
사진 한 장으로 내 방에 어울리는 가구를 바로 골라보고<br>
배치까지 할 수 있는 앱입니다.


<br><br>

# 🗣️ Demo

| 메인 페이지, 사진 촬영                              | 스타일 선택, 요구사항 작성 페이지                     |
| --------------------------------------------------- | ----------------------------------------------------- |
| <img width="300" alt="start" src="asset\start.gif"> | <img width="300" alt="choose" src="asset\choose.gif"> |

| 생성 이미지                                                 | AR기능                                        |
| ----------------------------------------------------------- | --------------------------------------------- |
| <img width="300" alt="generation" src="asset\generate.gif"> | <img alt="AR" src="asset\ar.gif" width="300"> |

<table>
  <tr>
    <th colspan="2" align="left">외부 쇼핑몰 링크</th>
  </tr>
  <tr>
    <td width="50%">
      <img width="300" alt="big" src="asset/link.gif">
    </td>
    <td width="50%"></td>
  </tr>
</table>

<br><br>

# 🛠 System Architecture

<img align="center" width="1000" alt="yolo" src="asset\sys.png">

<br><br>

# 😎 YOLO(You Only Look Once)

> 객체 감지를 한 번의 신경망 예측으로 수행하여 <br> 이미지 내의 여러 객체의 위치와 클래스를 동시에 빠르게 예측하는 모델

<img align="center" width="1000" alt="yolo" src="asset\yoloF2.png">
<br><br>

> 훈련 및 검증 과정에서 모든 손실 지표(box, cls, dfl)가 안정적으로 수렴하는 것을 보여주며,<br> 이는 효과적인 학습과 일반화 성능을 나타냅니다.

<img align="center" width="1000" alt="curve" src="asset\curve.png"> <img align="result" width="1000" alt="result" src="asset\yolo_result.png">

<br><br>

# ⚡CLIP(Contrastive Language–Image Pretraining)

> CLIP(Contrastive Language–Image Pretraining)은 이미지와 텍스트를 동시에 학습하여<br> 둘을 같은 임베딩 공간에 매핑하는 모델

<img align="center" width="1000" alt="clip" src="asset\clip_img.png">
<br><br>

> t-SNE 시각화는 CLIP 모델이 학습한 이미지 임베딩 공간에서 유사한 의미를<br> 가진 객체들이 밀집된 군집을 형성함을 보여줍니다.

<img align="center" width="1000" alt="clip_img" src="asset\CLIP.png">

<br><br>

# 💡 RoomGPT

> 사용자가 업로드한 실내 사진을 기반으로 다양한 인테리어 스타일로 공간을<br> 자동 재구성해주는 AI 기반 이미지 변환 모델

<img align="center" width="1000" alt="roomgpt" src="asset\roomgpt.png">

<br><br>

# 🎮 WebXR

> 웹 브라우저를 통해 가상 현실(VR) 및 증강 현실(AR) 경험을 제공하는 웹 표준 기술

<img align="center" width="300" alt="webxr" src="asset\ar.gif">

<br><br>

# 📊 ERD

<img align="center" width="1000" alt="erd" src="asset\erd.png">

<br><br>

# 🔗 API

<img align="center" width="1000" alt="api_1" src="asset\api_1.png">
<img align="center" width="1000" alt="api_2" src="asset\api_2.png">

<br><br>

# ⚙️ Preprocessing

> 각 카테고리별로 필터링, 인코딩, 정규화 처리를 거쳐 데이터 전처리 과정에서 총 8,118개의 이미지가 7,100개로 축소되었으며,<br> 최종적으로 이미지 전처리 후 총 물품 개수는 2,633개입니다.

<img align="center" width="1000" alt="Preprocessing" src="asset\Preprocessing.png">

<br><br>

# 💻 Monitoring

<div align="center">
  <h3 align="left">Prometheus & Grafana</h3>
  <table>
        <tr>
            <th colspan="1">Grafana</th>
        </tr>
        <tr>
            <td><img src="asset\grafana.png" alt="Django"></td>
        </tr>
        <tr>
            <th colspan="1">Traefik</th>
        </tr>
        <tr>
            <td><img src="asset\traefik.png" alt="cAdvisor"></td>
        </tr>
    </table>
</div>
</br>

# 🚀 Tech Stack

<div align="center">
  <table>
    <tr>
      <th>Field</th>
      <th>Technology of use</th>
    </tr>
    <tr>
      <td><b>Frontend</b></td>
         <td>
           <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
           <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
           <img src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
           <img src="https://img.shields.io/badge/PWA-339933?style=for-the-badge&logo=pwa&logoColor=white">
           <img src="https://img.shields.io/badge/Yarn-2C8EBB?style=for-the-badge&logo=yarn&logoColor=white">
           <img src="https://img.shields.io/badge/vite-646CFF?style=for-the-badge&logo=vite&logoColor=white">
           <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white">
           <img src="https://img.shields.io/badge/axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">
           <img src="https://img.shields.io/badge/WebXR-0A7EA4?style=for-the-badge&logo">
           <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white">
           <img src="https://img.shields.io/badge/eslint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white">
           <img src="https://img.shields.io/badge/prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=white">
           <img src="https://img.shields.io/badge/zustand-F3DF49?style=for-the-badge&logo=zustand&logoColor=white">
           <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white">
         </td>
    </tr>
    <tr>
      <td><b>Backend</b></td>
      <td>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
        <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=RabbitMQ&logoColor=white">
        <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=Celery&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>DevOps</b></td>
      <td>
        <img src="https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white">
        <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
        <img src="https://img.shields.io/badge/Google_Cloud_Run-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white">
        <img src="https://img.shields.io/badge/gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=black">
        <img src="https://img.shields.io/badge/Google_Compute_Engine-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white">
        <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
        <img src="https://img.shields.io/badge/GitLab-FCA121?style=for-the-badge&logo=gitlab&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>DB</b></td>
      <td>
        <img src="https://img.shields.io/badge/Google_Cloud_Storage-4285F4?style=for-the-badge&logo=googlecloudstorage&logoColor=white">
        <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white">
        <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white">
        <img src="https://img.shields.io/badge/Qdrant-FF4A4A?style=for-the-badge&logo=qdrant&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>AI</b></td>
      <td>
        <img src="https://img.shields.io/badge/OpenAI-74aa9c?style=for-the-badge&logo=openai&logoColor=white">
        <img src="https://img.shields.io/badge/Replicate-4A90E2?style=for-the-badge&logo=replicate&logoColor=white">
        <img src="https://img.shields.io/badge/Roboflow-FF6C37?style=for-the-badge&logo=roboflow&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>Monitoring</b></td>
      <td>
        <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=black">
        <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=black">
        <img src="https://img.shields.io/badge/Loki-F46800?style=for-the-badge&logo=grafana&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>etc</b></td>
      <td>
        <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
        <img src="https://img.shields.io/badge/slack-4A154B?style=for-the-badge&logo=slack&logoColor=white">
        <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">
        <img src="https://img.shields.io/badge/zoom-0B5CFF?style=for-the-badge&logo=zoom&logoColor=black">
        <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
      </td>
    </tr>
  </table>
</div>

<br>

# 🧩 Team Members

<table style="border-collapse:collapse;">
  <tr>
    <th style="border-bottom:1px solid #fff;">Name</th>
    <th style="border-bottom:1px solid #fff;">정기홍</th>
    <th style="border-bottom:1px solid #fff;">최재현</th>
    <th style="border-bottom:1px solid #fff;">정주호</th>
    <th style="border-bottom:1px solid #fff;">황민선</th>
    <th style="border-bottom:1px solid #fff;">조은해</th>
  </tr>
  <tr>
    <th style="border-bottom:1px solid #fff;">Profile</th>
    <td style="text-align:center; vertical-align:middle; border-bottom:1px solid #fff;"><img src="https://github.com/Jungkihong07.png" style="width:100px;height:100px;"></td>
    <td style="text-align:center; vertical-align:middle; border-bottom:1px solid #fff;"><img src="https://github.com/MacArthur17.png" style="width:100px;height:100px;"></td>
    <td style="text-align:center; vertical-align:middle; border-bottom:1px solid #fff;"><img src="https://github.com/jinks145.png" style="width:100px;height:100px;"></td>
    <td style="text-align:center; vertical-align:middle; border-bottom:1px solid #fff;"><img src="https://github.com/minseon0201.png" style="width:100px;height:100px;"></td>
    <td style="text-align:center; vertical-align:middle; border-bottom:1px solid #fff;"><img src="https://github.com/Eunhea411.png" style="width:100px;height:100px;"></td>
  </tr>
  <tr>
    <th style="border-bottom:1px solid #fff;">Role</th>
    <td style="border-bottom:1px solid #fff;">Leader, Backend,<br>Frontend, DevOps</td>
    <td style="border-bottom:1px solid #fff;">Backend, DevOps</td>
    <td style="border-bottom:1px solid #fff;">Backend, DevOps</td>
    <td style="border-bottom:1px solid #fff;">Frontend</td>
    <td style="border-bottom:1px solid #fff;">Frontend, Design</td>
  </tr>
  <tr>
    <th style="border-bottom:1px solid #fff;">GitHub</th>
    <td style="border-bottom:1px solid #fff;"><a href="https://github.com/Jungkihong07"><img src="https://img.shields.io/badge/Jungkihong07-green?style=social&logo=github"/></a></td>
    <td style="border-bottom:1px solid #fff;"><a href="https://github.com/MacArthur17"><img src="https://img.shields.io/badge/MacArthur17-green?style=social&logo=github"/></a></td>
    <td style="border-bottom:1px solid #fff;"><a href="https://github.com/jinks145"><img src="https://img.shields.io/badge/jinks145-green?style=social&logo=github"/></a></td>
    <td style="border-bottom:1px solid #fff;"><a href="https://github.com/minseon0201"><img src="https://img.shields.io/badge/minseon0201-green?style=social&logo=github"/></a></td>
    <td style="border-bottom:1px solid #fff;"><a href="https://github.com/Eunhea411"><img src="https://img.shields.io/badge/Eunhea411-green?style=social&logo=github"/></a></td>
  </tr>
</table>
<br>

</div>
