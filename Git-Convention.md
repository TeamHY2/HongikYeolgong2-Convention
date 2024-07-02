## Git Branch Strategy

### Git-Flow
<img src="https://github.com/TeamHY2/HongikYeolgong2-Convention/assets/22425650/775c28d1-6ec3-425e-bc09-bc1b1b451fe5" width="50%" height="50%">

## Branch Name

`{Type}/#{issue number}-{decription}`

Type의 예는 다음과 같습니다.
- Feature
- Chore
- Infra
- Refactor
- Test
- Style
- etc..

## Git Commit

> AngularJS의 Git Commit Convetion을 기반에 두고 있습니다.

### Commit Message

```
<type>: <subject>
<BLANK LINE>
<body>(optional)
```

가독성을 위해 모든 줄은 50자를 넘지 않도록 합니다.

 **`<type>` 에 올 수 있는 태그들**

- feat (feature)
- fix (bug fix)
- docs (documentation)
- style (formatting, missing semi colons, …)
- refactor(refactoring)
- test (when adding missing tests)
- chore (maintain)

**`<subject>`**

제목에는 변경 사항에 대한 간결한 설명이 포함됩니다.

**`<body>`**

제목에 커밋의 의도를 정확하게 표현하기 어려울 때 선택적으로 부가설명을 위해 작성합니다.

## Pull Request
- **Pull Request에는 다음과 같은 내용이 포함되어야 합니다.**
  - AS-IS
  - TO-BE
  - 연관 이슈
  - 리뷰어에게 할 말
  - 스크린샷(optional)

- **Pull Request는 변경사항 300줄 내외로 나눠서 작성합니다.**
- 최소 **1**명에게 리뷰를 받아야 합니다.
- 리뷰는 **24**시간이내 해야합니다.


