# Kaggle LLM - AI 생성 text 감지를 위한 딥러닝 분류모델 경진대회
     


- url 주소 :
https://www.kaggle.com/competitions/llm-detect-ai-generated-text/overview

- 순위 : (✔내용 추가 예정)



## 학습방법 및 실험내용



### 학습 키워드와 핵심역할 :

     Encoder 기반 딥러닝 모델
     vs Decoder 기반 딥러닝 모델 차이       : 이호열
     중복데이터 처리방법 및 데이터 EDA      : 황석준
     감정 분석의 정의와 코드구현            : 이재영
     난독화 문제 대비의 정의와 코드구현     : 


- 개요 (분류모델선정 이유 및 진행방향 요약)
    - BERT, RoBERTa, GPT


- 데이터 EDA

    - train_essay : (✔내용 추가 예정)
      - train 데이터 증강
      - target의 불균형 유무
      - 이상치 유무
      - Null 값의 유무
      - 로그스케일링 등 추가 벡터의 인코딩 방법 선정
      - 새로운 특성의 생성 유무
      - matplotlib을 통한 train 데이터 시각화

    - train_prompt : 해당 찬반토론 기반 text의 주제.
           - 0 : Car-free cities
           - 1 : Does the electoral college work?

    - 전처리 진행
      
        - 중복데이터 처리 및 데이터 증강
          - (✔내용 추가 예정)
          
        - 감정 분석
          - (✔내용 추가 예정)
          
        - 난독화
          - (✔내용 추가 예정)
          - 'https://link.springer.com/article/10.1007/s40979-023-00146-z' 관련 논문 참고했습니다
          
       


- 모델학습
     - (✔내용 추가 예정)
     - (하이퍼파라미터, 학습률, 배치크기, 에포크 수)



- 추론 및 대처, discussion
  - accuracy 향상을 위한 노력

## 개발환경

## 라이브러리 버전

## pip

## 실행방법

## sample parameter 설정

## Test 및 Inference



