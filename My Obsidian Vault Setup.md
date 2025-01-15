---
share: true
---

# 1. 파일 관리
## PARA
![PARA](PARA.md)
- 각각 폴더 별 언제든 문서 및 하위 폴더 이동 가능
### Project
- 도시기후과제
- JSPS
- tocopherol coating
	- 실험노트 작성
	- 실험 process 문서화
	- paper 폴더
		- 각각 chapter별 진행사항, 작성 논문 개별 문서화
		- 추후 plugin으로 merge해서 통합
		- project plugin으로 canvan board 진행사항 관리
- 기타 실험 task
자세한 설명은 [Research Workflow explain](./Research%20Workflow%20explain.md) 참고
### Area
- Lab
	- 아마도 Lab vault로 옮기지 않을까
- microplastic removal
### Resource
- Clippings
	- Obsidian web clipper 활용해 인터넷 문서들 저장 -> 이후 개별 활용되는 폴더로 옮기기
- Mail
	- Actions for obsidian 프로그램 활용해 mail clipping
- Personal Knowledgement
	- About My obsidian Vault 폴더
		- 내 옵시디언 관련한 사항들 문서화
		- 개별 테마 문법, zotero 문법, 워크플로우 설명 등
		- 플러그인 리스트
		- obsidian 관련 task
	- Obsidian 관련 기초 지식들
	- PARA
	- zettelkasten
- Research
	- 연구 장비 사용법
		- SEM, XPS, Contact angle goniometer 등
	- 논문 작성 관련 자료들
	- 프로그램 사용법
- Zotero
	- Zotero Import 플러그인 사용해 zotero annotation 가져오기
	- 추후 개별 문서 폴더로 이동
### Archive
- 박사논문연구 수업 자료
- 2025 신진 자료

## Zettelkasten
![Zettelkasten](Zettelkasten.md)
### Fleeting Note
- Actions for obsidian 프로그램 활용해서 Apple 메모 앱에서 **간단한 아이디어 노트** 가져오기
- 임시 노트 느낌
### Literature Note
Zotero Import, Web clipping 등 **자료를 내 언어로 요약 및 정리**, **의견 및 아이디어 추가**
*Template 작성 필요할 수도*
### Permanent Note
Fleeting Note + Literature Note 결합
하나의 **정제된 아이디어** 및 **나만의 생각** 문서화
*Template 작성 필요할 수도*
## GTD
- Get, Things, Done 3단계
- 기본 노트 생성 경로는 Inbox
- 일단 Inbox에서 노트 작성 후 추후 다른 폴더로 이동 (메일 분류 느낌)
- **당장 해야할 일 및 앞으로 해야할 일을 분류**해서 Task로 작성
- Task Calendar Wrapper, Calendar, Tasks 플러그인 활용해 오른쪽 sidebar에서 할일 잊지 않게 트래킹
- Homepage 플러그인 활용, 프로그램 켤 때마다 Home에서 내가 직전에 작업했던 문서(프로젝트 별) 및 최근 저장한 resource(웹, 논문, 메일) 확인
## Productivity
- MOC(Map of Contents): 전체 파일들 접근하기 쉽게 문서화
- Periodic
	- 일간, 주간, 월간, 분기별, 연도별 노트 템플릿, 개별 문서화
	- 일기 느낌 + 할 일 잊지 않도록 + 그 날 무슨 일 했는지 나중에 복기 가능하게
## Others
Personal: 영화, 독서, IT 등 기타 내 잡다한 관심사들
Template: 템플릿 모아놓는 폴더
Attached File: 첨부파일(이미지) 보관함
RSS: RSS feed 저장한 파일 (RSS feed 관리 필요)

---
# 2. 플러그인 활용 방법
## 자동화
`Actions URL`: Actions for Obsidian 활용해서 메모 불러들이기, 메일 clipping 등 자동화(only mac user)
`Obsidian Web Clipper`: 인터넷 글 마크다운 문서로 아카이빙 - 브라우저 확장 프로그램
`Zotero Integration`: Zotero Annotation Import
`Templater`, `Calendar`, `Periodic Notes`: 일간 노트 자동화
`Waypoint`: MOC 자동 생성

## 업무 관리
`Tasks`: Todo checklist 관리
`Calendar`: 오른쪽 사이드바에서 달력 확인, 달력 클릭시 일간/주간노트 바로 진입
`Tasks Calendar Wrapper`: 오른쪽 사이드바에서 까먹지 않도록 할일 관리
`Periodic Note`: 매일매일 일간노트/일기 작성, 할일 까먹지 않게 그날 Task 자동으로 정리해서 보여줌

- [p] `Tasks Calendar Wrapper` 통해서 시각적으로 계속 할일 확인 가능, Periodic Note로 그날/주간/월간으로 할 일 확인 및 정리 요약 가능. **이중 삼중 확인 프로세스**로 중요 일정 놓치지 않음
## 자료 접근성
`Dataview`로 Table / list 구현
`Omnisearch`로 효율적 검색
`DB Folder` 활용하면 Notion과 같은 방식으로 가능 (조금 더 공부 필요)
`Smart Composer`로 RAG 활용 연관성 있는 노트들 묶어서 찾기

- [p] 마크다운 문법 양식에 맞는 데이터 작성 및 관리, LLM 활용에 용이
