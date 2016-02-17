# Safari Ko Readability
사파리 환경에서 한글 가독성을 향상시키는 CSS 파일입니다. Apple SD Gothic Neo 기준으로 제작되었으며, 지속적으로 보완할 예정입니다. 사파리 익스텐션 개발은 고민 중입니다.

추가적으로, 터미널 앱을 실행하여 아래와 같은 명령어를 입력해주세요.

```shell
# 사파리 웹킷 기본 폰트 변경
$ defaults write com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2StandardFontFamily 'AppleSDGothicNeo-Regular'

# 선택사항: 사파리 웹킷 기본 고정폭 폰트 변경
$ defaults write com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2FixedFontFamily '임의의 고정폭 폰트'
```

------
## Problems
- [ ] 네이버 블로그, 카페 등에서 일부 적용되지 않음.
- [ ] font-family에 명시된 폰트가 존재하지 않을 경우 적용되지 않음.
