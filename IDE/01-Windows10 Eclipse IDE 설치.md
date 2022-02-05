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

## Eclipse Download & Install

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


## Eclipse IDE 실행 및 Hello World! 출력

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

<hr>


이클립스 IDE 정상적으로 실행이 되었고

Console 창에 다른 메시지나 실행이 안되는 경우

Java 설치 및 경로 등 잘 못 지정되는 가능성이 높다.
