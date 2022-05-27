# 백엔드 개발자 면접 사전 테스트


## 데이터 포멧 변환


1. csv파일을 읽어서 읽은 데이터를 json 형식으로 변환
    1. 아래 제공된 csv 파일을 읽고 출력  
       [TOP20.csv](../data/top20.csv)
    2. 읽은 csv파일을 json 파일 포맷으로 아래와 같은 형식으로 저장
    ```json
   [
    {
    "id":1,
    "title":"토익(TOEIC)",
    "licenseOrgan":"미국 ETS",
    "esRegdt":"2021-06-11T00:00:00.000+00:00"
    },
    {
    "id":2,
    "title":"한국사능력검정시험",
    "licenseOrgan":"국사편찬위원회",
    "esRegdt":"2021-07-13T00:00:00.000+00:00"
    },
     ......
   ]
    ```
    3. 저장한 json 파일에서 licenseOrgan 만 출력

3. 해당 결과물을 본인의 github 에 올리기
4. github에 올린후 dev@nine2021.com 으로 해당 github 주소를 dev@nine2021.com 로 발송
