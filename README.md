### Commit !!!

- 작은 단계로 커밋하여 코드 개발 과정을 가시적으로 보여줘함.
- 메서드 리팩터링이나 새로운 메서드 또는 클래스를 추가할 때마다 커밋
- 실험이나 성능 튜닝을 할 때도 각 단계별로 커밋
- 소스 코드 변경 내역이 없을 때는 커밋 X

# [ Project Title ]

# [ write a project introduction ]
프로젝트 문서 = 음식의 레시피

모범 예제
> https://github.com/matiassingers/awesome-readme

포함 내용
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

# [ Commit Message ]
`제목(Title)`

`본문(Body)`

`꼬리말(Footer)`


- #### Type: 제목(Title)
  커밋 제목은 
  
  > Docs: Edit README.md to include New Features Use-Cases
  
  이와 같은 방법으로 작성 (총 글자 수 50자)
  
  타입 라벨 :
  > feat: 새로운 기능을 추가할 경우
fix: 버그를 고친 경우
docs: 문서 수정한 경우
style: 코드 포맷 변경, 세미 콜론 누락의 경우(코드 수정이 없는 경우)
refactor: 프로덕션 코드 리팩터링
test: 테스트 추가, 테스트 리팩터링 (프로덕션 코드 변경 없음)
chore: 빌드 테스크 업데이트, 패키지 매니저 설정할 경우 (프로덕션 코드 변경 없음)

- #### 본문(Body)
컷밋의 상세 내용 작성 (한 줄에 72자 이내로 작성)
문단을 사용해 내용을 구분하면 좋음

- #### 꼬리말(Footer)
Issue Tracker ID를 추가
> Resolves : #94
See also : #123, #456


출처：<http://sujinlee.me/professional-github/>