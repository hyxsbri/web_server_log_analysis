# **Webserver Log File Analysis(웹 서버 로그 파일 분석)**

### Project Outline


> #### 수행 기간: *23.06.05 ~ 23.06.28*

> #### 활용 데이터셋: *access.log(3.5 GB)*
    하버드 데이터버스에서 다운로드한 것으로, 이란 전자상거래 사이트(zanbil.ir) 로그가 포함되어 있습니다.
    (Zaker, Farzin, 2019, "Online Shopping Store - Web Server Logs", https://doi.org/10.7910/DVN/3QBYB5,
    Harvard Dataverse, V1)

#### 로그 파일을 고효율 열지향 포맷인 parquet 파일로 전처리 후, 응답 크기별 페이지 클러스터링/ Organic traffic(오가닉 트래픽) 분석 등을 수행했습니다.

> #### 작업 환경: *Google Colab(GPU T4)*
