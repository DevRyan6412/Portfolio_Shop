# **사용 기술 스택**
## Backend<br> ##
> Java 11<br>
> Build Tool : Maven<br>
> Database : MariaDB<br>
> Spring Boot 2.7.1<br>
> Spring Data JPA (Hibernate)<br>
> Spring Security<br>
> - 폼 로그인(세션기반)<br>
> - OAuth2 로그인 (Google, Naver, Kakao)
## Frontend<br> ##
> Thymeleaf<br>
> Bootstrap5<br>
> JavaScript / jQuery<br>

## **주요 기능**
### 1. 회원관리 
- 회원가입, 로그인/로그아웃<br>
> 회원가입<br><img width="500" height="300" alt="회원가입IMG" src="https://github.com/user-attachments/assets/9b7b3737-fffc-4019-880a-ae8707600969" /><br>
> 로그인<br><img width="500" height="300" alt="로그인IMG" src="https://github.com/user-attachments/assets/d0a2021e-ff13-4dcb-8713-af89e4fd142d" />

- 소셜로그인(Google, Kakao, Naver)<br>
> 소셜로그인<br><img width="500" height="300" alt="소셜로그인IMG" src="https://github.com/user-attachments/assets/6584a306-7519-4391-966a-cbe51c99aae3" />

- 마이페이지 : 회원정보 수정
> 회원정보수정<br><img width="500" height="300" alt="회원정보수정IMG" src="https://github.com/user-attachments/assets/336f7360-2768-4391-a3d4-390d2e9f96cb" />

### 2. 상품관리<br>
- 상품등록 / 수정/ 삭제(관리자)<br>
> 상품등록<br><img width="500" height="300" alt="상품등록IMG" src="https://github.com/user-attachments/assets/cf523513-a1cc-4320-b20a-8bbce68b4680" />

- 상품 목록, 상세보기, 카테고리별 조회 및 검색
> 카테고리<br><img width="500" height="300" alt="카테고리IMG" src="https://github.com/user-attachments/assets/bcf84efe-76ba-4bc9-9355-51fc1a45d53e" /><br>
> 물품검색<br><img width="500" height="300" alt="물품검색IMG" src="https://github.com/user-attachments/assets/b7460788-f25e-4db2-84a8-e206a75de493" />

### 3. 주문/결제<br>
> 장바구니 / 쿠폰 / 마일리지<br><img width="500" height="300" alt="장바구니IMg" src="https://github.com/user-attachments/assets/4008ca55-4feb-4100-87cb-ce4240181257" /><br>
> 주문, 결제(Portone)<br><img width="500" height="300" alt="결제IMG" src="https://github.com/user-attachments/assets/ab8fc178-20f7-4968-af57-08861a6d1e8f" />


### 4. 보안<br>
- Spring Security 기반 권한별(User, Admin) 접근 제어
- CSRF 보호 적용
