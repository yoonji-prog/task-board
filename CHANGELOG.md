# 변경 이력 (Changelog)

이 문서는 [Keep a Changelog](https://keepachangelog.com/ko/) 형식을 따르고,
버전은 [유의적 버전(SemVer)](https://semver.org/lang/ko/)을 사용합니다.
형식: `주(major).부(minor).수(patch)` — 큰 변경=major, 기능 추가=minor, 버그·소소한 수정=patch.

## [Unreleased]
- (다음 릴리즈에 넣을 변경을 여기 기록)

## [1.0.0] - 2026-07-24
### 최초 배포
- 업무별 **디자인 · 마크업 · 개발** 3트랙 진행 상태(예정 → 진행 → 완료) 관리
- 업무별로 해당 트랙만 켜고 끄기(카드에서 바로 토글), 진행률 자동 계산
- 트랙별 **시작~완료 기간 · 소요일 · 특이사항** 입력
- 업무 단위 **확인 필요 사항** + **성과 메모**
- 3트랙 완료 시 자동 아카이브(완료일·기간 기록)
- **카테고리** 태그·필터, 카테고리 이름 인라인 편집(더블클릭)·추가·삭제
- 빠른 추가 문법(`#카테고리`), 업무 복제, 드래그 순서 변경
- **주간보고용 내보내기**(카테고리 → 업무 → 트랙 포맷, 날짜·요일 표기)
- **내보내기**: Markdown / CSV, **JSON 백업 & 가져오기(복원)**
- 카톡용 요약 텍스트, 변경 히스토리 기록
- 디자인: 노션 스타일, Pretendard 글꼴, 진행률 링 파비콘
- 데이터는 브라우저(localStorage)에 저장 — 공개 배포해도 업무 내용은 비공개

[Unreleased]: https://github.com/yoonji-prog/task-board/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/yoonji-prog/task-board/releases/tag/v1.0.0
