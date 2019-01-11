# Hangul_NamuCorpus
Corpus generator of Namuwiki (https://namu.wiki) (Hangul, Korean)

사용 방법: 

1. namu.json 을 아래 주소에서 다운받고 preprocessor/ 에 이동시킨다.
* 테스트: 20180326 기준 테스트 했습니다.
- https://mu-star.net/wikidb
- https://mu-star.net/wikidb


2. python 또는 pypy로 pypy namu_json_to_txt.py 를 실행하여 json을 txt로 변환한다.

* (python or pypy) pypy namu_json_to_txt.py (path 직접 설정)
* (python or pypy) pypy namu_json_to_txt.py namu.json namu.txt err.txt (sys argv 사용하여 실행하는 경우)

