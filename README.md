# LINKGENESIS Industrial SI Site

링크제니시스의 AI, 반도체·디스플레이·배터리 장비 소프트웨어 및 공장 자동화 SI 역량을 소개하는 정적 웹사이트입니다.

## 실행

`dist/index.html`을 브라우저에서 열거나 정적 웹 서버의 루트로 `dist` 폴더를 지정하세요.

예시:

```powershell
python -m http.server 4173 --directory dist
```

브라우저에서 `http://127.0.0.1:4173/`에 접속하면 됩니다.

## 구성

- `dist/index.html`: 전체 사이트(스타일 및 상호작용 포함)
- `.openai/hosting.json`: Sites 정적 호스팅 설정
