# wowaistudy.github.io

GitHub Pages와 Jekyll 테마 Reverie를 사용한 공부 기록 블로그입니다.

## 로컬 실행

로컬에서 미리 보려면 Ruby 3 이상 환경을 권장합니다.

```bash
bundle install
bundle exec jekyll serve
```

브라우저에서 다음 주소를 엽니다.

```text
http://127.0.0.1:4000
```

GitHub에 올린 뒤에는 GitHub Pages가 자동으로 빌드합니다.

## 글 작성

새 글은 `_posts` 폴더에 아래 형식으로 만듭니다.

```text
YYYY-MM-DD-title.md
```

예시:

```text
2026-06-27-starting-this-blog.md
```

각 글의 맨 위에는 다음과 같은 설정을 둡니다.

```yaml
---
layout: post
title: 글 제목
categories: [기록]
---
```
