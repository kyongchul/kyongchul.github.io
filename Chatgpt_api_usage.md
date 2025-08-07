# Chatgpt API usage
 Chatbot, 및 음성 비서 만들기

  
## 1. 주피터  활용
주피터 파일을 활용하여, 검증을 해볼 수 있다. 
주피터 파일은 VS code 또는 구글 Colab에서도 검증을 진행할 수 있다. 


## 2. Streamlit의 활용
### table의 작성
import streamlit as st
import pandas as pd
이용하여, Web 상에서 열어본다. 미려한 테이블을 작성해 볼 수 있다.

### 그래프 작성
import streamlit as st
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
import plotly.graph_objects as go
플롯을 작성할 수도 있다. 

### 버튼, 라디오 박스 등 작성
버튼, 레디오 박스, selectbox 등을 streamlit을 이용하여 구현 할 수 있다. 

## 3. 스트림릿을 이용하여 글 요약 해보기
스트림릿을 이용하여, 데이터를 gpt prompt로 입력한다. 

## 4. chatgpt에 prompt를 여러 입력 제공
## 5. 섹션 5. 광고 문구 생성 프로그램 만들기
21. 광고 문구 생성 프로그램 개요

gpt의 입력으로 여러 정보를 넣어본다. 
    if st.button("광고 문구 생성"):
        prompt = f'''
        아래 내용을 참고해서 1~2줄짜리 광구문구 5개 작성해줘
        - 제품명: {name}
        - 브렌드 명: {com_name}
        - 브렌드 핵심 가치: {value}
        - 제품 특징: {strenghth}
        - 톤엔 매너: {tone_manner}
        - 필수 포함 키워드: {keyword}
        '''
        st.info(askGpt(prompt,st.session_state["OPENAI_API"]))

## 섹션 6. ChatGPT vs Bard 답변 비교 프로그램
23. ChatGPT vs Bard 답변 비교 프로그램 개요
24. Bard API 사용방법 익히기
	token = 'Bard token'
	bard = Bard(token=token,timeout=30)
	result = bard.get_answer("LG 트윈스에 대해 설명해줘")
	print(result)

25. Streamlit의 Session_state 이해하기

## 섹션 7. 번역 플랫폼 비교 프로그램 만들기
-. 번역 플랫폼 비교 프로그램 개요
-. 구글 번역기 API 사용방법 익히기
-. 파파고 번역기 API (변경 됨)
-. Deepl 번역기 API 사용방법 익히기

## 섹션 8. 인스타 포스팅 생성 및 업로드 프로그램 만들기
- 인스타 포스팅 생성 및 업로드 프로그램 개요
	cl.photo_upload(phot_path , "다음의 그림을 올립니다. instagrapi")
- DALL.E 2 사용방법 익히기
- 파이썬을 활용한 인스타그램 업로드 방법 익히기
Chatgpt에게 그림을 요청하는 경우
	-topic : {topic}
	-Mood : {mood}

## 섹션 9. 유튜브 내용 요약 프로그램 만들기
- 유튜브 내용 요약 프로그램 개요 (영어로 되어 있는 내용을 받아서, 요약해주는 서비스 제작)
  (Langchain: vector stores, text splitters, model, document loader, etc)
  Langchain을 이용하면 수많은 AI engine을 사용할 수 있다. 
- Langchain 소개 및 유튜브 대본 추출하기
- Langchain을 활용하여 긴 글 요약하는 방법 익히기
- 메인코드 작성하기

## 섹션 10. PDF 내용 질문 프로그램 만들기
40. PDF 내용 질문 프로그램 개요
41. 텍스트 임베딩/벡터 유사도 개념 알고 실습하기
42. Langchain을 활용하여 PDF 내용 질문 방법 익히기
43. 메인코드 작성하기
섹션 11. 나만의 음성비서 프로그램 만들기
44. 나만의 음성비서 프로그램 개요
45. 구글 TTS(Text-to-Speech)서비스 사용방법 익히기
46. Whisper STT(Speech-to-Text)서비스 사용방법 익히기
47. 메인코드 작성하기

## 섹션 12. 텔레그램 챗봇 만들기(로컬 PC를 서버로 활용)
48. 로컬 PC서버를 활용한 텔레그램 챗봇 만들기 개요
49. HTTP 통신의 개념 이해하고 파이썬 환경에서 실습하기
50. 텔레그램 API 사용법 익히기
51. Fast API 개념 이해하고 실습하기
52. ngrok를 활용하여 외부 접속 URL 생성하기
53. 메인코드 작성하기

## 섹션 13. 텔레그램 챗봇 만들기(AWS를 서버로 활용)
54. 아마존 웹 서비스(AWS)를 활용하여 텔레그램 챗봇 만들기 개요
55. AWS 람다함수 생성 및 사용방법 익히기
56. AWS 람다함수 코드 작성하기
57. AWS API Gateway 생성 및 사용방법 익히기
58. AWS 서버 로그 확인하는법 익히기


## 섹션 14. 카카오톡 챗봇 만들기(로컬 PC를 서버로 활용)
59. 로컬 PC서버를 활용한 카카오톡 챗봇 만들기 개요
60. 카카오톡 채널 및 챗봇 생성하기
61. 로컬 PC 서버와 카카오톡 서버 연결하기
62. 카카오톡 챗봇 제어 컨셉 설명
63. 멀티스레딩 개념 이해 및 파이썬 환경에서 실습하기
64. 메인코드 작성하기 #1
65. 메인코드 작성하기 #2

## 섹션 15. 카카오톡 챗봇 만들기(AWS를 서버로 활용)
66. 아마존 웹 서비스(AWS)를 활용하여 카카오톡 챗봇 만들기 개요
67. AWS 서버에 카카오톡 챗봇 구현하기
