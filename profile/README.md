# ⏳ Time Capsule

> 지금의 기록을 쌓아, 미래의 우리가 다시 꺼내볼 수 있도록  
> _A developer team that stores today's ideas for tomorrow._

## 🗂 팀 소개

Time Capsule은 개발 과정에서의 고민, 설계 의도, 기술적 선택을 코드와 문서로 남기는 것을 목표로 하는 프로젝트 팀입니다.  

기능 구현에 그치지 않고 왜 이 구조를 선택했는지, 어떤 문제를 해결하려 했는지를 설명할 수 있는 코드를 지향합니다.  
프로젝트 전반에서 유지보수성과 확장성을 고려한 설계를 중요하게 생각합니다.  

## 👥 멤버

| 이름 | 닉네임 | 역할 |
|----|------|----|
| 김지윤 | 찌늉 | Frontend |
| 나은정 | 난정 | Backend |

## 🛠 개발 방향

- 요구사항을 명확히 정의하여 구현  
- 설계와 구현 사이의 의사결정 과정 기록  
- 협업을 고려한 구조와 컨벤션을 유지  
- README와 문서를 통해 프로젝트 맥락을 공유  

## 프로젝트 모아보기

<details>
<summary> <h3> 나눠나눠 (Nanonano) </h3> </summary>

**회차 별 결제 금액 + 참여자**만 입력하면  
각자 부담액을 **깔끔하게 자동 정산**해주는 반응형 웹 서비스입니다.  
웹으로도, 폰에서도(모바일) 쓸 수 있게 만들었어요.

> ✅ 비회원 즉시 계산 기능  
> ✅ 회원은 모임 목록 저장/조회 → 링크 공유까지

**“정산은 빠르게, 공유는 편하게, 기록은 깔끔하게.”**  

## 🖼️ 미리보기 (Screenshots)

| 홈 | 로그인 |
| --- | --- |
| <img width="860" height="2268" alt="image" src="https://github.com/user-attachments/assets/fc47b271-3a46-4bdb-8765-e8566cdbae4a" /> | <img width="860" height="1864" alt="image" src="https://github.com/user-attachments/assets/71028291-4b08-4df3-953b-e710d3d73d08" /> |


| 편집/정산 | 모임 목록 | 공유 링크(읽기 전용) |
| --- | --- | --- |
| <img width="860" height="3742" alt="image" src="https://github.com/user-attachments/assets/e59b40c4-a5ad-4b15-a138-082063774770" /> | <img width="860" height="2980" alt="image" src="https://github.com/user-attachments/assets/2362617e-9820-42dd-b9d4-1e4c92563aad" /> | <img width="744" height="2123" alt="image" src="https://github.com/user-attachments/assets/355ecce8-958c-4198-82de-b6aeea58b927" /> |

## ✅ 주요 기능

- **비회원 계산 기능**  
  - 로그인 없이 바로 참여자, 차수, 금액 입력 → 즉시 정산 결과 확인

- **소셜 로그인**
  - 로그인 시 **모임 목록** 저장/조회 가능

- **결제 내역 추가**
  - 항목별로 **금액, 참여자, 메모** 입력
  - 총 10차까지 모임 회차수 추가 가능

- **모임 메모**
  - 모임에 대한 간단한 메모 저장 (회원 기능)

- **정산 후 링크 공유**
  - 결과를 링크로 공유 (읽기 전용)
  - 공유 링크는 1주일 뒤 자동 만료

## 🧾 사용 흐름

1. 새 모임 만들기
2. 참여자 추가
3. 차수(1차/2차/3차…)별 결제 내역 입력  
   - 금액 입력  
   - 참여자 선택  
   - 메모(선택)
4. 정산 결과 확인
5. (회원) 링크 공유

## 🔗 링크 공유

- 공유 링크는 읽기 전용(결과 확인용)
- 생성 시점 기준 7일 후 자동 만료
- 만료 이후에는 링크로 접근해도 결과를 볼 수 없어요

</details>



---

이 저장소는 Time Capsule 팀의 프로젝트 기록 공간입니다.  
> ⏳ *We code not only for now, but for the future us.*
