# zest

Client main 화면
localhost:8080/zest/main

관리자 main 화면
localhost:8080/admin/main

기본 구성 환경 설정
tomcat에서 project 추가시 root 주소 /zest 설정 
tomcat server.xml 에 
 <Host appBase="webapps" autoDeploy="true" name="localhost" unpackWARs="true">
	<Con0text docBase="C:/zest/" path="/LocalImage" reloadable="false"/> 내용 추가		
 </Host>

https://drive.google.com/drive/folders/1m6snG2xonN_bTM42jKCviXienDJjsV7E?usp=sharing
해당링크주소에서 압축 파일 압축해제 후 
zestImage 압축폴더 c:/zest 에 저장
