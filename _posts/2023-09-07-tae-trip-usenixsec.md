---
title:  나의 첫 발표하러 간 해외 학회 탐방기
date:   2023-09-07
author: Tae Eun Kim
kor_author: 김태은
tags:
  - Trip
  - USENIX Security 2023
classes: wide
---

| ![](https://lh3.googleusercontent.com/pw/AP1GczNxIO9eW1OPLeXequjC4LiBdsxDDQUBOWdSQfl5qMtakeAwJiJFYy6dDoZqCQSkHdJJfo8Eu-4VgU-PzAyTCwLRjZ2OZNpySg33xnhkqrg3PUWwmvxViihAJ_fqABaPcM_dDK2huNRrmIjog8S8TsoH=w1157-h868-s-no-gm?authuser=2) |
|:--:|
| <b>아쉽게도 유일한 단체사진. 왼쪽부터 나, 종찬님, 허기홍 교수님, 연희님, 수진님.</b>|


<br/><br/>

# 들어가며
꿈에도 그리던 기회가 드디어 왔다. 발표자 자격으로 해외 학회에 참석하는 것이다.
석사 기간동안 연구한 결과를 정리한 논문이 감사하게도 USENIX Security 2023에 받아들여져 미국으로 떠나게 되었다.
사실 과분하게도 이번이 벌써 세번째 참가하는 해외 학회이지만 내 논문을 들고 가는 것은 처음이기에 어느때보다 더 설레였다.
그렇게 허기홍 교수님과 연구실 동료들, 연희님, 종찬님, 수진님과 함께 미국으로 떠나게 되었다.

<br/><br/>

# 목표 세우기
이번 학회는 평소에 세우던 목표보다 높은 우선순위의 목표 하나가 추가되었다. 발표 잘 하기.
다만 이 목표가 너무 부담이 되었는지 발표 전까지 그 외의 것은 전혀 생각할 수 없었다. 다행히 발표를 잘 마치고 나니 마음에 여유가 생겨 목표를 하나 더 챙길 수 있었다.

1. 발표 잘 하기
2. 친구 만들기


<br/><br/>

# 목표 이루기

## 발표 잘 하기

### 준비 과정
나는 정말 발표를 잘 하고 싶었다. 수많은 발표 중 하나로 기억되고 싶은 마음이 전혀 없었고, 가장 기억에 남는 발표를 하고 싶었다. 이왕 하는 거 세계 최고가 되면 좋지 않겠는가? 주어진 기회를 허투루 쓰고 싶은 마음이 전혀 없었기에 발표 준비에 굉장히 많은 공을 들였다.

하지만 나 혼자 준비한 것은 결코 아니다. 공동 저자인 허기홍 교수님과 최재승 교수님, 차상길 교수님의 피드백이 있었고, 연구실 동료들의 피드백, 아내의 피드백도 있었다. 어떠한 과정을 통해 이들의 피드백이 적용되었는지, 그리고 발표를 준비했는지 간단히 적어보려 한다.

1. **발표 초안 작성:** 출장 전 주, 수요일 밤에 초안을 완성하였다. 사실 더 미리 준비하고 싶었는데 다른 급한 일들이 많아 준비가 조금 미뤄지게 되었다. 게다가 지난 2년간 애용하던 발표자료는 구글 슬라이드로 되어 있었고 자료의 내용이 학회 논문 발표에는 적절하지 않았다. 그래서 이번 기회에 애플 키노트로 발표자료를 처음부터 새로 만들었다. 키노트를 쓰는 것 자체가 처음이라 이를 다루는 것도 힘들었지만 논문 발표를 위한 자료를 만든다는 것이 새로운 경험인지라 많이 헤메었다. 기존의 발표는 주로 "이러이러한 연구를 합니다" 정도로 소개하는 수준이었다면, 이번 발표는 "이런 문제가 있었고, 이렇게 풀었습니다"를 구체적이고 명확하게 전달해야 했다. 그래도 어떻게든 내용을 우겨 넣어 초안을 완성하였다.

2. **1차 피드백:** 발표 자료 초안을 공동 저자 교수님들과 공유하였다. 자기 전에 완성하여 공유드리고 목요일 아침에 일어나니 모니터 한 화면 가득 피드백이 와 있었다. 자료 수준이 너무 부족했나 싶어 죄송할 정도였다. 대표적인 문제는 배경 설명이 너무 길다는 점과, 기존의 문제가 명확하게 설명이 안 되어 우리의 접근이 왜 좋은지 잘 안보인다는 것이었다. 그래서 하루 종일 피드백을 적용하여 자료를 수정하고, 퇴근 전 허기홍 교수님께 다시 한번 피드백을 받았다.

3. **2차 피드백 / 1차 리허설:** 우리 연구실은 매주 금요일마다 연구실 세미나를 연다. 이번 주는 내 발표 예행 연습으로 세미나를 진행하였다. 한 번 갈아엎고, 또 전날 밤 늦게까지 다듬은 발표 자료를 가지고 10분 발표를 하였다. 그리고 그 이후 1시간동안 피드백이 진행되었다. 아예 첫번째 슬라이드부터 다시 시작해서 한장, 한장 넘기며 모두의 질문과 코멘트를 받은 결과 또 한번 자료를 갈아엎다시피 했다. 특히 발표 자료를 만드는데에 집중하느라 정작 발표 연습을 잘 못했었는데 중간에 멘붕이 오는 지점이 있었다. 그런데 그 부분이 바로 설명이 애매한 지점이어서 듣는 사람도 뭔가 이상함을 느끼는 것이었다. 그날 세미나는 그렇게 특별히 보강해야 될 지점을 확인하면서 마무리하였다. 그리고 주말 내내 아내를 앉혀놓고 비전문가도 내용을 어느정도 이해할 수 있는 수준으로 발표를 준비하였다.

4. **3차 피드백 / 2차 리허설:** 이번에는 차상길 교수님 연구실에서 출장 전 날, 피자를 먹으며 리허설을 진행한다고 하였다. 감사하게도 나를 초대해주셔서 또 한번의 연습 기회를 얻었다. 차상길 교수님 연구실에는 내 연구를 잘 모르는 분들도 있어 예상 질문을 파악하는 데에 큰 도움이 되었다. 특히 논문을 쓸 때 통계 검증에 도움을 주신 수민님이 질문을 많이 해 주셔서 다시 한 번 감사했다. 차상길 교수님이 세션 체어처럼 진행을 해 주셨는데, 실제로 내 발표가 배정된 세션의 체어가 차상길 교수님이셔서 더욱 실전 같은 리허설이었다. 이후에 피드백을 반영하여 자료를 수정하고, 예상 질문 슬라이드를 준비함으로써 발표 자료 최종본을 완성하였다.

5. **입에 붙이기:** 나는 글로 된 대본을 따로 쓰지 않는 편이다. 다만 머리 속에 대본을 넣고 그대로 하는 것을 선호하는 편인데, 이 방법은 모든 슬라이드와 멘트가 입에 완벽히 붙어야 한다. 그래서 발표 전날까지 매일 연습을 하였고 발표 당일 아침에는 샤워를 하면서 눈을 감고도 머리 속에서 슬라이드를 한장 한장 넘기며 연습을 하는 경지에 이를 수 있었다.

6. **몸과 마음 준비하기:** 나는 이번에 특히 컨디션을 최상으로 유지하고 싶었다. 그래서 미국에 가자마자 시차적응을 위해 멜라토닌 성분의 수면 유도제를 샀고, 소화 불량을 방지하기 위해 밥도 (평소에 비해...) 조금씩만 먹었다. 몸은 그렇게 준비하였고 마음은 그냥 굳세게 먹었다.



| ![](https://lh3.googleusercontent.com/pw/AP1GczPMdDucRDbQMflApdSEWtMVAnnYL5Vnx6e89oX2heoExTZbZ08ZVHuXyprSVL4ahEPj9dRoW3EPtP8hjJ4kghcROexfOoBkvOj57fAI4cx7MtIUBhbQj3OrnOnJ3Wd8BBLStcDHj29nRP9c0-PesyZR=w1157-h868-s-no-gm?authuser=2) |
|:--:|
| <b>내가 여기서 발표한다고??</b>|

### 발표 현장
발표는 학회 둘째날 마지막 세션이었다. 이때쯤이면 사람들의 피로도가 슬슬 정점을 향해 가고 있을 때다. 보통 둘째날 밤에 정점을 찍기 때문에 셋째날에는 사람들이 소리소문없이 사라지기 마련이다. 셋째날은 아니어서 다행이었다. 그래도 혹시나 다들 일찍 저녁 먹으러 가버리진 않을까 하는 걱정을 하며 하루를 보냈다. 나는 세션의 두번째 발표였는데, 첫 발표가 시작할때만해도 발표장에 사람이 별로 없었다. 이왕 열심히 준비한 것, 많은 사람들이 들었으면 좋겠어서 제발 더 오라고 속으로 기도했다. 다행히 첫 발표 중간에 사람들이 점점 들어오더니 내 차례쯤에는 3분의 2 가량의 좌석이 차 있었다.

그렇게 발표를 시작했다. 발표는 준비한대로 흘러가 순조로웠고 사람들도 이해를 잘 한것 같았다. 질문도 두명이나 해 주어서 기쁜 마음으로 답을 하였다. 내용은 다음과 같았다.

1. 데이터 의존성 정보를 활용해서 연관된 함수에만 집중한다고 했는데, 함수 포인터를 안전하게 (Sound) 고려하면 너무 많은 함수들이 고려되는 것 아닌가? 이 질문은 내가 반대로 이해해서 포인터 분석도 하니까 놓치지 않아요!라고 당당하게 대답해 버렸다. 다행히 나중에 따로 만나서 오해를 풀었는데, 그 내용은 후술하도록 하겠다.

2. DAFL의 핵심 요소 두 가지, 선별적 커버리지 기록과 의미 기반 연관성 점수 각각의 기여도가 어떻게 되는가? 아주 훌륭한 질문이었다. 왜냐하면 내가 백업 슬라이드를 준비한 질문이기 때문이다. 슬라이드를 보여주면서 쉽게 대답할 수 있었다.

3. 선별적 커버리지 기록이 성능에 악영향을 준 경우가 있었는가? 이 경우는 논문에 나온 DAFL의 한계에 대한 예시로 설명이 가능했다. 즉, 데이터 의존성 관계로는 포착되지 않는 함수들은 누락되는데 이런 함수들이 목표 지점에 도달하는데 중요한 역할을 할 수도 있다는 것이다.

예상했던 것보다 질문의 수준이 높아서 질문자들에게 정말 고마운 마음이 들었다. 질문은 모두 EPFL의 Matias Payer 교수님 그룹의 사람들이 해 주었다. 아무래도 비슷한 분야에 관심이 있는 사람들이다보니 깊이 있는 질문들이 나온 것 같다.

이렇게 발표는 마무리되었다. 2년간 수고에 대한 충분한 보상이었다.


| ![](https://lh3.googleusercontent.com/pw/AP1GczMtq15qWCXWWUh6dcsSRy9_JeTVHIGxCGSFGgtzLun8YrQp_sNiEzS6G6atdRHLu5Bt9vNvnknr5sU26CSkkcwfrjNPSz7VDHURlEeDGORrQS3ChBiOliXaZgioOpWmOWo1sBHe1PweYrOpNi3jSqvXUA=w1157-h868-s-no-gm?authuser=2) |
|:--:|
| <b>발표 중.</b>|


<br/>

## 친구 만들기
논문 발표를 마친 후, 억눌렸던 네트워킹의 욕구가 마구 샘솟아서 친구를 사귀고 싶다는 생각이 강하게 들었다. 이번에는 특히 퍼징하는 사람들과 얘기하고 알아갈 기회가 있었는데, 너무 좋았다. 그 중 대화를 길게 나눈 두 사람이 기억에 남아 여기 기록을 남긴다. (사실 알게 된 사람이 그 두 사람이 전부다 ㅎㅎ)

한 사람은 현재 EPFL의 Matias Payer 교수님 그룹에서 박사후연구원으로 있는 Flavio Toffalini이다. 서로 발표를 듣고 질문을 주고 받았는데, 넓게 보면 같은 주제의 논문이라 동질감이 들었다. 그런데 마침 둘째날 저녁 포스터 세션에서 이번에 발표한 논문의 포스터 발표를 하고 있는 것이었다. 보통 발표한 논문은 포스터 발표를 잘 안 하는것 같긴 한데 나에게는 좋은 기회였다. 우선 내가 10분짜리 발표를 듣는 것으로는 미처 해결되지 않았던 궁금증을 몇 가지 물어보았다. 역시 이렇게 직접 물어보고 답을 듣는것이 가장 이해가 잘 되는 것 같다. 이번에는 Flavio가 나에게도 질문이 있다고 하며 여러가지를 물어보았다. 그 중에는 내가 발표장에서 제대로 답하지 못한 질문도 있었는데, 이번에는 다행히 제대로 답을 하여 오해를 풀 수 있었다. 각자 논문 외에도 퍼징 이야기도 하고 연구하면서 겪는 어려움도 얘기하고 이런저런 아이디어도 나누었다. 비슷한 분야를 하는 사람을 처음 만났는지라 대화가 너무 재미있고 유익했다. 물론 얘기를 끝내고 나서는 손이 덜덜 떨리고 있을 정도로 긴장하긴 했었다.

또 다른 사람은 CISPA의 Thorsten Holz 교수님 연구실의 박사과정 학생인 Moritz Schloegel이다. 셋째날 아침에 USENIX 슬랙 채널에 DM이 와 있길래 확인해보니 어제 발표가 너무 좋았다고, 혹시 오늘 시간되면 잠깐 얘기할 수 있겠냐는 내용이었다. 누군가 싶어 홈페이지를 찾아보니 어제 발표를 마치고 자리에 앉을 때 옆에서 발표 잘했다고 칭찬해준 사람이었다. 논문 목록도 쭉 읽어보니 내가 봤던 논문들도 몇 편 있는 사람이었다. 이왕 만나는거 준비 좀 하고 싶어서 나도 질문을 좀 준비해서 만나러 갔다.  Moritz는 우선 내가 WindRanger를 비교 대상으로 썼다 했는데 어떻게 빌드했는지 물어보았다. 이건 내가 쉽게 도와줄 수 있어서 나중에 메일을 달라고 했다. 그리고 내가 앞으로 뭘 하고 싶은지 물어보길래 염두에 두고 있는 연구 방향을 같이 얘기했다. 전날 본 발표 중 이 사람이 2저자로 참여한 논문도 있었는데 마침 궁금했던게 있어 물어보았고, 그 이후에도 퍼징 관련해서 이런저런 얘기를 나누었다. 굉장히 인상 깊었던 것은, 자신이 이번에 S&P에 내는 논문에 대해 얘기를 해 주려다가 먼저 내가 혹시 논문 심사위원인지 확인을 하는 것이었다. 나는 미처 생각하지 못한 부분이었는데, 연구 윤리를 지키기 위해 조심하는 모습을 보며 멋있다고 생각했다. Moritz와는 길게 얘기하진 못했지만 서로 응원하며 다음에 또 보자는 인사와 함꼐 헤어졌다. 물론 다녀와서 WindRanger건으로 메일은 주고 받았다.

두 사람과 얘기를 할 때 공통적으로 나온 얘기는 퍼징 자체의 성능은 이제 수렴하였고, 이제는 다른 기술과의 조합이나 특정한 도메인을 위한 퍼징 기법을 연구하는 것이 필요하다는 것이었다. 그래서 내가 현재 하고 있는 것, 정적 분석과 퍼징의 결합에 대한 자신감을 더 가질 수 있었다. 다들 성격도 좋고 친절했어서 다음에 또 만나 얘기를 나누고 싶은 사람들이었다.


<br/><br/>

# 재밌었던 발표들

## 퍼징 세션
이번에는 퍼징 세션이 무려 5개나 있었다. 물론 모두 내 관심사는 아니었지만 아무튼 굉장히 많은 논문들이 있었다. 그 중에서 내가 재밌게 들었던 발표들을 소개하려 한다.


**FISHFUZZ: Catch Deeper Bugs by Throwing Larger Nets<sup>[1](#fishfuzz)</sup>** \
이 논문은 지향성 퍼징과 비슷하지만, 저자의 말로는 프로그램 안전벨트(Sanitizer)에 집중하는 퍼징 (Sanitizer-guided Fuzzing)이라고 한다. 지향성 퍼징은 하나에서 많아야 10개 이하의 목표 지점을 대상으로 하지만 FISHFUZZ의 경우는 프로그램 안전벨트가 채워진 모든 지점, 수천개가 넘는 지점을 목표로 한다. 따라서 효율성을 위해서는 지향성 퍼징과는 조금 다른 접근을 취해야 한다. 특히 목표 지점과의 거리를 계산할 때, 각 프로그램 **지점**에는 모든 목표 지점과의 거리를 미리 계산해두지만 각 **시드**는 자기가 지난 프로그램 지점들에서 가장 가까운 목표 지점과의 거리 하나만을 가진다. 따라서 목표 지점의 개수와 상관없이 시드는 항상 하나의 거리 점수를 가지게 되고 이는 퍼징 과정에서 필요한 시드 거리의 비교 연산 비용을 크게 절약해준다. FISHFUZZ는 퍼징 과정을 탐험(exploration)과 탐색(exploitation)의 단계로 나누어 진행하는데, 탐험 단계의 경우 일반적인 퍼징과 동일하게 진행된다. 탐색 단계의 경우 조금 재미있는데, 먼저 탐험 단계에서 한번도 도달하지 못한 목표 지점들은 무시한다. 그리고 한번이라도 도달한 목표 지점들 중에서는 상대적으로 덜 자주 도달한 목표 지점에 집중하여 퍼징을 진행한다. 이렇게 FISHFUZZ는 최대한 많은 목표 지점에 균등하게 도달하도록 하는 것을 목적으로 한다. 앞서 만난 Flavio가 저자로 참여한 논문이다.

**Fuzztruction: Using Fault Injection-based Fuzzing to Leverage Implicit Domain Knowledge<sup>[2](#fuzzstruction)</sup>** \
퍼징은 무작위로 입력을 생성하는 기법이다. 따라서 단순한 입력을 받는 프로그램에 대해서는 잘 동작하지만, 구조화가 잘 되어있는 입력을 받는 프로그램에 대해서는 비교적 성능이 떨어진다. 예를 들어 JPEG 파일을 입력으로 받는 프로그램의 경우, JPEG 파일의 포맷이 갖춰진 입력을 주어야 하기 때문에 퍼저가 이를 직접 생성하거나 변형하려 한다면 포맷이 어그러져 유효하지 않은 입력이 만들어질 확률이 크다. 여기서 이 논문은 재미있는 접근을 취한다. 바로 입력 파일이 아닌, 입력 파일을 생성하는 프로그램을 변형하는 것이다. 예를 들어 JPEG 파일을 생성하는 프로그램이 있다고 하면 이 프로그램을 변형시켜서 핵심적인 포맷을 맞지만 어딘가 이상한 입력을 만들도록 하는 것이다. 즉, 생성자 프로그램이 가지고 있는 도메인 지식을 활용하는 것이다. 굉장히 기발한 아이디어였고 논문도 잘 썼는지 최우수논문상을 받았다. 앞서 만난 Moritz가 2저자로 참여한 논문이다.


**autofz: Automated Fuzzer Composition at Runtime<sup>[3](#autofz)</sup>** \
세상에는 굉장히 다양한 퍼저들이 있다. 어떤 퍼저가 가장 좋은 퍼저일지는 각 프로그램마다, 각 시점마다 다를 것이다. 이 논문은 자동으로 매 순간 최적의 퍼저를 선택하여 궁극적으로는 다양한 퍼저들의 장점만 살린 하나의 퍼저처럼 동작하는 기술을 제안한다. 구체적으로는 모든 퍼저를 조금씩 돌려보고 성능을 측정하는 준비 단계, 그리고 그중 제일 결과가 좋은 퍼저에 집중하는 집중 단계를 왕복하며 그때 그때 최적의 퍼저를 선택한다. 이 때 시드 동기화 (Seed Synchronization)이라는 기법을 사용하면 각 퍼저들이 서로의 진행 상황을 공유할 수 있다고 하는데 이건 처음 듣는 거라서 신기했다. 시드 동기화가 있기 때문에 최적의 퍼저가 바뀌어도 이전 시점의 최적의 퍼저가 달성한 진행 상황을 잃지 않고 이어서 진행할 수 있게 되는 것이다.


**Systematic Assessment of Fuzzers using Mutation Analysis<sup>[4](#mutation)</sup>** \
퍼저들의 성능 평가를 위해 변형 분석(Mutation Analysis)을 활용하는 논문이다. 퍼저의 성능을 평가할 때 가장 좋은 지표 중 하나는 얼마나 많은 결함을 발견했는지인데, 결함이라는 것이 흔하지도 않고 정의하기도 어렵다. 따라서 대상 프로그램을 의도적으로 변형시켜 결함을 삽입한 다음 이를 퍼저가 발견하는지를 측정하는 방식을 사용하는 것이다. 사실 기존의 일반 프로그램에 인위적으로 결함을 삽입하여 만든 벤치마크와 본질적으로 무엇이 다른지는 잘 와닿지 않았다.

이 외에도 드라이버 퍼징 논문이 참 많았는데, 커널 퍼징과 함께 잘은 모르지만 왠지 해보고 싶은 것이 드라이버 퍼징인 것 같다. 잘 몰라서 막연하지만 그래도 실용적인 느낌이 나서 그런 것 같기도 하다.


<br/>

## 그 외의 재미있는 세션 / 발표

**괴롭힘(Interpersonnal Abuse) 세션**
보안 이슈로 인해 발생하는 다양한 종류의 괴롭힘에 대한 세션이었다. 예를 들어 IoT 장치를 이용한 케이스가 많다고 한다. IoT 장치를 통해 피해자를 감시 하거나 조명/냉난방을 조작해 위해를 가하는 등의 공격이 가능하다. 이 세션에서는 전부 이러한 괴롭힘이 어떻게 일어나는지, 어떻게 분류할 수 있는지 등 기술적인 내용보다는 서베이 형식의 논문이 발표되었다. 그래서 그냥 이런게 있구나 정도로만 들었다. 다만 여기서 느낀 점이 한 가지 있었다. 이런 종류의 피해는 주로 여성들이 겪는다고 하는데, 이번 세션의 발표자들이 전부 (스스로 분류하기로는) 여성이었다. 그래서 커뮤니티의 구성원이 다양해야 다양한 집단의 문제를 해결할 수 있다는 것을 처음으로 체감했다.

**TPatch: A Triggered Physical Adversarial Patch<sup>[5](#tpatch)</sup>**
영상 처리 인공지능을 속이는 공격 기법이다. 이 논문은 재미있게도 특정 타겟만 공격하는 기법을 제안했다. 도로에서 표지판을 잘못 인식하게 만들고 싶은데, 다른 차들은 공격하지 않고 특정 차량만 공격해서 사고가 나게 하고 싶다면 어떻게 할까? 방법은 다음과 같다. 우선 표지판에 영상처리 모델을 속이는 이미지를 미리 부착한다. 단, 이 이미지는 그 자체로는 아무 효과가 없다. 이 때, 목표 차량이 지나갈 때 초음파를 쏴서 목표 차량의 카메라가 특정 방향과 진폭으로 흔들리게 한다. 그러면 표지판에 부착된 이미지가 카메라의 흔들림에 의해 영상처리 모델을 속이는 숨겨진 효과를 발휘하게 된다. 이렇게 하면 특정 차량만 공격할 수 있게 된다. 무슨 공상과학 영화에 나올법한 공격 기법이라서 신기했다. 다만 실험은 핸드폰 카메라와 철제 프레임으로만 이루어진 자동차 모형을 가지고 진행되어서 아직 실제로 적용되기는 어려울 것 같다.

**Glaze: Protecting Artists from Style Mimicry by Text-to-Image Models<sup>[6](#glaze)</sup>**
요즘은 인터넷에 그림을 그려 올려 자신을 홍보하고 그런 그림으로 생계를 유지하는 화가들이 많다고 한다. 그런데 이런 사람들의 작품들이 무단으로 인공지능의 학습 데이터로 들어가게 되고, 그렇게 학습된 인공지능 모델은 해당 화가의 화풍을 그대로 따라할 수 있다고 한다. 이런 일들이 실제로 일어나고 있고, 이를 막기 위한 기술이 바로 이 논문에서 제안하는, 그리고 이미 상용화되어 있는 Glaze다. Glaze 간단히 말해 인공지능 모델이 화가의 그림을 왜곡해서 인식하게끔 노이즈를 섞는 것이다. 이 때, 이 노이즈는 사람 눈으로는 구분할 수 없지만 인공지능 모델에게는 그림이 전혀 다른 그림으로 보이게 하는 효과를 준다. 발표 구성이 굉장히 독특했는데 마치 세바시나 TED 발표같았다. 한 명의 실제 화가의 사례를 들면서 그 화가의 어린 시절부터 시작하는 구구절절한 사연을 들려주었다. 기술적인 얘기는 거의 없는 상당히 감성적인 발표였는데, 보안 하는 사람들에게는 잘 먹히지 않은 것 같았다. 첫 질문이 "그래서 정확히 뭘 어떻게 한거죠?"였고 거기에 동의하는지 많은 사람들이 웃었다. 발표 자체는 훌륭했는데 청중이 원하는 발표가 아니었던 것 같다. 발표 잘 하는게 참 어렵다는 생각을 다시 하게 되었다. 그렇지만 논문은 훌륭했는지 최우수논문상을 받았다.

| ![](https://lh3.googleusercontent.com/pw/AP1GczMZ8szdDXNOO5Yo0RUF1k0HCzw4qzJDT9MBN4klJSRkCtMRF_haTNmv2v-iMNTcZDB5NhoFoztGtZ8hQC4hFuuzm7YSApOyT28yPwOHrcV8etjK7aX2dSjE132ZGN9Nrsc7yLFR3Rihzzv_NzBZisvH=w1443-h750-s-no-gm?authuser=2) |
|:--:|
| <b>Glaze [홈페이지](https://glaze.cs.uchicago.edu/).</b>|


<br/><br/>

# 잡다한 이야기

### **수염**
해외 학회에서 강렬한 인상을 주고 싶어 수염을 길렀는데, 돌아와서 사진을 정리하다보니 왠지 성공한 것 같다는 느낌이 든다.

| ![](https://lh3.googleusercontent.com/pw/AP1GczO2w6o4jrJ3uA2XVIP091nNiy08c3qTGnY_G6wP-ROXRPTbVD9i5O5oR_j2ViEjtl9OzpTGJE6eLuhr_fuzCU8D7M9oEyhfHgE5HnigLVTenohs6JSdyKZFmIppXNQM-7lKdiG32K4z0yG6RsumxpxD=w1302-h868-s-no-gm?authuser=2) |
|:--:|
| <b>강렬한 인상.</b>|


### **LA의 날씨**
8월의 캘리포니아는 푹푹 찔 줄 알았던 나에게 LA의 날씨는 상당한 충경이었다. 태양은 여전히 뜨겁지만 바람은 시원했고, 낮에는 그늘에 있으면 전혀 덥지 않았다. 아침, 저녁으로는 쌀쌀한 정도였다. 한국의 습한 날씨를 뒤로 하고 와서 그런지 더욱 쾌적한 날씨였다.

### **엘리베이터 할당제**
학회장의 엘리베이터는 조작이 특이했다. 엘리베이터 내/외부에 버튼이 하나도 없고 모든 엘리베이터를 통틀어 이 조작판 하나만 있다. 원하는 층을 누르면 몇번 엘리베이터를 타야하는 지 알려준다. 알려준 엘리베이터를 타면 원하는 층에서 내려준다.

| ![](https://lh3.googleusercontent.com/pw/AP1GczPrcTPrJrrdEBnjU2ApwyyJYr1xJROP_0pmGAkndgxhvJq4ixF9GMTISjF66eVwothorzJ7adIXY2-uDKvmfegFWReLH6c7fpeLXj3uzGlXFaTz7vxwI0q9URDQn3oemI_6a7dr66rUXIWaHJtVMHU3=w651-h868-s-no-gm?authuser=2) |
|:--:|
| <b>엘리베이터 조작판.</b>|

### **어마어마한 논문 수**
이번 USENIX Security 학회는 총 1444편의 제출된 논문 중 422편을 승인했다고 한다. 이걸 3일안에 모두 발표하느라 매일 하루 종일 6개의 세션이 병렬로 진행되었다. 이번에는 학회 일정이 조정되면서 이전보다 승인률(acceptance rate)이 올라갔다고 한다. (정확히 왜 그런지는 기억이 안 난다)

| ![](https://lh3.googleusercontent.com/pw/AP1GczOaCHOuyRv2E3cgBciqStQEuiQ95EuWZNWxox9R6SnBdq0gOOVa_E5d8DhJlf7po57pP6WQ63619kBsJazCbGa-EEWgP7Et8yRq-keoedqTqIcdZ1OCnPp7WWfCTdtDIJdg8rSY1tOwYPbHgGP-FtTi=w1157-h868-s-no-gm?authuser=2) |
|:--:|
| <b>논문 수.</b>|

### **가족에게 감사**
개회식에서 사용된 슬라이드 중 모두의 가족에게 감사한다는 슬라이드가 있었다. 학회 위원장 두 분 모두 이번 학회를 준비하는 기간 동안 자녀가 태어났다고 했다. 나도 문득 돌아보니 논문 쓰는 나를 위해 배려해주고 양보해주었던 가족들이 생각났다. 최근 함께 시간을 많이 못 보낸 (한국에 두고 온) 아내에게도 미안하고, 자주 찾아뵙지 못한 부모님과 장인장모님께도 죄송한 마음이 들었다.

| ![](https://lh3.googleusercontent.com/pw/AP1GczM7vMP2QffZjpm3emWqY7RkoLdZI3btNuxf_2hNKIpnOmPpEMEsUrbHkE_b520azGJ6T0mZTRG0xK7_b-mrGPFjpQLMr1kkDfAcrrlqCko-jP6OQf9t-B5ZatGpzR9H8WfwmmcjTMC6WtK5kty65XKG=w1157-h868-s-no-gm?authuser=2) |
|:--:|
| <b>고마워요 우리 가족.</b>|


### **게티 센터(Getty Center)**
연희님 제안으로 마지막날 LA에 위치한 게티 센터에 방문했다. 미술관처럼 조성된 곳이었는데 볼만했다. 다양한 작품들을 봤는데, 특히 모네의 그림들이 기억에 남는다. 사진기의 등장으로 보이는 것과 똑같이 그리는 의미가 사라지자 모네는 기존에 그림에 담지 못하던 것, 인상을 담기 시작했다. 연구도 비슷하지 않을까? 다른 기술의 발전으로 내가 하던게 의미 없어지는 순간이 올 수 있겠지만, 그럴 때에도 내가 여전히 할 수 있는 일이 있을 것이다. 오히려 그 때 찾은 일이 더 가치 있을지도 모른다. 좋은 깨달음을 얻었다. 하지만 셀카는 고흐 그림과 함께 찍었다. 그게 더 유명하니까.

| ![](https://lh3.googleusercontent.com/pw/AP1GczPj4gKn7cemA875Edl2nW5ErcGEPSxOFbgZVNUNEmbYu5TisPW3pz_F1kaIQEZHNwtIrDKWpjvj29gxgrE8sshRJMkVqUbh42FRjfMs7-sL6t2YM5N4_MvKta0cp_UvIhKz0Jb5FY0HeeBZnPDV1PJ7=w1157-h868-s-no-gm?authuser=2) |
|:--:|
| <b>제일 인기가 많았던 고흐의 그림, Irises.</b>|



### **산타모니카 해변**
산타모니카 해변에도 갔다. 작년 CCS 학회도 LA에서 했는데, 학회 중에 만난 친구가 자기는 오늘 산타모니카 해변에 놀러갈 거라고 해서 부러웠던 기억이 있다. 그래서 이번에는 나도 갔다. 가보면 굉장히 큰 해변이다. 모래 사장도 바다쪽으로 깊게 뻗어 있고, 해변의 길이도 끝이 안 보일 정도이다. 즐겨보던 미드인 모던 패밀리에 나오는 놀이공원이 있어 반가운 마음이 들었다.

| ![](https://lh3.googleusercontent.com/pw/AP1GczOvr6DpiXyZOq2dshlKJ8fJE9ynf_ipFVZEetTY0wcjM3O6KTR-HV0-uf5RIbTHAlUxs_4wfnh42ovj8gm3i5KWSVZH_sxrWiR2CamLDy5Az0TtLmYQGbuE3Ai_wvaRYFKY4WSeIFK5YQwzRqJdTbEh=w1157-h868-s-no-gm?authuser=2) |
|:--:|
| <b>산타모니카 해변에서 연구실 동료들과.</b>|



### **미국의 음식**
이번 학회는 밥을 잘 안 줘서 많이 사먹었다. 주로 근처 멕시코 음식점에서 내 팔뚝만한 부리또를 먹었는데 질릴 때쯤 출장이 끝나서 다행이었다. 그리고 언제부터인지 미국에 가면 첫 식사는 스테이크라는 전통이 생긴 듯 한데, 이번에도 첫 식사는 스테이크를 먹었다. 그 외에도 다양한 음식들의 사진을 공유한다.

| ![](https://lh3.googleusercontent.com/pw/AP1GczOq29zAjCDxKFBqWP1Qsi9-RuVLfUvQS95D_crcdQAuJIk6VrJoWQ-JlIv2h8phEdAkJnx3D_JTD3H4L72ZAd6nRu8Awo7yb1x3ylAz9yrEZaW8C4ztUbE69wnG_eRqmC-SAOdBe121UZninz4xdvWl=w651-h868-s-no-gm?authuser=2) |
|:--:|
| <b>미국 스테이크.</b>|

| ![](https://lh3.googleusercontent.com/pw/AP1GczODCkrrWZ9lHtHMCrdol8NTk54q4WUwBOBNgapT8-tFVvGQqIHWGg1r630aCApKyYouBzt4vaFIn_UiZCR4vCJzSM6VCj24bzjL7Q7sNio4yE4RChRmek4vzZ1FDqURN1jD51-1g0Q0yxoejozzm_hv=w651-h868-s-no-gm?authuser=2) |
|:--:|
| <b>메타에서 준 밥. 맛있었다.</b>|

| ![](https://lh3.googleusercontent.com/pw/AP1GczO1wwvdC2xmw7pIpW1xmOvH0kSL_gQwqrlagPn8QUQxrHTNZEJLkafLdWWeVTuVW3BpGCx9LIU4dBZZqSSbNpiGJylZyXvm1ttax41VNmBPZVITKvTfFN6YfxdxH76PGxLpzvyUwDEqnIgs3eE_AudS=w651-h868-s-no-gm?authuser=2) |
|:--:|
| <b>3번 먹은 팔뚝만한 부리또.</b>|

| ![](https://lh3.googleusercontent.com/pw/AP1GczPlCn_SqiYCgBEfxXUj6MeB_WKKnkA_hczEtL0XbUnMEnQAKaacRIQo7HAdlgl4sslLOxIBgRIRsb4wtzoQX7dIOcNobPZjX3y1sMonnxoblf3evmkV6LNfhQmMVvJCPFvLlElOarNIIGbL7RpjCF6i=w651-h868-s-no-gm?authuser=2) |
|:--:|
| <b>싸고 맛 좋은 인앤아웃 버거 + 끈끈한 밀크쉐이크.</b>|

| ![](https://lh3.googleusercontent.com/pw/AP1GczMSr2Ovp3lwrhYQ6cAXHOYAA56drR0yce_OYDY789RtyXwg0YDBH-2hEsTea4V8dFACIufRPlvFhhX-f5Ng-bMWlApxd8Ck60RRNX9AOdbKfvH7L1IiXND2iNeUaDXovD5Qh4QL3UJePJVkSdpKO4hT=w651-h868-s-no-gm?authuser=2) |
|:--:|
| <b>드디어 먹어본 오렌지치킨과 그 친구들.</b>|




### **북두칠성**
돌아오는 비행기에서 창 밖을 내다보았는데 북두칠성이 눈높이에 있어서 깜짝 놀랐다.

| ![](https://lh3.googleusercontent.com/pw/AP1GczNZ9U2dcviPTSSiY7DPC-nX2Dm0qK_fHmSMNtvEuoc_yf-CSkuV5cqHNkGNRsCEalC-6PAOUTwUqoW-fuYGA_EM6cya2zYJb2pkyCBbOVS1zWxEU7hjgJ2LJF6Yk3x8ZUWWWkinphZll22Oa5AIw9ji=w651-h868-s-no-gm?authuser=2) |
|:--:|
| <b>눈앞의 북두칠성.</b>|


<br/><br/>

# 돌아오며
내 논문을 발표하는 감격스러운 출장이었다.
하지만 이제 고작 데뷔한 것에 불과하니 열심히 해서 얼른 또 좋은 성과를 내고 싶다.
항상 세계 최고가 되도록 격려해주시고 지도해주시는 허기홍 교수님께 감사드린다.
그 가르침 덕분에 훌륭한 연구와 발표를 할 수 있었다.
또 함께 학회를 즐기고 발표를 응원해준 동료들 덕분에 더 즐거운 출장이 된 것 같다.
마지막으로 출장 준비를 잘 도와 주신 나은진 선생님께 감사드리며 글을 맺는다.

<br/><br/>
<br/><br/>
<br/><br/>

----


### 각주

[<a name="fishfuzz">1</a>] Han Zheng et al. "FISHFUZZ: Catch Deeper Bugs by Throwing Larger Nets" USENIX Security (2023) \
[<a name="fuzzstruction">2</a>] Nils Bars et al. "Fuzztruction: Using Fault Injection-based Fuzzing to Leverage Implicit Domain Knowledge" USENIX Security (2023) \
[<a name="autofz">3</a>] Yu-Fu Fu, Jaehyuk Lee, and Taesoo Kim "autofz: Automated Fuzzer Composition at Runtime" USENIX Security (2023) \
[<a name="mutation">4</a>] Philipp Görz et al. "Systematic Assessment of Fuzzers using Mutation Analysis" USENIX Security (2023) \
[<a name="tpatch">5</a>] Wenjun Zhu et al. "TPatch: A Triggered Physical Adversarial Patch" USENIX Security (2023) \
[<a name="glaze">6</a>] Shawn Shan et al. "Glaze: Protecting Artists from Style Mimicry by Text-to-Image Models" USENIX Security (2023)