Apache Tomcat(아파치 톰캣)은 <br>
아파치라는 소프트웨어 재단에서 개발한 서블릿 컨테이너(또는 웹 컨테이너)만 있는 웹 애플리케이션 서버이다. <br>

<br> 

자바 환경에서 웹서버와 연동하여 자바서버 페이지(JSP)와 자바 서블릿이 실행할 수 있는 환경을 제공하고 있다. <br>
톰캣의 관리 툴을 통해 여러 환경 설정을 변경할 수 있고, XML 파일을 편집 기능과 HTTP 서버도 자체 내장되어 있다. <br>

<br> 

Apach Tomcat 홈페이지  <br>
<a href="https://tomcat.apache.org/">클릭</a>

<br>

# Apach Tomcat 9.0 Download & Install
왼쪽 카테고리 Download에서 Tomcat 9를 누른다.

<br>

![1](https://user-images.githubusercontent.com/60464237/156562897-72ee8756-e120-435d-82bb-be3bc7a8cafc.jpg)

<br>

OS 운영체제에 맞게 설치를 하면 된다.

<br>

Installer 파일도 있지만 프로그램 관리를 위해 '.zip' 파일을 다운로드를 진행한다.

<br>

![2](https://user-images.githubusercontent.com/60464237/156562900-eb4d0181-9b6d-4b7a-a290-94e4a738a25f.jpg)

<br>

'.zip'파일로 받았기 때문에 <br>

<br> 

다운로드한 파일의 압축을 풀면 설치는 끝이다.

<br>

![3](https://user-images.githubusercontent.com/60464237/156562902-3b30cf15-aa24-4568-8899-b393a249e4e5.jpg)

<br>

Eclipse와 Tomcat을 연동하기 위해 Eclipse를 실행한다.

<br> 

![4](https://user-images.githubusercontent.com/60464237/156562903-b48dcaea-1ac3-485b-9100-461dba9bf888.jpg)

<br>

Servers에 <br>
No servers are available. Click this link to create a new server... 를 누른다.

<br>

![5](https://user-images.githubusercontent.com/60464237/156562907-d6112f74-a41a-48a5-a536-0e722e22ef64.jpg)

<br>

상단에 있는 Apache를 더블클릭한다.

<br>

![6](https://user-images.githubusercontent.com/60464237/156562909-989d542b-478c-41ff-b8fd-097281482c7f.jpg)

<br>

설치한 버전은 9.0이기 때문에 <br>
Tomcat v9.0 Server를 클릭하고

<br>

"Next>"를 눌러 다음 단계로 진행한다.

<br>

![7](https://user-images.githubusercontent.com/60464237/156562912-a2a531b4-9bd1-4c32-ad05-4dc94c7874af.jpg)

<br>

Tomcat이 설치한 디렉토리를 설정해야 한다. <br>
"Browse..."을 누른다.

<br>
 
![8](https://user-images.githubusercontent.com/60464237/156562913-93408ede-8da3-4816-bf14-532c39fd2238.jpg)

<br>

압축 해제한 파일 경로를 찾아 폴더 선택을 하면 된다. <br>
경로가 다른 곳을 선택하는 경우 정상 작동하지 않으니 유의해야 한다.

<br>

![9](https://user-images.githubusercontent.com/60464237/156562915-dc70894c-c975-4bf8-bc38-8de187ce9367.jpg)

<br>

"Finish"를 눌러 설정을 완료한다.

<br>

![10](https://user-images.githubusercontent.com/60464237/156562916-c0c26525-af7b-44f3-b446-4d53e0294bd3.jpg)

<br> 

Server에 Tomcat 9.0 서버가 추가된 것을 확인할 수 있다. <br> 

추가가 된 후 설정을 위해 더블클릭한다.

<br>

![11](https://user-images.githubusercontent.com/60464237/156562917-aaa48f3a-7dd7-4269-80b2-b6a058f0eecf.jpg)

<br>

Tomcat 설정 창이 나타난다.

<br>

기본적으로 바꿔야 하는 부분들이 있다.

<br>

* Server Locations
- ⏺Use Tomcat installation (takes control of Tomcat installation)  변경
* Server Options
- ✅Publish module contexts to separate XML files  체크
* Ports
- Port NUmber 8181 변경 (8080은 오라클에서 주로 사용되기 때문에 충돌 방지를 위해 변경)

<br>

설정이 완료되면 'Ctrl + s'를 눌러 저장한다.

<br> 

![12](https://user-images.githubusercontent.com/60464237/156562919-6b0a7d3e-330a-4b21-8665-34405ec9c9e7.jpg)

<br>

Tomcat v9.0 Server at Localhost [Stopped, Republish]

<br> 

서버 실행을 위해 오른쪽 클릭 후 Start를 누른다.

<br> 

![13](https://user-images.githubusercontent.com/60464237/156562920-5be61635-cec0-4d6b-9902-aaa66af4d05b.jpg)

<br>

Windows 방화벽 보안 경고가 나타나는데 액세스 허용을 해준다.

<br>

![14](https://user-images.githubusercontent.com/60464237/156562922-df721c54-0889-470e-95d1-10dbbafd1157.jpg)

![15](https://user-images.githubusercontent.com/60464237/156562924-574f9a1f-39fc-4e3b-bce2-e7197ec52f34.jpg)

<br>

localhost:8181 접속을 하면 Apache Tomcat 창이 나타나고 <br> 

서버가 정상 작동되는 것을 확인할 수 있다.

<br>

![16](https://user-images.githubusercontent.com/60464237/156562926-cd88f57a-6353-41b4-b465-585831f6daaf.jpg)

<br>

<br>
# Tomcat에 Project Server 추가 Setting

Tomcat Server에 작동할 프로젝트를 추가하기 위해 <br>
Servers쪽에 Tomcat v9.0 Server at Localhost [Stopped, Republish] <br>
오른쪽 클릭 후 "Add and Remove..." 를 누른다. <br>

<br> 

(practice라는 프로젝트를 임의로 생성하였다.)

![17](https://user-images.githubusercontent.com/60464237/156562932-843796dc-d084-48a1-826c-41a0458ceb10.jpg)

<br>
Available : 에 있는 practice를 누른 후 <br>
"Add >" 눌러 Configured: 로 옮긴다.

<br>

![18](https://user-images.githubusercontent.com/60464237/156562933-a656beba-e9d9-4fdb-b590-f0293608ccc2.jpg)

<br>

Configured: 로 옮겨진 practice를 확인 하고 "Finish"를 누른다.

<br>

![19](https://user-images.githubusercontent.com/60464237/156562935-dc25e3cf-4085-452d-9b96-d82c441adaaa.jpg)

<br>
정상 작동을 확인을 위해 <br> 
practice 안에 WebContent 오른쪽 클릭하고 JSP File 생성한다. <br>

<br> 

WebContent > New > JSP File 

<br> 

![20](https://user-images.githubusercontent.com/60464237/156562937-5cc42c77-47b3-4d75-964a-d0c4e081d6e1.jpg)

<br>

File name은 helloworld.jsp 라고 지정했다. <br>

<br>

"Finish"를 눌러 JSP File을 생성한다. 

<br>

![21](https://user-images.githubusercontent.com/60464237/156562940-f999efbf-e2d6-4cbd-941a-32d0f2c944cc.jpg)

<br>

간단한 html을 작성 후 ▶ 실행 버튼을 누른다. 

<br>

![22](https://user-images.githubusercontent.com/60464237/156562941-ab8897cf-a8cb-4cfe-935f-9f1d20efda2a.jpg)

<br>

"Finish"를 누른다.

<br>

![23](https://user-images.githubusercontent.com/60464237/156562943-ae236a14-204f-4c4f-a7b9-bf3b0a38c953.jpg)

<br>

html에 작성된 문구가 정상적으로 실행 되는 것을 확인할 수 있다.

<br>
 
![24](https://user-images.githubusercontent.com/60464237/156562945-7b85131e-2b55-4b17-854e-6095f35b415a.jpg)

<br>

# Tomcat Server 실행 시 웹 브라우저 Chrome으로 설정하기

Window > Preferences를 누른다.

<br>

![25](https://user-images.githubusercontent.com/60464237/156562948-24052506-c412-4442-8ba5-9f8378f9acaf.jpg)

<br>

General > Web Browser안에 체크할 사항이 있다. <br>

⏺ Use external web browser <br>

✅ Chome  <br>

<br>

Apply and Close를 누른다. 

<br> 

![26](https://user-images.githubusercontent.com/60464237/156562951-4c2b9781-3c7b-4e00-a720-b885129eac78.jpg)

<br>

▶ 실행 버튼을 누른다.

<br>

![27](https://user-images.githubusercontent.com/60464237/156562953-4c6ea8d2-aa04-4ac0-a8fa-955df10a7dc2.jpg)

<br>

"Finish"를 누른다.

<br>

![28](https://user-images.githubusercontent.com/60464237/156562956-d9772a5c-c489-4df5-8b63-ccd6d93cb5c7.jpg)

<br>

새 Chrome 창이 열리면서 <br>
html에 작성된 문구가 정상적으로 실행 되는 것을 확인할 수 있다.

<br>

![29](https://user-images.githubusercontent.com/60464237/156562957-68934328-7163-427d-9ade-7196bc9a4f39.jpg)
