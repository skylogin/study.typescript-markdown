# markdown
마크다운 파싱 애플리케이션

+ 사용자는 텍스트영역에 입력
+ 텍스트 영역 내용이 바뀔 때 마다 문서 전체를 다시 파싱
+ 사용자가 엔터키를 누른 곳을 기준으로 문서를 분리
+ 시작 문자로 그 줄이 마크다운인지 아닌지 판단
+ \# 뒤에 공백이 들어오면 H1태그
+ \## 뒤에 공백이 들어오면 H2태그
+ \### 뒤에 공백이 들어오면 H3태그
+ ---은 가로줄로 변경
+ 마크다운으로 시작하지 않는 줄은 문단으로 취급
+ 결과 HTML은 부트스트랩 레이블에 표시
+ 텍스트 영역이 비어있으면 레이블은 빈 문단을 포함
+ 레이아웃에 부트스트랩을 사용하고 내용의 높이를 100%로 높임
