# varsql

varsql websqltool sqltool 


# 실행방법

01. Releases에서 파일 다운로드
02. 압축 풀기. 
03. bin/ 폴더 밑에 
    -startup.bat , startup.sh 실행 

04. 브라우저에서 http://localhost:12312/vsql
05. 초기 관리자 id/pw
   id : varsqladmin
   pw : varsqladmin

# 실행시 문제 해결 방법. 
실행 : C:/varsql-webappv.0.0.1/bin>startup.bat

1. JAVA_HOME 이 시스템 변수에 등록되어있지 않을경우. 
 로그 
    The JRE_HOME environment variable is not defined correctly
    This environment variable is needed to run this program
 조치
    내컴퓨터-> 마우스 오른쪽후 속성 클릭 -> 고급 시스템 설정 -> 환경변수 클릭
    새로만들기 클릭후 
    변수 이름 : JAVA_HOME
    변수값 : ["java설치 경로 추가 후 확인"] ex)C:\Java\zulu\
    
