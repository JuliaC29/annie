annie
=====

* 2016 국어 정보 처리 시스템 - 지정 분야: 개체명 인식 시스템 개발 및 적용
* https://ithub.korean.go.kr/user/contest/contestIntroLastView.do


실행 방법
----

```
./cqasys_annie.bash -i dev.json
```

* -i 옵션으로 입력 파일(JSON 포맷)을 전달합니다. (필수 옵션)
* --output=result.json 형태로 출력 파일(JSON 포맷)을 지정합니다.
    - 지정하지 않으면 현재 디렉토리에 result.json 파일을 출력합니다.
* --rsc-dir=./rsc 형태로 리소스 디렉토리의 경로를 지정합니다.
    - 지정하지 않으면 cqasys_annie.bash 파일과 동일한 위치에서 rsc 디렉토리를 찾습니다.


사용자 설명서
----

[user_manual.md](user_manual.md)


발표 자료
----

[notebook/annie_presentation.ipynb](notebook/annie_presentation.ipynb)


라이센스
----

### Software

* 본 소스 코드에 대해 어떠한 라이센스 권리도 행사하지 않습니다.
* License disclaimer! Just copyleft!

### 말뭉치(Corpus)

* 국립국어원 언어정보나눔터 홈페이지에서 개체명 인식용 말뭉치를 공개했습니다.
    - 통합자료실 => 기타 참고자료 게시판으로 이동합니다.
    - https://ithub.korean.go.kr/user/total/referenceManager.do
    - 114번 게시물 "개체명 인식용 말뭉치" 글에 첨부된 "개체명 인식용 말뭉치.zip" 파일을 사용하시면 됩니다.
