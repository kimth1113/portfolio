[← 포트폴리오](../README.md)

# 개인 앱 개발·운영

서비스 기획부터 화면·API 구현, 광고·결제 연동, 운영 중 오류 개선까지 수행했습니다. 앱별로 필요한 기술을 선택하고 ChatGPT/Codex를 개발 도구로 활용했습니다.

## 내폰네컷

**모바일 · Apps in Toss / 운영 중**

사진 촬영·선택, 자르기, 네 컷 배치, 프레임·문구 편집, 저장·공유 흐름을 구현했습니다. 모바일 앱에는 로그인·크레딧·인앱결제 흐름을, 토스 앱에는 Canvas 합성과 보상형 광고를 연결했습니다.

React Native·Expo·TypeScript / React 18·Vite·Canvas / Python·Django REST Framework

## AI 증명사진

**모바일 · Apps in Toss / 운영 중**

사진 입력, 규격 선택, 크롭·편집, 생성 결과 확인과 저장을 구현했습니다. 서버에서는 세션·입력 검증과 취소·실패 처리를 구성하고 Python 워커와 연결했습니다.

React Native·Expo / React 18·Vite / Node.js·Express·Python

## 메아리AI

**Apps in Toss / 운영 중**

녹음·파일 업로드, 음성 생성, 재생·이력·즐겨찾기를 구현했습니다. 최신 개발 소스에는 SQLite 기반 사용자별 데이터 관리와 로컬 음성 워커의 진행·취소·복구 흐름을 추가했습니다.

React 18·Apps in Toss·TDS / Express·SQLite·Python

## 치매타파

**Apps in Toss / 운영 중**

기억력·집중력 게임과 기록·랭킹, 닉네임, 로그인·게스트, 보상형 광고 흐름을 개발했습니다. 게임 진행과 화면 복귀, 저장 오류에 대한 테스트를 보완했습니다.

React 18·Apps in Toss·Firebase·Vitest

## AI야 이게 뭐게

**Apps in Toss / 운영 중**

Canvas에 그린 그림을 AI가 맞히는 퀴즈입니다. 라운드 진행·결과·개인 기록·랭킹과 광고 흐름을 구현했고, 로컬 추론 경로에는 이미지 검증·세션 인증·요청 취소를 적용했습니다.

React 18·Canvas·Firebase / Express·Python 비전 워커

## 책 읽어주는 AI

**Apps in Toss / 출시 준비**

책 페이지 촬영, OCR, 텍스트 확인, 음성 재생과 보관함을 연결했습니다. 로컬 Supertonic TTS 워커와 배포 API 설정 검증을 추가했습니다.

React 18·Apps in Toss / Express·OCR·Python·Supertonic

## 유지보수 검증

2026-10-30 확인 기준, 내폰네컷 47개·AI 증명사진 프런트 74개와 서버 31개·치매타파 11개·메아리AI 서버 6개·그림 인식 서버 4개 자동 테스트가 통과했습니다. 토스 앱 6개의 웹 빌드와 내폰네컷 모바일 TypeScript 검사도 통과했습니다. 새 개발 소스 반영과 스토어 배포는 별도 단계입니다.
