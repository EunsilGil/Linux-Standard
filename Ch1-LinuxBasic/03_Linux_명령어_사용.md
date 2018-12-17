# Linux 명령어 사용

## Basic

* Ubuntu Unity에서 terminal을 이용하여 명령어 입력 및 사용이 가능하다.

* terminal 창의 기본 directory는 해당 사용자의 home directory에 위치한다.

  * terminal 창 상단에 적혀있는 제목으로  home directory를 확인할 수 있다.

  `Ex. user name @ host name(ubuntu system 자체를 의미) : ~(user의 home directory를 의미)`

## Linux 명령 행 편집

* 하나의 문자 삭제 : `Backspace`
* 하나의 단어 삭제 : `ctrl`+w
* 해당 행의 내용을 모두 삭제 : `ctrl`+u

## Linux 명령어 구조

* 형식

  `명령 [옵션] [인자...]`

* 명령 

  *  Linux에는 수백가지가 넘는 명령이 존재하므로 지금 당장은 기초적인 몇가지 명령어에 대해서만 다루도록 하겠다.

* 옵션 

  * `-`기호로 시작
  * 옵션을 사용하여 명령의 세부 기능을 선택할 수 있다.

* 인자

  * 명령으로 전달되는 값으로, 주로 `파일명 or 디렉터리명`이 사용된다.

  ##### 옵션과 인자는 각 명령에 따라 필요와 구성이 달라지므로, 사용하고자 하는 명령의 사용법을 반드시 참조해야 한다.

## 기초 명령어

* date : 날짜와 시간을 출력
* **clear** : 현재 보이는 화면을 완전히 지움
* man : Linux가 제공하는 명령의 사용법을 제공
  * man 을 실행할 때 출력되는 결과

    ~~~markdown
    - NAME : 명령에 대한 간략한 설명
    - SYNOPSIS : 명령의 사용법 요약
    - DESCRIPTION : 명령에 대한 상세한 설명
    ~~~

     등이 제공된다.

* passwd : 사용자(user) 계정의 비밀번호를 변경
* **exit** : 터미널 종료

