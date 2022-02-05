IDE는 개발자의 코딩 실수를 줄여주고 키워드의 색깔 구분,
자동 코드 완성 기능 및 디버깅 기능뿐만 아니라
개발에 필요한 다양함과 편리한 기능 덕분에 IDE로 개발을 많이 한다.
Java IDE 중 Eclipse IDE를 설치 방법에 대해 기록을 남긴다.

<hr>

```
Eclipse  설치 전 확인
```

참고로 이클립스를 설치하기 전 Java 버전 확인 및 설치가 끝난 후 진행을 해야 한다.
Eclipse 설치하기 전에 Java 버전을 확인해야 하는 이유는 
이클립스 IDE 최신 버전은 Java 8 버전이 미지원 상태이기 때문이다.
Eclipse 2020-09 버전부터는 Java 11 이상 지원이 되기 때문에
Java 8 버전이 지원되는 Eclipse 2020-06 (4.16) 버전을 설치하고자 한다.

<hr>

### Eclipse Download & Install
이클립스 홈페이지를 접속한다.
https://www.eclipse.org/


이클립스 홈페이지 상단에 있는 Download를 누른다.
![1](https://user-images.githubusercontent.com/60464237/152646102-264cc86f-d549-4a00-bc4e-5b23e5bb021b.jpg)


Java 11 버전 이상인 경우
Eclipse IDE 최신 버전으로 다운 받아도 되지만
Java 8 버전이기 때문에 Download Packages 부분을 누른다.
![2](https://user-images.githubusercontent.com/60464237/152646103-1afae8cf-a38d-41a2-bf59-07c37cd2d104.jpg)


오른쪽 MORE DOWNLOADS에
Eclipse 2020-06 (4.16)을 누른다.
![3](https://user-images.githubusercontent.com/60464237/152646104-736b0747-a7dc-4a3a-add1-c0fdbb6a08f0.jpg)

 
Eclipse IDE 2020-06 R Packages가 맞는지 확인을 하고
설치하기 전 OS 운영체제에 맞게 다운로드를 진행하면 된다.
Windows로 설치를 위해서 Windows x86_64를 누른다.
![4](https://user-images.githubusercontent.com/60464237/152646105-54920b3d-03d2-4dbc-985d-85268ccd9de1.jpg)
 
Eclipse IDE는 설치형이 아니기 때문에 
다운로드한 파일의 압축을 풀면 설치는 끝이다.
![5](https://user-images.githubusercontent.com/60464237/152646107-13b04ce1-ec8e-458c-ad4a-63a3fd342d0f.jpg)


### Eclipse IDE 실행 및 Hello World! 출력
압축 해제가 완료 후 폴더 안에 eclipse를 실행한다.
![6](https://user-images.githubusercontent.com/60464237/152646109-aa36996f-fa83-43bd-92d3-5975e7080eb2.jpg)


Java 8 버전으로 eclipse IDE 2020-06 실행 화면
![7](https://user-images.githubusercontent.com/60464237/152646112-c7647ec4-b240-4a9d-865a-4bfb7a137865.jpg)


처음 이클립스를 실행하면 워크스페이스 위치를 선택하라고 나타난다.
"Browse..."를 통해 원하는 Workspace 경로를 설정할 수 있고
경로 설정을 따로 하지 않을 경우 기본 경로로 지정된다.
Launch를 누르면 이클립스를 실행한다.
![8](https://user-images.githubusercontent.com/60464237/152646113-f57cc5f6-b17b-41c6-8174-1376f13bf405.jpg)


이클립스 실행 중..
![9](https://user-images.githubusercontent.com/60464237/152646114-c9db68c0-5f0b-4fea-869d-4ddef2b1d28c.jpg)


Eclipse 첫 화면으로 Welcome을 표시해준다.
Welcome은 'X'를 눌러 닫아주고 왼쪽에 커피콩처럼 생긴 아이콘을 누른다.
![10](https://user-images.githubusercontent.com/60464237/152646115-7fabfafa-66b4-4fa5-9d53-0c7277445b69.jpg)


오른쪽 상단에 해당 아이콘을 누른다.
![11](https://user-images.githubusercontent.com/60464237/152646116-7bf359b6-b589-4741-8014-bb5caf9d4cd1.jpg)


Open Perspective 창이 하나 나타나는데 이클립스의 작업환경(모드)을 설정할 수 있다.
'Java'를 클릭 하고 Open을 누르거나 또는 'Java'를 더블 클릭한다.
![12](https://user-images.githubusercontent.com/60464237/152646120-20819c93-80f8-4977-8d8a-0abc40330cbc.jpg)


Create a Java project를 누른다.
![13](https://user-images.githubusercontent.com/60464237/152646121-b7db2ed1-bfb3-4463-84ce-ef868bf019d8.jpg)


Project name은 HelloWorld라고 입력했다.
꼭 HelloWorld로 할 필요는 없고 다른 이름으로 지정해도 된다.
따로 설정할 게 없어서 Next가 아닌 Finish를 누른다.
![14](https://user-images.githubusercontent.com/60464237/152646122-a26a5058-94b0-4137-8976-eeda768c7f81.jpg)


HelloWorld 프로젝트 하위 폴더인 src에 Class를 생성한다.
생성 방법은 src를 오른쪽 마우스 클릭하면 여러 선택 창이 나타난다.
HelloWorld > src > New > Class 
![15](https://user-images.githubusercontent.com/60464237/152646123-efc25f8e-4837-48ea-a477-fec983c08f0b.jpg)


name에 HelloWorld라고 작성하고

Which method stubs would you like to create?
☑ public static void main(String[] args)
체크 박스에 체크를 한다.

클래스를 생성할 때 메인 메서드를 만들어주는 역할이다.
![16](https://user-images.githubusercontent.com/60464237/152646124-ab7eac17-450f-4468-847b-14e8edf75847.jpg)


System.out.println("Hello World!");
라고 작성을 한 후 'Ctrl + F11'를 누르면 
Console 창에 작성한 Hello World! 가 출력되는 것을 볼 수 있다.
![17](https://user-images.githubusercontent.com/60464237/152646125-70499c2d-a165-45e0-99a6-fa9aaf2c78d4.jpg)


이클립스 IDE 정상적으로 실행이 되었고
Console 창에 다른 메시지나 실행이 안되는 경우
Java 설치 및 경로 등 잘 못 지정되는 가능성이 높다.

















### ** JDK **(Java Development kit 약자로 자바 개발 키트라고 한다.) 
+ JDK는 프로그램 개발에 필요한 자바 가상 기계(JVM)
+ 라이브러리 API, 컴파일러 등의 개발 도구가 포함되어 있다.

### ** JRE **(Java Runtime Environment 약자로 자바 실행 환경이라고 한다.)
+ JRE는 프로그램 실행에 필요한 자바 가상 기계(JVM)
+ 라이브러리 API만 포함되어 있다.
+ 자바 프로그램을 개발하는 것이 아니고, 이미 개발된 프로그램만 실행한다면 JRE만 설치하면 된다.

Oracle에서 무료로 제공되기 때문에 해당 사이트를 통해 설치를 진행하면 된다.
http://www.oracle.com


## 자바 SE 8 (JAVA 1.8 version) Download

오라클 홈페이지에 처음 접속하면 쿠키 관련 창이 나타나는데 모두 승인하면 된다.

![1](https://user-images.githubusercontent.com/60464237/151926752-767dadba-85dd-452e-9c9e-1631d47d1e09.jpeg)


1. Products 카테고리를 누른다.

2. 하위 카테고리에 Java를 누른다.

![2](https://user-images.githubusercontent.com/60464237/151926756-74bcdb7f-22a9-4703-bcc3-229a76216653.jpeg)

Java SE에 Download Java now를 누른다.

![3](https://user-images.githubusercontent.com/60464237/151926758-4748095d-74c2-42d9-b43e-2e389c02253a.jpeg)

Java 8 버전을 확인하고 OS 운영체제에 맞게 선택 후

jdk-8 u311-windows-x64.exe를 누른다.

(Windows 환경에 설치하기 때문에 Windows를 선택)

<span style="color:blue">8u311은 업데이트 내역으로 숫자는 매번 바뀐다.</span>

![4](https://user-images.githubusercontent.com/60464237/151926759-46eaa61d-8809-4873-8be5-436b16ffeb7b.jpeg)

체크 박스에 체크를 하고 Download를 누른다.

![5](https://user-images.githubusercontent.com/60464237/151926764-a939b7b5-b260-46f5-8df5-267abfe41620.jpeg)

Download를 받기 위해서 오라클 계정 로그인을 해야 한다.

회원가입은 어렵지 않기 때문에 계정 만들기를 통해 계정을 만들어준다.

무료로 다운 받을 수 있지만 계정이 없으면 다운 받지 못한다.

![6](https://user-images.githubusercontent.com/60464237/151926768-f8ec34c6-255c-4f63-a5fc-e01380d6d16a.jpeg) 
<hr>

## 자바 SE 8 (JAVA 1.8 version) Install

Download가 완료된 파일을 실행 시킨다.

"Next>"를 눌러 다음 단계로 진행하면 된다.

![7](https://user-images.githubusercontent.com/60464237/151926769-1c806691-e444-40e8-a992-477757bce29d.jpeg)


JDK 설치 경로

1. "Change..." 설치 경로를 바꿀 수 있지만 웬만해선 바꾸지 않는 게 좋다.

2. "Next>"를 눌러 다음 단계로 진행한다.

![8](https://user-images.githubusercontent.com/60464237/151926771-8f61aa3f-8dd3-49f7-bcf6-4e0c884cc28f.jpeg)

설치 진행 중...

![9](https://user-images.githubusercontent.com/60464237/151926774-47724626-8af3-40f5-aa29-db26a9476087.jpeg)

JRE 설치 경로

1. "변경(C)" 설치 경로를 바꿀 수 있지만 왠만해선 바꾸지 않는게 좋다.

2. "Next>"를 눌러 다음 단계로 진행한다.

![10](https://user-images.githubusercontent.com/60464237/151926775-caa0e0c8-ad48-4b48-b35b-2a21c6ce3f8e.jpeg)

설치 진행 중...

![11](https://user-images.githubusercontent.com/60464237/151926776-142b2254-476d-4052-8642-b8f063410cc6.jpeg)

자바 설치가 완료되었다.

"Close" 버튼을 눌러서 인스톨 파일을 종료시킨다.

![12](https://user-images.githubusercontent.com/60464237/151926777-d2e8ac08-1874-4a1c-9a21-e3eaec389e1d.jpeg)

<hr>

## 자바 SE 8 (JAVA 1.8 version) 환경변수 설정

환경변수를 설정하는 이유

JDK 내부의 bin 디렉토리는 컴파일러인 javac.exe, 자바 가상 기계(JVM) 구동 명령어인 java.exe가 포함되어 있다.

자바 프로그램 개발 시 exe라는 파일들 아주 빈번하게 사용되는데 

Java는 Windows 운영체제에서 최적화되어 있지 않기 때문에

다른 디렉토리에서 쉽게 실행할 수 있도록 환경변수를 설정해야 한다.

<hr>

내 컴퓨터 또는 내 PC 우클릭을 하면 속성(R)을 누르고 고급 시스템 설정을 누른다.

또는 윈도우 키를 누르고 고급 시스템 설정 보기 찾아서 실행한다.

![13](https://user-images.githubusercontent.com/60464237/151926780-be5e0e2d-4536-46f7-9d82-4b2945ab01fa.jpeg)

시스템 속성 팝업에 고급 카테고리에서 "환경 변수(N)..."을 누른다.

![14](https://user-images.githubusercontent.com/60464237/151926783-c5a356ef-70e4-4233-87ec-1cb38a831b57.jpeg)

환경 변수 팝업에서 시스템 변수(S) 쪽 "새로 만들기(W)..."을 누른다.

![15](https://user-images.githubusercontent.com/60464237/151926784-b67cd3de-dfac-4d74-9003-83906b1730c4.jpeg)

설정하기에 앞서 Java 설치 경로를 복사해준다.

경로는 정확해야 하기 때문에 꼭 설치 경로를 확인하고 복사해준다.

간혹 JDK 폴더가 아닌 JRE 경로를 복사하는 경우가 있으므로 잘 확인해야 한다.

![16](https://user-images.githubusercontent.com/60464237/151926786-d85ec1b4-322f-4e06-b6ab-8eae846a3969.jpeg)

변수 이름 : JAVA_HOME
변수 값 : 설치 경로 (C:\Program Files\Java\jdk1.8.0_311\bin)

확인 버튼을 눌러주면 JAVA_HOME이 생성된다.

![17](https://user-images.githubusercontent.com/60464237/151926788-800b2333-2026-4fad-8b87-75f498bd9358.jpeg)

시스템 변수에 JAVA_HOME이 추가된 것을 확인하고

Path에 JAVA_HOME을 추가해야 한다.

"편집" 버튼을 클릭한다.

![18](https://user-images.githubusercontent.com/60464237/151926789-90ec5d2c-4ad7-4b08-bf8a-77e888393174.jpeg)

"새로 만들기(N)"을 누르면 입력할 수 있는 행이 추가된다.

%JAVA_HOME% 을 입력하고 확인 버튼을 누른다.

![19](https://user-images.githubusercontent.com/60464237/151926792-a6b7294a-7130-47f3-9f4b-258aad8dfc8b.jpeg)

모든 설정이 완료되었다.

확인 버튼을 누른다.

![20](https://user-images.githubusercontent.com/60464237/151926794-86c51605-12bd-47bc-98f8-b5b158e82937.jpeg)

<hr>

## 자바 SE 8 (JAVA 1.8 version) 설치 및 설정 확인
Java 설치 및 환경변수 설정이 제대로 완료되었는지 확인해야 한다.
<hr>

명령 프롬프트를 통해 확인할 수 있다.

윈도우 키 + R 을 누르거나 또는 윈도우 키를 누른 후 cmd를 입력한다.

![21](https://user-images.githubusercontent.com/60464237/151926795-c3b0f441-e66a-4119-a5a8-cdf464916327.jpeg)

명령 프롬프트 창에서 "javac"를 입력하면

아래와 같이 메시지가 나타나면 정상적으로 컴파일러가 실행되는 것을 확인할 수 있다.

![22](https://user-images.githubusercontent.com/60464237/151926797-11137513-75f0-42f0-bc32-030d3740ee76.jpeg)

명령 프롬프트 창에서 "java -version"을 입력하면

아래와 같이 java version 메시지가 나타난다.

![23](https://user-images.githubusercontent.com/60464237/151926800-9383ab6b-668f-45d8-a005-227138ca51aa.jpeg)

설치가 정상적으로 완료되었고

해당 메시지가 다르게 나온 경우

경로 또는 설치 진행이 제대로 안되어 있을 가능성이 높다.

재설치 및 경로를 확인해서 수정한다.