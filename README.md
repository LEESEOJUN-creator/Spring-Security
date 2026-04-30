
###Spring Security 인증 실습###

Spring Boot 기반으로 JWT 인증과 카카오 소셜 로그인을 실습한 프로젝트입니다.
구현 내용

회원가입 / 로그인 / 로그아웃
JWT Access Token + Refresh Token 발급 및 재발급
Refresh Token Redis 저장 관리
카카오 OAuth2 로그인 연동
Spring Security 필터 기반 토큰 검증
Soft Delete 방식 회원 탈퇴

기술 스택

Java 17, Spring Boot 3.5.6
Spring Security, jjwt 0.11.5
MySQL, Redis
Kakao OAuth2
