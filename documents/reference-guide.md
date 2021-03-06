글자크기테스트입니다.
# 강아지
## 강아지
### 강아지
#### 강아지
##### 강아지
###### 강아지
강아지

> 여기는 어디일까요? ㅎㅎ    

![[크기변환]001](reference-guide.assets/[크기변환]001_cplmy6vbe.jpg)

# 컨테이너환경 표준 프레임워크 가이드
> 본 문서는 표준 프레임워크 환경에서 어쩌구 저쩌구  
> 본 문서를 PC에서 보는 경우 [Chrome 브라우져 최신버젼](https://www.google.com/intl/ko/chrome/)에서 보는 것을 권장합니다.  
> _2020.11.21 lnijtsy_

이 가이드는 테스트 가이드 입니다.
만나서 방가방가방가

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
Quick Start 는 다음과 같은 순서로 진행한다.
1. [소프트웨어 설치](https://github.com/ytsyts77/test-project/blob/main/reference-guide.md#%EC%86%8C%ED%94%84%ED%8A%B8%EC%9B%A8%EC%96%B4-%EC%84%A4%EC%B9%98)
2. [JAVA_HOME 설정](https://github.com/ytsyts77/test-project/blob/main/reference-guide.md#java_home-%EC%84%A4%EC%A0%95)
3. [Path 설정](https://github.com/ytsyts77/test-project/blob/main/reference-guide.md#path-%EC%84%A4%EC%A0%95)
4. [프로젝트 복사](https://github.com/ytsyts77/test-project/blob/main/reference-guide.md#%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EB%B3%B5%EC%82%AC)
5. [프로젝트 실행](https://github.com/ytsyts77/test-project/blob/main/reference-guide.md#%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%8B%A4%ED%96%89)

### 소프트웨어 설치

표준 프레임워크 개발을 위해서는 아래의 항목들이 설치되어 있어야 한다.
* [Chrome Browser](https://github.com/ytsyts77/test-project.git)

* [AdoptOpenJDK 1.8](https://github.com/ytsyts77/test-project.git)

* [AdoptOpenJDK 11](https://github.com/ytsyts77/test-project.git)

* [Visual Studio Code](https://github.com/ytsyts77/test-project.git)

* [Git](https://github.com/ytsyts77/test-project.git)

* [Maven](https://github.com/ytsyts77/test-project.git)

* [SourceTree](reference-guide.assets/SourceTreeSetup-3.3.9.exe)

상단의 링크들을 클릭하여 설치를 진행한다.
설치시의 경로는 디폴트로 설정된 값 그대로 설치를 진행하는 것을 권장한다.

> Visual Studio Code 는 앞으로 VScode 라고 표현 하겠다.

### JAVA_HOME 설정

[^a]: 설명입니다.

### PATH 설정

<img src="reference-guide.assets/001-1605398072177.jpg" style="zoom:33%;" />

### 프로젝트 복사
1. 윈도우에서 CMD 창을 오픈한다.
2. 아래의 명령어를 순서대로 실행하면 자동으로 [Hello World 프로젝트](https://github.com/ytsyts77/test-project)의 리모트 저장소가 로컬로 복사가 되고 vscode 를 통해 프로젝트가 오픈된다.

```cmd
D:
cd D:\KBINSDEV
git clone https://github.com/ytsyts77/test-project.git
cd test-project
code .
```


### 프로젝트 실행
1. F5 를 눌러서 Hello World 어플리케이션을 실행한다.
1. 웹브라우져를 열어 http://localhost:9090/hello 에 접속하면 아래와 같이 문구가 보이는 것을 확인할 수 있다.


## CICD


## 프레임워크 - Spring Boot

## 퍼시스턴트 레이어 - MyBatis

## 형상관리 - Git
### Git, GitLab 개요
### 필수 명령어

1. [유튜브 사이트](https://www.youtube.com/)에 접속한다.
2. 뭐를 검색한다.

git 사용을 위해서는 우선 git 에 대한 지식을 가져야 한다. git 에 대한 기본 지식은 [Pro Git Book](https://git-scm.com/book/ko/v2) 등의 자료를 통해 스스로 익혀야 한다.  
git 의 명령어중 개발자가 반드시 알아야할 명령어는 다음과 같다.

* `git-status` 현재 상태를 확인 한다.
* `git-add` Modified 상태의 파일을 Staging 상태로 변경한다.
* `git-commit` Staging 상태의 파일을 Commited 상태로 변경한다.
* `git-clone` 리모트 저장소를 로컬 저장소로 복사한다.
* `git-push` 로컬 저장소의 현재 브랜치의 내용을 서버로 전달한다.
* `git-pull` 현재 브랜치의 서버 저장소의 내용을 로컬 저장소로 가져온다.
* `git-merge` 다른 브랜치의 커밋 내용을 현재 브랜치로 병합한다.

### VScode 에서 Git 사용법
### SourceTree

## 프로젝트관리 - Maven
### Maven 소개
### Dependency 추가 방법
### 새로운 Artifact 등록 방법
