# Custom_FaceDB

## 1. Crawling
- Crawler: [AutoCrawler](https://github.com/YoongiKim/AutoCrawler)
- 현재 chrome 버전 정보를 확인, 버전에 맞는 chromedriver를 다운
  * chrome 버전확인 링크: chrome://settings/help
  * 다른 버전의 chromedriver 다운로드 경로: [chromdriver](https://chromedriver.chromium.org/downloads)
- 미리보기 이미지와 원본 이미지 가리지 않고 다운

<p align="left"><img src="./crawler_example.gif" width="60%" height="50%" title="crawler_example" alt="crawler_example"></img><p>

## 2. Image Manual
- 크롤링 후 Category_tool을 사용하여 front, side, back로 사진을 구별하여 분류
- Category_tool: [classify_imgFile_tool](https://github.com/xylitol/Dataset_tools/tree/main/classify_imgFile_tool)
  * Category_tool은 front, side, back, delete로 이미지를 쉽게 분류할 수 있도록 함
- 검색어 인물 이외의 다른 사람이 존재해도 무방(labeling시 etc로 분류)
<img src="https://user-images.githubusercontent.com/59816618/113269154-22a78e00-9313-11eb-90c9-0026a52c129f.PNG" width="60%" height="60%" title="crawler_example" alt="crawler_example"></img>
- front image example<br>
<img src="https://user-images.githubusercontent.com/59816618/113272111-40c2bd80-9316-11eb-9e81-455945f1b1a7.PNG" width="50%" height="50%" title="crawler_example" alt="crawler_example"></img>
- side image example<br>
<img src="https://user-images.githubusercontent.com/59816618/113272476-9f883700-9316-11eb-8315-f54782a4211d.PNG" width="50%" height="50%" title="crawler_example" alt="crawler_example"></img>
- back image example<br>
<img src="https://user-images.githubusercontent.com/59816618/113272511-a747db80-9316-11eb-80c3-447702fb0a19.PNG" width="50%" height="50%" title="crawler_example" alt="crawler_example"></img>
- 이미지 이름을 유명인_숫자.jpg로 재설정(코드는 쉬워서 공개x)
- 코드로 원본 이미지와 같은 미리보기 이미지 삭제(코드는 차후 공개)
<img src="https://user-images.githubusercontent.com/59816618/113269709-b1b4a600-9313-11eb-8e73-5388b856d401.PNG" width="60%" height="60%" title="crawler_example" alt="crawler_example"></img>

## 3. Labeling
-Labeling_tool: [LabelImg](https://github.com/tzutalin/labelImg)
-LabelImg를 사용하여 target 인물은 이름으로 다른 인물들은 etc로 labeling하여 bounding box 생성
<img src="https://user-images.githubusercontent.com/59816618/113275726-0bb86a00-931a-11eb-8741-d6dd654b7838.jpg" width="50%" height="50%" title="crawler_example" alt="crawler_example"></img>
