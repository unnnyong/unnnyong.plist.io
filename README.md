# 이런곡으로 웹사이트

`unnnyong.plist.io/plist/`에서 제공하는 이런곡으로 앱 소개 및 고객지원 사이트입니다.

## GitHub Pages 설정

1. GitHub 저장소의 **Settings → Pages**로 이동합니다.
2. **Deploy from a branch**를 선택합니다.
3. `main` 브랜치의 `/ (root)`를 게시 대상으로 지정합니다.
4. **Custom domain**에 `unnnyong.plist.io`를 입력하고 DNS 확인 후 HTTPS를 활성화합니다.

DNS 제공자에는 `unnnyong.plist.io`의 CNAME 레코드를 `unnnyong.github.io`로 연결합니다.

AdMob 파일은 다음 주소에서 제공됩니다.

```text
https://unnnyong.plist.io/app-ads.txt
```

앱 소개와 개인정보 처리방침은 `plist/` 하위 경로에서 제공됩니다.

```text
https://unnnyong.plist.io/plist/
https://unnnyong.plist.io/plist/privacy.html
```
