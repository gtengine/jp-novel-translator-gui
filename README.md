# Jp Web Novel Translator (ja > kr)

1. **`requests`를 사용하여 일본의 라이트 노벨 연재 사이트에서 소설을 스크래핑**
    - [소설가가 되자](https://ncode.syosetu.com/)
    - [카쿠요무](https://kakuyomu.jp/)

2. **`selenium`을 사용한 웹 제어로 네이버의 papago 번역기에 접속 > 스크래핑한 소설 번역 > 텍스트 파일로 저장**
    - google-translate api, papago api를 사용하여 웹 제어 없이 스크립트 상에서 번역을 할 수 있으나, 두 번역 api 모두, 하루 번역할 수 있는 문자 수가  **10,000자로 제한**되어 있음.
    - `selenium`을 통해 접속한 google 번역기는 네이버 papago보다 한국어 번역 성능이 떨어지기 때문에 papago를 선택.