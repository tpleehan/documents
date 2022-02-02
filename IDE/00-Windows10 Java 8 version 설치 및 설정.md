자바를 통해 개발을 하기 위해선 Java SE(Standard Edition)의 구현체인 JDK를 설치해야 한다.

Java SE에는 JDK와 JRE가 포함되어 있다.

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