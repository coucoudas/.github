# 쿠앤에이(Cu&A) : 쿠팡 리뷰 플랫폼

## Service Link
[Cu&A Service Link](https://couni.store/)

## Introduce
![엔젤핵 해커톤-쿠쿠다스-쿠앤아이_pages-to-jpg-0001](https://github.com/user-attachments/assets/1883a1bc-896b-4664-bc70-a4fdb7668be4)
![엔젤핵 해커톤-쿠쿠다스-쿠앤아이_pages-to-jpg-0002](https://github.com/user-attachments/assets/02983842-61b8-4fa8-9311-675c013785a3)
![엔젤핵 해커톤-쿠쿠다스-쿠앤아이_pages-to-jpg-0003](https://github.com/user-attachments/assets/0b3e8a60-be18-4809-a30d-f98346493e09)
![엔젤핵 해커톤-쿠쿠다스-쿠앤아이_pages-to-jpg-0004](https://github.com/user-attachments/assets/fa3908f9-03a2-4a7a-a656-26ece99514ff)
![엔젤핵 해커톤-쿠쿠다스-쿠앤아이_pages-to-jpg-0005](https://github.com/user-attachments/assets/2dcbffec-45d3-4b5a-b785-04a99fa0cdc1)
![엔젤핵 해커톤-쿠쿠다스-쿠앤아이_pages-to-jpg-0006](https://github.com/user-attachments/assets/98438046-fdd1-486d-8061-022d71507cbc)
![엔젤핵 해커톤-쿠쿠다스-쿠앤아이_pages-to-jpg-0007](https://github.com/user-attachments/assets/a928c889-8b2a-4f54-bcaa-abf346ec7c18)
![엔젤핵 해커톤-쿠쿠다스-쿠앤아이_pages-to-jpg-0008](https://github.com/user-attachments/assets/75f88a5a-119f-4532-8542-a597562e4f44)

## Project Summary
* 쿠앤아이(Cu&A)는 쿠팡에서 제공되는 리뷰의 한계를 극복하기 위해 개발된 플랫폼입니다. 사용자들이 상품을 구매할 때, 모든 필요한 정보가 기존 리뷰에 포함되지 않을 수 있습니다. 이를 해결하기 위해 쿠앤아이는 해당 상품을 구매한 사용자들과 랜덤 매칭을 통해 직접 질문하고 답변을 받을 수 있는 기능을 제공합니다.
* 해당 프로젝트는 사용자 간 상세한 리뷰를 질의할 수 있는 프로젝트입니다. 상품 상세 페이지에는 없는 세세한 리뷰를 받음으로써 상품 구매의 실패를 줄임으로써 사용자 만족감을 증가 시키는 것이 주목적입니다.
  
## Main Feature
* 랜덤 리뷰어 매칭: 사용자는 구매한 물건에 대해 궁금한 점이 있을 경우, 해당 상품을 구매한 다른 사용자와 랜덤으로 매칭됩니다. 이를 통해 더욱 구체적이고 개인화된 정보를 얻을 수 있습니다.
* 질문 및 답변 기능: 매칭된 사용자에게 질문을 보내고, 직접적인 답변을 받을 수 있습니다. 이는 기존의 일방적인 리뷰 시스템을 보완하여, 사용자가 필요한 정보를 더욱 깊이 있게 얻을 수 있도록 돕습니다.
* 포인트 보상 시스템: 질문에 유용한 답변을 제공한 사용자에게는 포인트가 지급됩니다. 이를 통해 사용자들이 적극적으로 참여하고, 질 높은 정보를 공유할 수 있도록 유도합니다.

## 기대 효과
저희는 상품에 대한 질의를 바탕으로 기존 판매자 입장에서 벗어난 사용자 입장에서의 더 공정한 정보 전달과 사소하지만 본인에게 중요했던 정보를 질의함으로써 판매자 만족감과 사용자 참여를 상승 시킬 것으로 보고 있습니다.  
이와 같은 공정한 정보 전달과 물건 구매의 실패를 낮추는 전략으로 다른 서비스와 차별 되어 쿠팡은 더 많은 잠재 사용자를 불러 모아 e 커머스 시장에서의 비즈니스 성장을 이끌어 낼 수 있을 것을 예상하고 있습니다.

## Demo
[Demo Link](https://youtu.be/ry5GISQtAAo)

## System Architecture
![image](https://github.com/user-attachments/assets/3710a958-79ee-4832-83ca-fabaf149c30c)

## Tech Stack
| Role | stacks  | 
| --- | --- |
| **Client**| React, Vite  | 
| **Server** | FastAPI, uvicorn (ASGI) |
| **Infra/DevOps** | AWS Cloud (EC2, S3, CloudFront, RDS, Route53, Application Load Balancer), GitHub Actions, Docker, Nginx  |
| **DB** | MySQL    |
| **AI** |  OpenAI (GPT 4o mini) |

## Team Introduce
### 팀 소개: 쿠쿠다스

<aside>
💡 `@coucoudas` 이름처럼 부드럽고 맛있는 유저 경험을 제공하는 프로덕트를 만들기 위해 모였습니다.

</aside>

클라이언트 개발자 1명, 서버 개발자 2명, 그리고 디자이너 1명으로 이루어진 저희 팀은, 각자의 전문성을 바탕으로 사용자에게 꼭 필요한 가치를 담은 플랫폼을 개발하는 데 최선을 다하고 있습니다.

저희 쿠쿠다스 팀은 **사용자에게 진정으로 유용한 정보를 제공**하고, **리뷰 문화를 혁신**하는 것을 목표로 하고 있습니다. 맛있는 쿠키처럼 **사용자가 찾는 답변**을 쉽고 빠르게 제공하는 플랫폼 쿠앤아이(Cu&A)를 통해, 사용자들이 더 나은 구매 결정을 내릴 수 있도록 돕겠습니다. 저희는 항상 사용자 중심의 프로덕트를 만들기 위해 노력하며, 지속적으로 성장하고 발전하는 팀이 될 것입니다.

### Member
| Park Min Hyeong | Kim Su Gon | Oh Yun Jeong | Yu Hee Jin |
| ---| --- | --- | --- |
| [park-minhyeong](https://github.com/park-minhyeong) | [rocknroll17](https://github.com/rocknroll17) | [dhdbswjd124](dhdbswjd124@gmail.com) | [yu-heejin](https://github.com/yu-heejin) |
| Team Leader, Frontend | Planning, Backend | Planning, Design | Backend, DevOps |
