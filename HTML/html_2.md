# HTML DAY02

1. `<html> </html>` 태그 안에
2. `<head> </head>` 태그(제목) 와
3. `<body> </body>` 태그(내용) 로 이루어진다
4. `<style>{}</style>태그로 꾸미기(CSS)
```
<style> 
a {
    color : orange;
}
</style>
```

- `<a href="이동할 웹 사이트 주소"> </a>` : 태그 사이에 있는 내용이 하이퍼 텍스트로 변환되어 연결된 웹 페이지가 나온다
  - `<a href="이동할 웹 사이트 주소" target="_blank"> ..내용.. </a>`
  - target="_blank" 는 새 창에서 해당 링크를 열어주는 코드이다
  - title="html5 tooltip" 은 마우스를 올렸을 때 따옴표 안 내용이 나온다


## 페이지 만들기
- 웹 사이트 시작 페이지는 `index.html`로 많이 사용한다
```클릭 : 웹브라우저 실행 -> 주소입력 -> 웹서버로 이동-> 웹서버는 index.html을 클라이언트에게 전달 -> 클릭:웹브라우저가 해석 -> 해석 결과를 화면에 출력```

- 웹 호스팅 : 웹서버 컴퓨터를 빌려주는 것
- 호스트(host):인터넷에 연결된 컴퓨터
- static 웹 호스팅 서비스