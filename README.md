# Coffee Team 필독사항

## 항상 pull 먼저 해야합니다 !!!
각자 개인 branch 생성후 작업 진행!!
본인 branch 에서 작업후 커밋, push 한 뒤에 팀장한테 merge요청!!
팀장이 merge 승인한걸 확인하면 local branch 삭제
브랜치를 삭제하는 이유는 원본 저장소에 Merge가 완료되면 작업공간이 더이상 필요 없으므로 삭제한다.

pull -> git branch [사용할 브랜치명] git switch [사용할 개인브랜치] -> 작업 -> add, commit -> git push origin [사용할 개인브랜치]
-git push하는 과정에서 오류가 뜰 경우 origin +main으로 해볼것.

```
 $ git pull origin main
 $ git add .
 $ git commit -m " 커밋내용 "
 $ git push origin [branch name]
 
 push error시에 바꿔봐야 할 코드
 $ git push origin +[branch name]
 
```




# OPEN API SITE

- 공공데이터 포털 https://www.data.go.kr/
- 부산 공공데이터 https://data.busan.go.kr/index.nm;jsessionid=2BE87469E6B9D2DEEBB25BA45DAF2C8D
- KAKAO OPEN API https://developers.kakao.com/

# Tools
<div align=center>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=&logoColor=white"/>
  <img src="https://img.shields.io/badge/Github-181717?style=flat-square&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/vsCode-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tomcat-F8DC75?style=flat-square&logo=apachetomcat&logoColor=white"/>
  <img src="https://img.shields.io/badge/Eclipse-2C2255?style=flat-square&logo=eclipseide&logoColor=white"/>
  <img src="https://img.shields.io/badge/json-000000?style=flat-square&logo=json&logoColor=white"/>
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=flat-square&logo=javascript&logoColor=white"/>
  <img src="https://img.shields.io/badge/python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white"/>
  <img src="https://img.shields.io/badge/git-F05032?style=flat-square&logo=git&logoColor=white"/>
</div>


## 팀소개

#### 팀장 : 김경돈  JS, API, HTML ,CSS
#### 팀원 : 김경목  DB, API, Erwin, HTML ,CSS
#### 팀원 : 이아진  JS, API, HTML ,CSS
#### 팀원 : 장연서  JS, API, HTML, CSS

✔개발후기

오픈API를 정말 처음 접해봤다. 오픈API를 사용하기 위해 정말 많은 시도를 했고, 그놈의 CORS 오류가 뭔지..

프로젝트를 시작함과 동시에 접하게된 CORS오류가 우리 팀의 발목을 3일동안 붙잡았던 기억이 남는다.

해당 오류를 해결하기 위해 도메인구입, github.io사용, Node.js 이 세가지 방법 역시 우리는 처음 사용하는 것이었고

이중 도메인 구입을 최후의 보루로 사용하자는 회의끝에 3일째 되던날 팀원 한명이 fetch함수를 사용했더니 CORS오류가 해결되었다 라는 말을 알렸다.

공공API나 카카오API 등을 처음 접하는 우리로서는 가이드라인대로 시도했는데도 오류가 뜨는 이슈 때문에 참 많이 힘들었지만

이런일을 한번 겪어보니 API 사용에 대한 두려움이 사라지게 되었다.

프로젝트 진행기간의 반을 CORS오류 해결에 사용해서 결과물이 썩 괜찮지는 않지만 앞으로 이런 오류를 겪을 경우에 좀더 유연한 대처를 할 수 있지 않을까 한다. 






