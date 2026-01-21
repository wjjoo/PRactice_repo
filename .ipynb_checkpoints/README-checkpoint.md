### PR을 실습하기 위한 Repository(이하 Repo)입니다.

#### 배정받은 번호의 폴더에 본인이 작성한 REAEME파일을 업로드합니다.

1. 본 Repo를 본인의 GitHub에 Fork합니다.
2. 본인의 로컬에 Clone합니다.
3. 배정받은 폴더명을 본인의 이름(영어)으로 변경합니다.
    - mv 사용
4. 다음 내용을 반영한 README파일을 작성합니다.
    - README파일의 코더를 본인의 이름으로, 리뷰어를 퍼실의 이름(아무나)으로 변경합니다.
      - 1, 3, 4, 5번 체크박스에 체크합니다.
        - markdown에서 체크는 X입니다.
        - 체크를 원하지 않는 2번은 비워둡니다.
      - 1번 항목에 이미지를 추가합니다.
        - 본인이 활용한 CLI의 화면을 캡쳐하여 추가합니다.
        - 퀘스트시 활용하는 PRT는 근거이미지를 첨부해야 하니 꼭 수행하세요 :)
    - 변경사항을 반영하여 push합니다.
      - branch명은 본인이 할당받은 폴더 명으로 설정합니다.(user01, user02, ...)
      ```bash
      # branch 생성
      # git checkout -b 브랜치명
      git checkout -b user01
  
      #branch 변경
      # git checkout 브랜치명
      git checkout user01
  
      # branch 확인
      git branch
      ```
5. 변경사항을 반영하여 Pull-Request를 보냅니다.


---
- 본 Repo의 구조는 다음과 같습니다.
```bash
PRactice_repo
├─user01
│  └─README.md
├─user02
│  └─README.md
.
.
.
└─User30
  └─README.md
```
