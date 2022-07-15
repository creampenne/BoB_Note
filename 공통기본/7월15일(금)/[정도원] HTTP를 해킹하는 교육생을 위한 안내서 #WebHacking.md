# [정도원] HTTP를 해킹하는 교육생을 위한 안내서 #WebHacking
**07/15/2022**  

## 클라이언트 사이드에서의 Side Channel Attack
- 응답 시간, 응답 코드, 브라우저 히스토리, 폰트 등 공격 벡터가 무수히 많음
- 웹 어플리케이션과 브라우저간의 책임 소재가 불분명함
- 개인정보 이슈가 점점 민감하게 받아들여짐
- 연구하는 사람이 적은 블루오션

## Injection
- SQL Injection
- XSS (Client side javascript injection)
- LDAP Injection
- XPath Injection
- OS Command Injection

## 문법을 어떻게 조작할 것인가?
- 키워드 필터링 -> 필터 우회
- 웹 어플리케이션 방화벽 -> 방화벽 우회
- 길이 제한 -> 페이로드 줄이기

## 문법을 조작할 수 있는가?
- Stored, Reflected ...
- CSP -> unsafe domain, missing

XS-Leak