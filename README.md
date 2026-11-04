# 이상현의 개발 기록

컴퓨터공학을 전공하며 학습한 기술과 직접 구현한 프로젝트를 정리한 개인 포트폴리오 웹사이트입니다.

웹 개발과 Android 애플리케이션 개발 경험을 기록하고, 프로젝트의 구현 과정과 문제 해결 경험을 공유하기 위해 제작했습니다.

## 웹사이트

- **배포 주소:** https://lsanghyl.github.io/MyProfile/
- **GitHub 저장소:** https://github.com/lsanghyl/MyProfile
- **배포 방식:** GitHub Pages + GitHub Actions

## 주요 콘텐츠

- **자기소개:** 관심 분야, 기술 및 도구, 프로젝트 경험, 학습 목표
- **감사 나눔 웹사이트:** 그룹 기반 감사 기록 공유, Supabase 데이터베이스 및 접근 권한 관리
- **SetLog 스타일 Android 앱:** Kotlin과 Firebase를 활용한 일상 기록 및 친구 공유 기능

## 개발 환경

- **정적 사이트 생성기:** Hugo Extended 0.167.0
- **테마:** Hugo Theme Stack
- **콘텐츠 작성:** Markdown
- **버전 관리:** Git / GitHub
- **자동 배포:** GitHub Actions
- **호스팅:** GitHub Pages

## 로컬 실행 방법

Hugo Extended를 설치한 후 프로젝트 저장소에서 다음 명령어를 실행합니다.

```bash
cd site
hugo server
```

개발 서버가 실행되면 터미널에 표시되는 로컬 주소로 접속하여 사이트를 확인할 수 있습니다.

## 콘텐츠 수정 방법

주요 콘텐츠는 `site/content/` 디렉터리에서 관리합니다.

- `site/content/page/about/index.md`: 자기소개
- `site/content/post/gratitude-web/index.md`: 감사 나눔 웹사이트
- `site/content/post/setlog-app/index.md`: Android 앱 프로젝트

사이트 설정 파일은 `site/config/_default/` 디렉터리에서 관리합니다.

## GitHub Actions 자동 배포

`main` 브랜치에 변경 사항을 푸시하면 GitHub Actions 워크플로가 실행됩니다.

1. 저장소의 소스 코드를 가져옵니다.
2. Hugo Extended와 필요한 의존성을 준비합니다.
3. Hugo를 이용해 정적 웹사이트를 빌드합니다.
4. 빌드 결과물을 GitHub Pages에 배포합니다.

워크플로 파일: `.github/workflows/hugo-pages.yml`

## 테마 및 라이선스

이 웹사이트는 [Hugo Theme Stack](https://github.com/CaiJimmy/hugo-theme-stack)을 기반으로 제작했습니다.

원본 테마 제작자: Jimmy (CaiJimmy)

원본 테마의 라이선스는 GNU General Public License v3.0입니다. 원본 테마의 저작권 및 출처 표기를 유지합니다.

## 향후 개선 계획

- 프로젝트 소개 및 개발 기록 지속적으로 추가
- 모바일 환경에서의 사용성 개선
- 웹 접근성 및 사용자 경험 점검
- 새로운 기술 학습 결과 정리