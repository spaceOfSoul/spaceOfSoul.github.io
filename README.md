# spaceOfSoul.github.io

유창현의 프로젝트와 이력을 소개하는 개인 사이트입니다. 빌드 과정 없는 HTML과 CSS로 되어 있습니다.

주소: https://spaceofsoul.github.io/

## 미리보기

저장소 폴더에서 아래 명령을 실행한 뒤 http://localhost:8000 을 엽니다.

```sh
python -m http.server 8000
```

`index.html`을 더블클릭해도 볼 수 있지만, `404.html`은 서버로 열어야 스타일이 적용됩니다.

## 프로젝트 추가

간단히 올릴 때는 3번만 하면 됩니다. 소개 페이지가 필요할 때 1, 2번을 함께 합니다.

1. `projects/9omoku.html`을 복사해 `projects/프로젝트-이름.html`로 저장하고 내용을 바꿉니다.
2. 스크린샷은 `assets/img/`에 넣고 새 페이지의 `<img>` 경로와 크기를 바꿉니다.
3. `index.html`의 `<li class="project">` 블록을 복사해 날짜 순서에 맞게 추가합니다.

`main` 브랜치에 push하면 사이트에 반영됩니다.

## 파일 구성

| 경로 | 내용 |
| --- | --- |
| `index.html` | 소개, 프로젝트 목록, 이력 |
| `projects/` | 프로젝트별 소개 페이지 |
| `assets/style.css` | 전체 스타일 (밝은 테마와 어두운 테마 색상은 맨 위에 있음) |
| `assets/img/` | 스크린샷 등 이미지 |
| `404.html` | 없는 주소로 접속했을 때 표시되는 페이지 |
| `.nojekyll` | GitHub Pages의 Jekyll 빌드를 끄는 빈 파일 |
