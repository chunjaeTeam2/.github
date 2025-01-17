# 요구사항

---

1. 주제 선정: 메뉴, 맛집 추천과 회원 간 모임이 가능한 서비스 <밥메이트>
2. 벤치마킹: 같이가요

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/03086bcf-a036-4692-83ad-d1123cd1f0d0/18f53c6a-e77f-4042-898e-ab98c14bda88/image.png)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/03086bcf-a036-4692-83ad-d1123cd1f0d0/430231fd-1aa6-41e7-b47a-5b12e6ccf676/image.png)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/03086bcf-a036-4692-83ad-d1123cd1f0d0/599a348b-0dc4-4c2e-a15b-34d52ae5a4d4/image.png)

https://www.youtube.com/watch?v=hf-FeEIQ_d0

![같이가요.gif](https://prod-files-secure.s3.us-west-2.amazonaws.com/03086bcf-a036-4692-83ad-d1123cd1f0d0/64f38836-eaa8-4b63-b240-826728b93394/%EA%B0%99%EC%9D%B4%EA%B0%80%EC%9A%94.gif)

![랜덤메뉴(1).gif](https://prod-files-secure.s3.us-west-2.amazonaws.com/03086bcf-a036-4692-83ad-d1123cd1f0d0/21d31923-c021-45b4-baab-28b9406a0b5e/%EB%9E%9C%EB%8D%A4%EB%A9%94%EB%89%B4(1).gif)

### 요구사항

1)  회원정보

(1) 앱을 통해서 고객이 회원가입을 할 수 있다.

(2) 회원가입 시 고객에게 이름/이메일/휴대폰 번호/패스워드/닉네임/성별/생년월일/회원가입일/프로필 사진 URL/추천설정(선호하는 성별) 정보를 받는다.

2) 모임

(1) 고객은 커뮤니티를 이용해 다른 고객과 모임을 결성할 수 있다.

(2) 제안 시 날짜, 시간대, 장소 등을 명시하고, 제안된 모임에 다른 회원들이 참여 신청을 할 수 있다.

(3) 참여 인원이나 모임 상태(모임 종료, 진행 등)를 표시해 실시간으로 알 수 있게 한다.

3) 맛집 및 메뉴 추천

리뷰 데이터(평점, 리뷰 등)를 이용해 맛집을 추천할 수 있게 한다.

사용자 추천이 많거나 평점이 높은 메뉴는 인기 메뉴로 표시되어 다른 사용자가 인기 메뉴를 파악하기 쉽게 한다.

위치, 음식 종류, 가격대를 기준으로 검색 기능을 제공한다.

GPS를 활용하여 사용자의 현재 위치를 기준으로 추천을 제공하며, 근처의 인기 맛집을 확인할 수 있다.

4) 공기

친구 초대, 모임 만들기, 리뷰 등록을 통해 (포인트)공기를 획득할 수 있다.

획득한 포인트는 같이가요 제안, 채팅, 다른 회원 프로필 확인 기능에 이용할 수 있다.

5) 알림

모임 초대, 리뷰에 대한 피드백을 고객에게 알릴 수 있다.

## 모델링

1.  개념적 모델링

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/03086bcf-a036-4692-83ad-d1123cd1f0d0/27b849ac-8dc9-4bff-ab93-0ab8620c0f4d/image.png)

1. 논리적 모델링

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/03086bcf-a036-4692-83ad-d1123cd1f0d0/b0daec02-4d57-4c13-b298-e624e1a67569/image.png)

1. 물리적 모델

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/03086bcf-a036-4692-83ad-d1123cd1f0d0/93a258ff-5feb-4f42-816e-84b336ab2064/image.png)
