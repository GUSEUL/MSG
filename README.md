# MSG (Message & AI)

Void 에디터를 기반으로 한 AI 코딩 도우미 프로젝트입니다.

## 실행 방법

1. 의존성 설치:
```
npm install
```

2. 빌드:
```
npm run watch
NODE_OPTIONS="--max-old-space-size=8192" npm run buildreact
```

3. 실행:
```
./scripts/code.sh --user-data-dir ./.tmp/user-data --extensions-dir ./.tmp/extensions
```

## 참고사항
- 빌드는 시간이 다소 걸릴 수 있습니다
- 빌드 과정에서 오류가 발생하면 NODE_OPTIONS="--max-old-space-size=8192" 옵션을 추가하세요
- 실행 중 오류 발생 시 `sudo chown root:root .build/electron/chrome-sandbox && sudo chmod 4755 .build/electron/chrome-sandbox` 명령 실행 후 다시 시도하세요
