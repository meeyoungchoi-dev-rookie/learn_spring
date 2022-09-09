# 개발 환경 설정
- jdk 설치
    - 환경변수 설정 - JVM 과 컴파일러 - java.exe , javac.exe
    - java_home 환경변수 추가 (jdk 버전 폴더 안에 까지 들어가야 한다)
    - 시스템 변수에 bin 디렉토리 추가
    - cmd에서 현재 컴퓨터에 설치된 자바 버전 확인
- IDE(eclipse) 다운로드

# 프로젝트 생성
- Maven project
- pom.xml  - 필요한(의존하는) 모듈을 가져오기 위한 파일
    - project configurations ~~ 관련 에러가 발생하면 프로젝트의 maven을 업데이트 해준다
- java
- resources
- pom.xml
- applicationContext.xml - <bean></bean> => spring 컨테이너에 bean을 등록해 준다