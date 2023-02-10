# projectSiwoo

## Project : 내방 어디?
- 폴더 링크 : [Project_1](https://github.com/siwookoon/projectSiwoo)
- 배포 링크 : [내 방, 어디?](https://siwookoon-projectsiwoo-app-ccp9zs.streamlit.app/)
- 기간 : `2022.01.27 ~ 2023.02.10`
- 사용 언어 : `Python (3.9.13)`
- 사용 Tool : `VS code (1.74.1)`, `Google Colab`
- 라이브러리 `Version`
    + `pandas (1.5.3)`, `numpy (1.24.1)`, `plotly (5.13.0)`, `matplotlib (3.6.3)`, `streamlit (1.17.0)`, `streamlit-option-menu (0.3.2)`, `geopandas (0.12.2)`, `joblib (1.2.0)`, `scikit-learn (1.2.1)`, `tensorflow (2.9.0)`, `seaborn (0.12.2)`, `geopandas (0.12.2)`, `pydeck (0.8.0)`, `prophet (1.1.2)`, `openai (0.26.5)`, `streamlit_chat (0.0.2.1)`, `requests (2.28.2)`
- 내용 : 서울시 전/월세 실거래 데이터를 기반한 검색, 머신러닝을 이용한 전세 시세 예측
***

### 내용
- 🏠Home
    + 최근 한달 실거래 현황(최신순)
- 🔎전월세 검색
    + 구, 동, 전세/월세, 보증금, 임대면적 선택 후 조회
    + 계약일 기준 거래내역 표로 표현
- 📊전세예측
    + 구 선택 시, 전세 월평균 그래프
    + 월세 월평균 -> 보증금 월평균, 월세 월평균 그래프 표현
- 🤖챗봇
    + GPT-3 api를 이용한 chatbot
    + 서울시 공공데이터를 통한 날짜별 자치구 거래내역 조회 가능
    + 이외에 GPT-3를 통해 학습시켜 놓은 데이터를 바탕으로 AI 채팅
- 💬건의사항
    + 문의하기를 통해 사용자의 불만이나 궁금증을 접수
    + 검색 기능으로 건의사항을 검색
    + 자주 묻는 질문과 목록 탭