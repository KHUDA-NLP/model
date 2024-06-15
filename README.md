# 💞 T를 위한 연애 솔루션 챗봇, Sol._.T 💞
<br>

## 1️⃣ 프로젝트 소개
 최근 거대 언어 인공지능 (LLM)의 발전으로, 사용자에게 맞춤형 유저 경험을 제공하는 ‘대화형 인공지능 연구’가 활발히 이루어지고 있다. 대화형 인공지능은 인간과 자연어 간의 상호작용을 원활하게 하여 자연스러운 대화를 가능케 할뿐만 아니라, 사람들의 감정과 같은 복잡한 주제에 대해서도 적절한 답변을 생성해낼 수 있게 되었다.

 이로부터 사용자들은 연애와 같이 개인적이고 섬세한 문제를 다루기 위한 목적으로도 챗봇을 사용하기 시작했다. 연애는 감정적 교류나 공감과 긴밀하게 연결되어 있기 때문에 서로의 감정을 이해하고 공감하는 능력이 부족하거나, 갈등이나 불화를 피하기 위해 진정한 감정을 표현하지 못하는 경우 연인 간의 갈등을 해결하기 힘들다.

 따라서 우리는 연인, 부부 사이의 일상, 연애 고민을 해결할 수 있는 공감 기반의 연애 상담 모델, sol._.T를 개발했다. sol._.T는 개인 맞춤형 대화를 제공하기 때문에, 감정적 교류와 공감에 서툰 이들의 정서적 부담을 줄일 수 있다. 이는 서로에 대한 이해와 연결을 도모하여 건강한 연애 관계를 유지하는 데에 도움을 준다. 나아가 사용자들은 언제든지 저비용으로 연애와 관련된 조언을 얻을 수 있기 때문에, 연인/부부 간 원활한 소통을 도모하고 및 연애 관계를 진전하는 데에 도움을 줄 것으로 기대한다.


<br>

## 2️⃣ 주요 기능
<img src = "https://github.com/coqls1229/Sol-T/assets/127406760/1c291849-e59f-4a5b-bdd6-636226b27ddf" width = "480" height = "400"/>
<br>

사용자가 sol._.T에게 자신의 상황을 입력하면, sol._.T는 그에 맞는 연애 솔루션을 제공해 준다. 만약 사용자의 채팅이 불충분한 정보를 담고 있는 경우, sol._.T는 상황이나 맥락을 이해하기 위해 추가 질문을 요구하기도 한다.

<img src = "https://github.com/coqls1229/Sol-T/assets/127406760/562c8951-f04b-4e02-a991-325b76e3afc3" width = "480" height = "400"/>

<br>
사용자가 채팅을 통해 자신의 상황을 충분히 설명하였다면, sol._.T는 문제 상황을 파악한 후 상대방의 입장에 공감하여 갈등을 해소할 수 있는 해결책을 제시해 준다. 만약 연인과 어떻게 대화를 이어나가야 할지 고민되는 상황에서는, 상황에 따라 메세지 예시를 추천해 주기도 한다. 

<br>
<br>

## 3️⃣ 챗봇 최종 아키텍처
<img src = "https://github.com/leejoon2067/Chat-Bot_Sol-T/blob/main/data/img/SOL_T%20%EC%95%84%ED%82%A4%ED%85%8D%EC%B3%90.png" width = "500" height = "280"/>
1) CSV Loader -> 2) Text Split -> 3) Vectore Store DB(FAISS) -> 4) Retriever -> 6) LLM 

<br><br>

## 4️⃣ 활용 방안
- **연애 고민 상담 & 조언 서비스**

  연애 문제로 고민하는 사용자들은 sol._.T에게 자신의 상황을 이야기하면서 고민 상담을 진행할 수 있고, 그로부터 실질적인 조언을 구할 수 있다. sol._.T는 사용자의 상황에 따라 공감이나 위로를 제공하기 때문에, 연인과의 갈등 상황을 해결하면서 동시에 사용자의 감정적인 안정에 도움을 줄 수 있다.

- **연애 기술 & 공감 대화 연습 서비스**

  실제 연애 경험이 부족한 사용자들은 sol._.T와의 대화를 통해 연애 기술을 익히고, 공감을 기반으로 한 의사소통 방식을 배워갈 수 있다. 사용자들은 sol._.T의 제안을 통해 소통 능력 강화, 갈등 관리 방법, 관계 강화 전략 등을 배워갈 수 있다.
  
- **감정 이해 & 표현력 향상 도움 제공**

  연인 간, 가족 간, 친구 간의 감정을 이해하고 표현하는 데 어려움을 겪는 사용자들은 sol._.T를 통해 자신 및 연인의 감정을 이해할 수 있고, 감정적에 대한 표현력을 향상할 수 있다. 연애 상담 챗봇이 인간에게 익숙한 대화 형식으로 사용자와 상호작용한다면, 사용자들은 자연스럽게 자신의 감정을 표현하면서 감정 이해의 폭을 넓힐 수 있을 것이다.

<br>

## 😊 팀원 소개
|멤버이름|역할|
|------|---|
|이준혁| 트랙장, DB-Retriver-Chain 구조 완성, streamlit 웹 프론트 구현 |
|이두원| 공감형 대화 데이터 전처리, Faiss에 데이터 저장 및 임베딩, 유사도 측정 |
|권서연| 공감형 대화 데이터 전처리, vector embeddinngs/vector DB 구조 완성 |
|최소영| Vectorstore과 연결하여 Retriever Module 구조 완성 |
|방채빈| LLM Prompt 정의 및 model과 Prompt 연결, Retriver-Chain 구조 완성 |

- 🔤 NLP(Natural Language Processing) Track [Notion](https://simple-board-99d.notion.site/NLP-09f76e5ca2214aea89cac18073a46846)
- 💞 SOL._.T archive [Notion](https://simple-board-99d.notion.site/88e6854a57234b8b92e8c01e070115a4)

<br><br>

## 📑 참고 문헌
[1] [선물 추천 챗봇 PresenTALK 개발기](https://github.com/mu0gum/nlp_research?tab=readme-ov-file)

[2] [자연어 처리_연애 상담 챗봇_프로젝트 (1)](https://velog.io/@min0731/%EC%9E%90%EC%97%B0%EC%96%B4-%EC%B2%98%EB%A6%AC%EC%97%B0%EC%95%A0-%EC%83%81%EB%8B%B4-%EC%B1%97%EB%B4%87%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-1)

[3] [혼자 힘으로 한국어 챗봇 개발하기](https://exagen.tistory.com/notice/63)

[4] [KoELECTRA v3 (Base Discriminator)](https://huggingface.co/monologg/koelectra-base-v3-discriminator)

[5] [Streamlit을 이용한 Chatbot 만들기 (Blenderbot, GPT-3)](https://yunwoong.tistory.com/227)

[6] [Using langchain for Question Answering on Own Data](https://medium.com/@onkarmishra/using-langchain-for-question-answering-on-own-data-3af0a82789ed)

[4] KoELECTRA v3 (Base Discriminator), https://huggingface.co/monologg/koelectra-base-v3-discriminator 

[5] Streamlit을 이용한 Chatbot 만들기 (Blenderbot, GPT-3), https://yunwoong.tistory.com/227

[6] Using langchain for Question Answering on Own Data, https://medium.com/@onkarmishra/using-langchain-for-question-answering-on-own-data-3af0a82789ed
