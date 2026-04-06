---
title: 메타데이터 품질 개선 프로젝트
date_created: 2026-04-07
status: in-progress
---

# 메타데이터 품질 개선 프로젝트

## 목표
워크스페이스 내 모든 마크다운 파일의 메타데이터(제목, 날짜, frontmatter) 완전성을 100%로 달성한다.

## 배경
기록물의 메타데이터는 맥락을 보존하는 핵심 요소다. 파일명에 날짜가 없거나, frontmatter가 누락된 파일은 시간이 지나면 언제, 왜 만들었는지 알 수 없게 된다.

## 할 일
- [ ] metadata-validator 에이전트로 현재 상태 점검
- [ ] 미통과 파일 목록 확인
- [ ] 파일명에 날짜 추가
- [ ] frontmatter 보완
- [ ] 재검증으로 100% 달성 확인

## 참고
- 에이전트: `.claude/agents/metadata-validator.md`
- 검사 대상: `20-created/`, `30-collected/`
