# Hangul_NamuCorpus
Corpus generator of Namuwiki (https://namu.wiki) (Hangul, Korean)

나무위키 (https://namu.wiki)의 덤프파일을 사용한 말뭉치 생성기 (한글, 한국어)

## 사용 방법: 

### 1. namu.json 을 아래 주소에서 다운받고 preprocessor/ 에 이동시킨다.
* 테스트 덤프파일: 20180326 기준 덤프파일로 실행확인 했습니다. (약 56만개 문서)
  + https://mu-star.net/wikidb 
  + http://dump.thewiki.ga/
  + 출처: https://namu.wiki/w/나무위키:데이터베이스%20덤프

### 2. python 또는 pypy로 pypy namu_json_to_txt.py 를 실행하여 json을 txt로 변환한다.
* namu_json_to_txt.py 실행
  + (python or pypy) namu_json_to_txt.py (py 파일 내 path 직접 설정)
  + (python or pypy) namu_json_to_txt.py namu.json namu.txt err.txt (sys argv 사용하여 실행하는 경우)

