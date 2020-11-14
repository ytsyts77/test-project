글자크기테스트입니다.
# 강아지
## 강아지
### 강아지
#### 강아지
##### 강아지
###### 강아지
강아지

> 여기는 어디일까요? ㅎㅎ

![[크기변환]001](/assets/[크기변환]001_zxiriywk6.jpg)

# 컨테이너환경 표준 프레임워크 가이드
> 본 문서는 표준 프레임워크 환경에서 어쩌구 저쩌구  
> 본 문서는 [Chrome 브라우져 최신버젼](https://www.google.com/intl/ko/chrome/)에서 보는 것을 권장합니다.  
> _2020.11.21 lnijtsy_

이 가이드는 테스트 가이드 입니다.
만나서 방가

## 목차
1. [Quick Start - Hello World](https://github.com/ytsyts77/test-project/blob/main/README.md#quick-start---hello-world)
1. [표준 프레임워크 소개](https://github.com/ytsyts77/test-project/blob/main/README.md#%ED%91%9C%EC%A4%80-%ED%94%84%EB%A0%88%EC%9E%84%EC%9B%8C%ED%81%AC-%EA%B0%9C%EC%9A%94)
1. [CICD](https://github.com/ytsyts77/test-project/blob/main/reference-guide.md#cicd)
2. [프레임워크 - Spring Boot](https://github.com/ytsyts77/test-project/blob/main/README.md#%ED%94%84%EB%A0%88%EC%9E%84%EC%9B%8C%ED%81%AC---spring-boot)
3. [퍼시스턴트 레이어 - MyBatis](https://github.com/ytsyts77/test-project/blob/main/README.md#%ED%8D%BC%EC%8B%9C%EC%8A%A4%ED%84%B4%ED%8A%B8-%EB%A0%88%EC%9D%B4%EC%96%B4---mybatis)
4. [형상관리 - Git](https://github.com/ytsyts77/test-project/blob/main/README.md#%ED%98%95%EC%83%81%EA%B4%80%EB%A6%AC---git)
5. [프로젝트관리 - Maven](https://github.com/ytsyts77/test-project/blob/main/README.md#%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%EA%B4%80%EB%A6%AC---maven)

## 표준 프레임워크 개요

## Quick Start - Hello World

### GitLab 가입하기

### 소프트웨어 설치

표준 프레임워크 개발을 위해서는 아래의 항목들이 설치되어 있어야 한다.
* [AdoptOpenJDK 1.8](https://github.com/ytsyts77/test-project.git)
* [AdoptOpenJDK 11](https://github.com/ytsyts77/test-project.git)
* [Visual Studio Code](https://github.com/ytsyts77/test-project.git)
* [Git](https://github.com/ytsyts77/test-project.git)
* [Maven](https://github.com/ytsyts77/test-project.git)

상단의 링크들을 클릭하여 설치를 진행한다.
설치시의 경로는 디폴트로 설정된 값 그대로 설치를 진행하는 것을 권장한다.

> Visual Studio Code 는 앞으로 VScode 라고 표현 하겠다.

### JAVA_HOME 설정

### PATH 설정

### Sample 프로젝트 가져오기
아래와 같이 명령어를 실행하면 프로젝트가 가져와지고 실행된다.
```dos
<cmd 창을연다>
D:
cd D:\KBINSDEV
git clone https://github.com/ytsyts77/test-project.git
cd test-project
code .
```


### Hello World 테스트하기
F5 를 눌러스 샘플 어플리케이션을 실행한다.

웹브라우져를 열어 http://localhost:9090/hello 에 접속하면 아래와 같이 문구가 보이는 것을 확인할 수 있다.


## CICD


## 프레임워크 - Spring Boot

## 퍼시스턴트 레이어 - MyBatis

## 형상관리 - Git
### Git, GitLab 개요
### 필수 명령어
git 사용을 위해서는 우선 git 에 대한 지식을 가져야 한다.  
git 에 대한 기본 지식은 git book 등의 자료를 통해 스스로 익혀야 한다.
git 에서 제공하는 명령어중 아래의 명령어는 개발 진행을 위해 반드시 알아야 한다.  

* `git status` 현재 상태를 확인 한다.
* `git add` Modified 상태의 파일을 Staging 상태로 변경한다.
* `git commit` Staging 상태의 파일을 Commited 상태로 변경한다.
* `git clone` 리모트 저장소를 로컬 저장소로 복사한다.
* `git push` 로컬 저장소의 현재 브랜치의 내용을 서버로 전달한다.
* `git pull` 현재 브랜치의 서버 저장소의 내용을 로컬 저장소로 가져온다.
* `git merge` 다른 브랜치의 커밋 내용을 현재 브랜치로 병합한다.

### VScode 에서 Git 사용법
### SourceTree

## 프로젝트관리 - Maven
### Maven 소개
### Dependency 추가 방법
### 새로운 Artifact 등록 방법
