# THE 1ST SENT — 노방전도 현장 가이드

사랑의교회 Hi-5ive 청년5국 노방전도 웹페이지입니다.

## 구성
- `index.html`: 외부 라이브러리 없이 작동하는 모바일 반응형 단일 페이지
- 첫 인사, 복음 제시, 팀 역할, 시간표, 구역, 상황별 Q&A, 체크리스트

## Vercel 배포

1. 이 폴더를 GitHub 공개/비공개 저장소에 올리세요.
2. Vercel에서 **Add New Project → Import Git Repository** 선택
3. Framework Preset: `Other` / Build Command: 비움 / Output Directory: `.`
4. Deploy 버튼을 누르세요.

또는 Vercel CLI가 설치되고 연결된 환경이라면 이 폴더에서:

```bash
npx vercel --prod
```

`index.html`만으로 동작하므로 정적 호스팅도 가능합니다.
