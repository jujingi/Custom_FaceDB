# Custom_FaceDB

## 1.Crawling
- crawler: [AutoCraler](https://github.com/YoongiKim/AutoCrawler)
- 현재 chrome 버전 정보를 확인, 버전에 맞는 chromedriver를 다운
  * chrome 버전확인 링크: chrome://settings/help
  * 다른 버전의 chromedriver 다운로드 경로: [chromdriver](https://chromedriver.chromium.org/downloads)

<p align="left"><img src="./crawler_example.gif" width="60%" height="50%" title="crawler_example" alt="crawler_example"></img><br/><p>

## 2. Image Manual
<p align="left"><img src="https://user-images.githubusercontent.com/59816618/113269154-22a78e00-9313-11eb-90c9-0026a52c129f.PNG" width="60%" height="60%" title="crawler_example" alt="crawler_example"></img><br/><p>
- 크롤링 후 front, side, back 폴더를 만든 후 사진을 구별하여 분류<br>
- 검색어 인물 이외의 다른 사람이 존재해도 무방(labeling시 etc로 분류)

<p align="left"><img src="https://user-images.githubusercontent.com/59816618/113269709-b1b4a600-9313-11eb-8e73-5388b856d401.PNG" width="60%" height="60%" title="crawler_example" alt="crawler_example"></img><br/><p>
