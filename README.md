# 개인 프로필 웹사이트

정적 웹사이트 파일(`index.html`, `styles.css`, `script.js`)은 프로젝트 루트에 두었습니다. 별도 빌드 단계나 외부 패키지가 없어 Vercel에 배포할 때도 이 폴더를 그대로 사용할 수 있습니다.

## 로컬 실행

Node.js가 설치된 환경에서 프로젝트 폴더로 이동한 뒤 실행합니다.

```sh
npm start
```

브라우저에서 `http://localhost:3000`을 엽니다. 포트를 바꾸려면 `PORT` 환경 변수를 지정하면 됩니다.

## Vercel 배포

이 프로젝트 폴더를 Vercel에 연결하고 Framework Preset은 `Other`로 선택합니다. Build Command는 비워 두고 Output Directory는 `.`(프로젝트 루트)로 지정하면 루트의 정적 파일을 배포합니다. `server.js`는 로컬 미리보기 용도라 Vercel 배포 과정에는 사용되지 않습니다.
