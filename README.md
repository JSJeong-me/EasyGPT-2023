# (비전공자도 이해할 수 있는) 생성형 AI 이해와 업무 활용

### 강의교안:        https://buly.kr/BpBeaBQ
### WorkSheet:        https://buly.kr/HHYzhe2



`````
    제목:  '(비전공자도 이해할 수 있는) 생성형 AI 이해와 업무 활용'
    
    Part 1: 생성형 AI의 이해
    1. 생성형 AI의 작동 원리
    2. 원하는 답을 얻기 위한 Temperature와 Top P 설정
    3. 프롬프트란?
    
    Part 2: 생성형 AI의 업무 활용(기초)
    1. 정보 압축과 요약 (Summarization)
    2. 분류와 응용 (Classification)
    3. 정보 추출 (Extraction)
    4. 글쓰기 (Writing)
    5. 아이디어 도출 (Ideation)
    6. Google Sheets(엑셀) 와 Docs(문서) 연동
    
    Part 3: 생성형 AI의 업무 활용(심화)
    1. API활용
    2. 영상 콘텐츠 생성
    3. Python 코딩
    4. 데이터 분석
    5. 공문서 작성(예제)
    6. 재무제표 분석(예제)

`````
`````
    Google Chrome 확장 프로그램 가기 ->  https://workspace.google.com/marketplace
    오늘 사용할 확장프로그램
    1. ChatGPT File Uploader ->   https://chrome.google.com/webstore/detail/chatgpt-file-uploader-ext/becfinhbfclcgokjlobojlnldbfillpf
    2. 프롬프트 지니: ChatGPT 자동 번역기 ->   https://chrome.google.com/webstore/detail/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8-%EC%A7%80%EB%8B%88-chatgpt-%EC%9E%90%EB%8F%99-%EB%B2%88%EC%97%AD%EA%B8%B0/lhkgpdljnlplgbkonflbhifackjhjmdj?hl=ko
    3. ChatGPT in Google Sheets™ and Docs™ ->  https://workspace.google.com/marketplace/app/gpt_for_sheets_and_docs/677318054654
    4. Voice Control for ChatGPT ->     https://chrome.google.com/webstore/detail/voice-control-for-chatgpt/eollffkcakegifhacjnlnegohfdlidhn

`````
`````
    ChatGPT Plugins  ->     https://openai.com/blog/chatgpt-plugins
    1. AskYourPDF ->     https://askyourpdf.com/
    2. VideoInsights.io ->   https://www.videoinsights.io/
    3. Web Requests ->    https://www.whatplugin.ai/plugins/web-requests
    4. Wolfram ->     https://www.wolframalpha.com/
    5. Browsing ->    https://openai.com/blog/chatgpt-plugins#browsing
    6. Advanced data analysis
          Solving mathematical problems, both quantitative and qualitative
          Doing data analysis and visualization
          Converting files between formats

`````

# 엔트로피란?

## 서론

이 보고서는 엔트로피에 대해 설명하고자 하는 목적으로 작성되었습니다. 엔트로피는 고등학생들을 대상으로 한 기술 문서이며, 엔트로피의 개념과 응용 분야에 대해 자세히 다루고 있습니다.

## 1. 엔트로피의 개념

### 1.1 엔트로피란 무엇인가?

엔트로피는 물리학과 정보 이론에서 사용되는 개념으로, 시스템의 무질서함을 나타내는 척도입니다. 엔트로피는 주어진 시스템의 상태에 대한 불확실성을 측정하는 것으로 생각할 수 있습니다. 엔트로피가 높을수록 시스템은 더 많은 무질서한 상태를 가지고 있습니다.

### 1.2 엔트로피의 수학적 정의

엔트로피는 주어진 시스템의 확률 분포에 기반하여 계산됩니다. 엔트로피는 다음과 같은 수식으로 표현됩니다:

H(X) = -Σ P(x) * log2(P(x))

여기서 H(X)는 시스템 X의 엔트로피를 나타내며, P(x)는 시스템 X의 각 상태 x의 확률을 나타냅니다. 이 수식은 정보 이론에서 가장 널리 사용되는 엔트로피 계산 방법입니다.

## 2. 엔트로피의 응용 분야

### 2.1 열역학에서의 엔트로피

열역학에서 엔트로피는 에너지의 분산과 관련된 개념으로 사용됩니다. 엔트로피가 증가할수록 에너지는 더 많은 형태로 분산되고, 시스템은 더 많은 무질서한 상태를 가지게 됩니다. 열역학에서 엔트로피는 열역학 제2법칙의 핵심 개념 중 하나입니다.

### 2.2 정보 이론에서의 엔트로피

정보 이론에서 엔트로피는 정보의 불확실성을 측정하는 척도로 사용됩니다. 엔트로피가 높을수록 정보의 불확실성이 더 크며, 엔트로피가 낮을수록 정보의 불확실성이 적어집니다. 정보 이론에서 엔트로피는 데이터 압축, 암호화, 통신 등 다양한 분야에서 중요한 개념으로 사용됩니다.

## 결론

이 보고서에서는 엔트로피의 개념과 응용 분야에 대해 설명하였습니다. 엔트로피는 시스템의 무질서함을 나타내는 척도로 사용되며, 열역학과 정보 이론에서 중요한 개념입니다. 엔트로피의 이해는 고등학생들에게 과학과 기술의 깊은 이해를 제공할 수 있을 것입니다. 


-------

# 엔트로피란?

## 서론

이 보고서는 초등학생들을 대상으로 엔트로피에 대해 설명하는 목적으로 작성되었습니다. 엔트로피는 물리학과 정보 이론에서 사용되는 개념 으로, 시스템의 무질서함을 나타내는 척도입니다. 이 보고서에서는 엔트로피의 개념과 응용 분야에 대해 자세히 다루고 있습니다.

## 1. 엔트로피의 개념

### 1.1 엔트로피란 무엇인가?

엔트로피는 시스템의 무질서함을 나타내는 개념입니다. 시스템의 엔트로피가 높을수록 시스템은 더 많은 무질서한 상태를 가지고 있습니다. 예를 들어, 방 안에 놓인 블록들이 무작위로 흩어져 있는 경우와 정렬되어 있는 경우를 생각해보면, 블록들이 무작위로 흩어져 있는 경우가 더 무질서한 상태이고 엔트로피가 높다고 할 수 있습니다.

### 1.2 엔트로피의 수학적 정의

엔트로피는 주어진 시스템의 확률 분포에 기반하여 계산됩니다. 엔트로피는 다음과 같은 수식으로 표현됩니다:

H(X) = -Σ P(x) * log2(P(x))

여기서 H(X)는 시스템 X의 엔트로피를 나타내며, P(x)는 시스템 X의 각 상태 x의 확률을 나타냅니다. 이 수식은 정보 이론에서 가장 널리 사용되는 엔트로피 계산 방법입니다.

## 2. 엔트로피의 응용 분야

### 2.1 열역학에서의 엔트로피

열역학에서 엔트로피는 에너지의 분산과 관련된 개념으로 사용됩니다. 엔트로피가 증가할수록 에너지는 더 많은 형태로 분산되고, 시스템은 더 많은 무질서한 상태를 가지게 됩니다. 열역학에서 엔트로피는 열역학 제2법칙의 핵심 개념 중 하나입니다.

### 2.2 정보 이론에서의 엔트로피

정보 이론에서 엔트로피는 정보의 불확실성을 측정하는 척도로 사용됩니다. 엔트로피가 높을수록 정보의 불확실성이 더 크며, 엔트로피가 낮을수록 정보의 불확실성이 적어집니다. 정보 이론에서 엔트로피는 데이터 압축, 암호화, 통신 등 다양한 분야에서 중요한 개념으로 사용됩니다.

## 결론

이 보고서에서는 초등학생들을 대상으로 엔트로피의 개념과 응용 분야에 대해 설명하였습니다. 엔트로피는 시스템의 무질서함을 나타내는 척도로 사용되며, 열역학과 정보 이론에서 중요한 개념입니다. 엔트로피의 이해는 초등학생들에게 과학과 기술의 깊은 이해를 제공할 수 있을 것입니다.

