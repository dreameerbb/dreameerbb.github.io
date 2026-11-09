# Jaeheon Song — Personal Website

[홈페이지](https://dreameerbb.github.io/) · [CV](https://dreameerbb.github.io/cv/) · [Notes](https://dreameerbb.github.io/blog/)

연구·프로젝트·경력과 개인적인 글을 모은 홈페이지입니다. 이 저장소는 GitHub Pages에서 제공하는 정적 배포 파일을 보관합니다.

## 파일 구성

| 경로 | 용도 |
| --- | --- |
| `docs/` | GitHub Pages가 제공하는 정적 홈페이지 |
| `docs/index.html` | 홈페이지 |
| `docs/cv/`, `docs/blog/` | CV와 발행된 글 |
| `docs/_next/` | JavaScript·CSS·폰트 |
| `docs/images/`, `docs/published-assets/` | 이미지와 공개 첨부 파일 |
| `docs/404.html`, `docs/404/` | 오류 페이지 |
| `docs/robots.txt`, `docs/sitemap.xml` | 검색 엔진 안내 |
| `docs/index.txt`, 각 페이지의 `index.txt` | Next.js의 페이지 이동 데이터 |
| `docs/.nojekyll` | `_next/` 파일을 GitHub Pages에서 그대로 제공 |
| `docs/_publication.json` | 자동 배포 완료 확인 |
| `.gitattributes` | GitHub 변경 화면에서 자동 생성 파일 구분 |

Pages는 `main` 브랜치의 `/docs`를 제공합니다. `docs/` 내부 파일은 자동 생성되며 페이지 이동·수식·이미지 표시 등에 사용됩니다.

## 업데이트

콘텐츠와 디자인은 [portfolio-manager](https://github.com/dreameerbb/portfolio-manager)에서 관리합니다. 관리자에서 공개 내용을 저장하면 정적 파일 생성과 GitHub push를 거쳐 Pages에 자동 배포됩니다. 관리자 기능·DB·초안은 배포하지 않습니다.

배포 파일을 직접 수정하면 다음 자동 발행 때 덮어씁니다. 수정은 원본 프로젝트에서 진행하세요. 이 README와 `.gitattributes`도 원본의 `homepage/publishing/`에서 관리합니다.
