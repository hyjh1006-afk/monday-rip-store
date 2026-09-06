# monday-rip-store
## 무엇
- ‘월요일 파쇄소’ PWA의 스토어용 정적 배포본.
- 루트에 원본 소스·package.json·deploy.sh·README·WORKLOG.md가 없다.
## 핵심 명령
- 실행·빌드·배포 명령은 이 폴더에 문서화되어 있지 않다.
- 빌드 산출물 폴더이므로 npm scripts나 배포 대상을 추정하지 않는다.
## 구조·진입점
- `index.html`: 진입점, `assets/`: 번들 JS·CSS, `fonts/`·`icons/`: 정적 자산.
- `manifest.webmanifest`: PWA 설정, `service-worker.js`: 서비스워커.
## 주의
- 번들 파일을 원본 소스처럼 취급하지 않는다. 변경 시 원본 프로젝트와 배포 관계부터 확인한다.
- WORKLOG가 없어 프로젝트별 함정은 확인되지 않았다.
