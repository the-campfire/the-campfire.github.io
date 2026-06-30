# the-campfire.github.io

모닥불 서버 안내서(가이드 사이트) 소스입니다.

- **사이트 주소**: https://the-campfire.github.io/
- **빌드 도구**: [MkDocs](https://www.mkdocs.org/) + [Material](https://squidfunk.github.io/mkdocs-material/)
- **배포**: `main` 브랜치에 push 하면 GitHub Actions가 자동으로 빌드·배포합니다.

## 문서 수정 방법

`docs/` 폴더의 마크다운(`.md`) 파일을 고치고 `main` 브랜치에 push 하면 끝입니다.

## 로컬 미리보기 (선택)

Python이 설치돼 있다면:

```bash
pip install -r requirements.txt
mkdocs serve
```

브라우저에서 http://127.0.0.1:8000 으로 확인할 수 있습니다.
