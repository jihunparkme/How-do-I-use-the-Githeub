# Let's use the Githeub.

Let's use github well !!

<br/>


## [ write a project introduction ]
- 프로젝트 문서 = 음식의 레시피

- 모범 예제

> https://github.com/matiassingers/awesome-readme

- 포함 내용

```
프로젝트명
프로젝트 소개
설치 방법
사용 예제
개발 환경 설정 방법
변경 로그(업데이트 내역)
라이센스 및 작성자 정보
기여 방법
```

### 프로젝트명

- 제목만으로도 어떤 기술을 사용하여 무슨 프로젝트를 만들었는지 상대방이 이해할 수 있게 직관적으로 작성

- 사용 기술, 분야, 주제 등 태그 추가

- 프로젝트 소개 웹 사이트도 추가

- gh-pages, heroku, surge.sh 등 무료 호스팅 서비스를 적극 활용

### 프로젝트 소개

- 짧은 소개 문구와 한 문단 분량의 프로젝트 내용 작성
- 프로젝트의 목적, 동기, 주요 기능이 잘 드러나 있어야 함
- 사용자에게 프로젝트 실제 데모를 보여주는 것이 중요
- 녹화가 필요할 경우
  ```
  1.스크린 캡쳐 프로그램으로 녹화
  2.git 파일로 변환
  3.유튜브에 올리고 링크
  ```

- 추가로 [shields.io](https://shields.io/) 에서 뱃지를 선택해 배포, 소셜 네트워크, 코드 커버리지, 다운 수, 버전 등을 명시해 더 시각적으로 표현 가능
### 설치 방법

- 사용자가 설치를 쉽게 할 수 있도록 최대한 자세하고 친절하게 작성

- 가능한 사용자가 간단한 명령어로 설치를 끝내도록 설치 과정을 간결히

- 운영체제(Windows/OS X/Linux ...)별 설치 방법도 작성

### 사용 예제

- 설치 이후 실제 사용 방법 가이드 작성
- 코드 예제와 실제 적용 사례를 보여줌

### 개발 환경 설정 방법

- 잠재적이 기여자가 프로젝트에 기여할 수 있도록 명확한 가이드 제시
- 신규 소프트웨어 빌드 및 릴리즈 하는 방법도 작성

### 기여 방법

- 프로젝트에 관심을 가진 누군가 직접 기여할 수 있도록 개발 프로세스와 기여 방법에 관한 명확한 지침을 제공

### 로그 변경

- 기능 개선과 수정 내역을 함축적으로 정리하여 로그 변경 히스토리를 관리

### 크레딧

- 이 프로젝트에 도움을 준 누군가를 꼭 언급해주기

### 라이센스

- 라이센스를 명시하고 디렉터리에 LICENSE.txt를 포함
- 오픈 소스 라이센스 사이트에서 라이센스 목록 확인 가능
  영문 : <https://choosealicense.com/>
  국문 : <https://www.olis.or.kr/license/licenseGuide.do>
- 가장 많이 사용하는 라이센스는 MIT, Apache 2.0, ISC, BSD 라이센스

### 연락처

- 신뢰성을 위해 프로젝트 담당자 또는 팀원들의 깃허브 프로필 링크, SNS, 이메일 등 연락처를 기입

<br/>


## [ Commit ]

- 작은 단계로 커밋하여 코드 개발 과정을 가시적으로 보여줘함.

- 메서드 리팩터링이나 새로운 메서드 또는 클래스를 추가할 때마다 커밋

- 실험이나 성능 튜닝을 할 때도 각 단계별로 커밋

- 소스 코드 변경 내역이 없을 때는 커밋 X


커밋할 목록에 파일 추가

```
$ git add [fileName] or -A
```

커밋하기

```
$ git commit -sm "[commit message]"
```

Github 원격 저장소에 push

```
$ git push [name] master
```
-----

repository 변경 사항 확인

```
$ git diff
```

git 상태 확인

```
$ git status
```

log 확인

```
$ git log
```

--------------

새로운 Github 원격 저장소 등록 시

```
$ git remote [alias] [repository URL]
```

별칭, 원격 저장소 확인

```
$ git remote -v
```

로컬에 새로운 폴더를 생성했을 경우 git 초기화

```
$ git init
```

- Another way to manage git : [git_management](https://github.com/jihunparkme/How-do-I-use-the-Githeub/blob/master/git_management.md)

<br/>

## [ Commit Message ]

1. 제목(Title)

2. 본문(Body)

3. 꼬리말(Footer)

### Type: 제목(Title)
- 커밋 제목

> Docs: Edit README.md to include New Features Use-Cases

이와 같은 방법으로 작성 (총 글자 수 50자)

- 타입 라벨 

```
feat: 새로운 기능을 추가할 경우
fix: 버그를 고친 경우
docs: 문서 수정한 경우
style: 코드 포맷 변경, 세미 콜론 누락의 경우(코드 수정이 없는 경우)
refactor: 프로덕션 코드 리팩터링
test: 테스트 추가, 테스트 리팩터링 (프로덕션 코드 변경 없음)
chore: 빌드 테스크 업데이트, 패키지 매니저 설정할 경우 (프로덕션 코드 변경 없음)
```

### 본문(Body)

- 컷밋의 상세 내용 작성 (한 줄에 72자 이내로 작성)
- 문단을 사용해 내용을 구분하면 좋음

### 꼬리말(Footer)

- Issue Tracker ID를 추가

> Resolves : #94
See also : #123, #456

<br/>

참고：<http://sujinlee.me/professional-github/>