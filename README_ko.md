# Shiene1010 포트폴리오 - Minimal Light

[![LICENSE](https://img.shields.io/github/license/shiene1010/minimal-light?style=flat-square&logo=creative-commons&color=EF9421)](https://github.com/shiene1010/minimal-light/blob/main/LICENSE)

\[[라이브 데모](https://shiene1010.github.io/minimal-light/)\] | \[[English Version](README.md)\]

이 웹사이트는 [Minimal Light](https://github.com/yaoyao-liu/minimal-light) 테마를 포크하여 만든 저의 개인 포트폴리오입니다. Jekyll을 기반으로 하며 GitHub Pages를 통해 배포되었습니다.

## 주요 특징

- **iOS 개발자 맞춤형**: iOS/SwiftUI 개발 프로젝트 및 학습 내용을 중심으로 재구성했습니다.
- **실시간 피드백**: **Giscus**(GitHub Discussions)를 통합하여 방문자가 직접 후기를 남길 수 있습니다.
- **깔끔한 히스토리**: Git 히스토리를 초기화하여 깨끗하고 가벼운 저장소를 유지합니다.
- **모바일 최적화**: 모든 기기에서 보기 편한 반응형 디자인을 제공합니다.
- **다크 모드 지원**: 사용자 설정에 맞는 테마 전환이 가능합니다.

## 프로젝트 구조

```
.
├── _data                    
│   ├── publications.yml      # 프로젝트 데이터 (제목, 설명, 이미지 링크)
│   └── reviews.yml           # (선택 사항) 정적 리뷰 데이터
├── _includes                    
│   ├── giscus.html           # Giscus 피드백 위젯 설정
│   └── publications.md       # 프로젝트 레이아웃 포함 파일
├── _sass                     # 스타일 파일 (SCSS)
├── assets                    # 이미지 에셋 (프로필, 스크린샷)
├── index.md                  # 메인 페이지 컨텐츠
└── _config.yml               # 사이트 전역 설정 및 메타데이터
```

## 시작하기 및 커스터마이징

1.  **프로필**: `_config.yml`에서 이름, 소셜 링크 등을 본인 정보로 수정합니다.
2.  **컨텐츠**: `index.md`에서 "About Me"와 "News" 섹션을 수정합니다.
3.  **프로젝트**: `_data/publications.yml`에 본인의 프로젝트를 추가합니다.
4.  **피드백**: [giscus 앱](https://github.com/apps/giscus)을 설치하여 댓글 기능을 활성화합니다.

## 라이선스

이 프로젝트는 [Creative Commons Zero v1.0 Universal](LICENSE) 라이선스를 따릅니다.
