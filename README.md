# Jp Web Novel Translator (ja > kr)

- **`requests`를 사용하여 일본의 라이트 노벨 연재 사이트에서 소설을 스크래핑**
    - [소설가가 되자]("https://ncode.syosetu.com/")
    - [카쿠요무]("https://kakuyomu.jp/")

- **`selenium`을 사용한 웹 제어로 네이버의 papago 번역기에 접속하여 스크래핑한 소설의 번역 정보를 받아 텍스트 파일로 저장**

*`google-translate`, `papago` api를 사용하여 웹 제어 없이 스크립트 상에서 번역을 할 수 있으나, 두 번역 api 모두, 하루 번역할 수 있는 문자 수가  10,000자로 제한되어 있음.*

*selenium을 통해 접속한 google 번역기는 네이버 papago보다 한국어 번역 성능이 떨어짐. 따라서, papago를 선택.*