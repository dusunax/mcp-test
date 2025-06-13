# MCP Test Project 🚀

MCP (Model Context Protocol)를 활용한 자동화 테스트 프로젝트입니다.

## 📋 개요

다양한 MCP 서버들의 기능을 테스트하고 검증하는 프로젝트입니다.

### 테스트 대상 MCP 서버
- **GitHub MCP**: 이슈/PR 자동화, 라벨링, 할당 등
- **Figma MCP**: 디자인 파일 관리 및 자동화 (예정)
- **Notion MCP**: 문서 관리 및 자동화 (예정)

## 🎯 GitHub MCP 자동화 기능

### 자동 라벨링
- "MCP"로 시작하는 이슈/PR에 "mcp test" 라벨 자동 추가
- 대소문자 구분 없음

### 자동 할당
- 모든 이슈/PR 작성자를 자동으로 Assignees에 추가

## 🧪 주요 테스트 케이스

| 이슈 | 제목 | 목적 | 상태 |
|------|------|------|------|
| [#1](https://github.com/dusunax/mcp-test/issues/1) | MCP 테스트 프로젝트 설정 | 프로젝트 초기 설정 | ✅ |
| [#2](https://github.com/dusunax/mcp-test/issues/2) | MCP 기능 테스트 | 기본 기능 테스트 | ✅ |
| [#6](https://github.com/dusunax/mcp-test/issues/6) | MCP 라벨 관리 및 태깅 테스트 | 라벨 자동화 시스템 | ✅ |

## 🔧 워크플로우

- `.github/workflows/auto-label.yml`: 자동 라벨링
- `.github/workflows/auto-assign.yml`: 자동 할당

## 📈 향후 계획

- [ ] Figma MCP 연동 테스트
- [ ] Notion MCP 연동 테스트
- [ ] 통합 자동화 워크플로우 구축

---

**Made with ❤️ using MCP**