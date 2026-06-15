# leemyeongje.github.io

개인 디지털 가든 / 노트 사이트입니다. [Quartz v5](https://quartz.jzhao.xyz/)로 만들고 GitHub Pages로 배포합니다.

🔗 **https://leemyeongje.github.io**

## 개발

```bash
npm ci                 # 의존성 설치
npx quartz build --serve   # 로컬 미리보기 (http://localhost:8080)
```

콘텐츠는 `content/` 디렉터리의 Markdown 파일로 작성합니다.

## 배포

`main` 브랜치에 push하면 `.github/workflows/deploy.yaml` 워크플로우가 사이트를 빌드해 GitHub Pages에 자동 배포합니다.

## 크레딧

[Quartz](https://github.com/jackyzha0/quartz) by [Jacky Zhao](https://jzhao.xyz/) 기반으로 제작되었습니다.
