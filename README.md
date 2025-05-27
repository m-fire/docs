# Mintlify 스타터 키트

`Use this template`를 클릭하여 Mintlify 스타터 키트를 복사하세요. 이 스타터 키트에는 다음과 같은 예제가 포함되어 있습니다.

- 가이드 페이지
- 네비게이션
- 커스터마이징
- API 레퍼런스 페이지
- 인기 컴포넌트 사용

### 개발

[Mintlify CLI](https://www.npmjs.com/package/mintlify)를 설치하여 로컬에서 문서 변경 사항을 미리 볼 수 있습니다. 설치하려면 다음 명령어를 사용하세요.

```
npm i -g mintlify
```

`docs.json` 파일이 있는 문서 루트에서 다음 명령어를 실행하세요.

```
mintlify dev
```

### 변경사항 배포

Github App을 설치하면 저장소의 변경사항이 배포에 자동으로 반영됩니다. 기본 브랜치에 푸시하면 변경사항이 자동으로 프로덕션에 배포됩니다. 설치 링크는 대시보드에서 확인할 수 있습니다.

#### 문제 해결

- Mintlify dev가 실행되지 않음 - `mintlify install`을 실행하면 의존성이 재설치됩니다.
- 페이지가 404로 표시됨 - `docs.json` 파일이 있는 폴더에서 실행 중인지 확인하세요.
