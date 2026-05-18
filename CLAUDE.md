# 작가팀 기술 명세 (Technical Specs)

> [!IMPORTANT]
> 에이전트 페르소나, 직급 체계 및 전사 운영 규칙은 루트의 [CLAUDE.md](file:///c:/Python/CLAUDE.md)를 준수한다. 본 파일은 프로젝트별 기술 명령어 및 파일 참조용으로만 활용한다.

## 1. 빌드 및 실행 명령어 (Workflows)

- **뉴스 리서치 스크립트 실행 (이지수 담당)**: `python research_news.py`
- **테크니컬 가이드 평문화 (양하연 담당)**: `python technical_translator.py`
- **맞춤법 및 팩트체크 (김세민 담당)**: `python fact_checker.py`

## 2. 참조 파일 및 폴더

| 파일/폴더 | 설명 |
|-----------|------|
| `output/` | 최종 발행 콘텐츠 저장 폴더 |
| `sources/` | 인터뷰 녹취록 및 외부 리서치 자료 |
| `templates/` | 콘텐츠 타입별 톤앤매너 템플릿 |

## 3. 환경 관리 원칙 (Local)

- **보존 대상**: `output/` 폴더 내 결과물, 의뢰 팀 수신 원천 자료
- **삭제 대상**: 중간 초안, 임시 메모용 `.txt`, 작업용 임시 스크립트
