# Jinju Kim

기업·금융 데이터를 다루는 AI 서비스를 만들고, 사람이 결과의 근거를 확인할 수 있는 업무 흐름으로 연결합니다.

- 통계학 석사 · 빅데이터·금융 AI 전문가 과정(1,040시간) 수료
- 관심 분야: 생성형 AI 서비스, RAG, 데이터 모델링·품질 관리, 설명 가능한 머신러닝

## Featured Projects

### 1. 산업코드 분류 AI Agent — 검수 가능한 AI 업무 흐름

기업의 업태·종목 정보로 산업코드 후보를 제시하고, 관리자 배정 → 작업자 AI 후보 검토 → 검수자 승인·재작업으로 이어지는 흐름을 구현한 데모입니다(합성 데이터). 후보 코드와 판단 근거, 검수 결과와 변경 이력이 함께 남습니다.

- 원 프로젝트에서 맡은 일: 서버·DB 구축, 화면–DB 연동, 공식 분류 기준에 따른 후보 검증 필터, LLM 판정 프롬프트 설계
- Repo: [nice-industry-code-ai-agent-demo](https://github.com/kjj403/nice-industry-code-ai-agent-demo)

### 2. 공시 문서 산업코드 Agent — 설명 가능한 문서 AI

합성 공시 문서에서 사업 활동을 분리하고, 복수 산업코드 후보와 문장 근거를 제시한 뒤 사람의 검토 결과를 구조화합니다.

- Repo: [public-filing-industry-agent-demo](https://github.com/kjj403/public-filing-industry-agent-demo)

### 3. 감사보고서 RAG — 근거 기반 질의응답 (팀 프로젝트)

11개 연도 감사보고서를 구조화해 수치 질문은 SQL로, 설명형 질문은 RAG로 처리했습니다.

- 맡은 일: 문서 파싱(표의 행·열, 단위, 연도 보존), 근거 밖 내용을 만들지 않도록 하는 프롬프트 규칙 설계
- Repo: [samsung-audit-rag](https://github.com/njungyeon/samsung-audit-rag)

### 4. 다국어 RAG 키오스크 (팀 프로젝트)

자연어로 주문하는 AI 키오스크를 한국어·영어·중국어·일본어로 제공했습니다.

- 맡은 일: Streamlit 화면 구현, 내부 검색·추론 언어를 고정하고 마지막 단계에서 선택 언어로 응답하도록 흐름 수정
- Repo: [cafe_kiosk_prj](https://github.com/SarahCho0/cafe_kiosk_prj)

### 5. 대출 부도 예측과 위험조정수익 평가

고액 부도의 비대칭 손실을 반영한 비용 민감 학습, 승인율을 통제한 비교, 샤프지수 기반 평가를 결합했습니다. 부스팅 모델군을 맡았습니다.

- Repo: [Lending-Club-Project](https://github.com/kjj403/Lending-Club-Project)

### 6. 고객 이탈 분석

공개 대체 데이터로 고객 세분화, 이탈 예측, SHAP 기반 설명을 구성했습니다.

- Repo: [Insurance-Churn-Analysis](https://github.com/kjj403/Insurance-Churn-Analysis)

## Research

- First author — covariance regression for US airport network and KOSPI volatility: [CSAM 32(5), 655–672 (2025)](https://doi.org/10.29220/CSAM.2025.32.5.655)
- Co-author — government and information trust in environmental risk perception: [Humanities and Social Sciences Communications (2026)](https://doi.org/10.1057/s41599-026-08463-7)

## Tools

Python · SQL · R · PostgreSQL · AWS (EC2, RDS, S3) · Streamlit · LLM/RAG · Machine Learning · Git/DVC
