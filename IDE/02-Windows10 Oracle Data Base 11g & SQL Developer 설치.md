데이터베이스의 사전적 의미로 <br>
여러 사람이 공유하여 사용할 목적으로 체계화하여 통합, 관리하는 데이터의 집합이다.

<br>

DBMS (Database Management System) 데이터베이스 관리 시스템은 <br>
데이터베이스 내의 데이터를 관리하고 조작하기 위한 소프트웨어라고 보면 된다.

<br>

다양한 데이터베이스 관리 시스템이 존재하지만, 그중 오라클 11g 버전을 설치하고자 한다.

<br>

오라클 데이터 베이스의 버전도 다양하지만 <br>
학습용으로 많이 사용하고 있는 버전은 11g로 보면 된다.

<br> 

Oracle 홈페이지에 찾기가 힘들기 때문에 링크를 통해 설치를 진행하면 된다. <br>
<a href="https://www.oracle.com/database/technologies/xe-prior-release-downloads.html">클릭</a>

<br>

# Oracle DataBase 11g XE Download & Install

링크를 통해 Download를 진행하기 전

<br>

OS 운영체제에 맞게 진행하면 된다.

<br>

(Windows 환경에 설치하기 때문에 Windows를 선택)
<br>
![1](https://user-images.githubusercontent.com/60464237/156157294-67278aa4-8713-41f5-b65e-3942ec720979.jpg)
<br>
체크 박스에 체크를 하고 Download를 누른다.
<br>
![2](https://user-images.githubusercontent.com/60464237/156157302-567f3a5a-edda-4404-86d3-2ac0c8f69aa6.jpg)
<br>
Download를 받기 위해서 오라클 계정 로그인을 해야 한다.

<br>

회원가입은 어렵지 않기 때문에 계정 만들기를 통해 계정을 만들어준다.

<br>

로그인을 하면 다운로드가 진행된다.
<br>
![3](https://user-images.githubusercontent.com/60464237/156157308-f1742b2a-c7c0-429b-8e97-0fce7736330b.jpg)
<br>
다운로드가 완료 된 파일은 압축을 풀어준다.
<br>
![4](https://user-images.githubusercontent.com/60464237/156157310-61785ed9-4e1d-4b8a-863f-ecc721675a08.jpg)
<br>
압축이 완료된 폴더 안에 setup.exe를 누른다.
<br>
![5](https://user-images.githubusercontent.com/60464237/156157314-9f923237-a1b5-448e-958f-9a3c66ecaac0.jpg)
<br>
설치 준비 진행 중...
<br>
![6](https://user-images.githubusercontent.com/60464237/156157316-106434c6-94fe-4ef5-963d-441cdcff4946.jpg)
<br>
"Next"를 눌러 다음 단계로 진행한다.
<br>
![7](https://user-images.githubusercontent.com/60464237/156157317-386e0e1e-9bc6-40d2-a9a3-18efb6590ff5.jpg)
<br>
⏺ I accept the terms in the license agreement <br>
체크 부분에 체크를 한다.

<br>

"Next"를 눌러 다음 단계로 진행한다.
<br>
![8](https://user-images.githubusercontent.com/60464237/156157321-2857ffa3-687f-45f0-a0c9-435cea9a472f.jpg)
<br>
"Browse..."을 통해 설치 경로를 바꿀 수 있지만 웬만해선 바꾸지 않고 설치한다.

<br>

"Next"를 눌러 다음 단계로 진행한다.
<br>
![9](https://user-images.githubusercontent.com/60464237/156157324-46061b7e-dcfa-4929-855b-a5e895103bb0.jpg)
<br>
DataBase를 관리하기 위해 사용할 비밀번호를 입력한다.

<br>

비밀번호는 알기 쉽게 설정하는 것이 좋다. <br>
(설정된 비밀번호는 따로 바꿀 수 있다.) 

<br>

"Next"를 눌러 다음 단계로 진행한다.
<br>
![10](https://user-images.githubusercontent.com/60464237/156157325-7fc2bd80-98d9-47dc-8d81-cd4ede1ec7fc.jpg)
<br>
"Install"을 눌러 설치를 진행한다.
<br>
![11](https://user-images.githubusercontent.com/60464237/156157326-d1a3790f-5c55-4c11-ac1f-bcd47752eb30.jpg)
<br>
설치 진행 중...
<br>
![12](https://user-images.githubusercontent.com/60464237/156157328-3aa3a7e6-b159-4e94-a0ef-3dd0a20acb37.jpg)
<br>
"Finish"를 눌러 설치를 완료한다.
<br>
![13](https://user-images.githubusercontent.com/60464237/156157330-d6966a4c-db13-4a1d-a7c3-0ee995bbb353.jpg)

<br>

# Oracle DataBase 11g XE 설치 확인

윈도우 키 + R을 누르거나 또는 윈도우 키를 누른 후 cmd를 입력한다.
<br>
![14](https://user-images.githubusercontent.com/60464237/156157332-70711e11-7d58-4cfa-8cd8-a38b65e6fac1.jpg)
<br>
명령 프롬프트 창에서 "sqlplus"를 입력하면

<br>

SQL*Plus : Release 11.2.0.2.0 버전을 확인할 수 있다.

<br>

정상 접속 확인을 위해 입력한다. <br>
Enter user-name: system <br>
Enter password: 지정한 비밀번호 

<br> 

Conneted to: <br>
Oracle Database 11g Express Edition Release 11.2.0.2.0 - 64bit Production <br>
접속된 메시지가 나타나는 것을 확인할 수 있다.
<br>
![15](https://user-images.githubusercontent.com/60464237/156157334-33b66c24-71e2-4fb1-a246-f91aa7ec1cda.jpg)
<br>
Oracle Database는 cmd 명령 프롬프트에서 사용하기엔 불편함이 많이 있다.

<br> 

GUI를 통해 쉽게 확인할 수 있는 tool 중 Sql Developer를 설치하면 편리하게 사용할 수 있다.

<br> 

SQL Developer는 Oracle에서 제공된다. <br>
<a href="https://www.oracle.com/tools/downloads/sqldev-downloads.html">클릭</a>

<br>

# SQL Developer Download & Install

링크를 통해 Download를 진행하기 전

<br>

SQL Developer는 자바 JDK 8 included 가 있다.

<br> 

Java가 설치된 상황이기 때문에 JDK가 포함되어 있지 않은 버전을 다운로드한다.

<br> 

OS 운영체제에 맞게 진행하면 된다.

<br>

(Windows 환경에 설치하기 때문에 Windows를 선택)
<br>
![16](https://user-images.githubusercontent.com/60464237/156157339-4d86d635-fcf6-4900-9391-db0c7de8650c.jpg)
<br>
체크 박스에 체크를 하고 Download를 누른다.
<br>
![17](https://user-images.githubusercontent.com/60464237/156157342-87591be5-01de-47f7-a4fa-fc5ca16a73b5.jpg)
<br>
SQL Developer는 설치형이 아니기 때문에 

<br>

다운로드한 파일을 압축을 풀면 설치는 끝이다.
<br>
![18](https://user-images.githubusercontent.com/60464237/156157343-fcfeb3e1-c099-4fde-84e8-91ef365e8d94.jpg)
<br>
압축 해제 완료 후 폴더 안에 sqldeveloper를 실행한다.
<br>
![19](https://user-images.githubusercontent.com/60464237/156157345-d40e6f7c-873d-4fa9-b5bb-50de39b5577c.jpg)
<br>
파일을 실행하면 JDK 경로를 입력하라고 나온다.

<br>

"Browse..."를 누르고 자바가 설치된 경로에서 JDK까지만 설정해주면 된다.
<br>
![20](https://user-images.githubusercontent.com/60464237/156157346-88608206-a72e-459c-8839-ffb51a930f94.jpg)
<br>
자바 기본 설치경로는 <br>
C:Program Files\Java\jdk1.9.0_311 <br>
폴더 선택을 눌러 진행한다.
<br>
![21](https://user-images.githubusercontent.com/60464237/156157349-ecd0dc2d-8076-4541-9454-f3200dc88d3a.jpg)
<br>
JDK 설치 경로를 꼭 확인한 후 "OK" 버튼을 누른다.
<br>
![22](https://user-images.githubusercontent.com/60464237/156157351-15fc5fdf-ee5c-41e3-a13f-dac197a9fedd.jpg)
<br>
SQL Developer 실행 중...
<br>
![23](https://user-images.githubusercontent.com/60464237/156157353-e0a966b2-31ac-49b8-af0a-dd5dcd41ee7e.jpg)
<br>
환경설정 임포트 확인 창이 나타나는데

<br> 

"아니오(N)"을 누른다.
<br>
![24](https://user-images.githubusercontent.com/60464237/156157355-62eb6742-c386-4630-8b94-3c4f8713c4a0.jpg)
<br>
SQL Developer에서 오라클 접속을 위해

<br>

왼쪽 상단에 ➕ 아이콘을 누른다.
<br>
![25](https://user-images.githubusercontent.com/60464237/156157360-d468a34a-2e62-483e-a6a0-080bb1afe2c9.jpg)
<br>
1. name은 임의로 설정할 수 있기 때문에 하고 싶은 이름으로 지정한다.
2. 오라클 계정의 사용자 이름과 비밀번호 입력해야 한다.
	* 사용자 이름: system
	* 비밀번호: 설치할 때 설정한 비밀번호
3. 자신의 컴퓨터에서 오라클을 접속하는데 필요한 정보이다.
	* 호스트 이름: localhost  (IP 주소를 입력하는 부분이다.)
	* 포트: 1521 (오라클의 포트번호로 따로 설정하거나 변경하지 않으면 1521로 입력한다.)
	* SID: xe (데이터베이스의 고유 이름으로 따로 설정하지 않은 경우 xe로 입력한다.)
4. 접속 전 테스트를 누른다.
5. 상태: 성공 / 상태: 실패 확인할 수 있다.
6. 테스트 결과 성공이면 접속을 누른다.
<br>
![26](https://user-images.githubusercontent.com/60464237/156157362-03ac2b95-daf3-4056-bf2f-1fbb172077ed.jpg)
<br>
정상적으로 접속 확인을 위해 

<br>

SELECT * FROM all_all_tables; 

<br> 

SQL문을 실행하여 질의 결과가 출력된 것을 볼 수 있다.
<br>
![27](https://user-images.githubusercontent.com/60464237/156157363-9ee230d3-e4a4-4f42-b094-4dd2d20c37d2.jpg)