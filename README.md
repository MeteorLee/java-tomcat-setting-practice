# 자바 프로젝트 - 톰캣 개발 환경 구축 연습

## 톰캣 연동

- 8080 포트 연동
- webapps 아래의 파일을 읽게 설정

## 인텔리제이 out 위치 설정

인텔리제이의 out을 webapps/WEB-INF/classes 아래로 변경하여 자바 프로젝트를 실행하면 자연스럽게 톰캣이 파일을 읽는 위치로 설정하게 함

Project Settings - Modules - paths - main 의 out 변경
![K-076](https://github.com/MeteorLee/java-tomcat-setting-practice/assets/111167712/a831ad78-6622-48af-bbfe-3d19cc6c5035)


Project Settings - Modules - paths - test 의 out 변경

![K-077](https://github.com/MeteorLee/java-tomcat-setting-practice/assets/111167712/64648ac7-6a25-409e-abdd-daa68c46bdcd)



WebApplicationServer 클래스 실행 시 WEB-INF아래에 바로 생성

![K-078](https://github.com/MeteorLee/java-tomcat-setting-practice/assets/111167712/f3c5621a-736d-423c-a682-46cd546c996e)
