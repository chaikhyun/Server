# 🛎️ 실시간 알림 시스템

## 📌 프로젝트 개요
내부 설문 시스템의 관리자 웹 서비스에 실시간 알림 기능을 제공하기 위한 백엔드 프로젝트입니다.  
사용자가 설문 종료 시점에 알림을 받을 수 있도록 Server-Sent Events(SSE)와 Redis Pub/Sub를 활용해 **확장성과 안정성을 고려한 실시간 알림 시스템**을 구현하였습니다.

## 🛠 기술 스택
- Java 17
- Spring Boot 3.x
- Spring Security
- JPA (Hibernate)
- Redis (Pub/Sub)
- Server-Sent Events (SSE)
- MySQL
- Git & GitHub

## 🔍 주요 기능
- 인증 사용자 전용 알림 구독 (SSE 방식)
- Redis 기반 실시간 메시지 브로드캐스트
- 클라이언트 연결 관리 및 재연결 처리
- 알림 수신 여부 기록 및 읽음 처리
- 다중 서버 환경을 고려한 메시지 처리 설계
- 네트워크 예외 처리 및 타임아웃 설정
