# 포켓베이스와 스벨트킷으로 인증 서비스 구현

![세션 방식의 인증](attachments/20231029215129.png)

![JWT 방식의 인증](attachments/20231029215203.png)

![OAuth 방식의 인증](attachments/20231029215222.png)

![인증 구현](attachments/20231029220447.png)

## Pocketbase 설치
https://pocketbase.io/docs/

Pocketbase 실행
```bash
$ ./pocketbase serve
2023/10/30 13:30:20 Server started at http://127.0.0.1:8090
├─ REST API: http://127.0.0.1:8090/api/
└─ Admin UI: http://127.0.0.1:8090/_/
```

## SvelteKit 프로젝트 생성

SvelteKit 프로젝트 생성
```bash
$ npm create svelte@latest app
$ cd app
$ npm install
```

SvelteKit 프로젝트 실행
```bash
$ npm run dev
```

## Picocss 설정
https://picocss.com/docs/

app.html에 추가
```html
<**link** _rel_="stylesheet" _href_="https://cdn.jsdelivr.net/npm/@picocss/pico@1/css/pico.min.css">
```

## nav layout 추가
https://picocss.com/docs/navs.html
