# qwa310.github.io

## Blog Theme (Jekyll)
[minimal-mistakes](https://github.com/mmistakes/minimal-mistakes)

## Jekyll Struct
directory | func
---------- | ----------
_config.yml | 환경설정
_drafts     | 게시 전인 글 보관
_includes   | 재사용가능한 html 보관 (ex. header, footer), liquid 태그로 _include 내 html 소환가능
_layouts    | default.html: 최상위 Jekyll Blog 구성, post.html: Post 형태 정의
_posts      | 날짜별로 정렬, 파일명 반드시 **2018-01-28-title.md** 형태 갖출 것
_data       | 사용할 데이터 모아두는 곳, 확장자가 .yml, .yaml, .json, .csv 일 경우 자동으로 읽어 들여서 site.data 변수를 써서 소환 가능
_site       | 디렉토리 파일들로 Jekyll이 Site 변환 작업을 마치면 그 파일이 저장되는 곳, 주의) **_site 내 파일은 건드리지 말 것**
index.html  | 블로그 접속 시 자동으로 보여주는 html

[Github.io 블로그 생성 시 참고한 사이트](https://www.jihyeleee.com/blog/third-designer-can-make-jekyll-blog/)
