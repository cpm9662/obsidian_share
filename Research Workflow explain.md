---
tags:
  - lab
  - obsidian
share: true
---
# 연구 체계화(문서)
- [n] 연구 노트
	- [!] 각각 parameter 및 조건 틀 갖춰진 template 제작
	- [I] 화학 실험: 사용 물질 CAS, 양, 실험실 온습도, 첨가 순서, 반응 시간, 기타 특이사항 등
	- [I] 성능 평가 실험: 실험실 온습도, 입력값, 출력값, 변화량 등
	- [I] 시뮬레이션: mesh 개수, 특성, 기타 등등...
	- [?] 각자 실험 관련해서는 잘 모르니까 관련해서 피드백, 본인이 Template 직접 수정해서 사용
	- [p] 실험 **실패의 원인 규명 용이**, 체계적 데이터 관리로 중복 실험 등 **시간 낭비 방지**
- [n] 실험 문서화
	- [I] 각각의 실험 당 상세한 프로세스를 문서화
	- [I] 이론적인 내용보다는 실험 과정, 환경, 사용 물질 등의 것에 중점
	- [I] 처음 보는 사람도 어떤 과정인지 이해할 수 있도록
	- [p] 나중에 같은 실험 후배들이 할 때 인수인계 용이
# Paper Review (Using Zotero)
- [!] Zotero는 Library API가 오픈되어 있음
- [i] Zotero Library와 연동이 가능한 Tool List
	- [*] **SCIspace**: 논문 읽을 때 AI 챗봇이 논문 이해를 도와줌 https://typeset.io
	- [*] **ResearchRabbit**: 레퍼런스 구조화, 연관 논문 추천. https://researchrabbitapp.com/
	- [n] 그 외 많은 툴들이 Zotero library import 지원
# Obsidian
- [!] **마크다운 문법** 기반
- [!] **노트 간의 유기적 연결성** 강조, Zettelkasten과 같은 지식 관리
- [i] open-source, 많은 **외부 플러그인** 지원 [Obisidan Community Plugin List](Obisidan%20Community%20Plugin%20List.md)
- [*] **Zotero Integration** 활용해 Zotero에서 리뷰한 논문 가져오기 (설정 참고: https://youtu.be/C1nuZ2sJa9E?si=EbEZdGBiUkD4p6gC)
- [*] **Web Clipper**(브라우저 확장 프로그램) 활용해 인터넷 상 글을 내 문서로 저장
- [p] 업무 프로세스 관리에도 용이
# Markdown 문법
- [i] **개발용**으로 많이 쓰이는 언어
- [c] HTML 문서는 복잡한 태그로 인해 쓰기 어려움
- [i] **읽기도, 쓰기도 쉬운 문서**를 지향
- [c] Notion 등의 프로그램은 변형된 마크다운 문법을 활용함 → 호환성 떨어짐
- [p] **Obsidian**은 표준 마크다운 문법을 준수 → **호환성 우수**
- [*] chatGPT 등 **생성형 AI (LLM)는 모두 마크다운 문법 기반** 답변 생성 → GPT 답변 복사해서 obsidian에 붙여넣을 경우 문서 양식 그대로 적용
- [*] LLM이 마크다운 문법 기반 답변을 작성하기 때문에, 역설적으로 마크다운 문법은 **LLM이 가장 이해하기 쉬운(효율적인, 오류가 없는) 언어**

---
# RAG

![600](./Attached%20File/RAG%20framework%20flow.png)
![10분 만에 RAG 이해하기 > GPT-4o 요약](10%EB%B6%84%20%EB%A7%8C%EC%97%90%20RAG%20%EC%9D%B4%ED%95%B4%ED%95%98%EA%B8%B0.md#GPT-4o%20요약)

SmartComposer: obsidian과 chatGPT, Gemini, Claude 등의 LLM을 연결할 수 있는 RAG 플러그인. (사용 예시: https://youtu.be/_igEIdt2cVY?si=dFAzYhKU1Gl9g0_b)
Github: https://github.com/glowingjade/obsidian-smart-composer

## RAG 활용 연구 프로세스
### 문헌 조사 단계
- [k] **Zotero** 활용해서 논문 읽기 (`SCIspace`, `ResearchRabbit` 도움)
- [i] `Zotero Integration` 플러그인 통해서 리뷰한 논문 `Obsidian`으로 가져오기 
- [b] 인터넷에서 유용한 글 `Obsidian Web Clipper` 활용해서 **Clipping**
### 아이디어 도출 단계(Zettelkasten)
- [I] 매 순간마다 떠오르는 중요 아이디어들 바로 **Fleeting Note**로 메모
- [n] 문헌 조사한 내용에서 내 생각 및 중요 사항들을 **Literature Note**로 정리
- ["] 정리된 아이디어 및 생각을 개별 **Permanent Note**로 작성
- [!] Permanent Note간의 연결성 확인, 아이디어 도출
### 실험 단계
- [k] 상세 실험 **프로세스 문서화**
- [!] 매 **실험 노트** Template 활용해서 작성
- [l] `DB folder` 플러그인 활용해서 데이터베이스 관리
### RAG 단계
- [?] 실험 프로세스 문서 및 실험 노트 반영한 RAG 질문, **문제점 도출** 및 **아이디어 제안**
- [*] 문헌 조사 자료 및 Permanent Note 반영해서 RAG 질문 및 피드백
### 논문 작성 단계
- [<] `Projects` 플러그인 활용해서 챕터별 논문 작성 / 실험 등 진척 사항 관리
- [S] `Writing Goals` 플러그인 활용해서 작성 분량 트래킹
- [b] `Citations` 플러그인 활용해서 인용 관리(endnote 양식 연동)
- [*] 기존 작성한 문서들 바탕 **RAG로 구조화**, 논문 작성에 도움받기
