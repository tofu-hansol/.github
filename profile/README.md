# tofu-hansol (두부 한 모)
- 두부 한 모 프로젝트(tofu-hansol)은 사내 동호회 웹 서비스로서 동호회 정보 제공 및 회원 관리를 제공합니다.

<br />

## 필요성, 기대효과
 - 기존 사내에서는 어떤 동호회가 존재하는지 알 수 없음, 또한 동호회 가입을 원해도 동호회장이 누구인지 알 수 없는 불편함 존재
 - 따라서 사내 존재하는 동호회 정보를 제공할 뿐만 아니라 활동 내용 소개, 동호회 홍보 등의 목적으로 시스템 개발
 - 각기 다른 팀원이 모여 각자 역할을 맡아 협업하여 프로젝트 진행 (Frontend, Backend, Data visualization)

<br />

## ⚙ 사용 기술
<p>
  <img src="https://img.shields.io/badge/-SpringBoot-blue"/>&nbsp
  <img src="https://img.shields.io/badge/-Naver Cloud Platform-green"/>&nbsp
  <img src="https://img.shields.io/badge/-MySQL-blue"/>&nbsp
  <img src="https://img.shields.io/badge/-Github Actions-lightgrey"/>&nbsp
  <img src="https://img.shields.io/badge/-JPA-9cf"/>&nbsp
  <img src="https://img.shields.io/badge/-Java 17-ff6914"/>&nbsp
  <img src="https://img.shields.io/badge/-Docker-9cf"/>&nbsp
</p> 

<br />

## 프로젝트 계획서
- [tofu-hanol 프로젝트 계획서](https://docs.google.com/document/d/1Td_7HSA2XPvCZVvhALlNHwmeC7O54x9JO3k-hd7zquw/edit)

<br />

## UI 화면 구성
- [tofu-hansol figma (현재 비공개)](https://www.figma.com/file/2WY7OJT0fXGPzjNGyW1bTi/Untitled?type=design&node-id=0-1&mode=design&t=u204uxI9Mw5Thtsg-0)

<br /> 

## 📑 프로젝트 구조
![image](https://github.com/tofu-hansol/.github/assets/70880695/13317cf1-aae7-411e-98ed-ecc8659c2f73)


<br />

## ✏️ ERD
![image](https://github.com/tofu-hansol/.github/assets/70880695/de5a8bc7-3b11-4400-9594-59e17b204209)

<br />

## 프로젝트 관심사
1. Spring Security + JWT 활용하여 유저 인증 수행
2. 동호회 권한 (동적 권한) 체크 시 Spring Security 활용
3. 동호회 권한(동호회장, 총무, 회원)이 필요한 API는 어노테이션을 붙이는 것만으로 유저의 동호회 권한 확인할 수 있게 구현
4. 매 api마다 DB로부터 동호회 권한을 확인하는 것이 아닌 권한 인증 실패 시에만 권한을 가져와 Security Context에 등록
3. Kakao Maps API 적용하여 모임 위치 지정 및 지도 활용
4. CI/CD 구축, 테스트 혹은 빌드 실패 시 서버에 반영되지 않도록 구성
5. Junit 5 활용, 단위테스트 작성
6. 기존 사내 프레임워크 UI를 차용하기보다 직접 디자인하고 UI 구성하여 적용
7. 사진이 주가 되는 웹 서비스다보니 이미지 로딩 속도롤 향상하기 위해 CDN + Naver Image Optimizer 이용

<br />

## 서비스 내용


<br />




