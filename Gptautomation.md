# GPT를 이용한 업무의 자동화 

## Excel macro 자동 생성
Chatgpt를 이용하여, Excel macro를 자동으로 생성할 수 있습니다. 
file을 xlsm으로 저장하야합니다.

Chatgpt를 이용하여, 원하는 Excel 파일을 생성하는데, Colmn 정보가 Database가 됩니다. 

## Google Drive
goodgle drive에 google sheet를 생성하여, excel과 같은 내용의 DB를 생성한다.

google colab을 이용하여, 시험해 볼 수 있다. 
https://colab.research.google.com/ 

## Chatgpt를 이용한, python 개발

## Google smtp 계정 설정
설정:  SMTP 사용으로 설정변경

## 이메일 전송 테스트
ipynb를 이용하여 테스트를 수행한다. 
이메일 전송을 할 수 있는 Python script 생성을 Gpt에 요청한다.
2단계 보안 인증 등의 문제를 해결해야 한다. 

# 조건별 메일 전송
## 파일에서 데이터 추출
wb = openpyxl.load_workbook('xxx.xlsx')
ws = wb['name_email']

## Gmail 서버 연결
with smtplib.SMTP(smtp.server, smtp.port) as smtp:
smtp.starttls()
smtp.login(smtp.user, smtp.password)
for name, email in zip(name_list, email_list):
  mail_subject = f'[{name}] 메일 전송 테스트'
  mail_body = f'[{name}], \n\n 메일 전송 테스트'
  
smtp.sendmail(smtp.user, to_email, msg)   

## python schedule 페키지를 이용한 주기적 이메일 전송
import schedule
import time

def send_email()

schedule.every(30).minute.do(send_email)
while True: 
  schedule.run_pending()
  time.sleep(1)

내용을 이에밀 조건과 합친다. 

seoul_timezone = pytz.timezone('Asia/Seoul')
schedule.every().monday.at("08:00").do(send_email) # 8:00 AM

## google sheet를 이용해서, 이메일 전송 테스트 진행한다.
gpt for google이 있다. appsheet을 이용하여, 보낸다. 
Appscript를 활성화 한다. 
Gpt api를 발급하거나, gemini api를 이용하여, google sheet에 입력한다. 
A열이 1열이다. 

