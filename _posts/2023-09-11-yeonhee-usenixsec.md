---
title:  USENIX Security 2023 여행기
date:   2023-09-11
author: Yeonhee Ryou
kor_author: 류연희
tags:
  - Trip
  - USENIX Security 2023
---

내 발표가 없는 학회에 참석하게 되었다. 보안 학회는 처음 참석해서 더 배울 것도 많고 새로웠다. 우리 연구실 김태은님이 발표를 너무 잘해내고, 옆 복도 연구실 최민엽님이 우수 논문상을 수상하는 것을 보면서 질투의 동기부여를 다지기도 했다.

## 기계학습과 보안

지난해에 참석한 ESEC/FSE 학회에는 2박 3일 일정 동안 항상 기계학습 세션이 있었다. 이번에 참석한 USENIX Security도 마찬가지였다. 2박 3일 학회 일정 동안 거의 항상 기계학습 관련 세션이 있었는데, 주로 기계 학습 모델이나 학습 기술, 환경, 데이터 등을 공격하거나 이를 방어하는 기술을 다뤘다. 지난 학기에 수강한 "정보보호 기계학습 적용동향" 수업에서 배운 내용과 관련이 있어서 학회에서 발표를 듣는 내내 도움이 많이 되었다.

인상적이었던 발표를 세가지 소개한다.

### Tubes Among Us: Analog Attack on Automatic Speaker Identification[^1]

학회 첫날 첫 세션에서 발표된 논문이었다. 기계 학습을 이용한 음성 인증 시스템을 공격해서 다른 사람의 목소리인 척 시스템을 속이는 기술이었다. 그리고 그 기술의 중요한 아이디어는 기계로 합성한 소리를 사람의 목소리인것처럼 바꿔주는 아날로그 필터인데, 물리적인 튜브였다. 발표자는 실제로 팔뚝보다 좀 더 두껍고 기다란 종이 튜브를 가져와서 보여줬다. 복잡한 기계학습 기반 소프트웨어 시스템이 전원조차 필요 없는 간단한 도구를 이용해서 속일 수 있다는 점이 재미있었고, 그 아이디어가 사람의 신체 구조를 모방하는 데서 왔다는 점도 흥미로웠다.

[^1]: Ahmed, Shimaa, et al. *Tubes Among Us: Analog Attack on Automatic Speaker Identification.* 32nd USENIX Security Symposium (USENIX Security 23). 2023.

### The Case for Learned Provenance Graph Storage Systems[^2]

이 논문은 DNN 모델을 학습할 때 일부러 과적합을 일으켜서 스토리지로 사용하는 기술이다. 일반적으로 그래프 형태로 저장되는 데이터를 sequence-to-sequence 과제의 입출력으로 바꾸고, LSTM 모델에 학습시켰다. 전통적인 RDB, 그래프 데이터베이스인 Neo4J와 비교했는데 저장 공간과 쿼리 속도 면에서 월등히 좋았다고한다. DNN의 단점인 과적합 문제를 극단적으로 일으켜서 오히려 긍정적으로 활용했다는 점이 인상적이다. 보안 기술 중에는 이렇게 기술의 특징을 다른 용도로 활용하는 아이디어가 많은 것 같다.

[^2]: Ding, Hailun, et al. *The case for learned provenance graph storage systems.* 32nd USENIX Security Symposium (USENIX Security 23). 2023.

### Extracting Training Data from Diffusion Models[^3]

마지막 날 아침에 있었던 Nicholas Carlini의 논문 발표였다. 지난 학기 수업에서 대단히 많이 언급된 이름 이었기 때문에 궁금해서 발표를 들으러 갔었는데, 유명인의 발표가 어떤 것인지 볼 수 있었다. 우선 발표자료가 마케팅 발표자료처럼 생겼다. 자세한 설명이 거의 없고 키워드 중심으로 구성되었는데, 청중이 자신의 발표에 매우 집중할 것을 확신하는 것 같았다. 그리고 자신의 지난 논문을 설명 없이 언급했다. 모두가 자신의 지난 연구를 이미 잘 알고 있을 것이라고 가정하고 있었다. 마지막으로 질문이 굉장히 많았다. 발표가 끝나고 세션 체어가 질문을 받겠다고 말을 꺼내기도 전에 질문 마이크 앞에 이미 줄이 길게 나 있었다. 질문자들은 이미 발표 논문을 완벽하게 숙지하고 있었는지, 발표 내용에 없었던 부분에 대해서 질문하기도했다. 마이크 앞에 줄 선 모든 사람이 질문을 하지는 못했기 때문에 발표자가 발표장 밖으로 나갈 때 우르르 따라나가는 사람도 많았다. 신기하고 인상적인 장면이었다.

[^3]: Carlini, Nicolas, et al. *Extracting training data from diffusion models.* 32nd USENIX Security Symposium (USENIX Security 23). 2023.

## 그 외

### 보안 학회에서 정적 분석

기계 학습 세션 외에도 흥미로워보이는 세션들에 참석했는데 대체로 정적분석이 언급되는 발표가 한두개씩 포함되어있었다. 그곳에서는 정적분석을 "느리다" 와 "복잡하다", 하지만 "이론적으로 검증된 기술이다"를 대체하는 표현으로 사용하는 것 같았다. 예를 들어서 질문자가 어떤 부분은 정적분석을 사용하면 더 잘 해결할 수 있을 것 같다고 제시하면, 발표자가 그렇게 많은 노력을 들여서 얻을만큼 중요한 정보가 아니었다고 답하는 식이다. 발표에 참여하는 사람들이 정적분석을 알고 있고, 기술에 대해서 같은 이미지나 개념을 공유하고 있다는 게 반갑고 재미있었다.

### 만남과 교류

이번 학회에서는 자연스럽게 다양한 사람과 만나서 이야기를 나누게 되었다. 지난 ESEC/FSE에서 만났던 사람을 둘이나 다시 만났다. 두 명 모두 졸업하고 직장을 구하는 중에 학회에 오게 되었다고 했는데, 그래서인지 활발하게 사람들을 만나고 다니면서 중간에 나를 다시 마주칠 때 사람을 소개해주기도 했다. 그 덕분에 많은 사람들과 인사해 볼 기회가 있었다. 혼자 있을 때면 여교수님들이 와서 인사하고 내가 어떤 연구를 하고 있는지 물어봐주기도 했다. 여학생이 적은 만큼 학회장에 잘 적응할 수 있도록 신경써주는 것 같았다. 해외 학회인데도 한국인 학생들을 많이 만날 수 있어서 좋았다. 수민의 소개로 하선 박사과정 학생을 비롯해 유니스트 학생들과도 인사하고 같이 관광을 가기도 했다.

지난 7월에 참석했던 워크샵에서 학회에서 만나는 사람들이 1년에 한두번 만날까 말까 한 관계인데 매일 보는 가족보다 내 분야를 더 자세히 알고 있는 사람들이라는 이야기를 들었다. 그래서인지 이번 학회에서는 내 연구를 다른사람에게 소개할 때 더 신경써서 말하게 되었던 것 같다. 학회에서 발표를 하게 되면 좀 더 비슷한 분야의 사람들과 이야기할 수 있게 되지 않을까 기대해본다.

## 마치며

발표 논문이 없는데도 좋은 학회에 참석하고 경험할 수 있도록 기회를 주신 허기홍 교수님께 감사드린다. 그리고 논문 발표를 멋지게 해낸 태은님에게도 감사드린다. 덕분에 처음으로 보안 학회를 경험해볼 수 있었다. 학회 일정동안 함께했던 종찬님, 룸메이트로 일주일 내내 함께했던 수진님에게도 감사한다.

---

#### 참조
