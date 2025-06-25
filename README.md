<div>
  
  <!--Header-->
  ![header](https://capsule-render.vercel.app/api?type=Cylinder&color=gradient&height=300&section=header&text=Fairytale%20App%20%F0%9F%93%96)
  
</div>
<div>
  <!--Body-->
  
  ## 👀 About Project
  #### :raising_hand: AI 기반 개인화 동화생성 모바일 애플리케이션 "엄빠, 읽어도!"<br/>
  #### :fire: 아이만을 위한 맞춤형 동화와 색칠공부를 제공하는 풀스택 프로젝트<br/>
  #### :mortar_board: 1조 팀 협업 프로젝트 - Flutter + Spring Boot + Python FastAPI
  <br/>
  <br/>
  
  ## 🧱 Tech Stack
  ### Frontend
  <!--Flutter-->
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white"/>
  <!--Dart-->
  <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white"/>
  <br/>
  
  ### Backend
  <!--Spring Boot-->
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white"/>
  <!--Python-->
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <!--FastAPI-->
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=FastAPI&logoColor=white"/>
  <br/>
  
  ### Database & Storage
  <!--MySQL-->
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/>
  <!--Amazon AWS-->
  <img src="https://img.shields.io/badge/Amazon_S3-FF9900?style=flat-square&logo=amazon-s3&logoColor=white"/>
  <br/>
  
  ### AI & APIs
  <!--OpenAI-->
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/>
  <!--YouTube API-->
  <img src="https://img.shields.io/badge/YouTube_API-FF0000?style=flat-square&logo=youtube&logoColor=white"/>
  <br/>
  
  ### Tools
  <!--GitHub-->
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
  <!--Notion-->
  <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white"/>
  <!--Figma-->
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white"/>
  <br/>
  <br/>
  
  ## 🌟 Main Features
  #### 🎨 AI 동화 생성 - OpenAI GPT를 활용한 개인화된 동화 창작
  #### 🖼️ AI 이미지 생성 - DALL-E API로 동화 일러스트 자동 생성  
  #### 🎵 TTS 음성 합성 - 9가지 목소리로 동화 읽어주기
  #### 🎨 색칠공부 - 생성된 이미지를 흑백 변환하여 디지털 색칠
  #### 📱 갤러리 - 동화와 색칠 작품 저장 및 관리
  #### 🎬 커뮤니티 공유 - 동영상 생성 후 사용자간 공유
  #### 🎵 스마트 자장가 - YouTube API 기반 테마별 자장가 추천
  <br/>
  <br/>
  
  ## 🏗️ Architecture
  ```
  📱 Flutter App (Client)
      ↕️
  🌐 Spring Boot Server (API Gateway & Auth)
      ↕️  
  🧠 Python FastAPI Server (AI Processing)
      ↕️
  ☁️ AWS S3 + OpenAI API
  ```
  <br/>
  
  ## 📂 Project Structure
  ### Flutter App
  ```
  lib/
  ├── models/ - 데이터 모델
  ├── screens/
  │   ├── coloring/ - 색칠공부
  │   ├── gallery/ - 갤러리  
  │   ├── lullaby/ - 자장가
  │   ├── profile/ - 프로필 관리
  │   ├── share/ - 커뮤니티
  │   ├── home_screen.dart
  │   └── stories_screen.dart
  ├── service/ - API 통신
  └── main.dart
  ```
  
  ### Spring Boot Server
  ```
  src/main/java/com/fairytale/fairytale/
  ├── auth/ - 인증/인가
  ├── baby/ - 아이 정보
  ├── coloring/ - 색칠공부
  ├── gallery/ - 갤러리
  ├── lullaby/ - 자장가
  ├── share/ - 공유
  └── story/ - 동화 관리
  ```
  
  ### Python AI Server  
  ```
  python/
  ├── controllers/
  │   ├── music_controller.py
  │   ├── story_controller.py
  │   └── video_controller.py
  └── ai_server.py
  ```
  <br/>
  
  ## 🤔 Project Stats
  [![GitHub stars](https://img.shields.io/github/stars/ansdud923/fairytale-app)](https://github.com/ansdud923/fairytale-app)
  [![GitHub forks](https://img.shields.io/github/forks/ansdud923/fairytale-app)](https://github.com/ansdud923/fairytale-app)
  [![GitHub issues](https://img.shields.io/github/issues/ansdud923/fairytale-app)](https://github.com/ansdud923/fairytale-app)
  <br/>
  <br/>
  
  ## 🚀 Key Technologies
  #### 🧠 **AI Integration**: OpenAI GPT-4, DALL-E 3, TTS API 
  #### 🔐 **Authentication**: JWT Token, 소셜 로그인 (카카오, 구글)
  #### ☁️ **Cloud Storage**: AWS S3 Presigned URL, 안전한 파일 관리
  #### 📱 **Cross Platform**: Flutter 크로스플랫폼 네이티브 성능
  #### 🎵 **Media Processing**: YouTube API, 음성/동영상 스트리밍
  #### 🎨 **Digital Art**: 실시간 디지털 색칠공부 시스템
  <br/>
  <br/>
  
  ## 📋 Development Info
  #### 📅 **개발기간**: 2025년 6월 (36일)
  #### 👥 **팀구성**: 1조 팀 (풀스택 협업)
  #### 📱 **버전**: v1.0.0
  #### 🎯 **타겟**: 부모와 아이를 위한 교육 앱
  
</div>
<!--
**Fairytale App** is a ✨ *special* ✨ project that creates personalized fairy tales for children using AI technology.

Features:
- 🎨 AI Story Generation with OpenAI GPT
- 🖼️ AI Image Creation with DALL-E  
- 🎵 Text-to-Speech with multiple voices
- 🎨 Digital Coloring Book
- 📱 Gallery Management
- 🎬 Community Sharing
- 🎵 Smart Lullaby Service
-->
