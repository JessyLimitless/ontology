# 참고 자료 및 인용 가능 출처

> 에세이 작성 시 본문에 자연스럽게 녹여 인용할 수 있는 출처 모음.
> 하나의 챕터에 1~2개만 인용하는 것을 권장 (남발 금지).

## A. 핵심 학술·산업 자료

### A-1. Boids 알고리즘 (1장)
- **Craig W. Reynolds**, "Flocks, Herds, and Schools: A Distributed Behavioral Model"
- 발표: SIGGRAPH '87 (1987)
- 핵심: 분리·정렬·응집 3원칙으로 군집 행동 시뮬레이션
- 영향: 컴퓨터 그래픽 → 게임 AI → 로봇공학 → 드론

### A-2. SWARMs Ontology (3·4장)
- 출처: NCBI/PMC, EU H2020 프로젝트
- 주제: 수중·공중 로봇 협업의 시맨틱 상호운용성
- URL 참고: https://ncbi.nlm.nih.gov/pmc/articles/PMC5375855
- 핵심 인용 가능 표현: "데이터 이질성을 추상화하고 모든 로봇이 모호하지 않게 이해할 수 있도록 하는 형식적 사양"

### A-3. Dronetology (3·4장 핵심 무기)
- 출처: *Knowledge-Based Systems* (Elsevier)
- 게재: 2025년 7월
- 주제: UAS 도메인 정식 온톨로지, 의사결정 지원 프로토타입 구현
- 핵심: "비행 효율, 충돌 회피, 규제 준수" 등 복잡한 UAS 사례 처리
- 무기 포인트: **2025년 정식 학술지 게재** = "이건 2017년 옛날 얘기 아니다"

### A-4. 6G + 시맨틱 통신 + 드론 군집 (4장)
- 출처: arXiv 2503.00053 (2025년 2월)
- 주제: AI and Semantic Communication for Infrastructure Monitoring
- 핵심: URLLC (초저지연 고신뢰 통신) + 엣지 AI + 시맨틱 통신
- 인용 가치: "5G로는 대규모 드론 협업이 불가능하다"는 명시적 진술

### A-5. UAV Cognitive Semantic Communications (4장)
- 출처: arXiv 2502.03761
- 주제: 지식그래프 기반 객체 탐지
- IEEE ICC 2024에서 일부 발표
- 핵심: 채널 노이즈와 압축 왜곡을 지식그래프로 극복

### A-6. GoalSwarm (4장)
- 출처: arXiv
- 주제: Multi-UAV Semantic Coordination for Open-Vocabulary Object Navigation
- 핵심: 다중 UAV 시맨틱 조정의 첫 통합 프레임워크 주장

### A-7. 드론 위협 자동 탐지 온톨로지 (4장)
- 출처: IEEE
- 주제: 드론·드론 군집의 위협적 행동 자동 인식
- 핵심: "거리, 가시선, 미러 모션, 경로·위치 최적성, 협업, 편대" 등을 시맨틱 마커로 정의
- 인용 가치: 군사·방첩 영역 시맨틱 적용

## B. 오라클 관련 자료 (4장 핵심)

### B-1. Oracle RDF Knowledge Graph (제품)
- **공식 제품명**: Oracle RDF Knowledge Graph (구 RDF Semantic Graph)
- **포함 위치**: Oracle Database Enterprise Edition의 Spatial and Graph 옵션
- **지원 표준**: RDF, OWL (subset), SPARQL
- **문서**: Oracle Database 19c/21c/23ai 공식 가이드

### B-2. 오라클 공식 문서의 국방·공공안전 명시 인용
원문 (검증됨):
> "Governments can use graph technologies for defense and public safety, to aid in public health initiatives, and for linked open data initiatives for their citizens."

번역:
> "정부는 그래프 기술을 국방·공공안전, 공중보건, 시민 대상 링크드 오픈 데이터 사업에 활용할 수 있다."

출처: https://www.oracle.com/database/technologies/rdf-semantic-graph-ls.html

### B-3. 오라클이 명시한 활용 영역
- 사이버보안, 공급망, 온라인 커머스, **국방·공공안전**, 공중보건, 사기 탐지
- 즉, 드론 자율 군집의 응용 영역과 정확히 겹침

## C. 평창 올림픽 드론쇼 사실관계 (프롤로그)

| 항목 | 내용 |
|------|------|
| 일자 | 2018년 2월 9일 |
| 행사 | 평창 동계올림픽 개회식 |
| 운영사 | Intel |
| 모델 | Shooting Star |
| 대수 | 1,218대 (당시 기네스 세계 기록) |
| 제어 방식 | 단일 컴퓨터의 중앙집중 제어 |
| 파일럿 | 1명 |
| 위치 정확도 | RTK-GPS, cm급 |
| 드론 간 통신 | 없음 |

**중요**: 이는 **자율 군집 지능이 아니라 정밀 좌표 동기화**의 결과물.

## D. 부가 산업 온톨로지 사례 (참고용)

본문에 직접 인용은 안 하지만 신뢰도 백업용:

- **의료**: SNOMED CT, ICD-10/11, Gene Ontology, MeSH
- **금융**: FIBO (Financial Industry Business Ontology), XBRL
- **웹**: Schema.org, Wikidata, DBpedia
- **제조**: ISO 15926, IFC (BIM), Asset Administration Shell
- **국방**: JC3IEDM (NATO 지휘통제), STIX/TAXII
- **공공**: EU Core Public Service Vocabulary

## E. 인용 작성 권장 방식

본문에서 출처를 다음과 같이 자연스럽게 녹일 것:

**좋은 예**:
- "2025년 *Knowledge-Based Systems*에 게재된 'Dronetology'는..."
- "오라클은 자사 RDF Knowledge Graph 문서에서 '정부의 국방·공공안전 시장'을 명시적으로 언급한다"
- "1986년 크레이그 레이놀즈가 발표한 Boids는..."

**나쁜 예**:
- 각주를 본문에 노출 ("[1] Reynolds, 1987")
- 출처를 한 문단에 3개 이상 던지기
- URL을 본문에 그대로 노출

## F. 사실 검증 체크리스트

본문 작성 후 반드시 확인:

- [ ] 평창 드론쇼는 인텔 쇼팅스타 1,218대로 표기되었는가
- [ ] 평창 드론쇼를 "자율 군집 지능"으로 잘못 묘사하지 않았는가
- [ ] Boids는 1986년 Reynolds로 표기되었는가
- [ ] 온톨로지를 "신생 연구"가 아니라 "이미 표준화 진행 중"으로 표현했는가
- [ ] Dronetology의 게재 학술지(*Knowledge-Based Systems*)와 시점(2025)을 명시했는가
- [ ] 오라클이 RDF Knowledge Graph 제품을 보유했음을 정확히 적었는가
- [ ] RDF/OWL/SPARQL 같은 약어를 한 번에 폭격하지 않았는가
