# opensw
2024오픈소스sw  과제

----
#### 리눅스 명령어 [top]
----

## 리눅스 명령어 top이란?

리눅스에서 실행 준인 프로세스들의 현재 상태와 시스템 리소스 사용량을 실시간으로 모니터링하는 유틸리티이다.


###### 사용법 

`root#> top` 명령어를 치면된다.

화면![image](https://github.com/prettyburger1/opensw/assets/170292434/8328d626-bc83-4c00-8586-32eaf696c1b7)

---

###### top 실행 전 옵션 

1 순간의 정보를 확인하려면 `-b` 옵션 추가

2 `-n:top` 실행 주기 설정(반복 횟수)

---
###### 실행 후 명령어

`shift + p :` CPU 사용률 내림차순

`shit + m :` 메모리 사용률 내림차순

`shift + t :` 프로세스가 돌아가고 있는 시간 순

__등등이 있다.__

---
#### 리눅스 명령어 [ps]
---

## 리눅스 명령어 ps란?

ps명령어는 동작 중인 프로세의 상태를 출력해주는 명령입니다.

**ps의 옵션
> 전통적인 유닉스인 System V, BSD, GNU에 따라 결과가 다르게 나타나고, 표기법에도 차이를 보여준다.

__System V 계열__
> 옵션 사용 시, 1개의 __대시(Dash,-)를 사용한다.

__BSD 계열__
> 옵션 사용시, 대시(-)를 사용하지 않는다.

__GNU 계열__
> 옵션 사용 시, 2개의 대시(--)를 사용한다.



##### 사용법

`ps [option]`

###### ps명령의 주요 옵션!

ps명령어의 주요 옵션![image](https://github.com/prettyburger1/opensw/assets/170292434/32c9068a-8935-48c5-8fef-b28a82043345)

등등이 있다.

---
### ps와 top의 차이점

>ps는 ps한 시점에서 proc에서 검색한 cpu 사용량

>top은 proc에서 일정 주기로 합산해 cpu 사용율 출력한다.
---

## 리눅스 명령어 jobs란?

>jobs 명령어는 백그라운드로 실행된 프로그램이나 "<Ctrl> + z"를 입력하여 실행한 프로그램에 대해서 확인하는 명령어 입니다.

#### jobs 사용법

사용법 : `jobs [option]

추가옵션![image](https://github.com/prettyburger1/opensw/assets/170292434/97e02e52-93bf-4b18-b602-0c4d8874ab73)

##### jobs tmi

tmi 내용![image](https://github.com/prettyburger1/opensw/assets/170292434/5cbe4bf4-aec8-4bc4-9ac7-d73df2cf8ce9)

> '&'가 있음과 없음에 따라서 멈춰있는 상태 또는 실행 준인 상태임을 알려준다.
---

## 리눅스 명령어 kill이란?

