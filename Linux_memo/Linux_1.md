#### 오늘 하루엔 뭐했니?
#### 그냥 적어봐! LEE렇게!
___
**2020.04.03 LEE'Today_회고록**
> **목차**
	1. 운영체제와 리눅스의 기초
    
## 1. 운영체제와 리눅스의 기초
먼저 우리는 운영체제란 것이 무언인지 알 필요가 있다!
운영체제는 대게,
* 웹 : Windows10, macOS, ubuntu
* 모바일 : 안드로이드, Windows, IOS, 블랙베리

등이 있다.

### 1-1. 운영체제 정의
운영체제는 모든 하드웨어와 모든 소프트웨어를 관리하는 관리자다.
![](https://images.velog.io/images/ieed0205/post/4b2b20db-b894-4d45-a2fb-a277fae3935a/1.PNG)
> **특징**
* Hardware 위에 OS가 설치된다.
* OS는 Hardware와 응용프로그램을 관리한다.
* OS위에 응용프로그램들이 설치된다.
* User들은 해당 응용프로그램들을 사용하게 된다.
>> * 여기서 응용프로그램은?
  응용소프트웨어라고도 한다.
  즉, OS는 Hardware와 응용소프트웨어를 연결하는 역할이다.
  
  
  
### 1-2. 리눅스(Linux)


> **특징**
* 오픈소스 형태로 배포
>
  >>**오픈소스란?**
  : 소스코드를 일반에게 공개하고 누구나 자유롭게 사용할 수 있는 상태로 만드는 것을 말함
  >
* 다양한 종류의 리눅스가 존재
* 저렴하다
* 사용자 입장에서 편리하다고 여겨지는 것을 실현할 수 있음
* 사용자의 목소리가 전달되기 쉬움
* 빠르고 효과적으로 개선과 신기능 개발
---
> **장점**
* 높은 신뢰성
* 다중 사용자 및 다중 처리 시스템
* 완전히 공개된 시스템
* 뛰어난 네트워크 환경 지원
* 다양한 네트워크 환경 지원
* 다양한 파일 시스템 지원
* 뛰어난 이식성
* 유연성과 확장성
* 안정성과 보안성
---
> **단점**
* 기술지원 부족
* 특정 하드웨어 지원 부족
* 사용자의 숙력된 기술 요구
* 다소 불편한 사용자

### 1-3. 유닉스(Unix)
유닉스를 아시나요??
유닉스는 원조 OS로 초창기 개발자들에게 유료로 배포되어진 운영체제입니다.
하지만 유료이기에 많은 개발자들이 참여하진 못했죠.
그래서 무료버전인 Linux가 현재 인기를 끌고 있습니다!

![](https://images.velog.io/images/ieed0205/post/11e68490-1e1b-4397-a427-2e0c264248d4/123213.PNG)
> **Linux**
- 리눅스는 오픈 소스형태를 가지고 초보 개발자들도 누구나 개발에 참여할 수 있고, 무료여서 더욱 인기를 끌었습니다!
- 핀란드의 대학원생인 리누스 토발즈에 의해 처음 개발되었습니다.
>
* Redhat
* Debias
* Ubuntu
* Mint
* Suse

> **Windows**
- 윈도우즈는 빌게이츠가 Unix를 기초로 만들었지만 개인 개발요소가 더 들어가 사용자에게 더 편리하게 다가간 운영체제입니다.
- 현재 우리가 쓰고있는 Windows 10도 그중 포함되어있죠!
>
* MS-DOS
* MS-Windows

> **Mac OS**
- 맥OS는 애플사에서 만들어지고 있는 흔히 보는 사과! 입니다.
- 해당 운영체제도 Unix를 바탕으로 만들어졌습니다.
>
* Macintosh
* Mac OS
* IOS

### 1-4. 리눅스(Linux 구조)
![](https://images.velog.io/images/ieed0205/post/d4cc9a6b-4444-4db7-b497-e1682b54a819/12321321.PNG)
> **Linux Kernel Map**
![](https://images.velog.io/images/ieed0205/post/b36faacb-8a65-4649-8737-91d544b04791/Screenshot%202020-04-04%20at%2015.17.19.jpg)

리눅스의 구조는 다음과 같이 어플리케이션, 쉘, 커널로 구성되어 있습니다.

### 1-5. 리눅스 커널 버전 역사
>
* V.2.0(1997) : 멀티프로세싱(SMP)지원, 커널 모듈 동적로드
* V.2.2(1999) : 파일마운트(autofs), MCA 버스지원, PCI 변경
* V.2.4(고성능서버의 기반)
  : 엔터프라이즈급 서버지원, 물리메모리 64G 이상, 프로세스 무한대
* V.2.5(모바일장비도 가능)
  : 임베디드 CPU지원, MUMA머신 지원, 하이퍼스레딩 지원, 대용량 I/O 처리, 무선디바이스 강화
>
>
* 2017-12기준엔 v4.14 
지금은 엄청 발전했겠죠??

### 1-6. 리눅스 배포판??
사용자의 사용을 쉽게하기 위해 편리하도록 리눅스 커널에 각종 응용 프로그램(패키지)을 결합하여, 독립적으로 배포하도록 하네요!
ex) Ubuntu(우분투), Mint(민트), Fedora(페도라), CentOS(센트OS)...

리눅스 자체는 무료이지만 해당 배포판은 유료일수도 있다는 점!
알아봅시다!

> **데비안(Debian) 계열**
* 서버의 목적보다 개인 사용자가 PC에서 쓰기 적합
* 지속적인 기술 업데이트
>
>> **ubuntu(우분투)**
>> * 사용자의 편의성에 초점
>> * GUI가 잘되어있어 초보에게 적합
>> * 연2회 정기 업데이트, 2년에 1회 장기 업데이트
>
>> ** Mint(민트)**
>> * 우분투 기반으로 제작된 OS
>> * 자바, 웹 플러그인 등을 사용하기 편함
>> * 수시 업데이트
>
> **레드햇(Redhat) 계열**
* 서버용 OS가 목적으로 보안, 안정성이 뛰어남
* 업데이트보단, 안정성이 우선.
>
>> **Fedora(페도라)**
>> * 레드햇에서 개인용과 엔터프라이즈용을 구분
>> * 오픈소스 기반으로 컴퓨터 최신기술 선도가 목표
>> * 배포 간격과 이전버전 지원기간이 짧음
>
>> **CentOS(센트OS)**
>> * 레드햇엔터프라이즈 리눅스를 그대로 계승
>> * 무료 기업용 OS
>> * 기업에서 무료 서버용 리눅스를 활용하는 장점
>
>> 해당 리눅스 공부는 CentOS 7버전을 이용할 것입니다!
>>
>> **이유?**
>> * 서버용 운영체제를 사용가능
>> * 생물 정보들은 고성능 서버에서 돌려야하고 사용이 많기 때문에,
CentOS를 활용.

### 1-7. GUI(Windows 10) vs CUI(Linux)?
* GUI(Graphic User Interface)는 뭔가?
: 윈도우즈 탐색기, 엑셀 등. 마우스로 클릭하면서 사용할 수 있는 것!

* CUI(Character User Interface)는 뭔가?
: 명령프롬포트(cmd)에서 직접 디렉토리를 옮겨다니면서 사용한다!
~~( cd.. cd ___, ls ?)~~

> **GUI는 Windows 10!**
* GUI기반으로 많은 사람들이 범용적으로 쓸 수 있도록 만들어진 OS
* 폴더 생성, 파일 생성 및 작성 등 어떤 작업을 하려고 할 때,
하려는 기능들이 그래픽 요소로 보여 쉽게 사용.
* 내부 기능은 모두 공개가 아니고, 안정성 문제로 내부 시스템을 수정할 수 없다.
* 유료 라이센스!

> **CUI는 Linux!**
* CUI 기반으로 명령행을 이용하여 모든 작업을 수행.
* 리눅스 종류에 따라 준수한 GUI를 지원하는 경우도 있음!
* 오픈소스 기반으로 모든 사용자가 모든 기능들을 직접 수정할 수 있음.(작업환경 구성 용이)
* 오픈 소스 (무료 라이센스 - GPL)
* 분석에 사용하려는 개발 환경을 구성하기 용이하여 직접 분석 프로그램을 작성할 수 있음.
* 과학분야(생물정보) 많은 도구들이 리눅스에서 만들어짐.

> **Windows 10 vs Linux**
사용자가 편리하게 사용할 수 있는 Windows 10의 GUI 환경이냐,
조금 불편해도 안전하게 구동이 가능한 Linux의 CUI 환경의 차이이다.

### 1-8. Why? Linux를 사용하냐?
계속 반복되는 내용을 보여드려야 머릿속에도 오래 남는답니다 ㅎㅎ...
시작!
> 
* 오픈소스 기반으로 대부분의 리눅스가 무료로 사용 가능함
* 서버용 프로그램은 사용이 편리한 GUI이기 보단, 장시간 안정적인 CUI 환경이 많음.
* 서버용 운영체제로 널리 사용된. (최근 유닉스들이 리눅스로 변경된다)
* 다수가 사용하고 기여함으로써 보다 더 보안에 강력하고 안정적이며 신기술에 활용이 가능함.
* 소프트웨어 개발과 관련된 많은 오픈소스 프로그램을 쉽게 사용할 수 있음.
* 과학분야(생물 정보 등) 사용되는 수많은 도구들이 리눅스 환경에서 개발됨.

> 사용자 인터페이스는 PC운영체제, 서버 컴퓨팅은 리눅스 운영체제에서!

### 1-9. 바쁜 당신을 위한 요약정리!
>**Summary**
* 운영체제는 컴퓨터 하드웨어와 응용 소프트웨어를 연결한다.
* 리눅스는 오픈소스 기반의 무료 운영체제로, 리누스 토발즈에 의해 처음 개발되었다.
* 리눅스는 CUI기반으로 파일 생성, 복사, 삭제 등 대부분의 기능들을 명령어로 통해 작업할 수 있으며, 대부분의 오픈 소스 프로그램을 쉽게 활용이 가능.
* 빠른 업데이트를 제공하는 데비안 계열(Ubutu, Mint)
* 안정적인 레드햇 계열의 배포판이 존재(Fedora, CentOS)
* 과학분야, 생물정보에 사용되는 많은 분석도구가 리스트를 기반으로 만들어져 활용되어지고 있다.

#### 기억보단 기록하자! LEE'Today로!