![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=180&section=header&text=Sunghwan%20Hong&fontSize=55&fontAlignY=35&desc=Retrieval-Augmented%20Reasoning%20%7C%20LLM%20Agents&descAlignY=55&animation=twinkling)

# Sunghwan Hong

![RAG](https://img.shields.io/badge/🔍_Retrieval--Augmented_Generation-6366F1?style=flat-square&logoColor=white)
![GraphRAG](https://img.shields.io/badge/🕸️_GraphRAG-8B5CF6?style=flat-square&logoColor=white)
![Agent](https://img.shields.io/badge/🤖_LLM_Agents-3B82F6?style=flat-square&logoColor=white)

> 검색 증강을 통해 LLM의 추론 성능을 높이고, 그 추론이 근거에 기반한 것임을 보증하는 문제에 관심이 있습니다.

---

## 🎓 Education

**B.S. in Computer Science and Engineering**  
**Hansung University**, Seoul, South Korea  
Mar. 2021 - Feb. 2027 (Expected)  
**Tracks**: Web Engineering, Mobile Software  
**GPA**: 4.13 / 4.5 (Major 4.17)

---

## 🔬 Research Experience

### Undergraduate Research Assistant | IRIS Lab

**Interactive Intelligence and Data Systems Laboratory**  
Hansung University, Seoul, South Korea  
*Advised by Prof. Mi-Hwa Song* | Dec. 2025 - Present

**Activities:**
- 주간 랩 미팅에서 RAG 및 멀티 에이전트 시스템 관련 최신 논문 발표 및 토론
- 산학협력 프로젝트 참여 — RAG와 MAS를 도메인 문제에 적용
- 지식그래프 자동 구축 및 GraphRAG 기반 리스크 추론 연구 주도 (제1저자)

### Publications

**A GraphRAG System for Automated Construction of Corporate Relationship Knowledge Graphs and Risk Reasoning**

**First Author** | *Advisor: Prof. Mi-Hwa Song*  
Korea Computer Congress (KCC) 2026, pp. 1892-1894 | Jun. 2026

- SEC 10-K 공시로부터 기업 관계 지식그래프를 자동 구축하는 온톨로지 기반 파이프라인 설계
- 명시적 경로 탐색 기반 다중 홉 리스크 추론 — 유효 경로 부재 시 답변 거절로 환각 통제
- **Cross-Hop Reachability** 제안 — 기존 RAG 지표가 포착하지 못하는 다중 홉 경로 무결성을 정량화

**Short-form Transformation and Interactive Learning Platform for AI-Based University Lectures for Generation Z**

**Co-Author (2nd Author)**  
Korea Information Processing Society (ACK) 2025, vol. 32, no. 2 | Nov. 2025

---

## 💼 Project Portfolio

### BizNode — Intelligent Corporate Relation Analysis Workspace

**Team Leader, Data & AI Engineer** | Mar. 2026 - Present  
*Hanium Dream-Up, Korea Information Industrial Association*

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat-square&logo=databricks&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

- 비정형 데이터로부터 기업 관계와 다중 홉 금융 리스크를 분석하는 GraphRAG 워크스페이스 아키텍처 설계 및 총괄
- LangGraph 멀티 에이전트가 질의 구조에 따라 Graph / Vector / Relational 저장소로 라우팅
- 상위 관계 타입은 고정하고 하위 subtype은 데이터로부터 수렴시키는 계층형 온톨로지 설계
- 명시적 그래프 경로 추적 및 유효 경로 부재 시 답변 거절로 근거 기반 추론 보장

---

### Findish — Personalized & Group-tailored AI Dining Platform

**AI Agent Engineer** | Jan. 2026 - Jun. 2026  
🥇 **Best Project Award**, 2026 Capstone Design Exhibition  
[📂 GitHub Repository](https://github.com/SinseonSeolnongtang)

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-4A90E2?style=flat-square&logo=protocol&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white)

- 오케스트레이터가 사용자 의도를 분류해 ReAct 기반 Discovery / 트랜잭션 Action 서브그래프로 라우팅
- 예약·주문 등 비가역 작업에 'collect-confirm-execute' HITL 흐름 적용, 대화 턴을 넘어 상태 유지
- MCP 서버로 외부 도구를 표준 인터페이스에 노출해 에이전트 로직과 백엔드 분리

---

### LLM-based Autonomous Robot Agent — VLM-driven Warehouse Sorting

**AI Perception & Agent Engineer** | Jun. 2026 - Jul. 2026  
🥇 **1st Place**, Singapore AI·SW Industry-Academia Project  
*Hansung University & Menlo Research, Singapore*

![VLM](https://img.shields.io/badge/Vision--Language_Model-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Robotics](https://img.shields.io/badge/Embodied_AI-FF6B35?style=flat-square&logo=ros&logoColor=white)

- Menlo Research의 Asimov 창고 시뮬레이션에서 사전 지도 없이 큐브를 분류하는 embodied 에이전트 개발
- LLM 상위 의사결정 + 결정적 실행 코드의 하이브리드 구조 설계
- VLM 표지판 판독과 로봇 자세·거리 추정으로 좌표 산출 — 금지된 ground-truth scene state 대체
- 360° 연속 스캔 중 비동기 VLM 요청으로 탐색 지연 단축, 고정거리 가정의 한계 진단

---

### All is Well — Adaptive Natural Language Panel Extraction

**AI Systems & Full-Stack Developer** | Aug. 2025 - Dec. 2025  
🥈 **Excellence Award**, 2025 Hansung SW-Centered University Festival  
*Hansung University & PMI*

![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat-square&logo=databricks&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

- SQL + ChromaDB 하이브리드 검색에 BGE Cross-Encoder 리랭킹 결합, 63만 건 설문 데이터에서 고정밀 패널 추출
- LangGraph checkpointer와 동기화된 SQLite 상태 관리로 다중 턴 드릴다운 세션 구현

---

### E-Clips — AI-Powered Short-form Lecture Platform

**Frontend Developer** | Feb. 2025 - Oct. 2025  
🥉 **Encouragement Award**, Hanium Dream-Up Contest · 📄 **Paper Accepted**, ACK 2025

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

- RAG 기반 대학 챗봇 및 AI 퀴즈 시스템의 인터랙티브 프론트엔드 구현
- 영상 생성·STT/TTS·LLM 백엔드 파이프라인 연동 및 저지연 상태 관리 최적화

---

## 🏆 Awards & Honors

| Date | Award | Competition / Organization |
| --- | --- | --- |
| 2026.07 | 🥇 **1st Place** | Singapore AI·SW Industry-Academia Project |
| 2026.06 | 🥇 **Best Project Award** | 2026 Capstone Design Exhibition |
| 2025.11 | 🥈 **Excellence Award** | 2025 Hansung SW-Centered University Festival |
| 2025.11 | 🥉 **Encouragement Award** | Hanium Dream-Up (ICT Mentoring) Contest |
| 2025.03 | 🎓 **Academic Excellence Scholarship** | Hansung University |
| 2021.10 | 🥉 **Encouragement Award** | Smart Corona Era Idea Contest |

---

## 🎯 Extracurricular Activities

**2026 AI·SW Industry-Academia Overseas Internship** | Jun. 2026 - Jul. 2026  
*Hansung University & Menlo Research, Singapore*
- Global AI/SW Fellowship 선발, Menlo Research와 자율 로봇 에이전트 개발
- AWS · Grab · HMGICS · Autonomous A2Z · QuikBot · PIA Space 현장 방문, NUS·SUTD 세미나 참여

**DC&M** | Aug. 2024 - Present  
*Official Academic Club of Computer Engineering, Hansung University* — Executive Board Member
- 기술 스터디 그룹 운영 및 공모전·해커톤 팀 멘토링, 교내 SW 축제·학술 행사 기획

---

## 🛠️ Tech Stack

**LLM & Agent**  
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-4A90E2?style=flat-square&logo=protocol&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

**Language**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Database**  
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat-square&logo=databricks&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Web & Infra**  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Spring](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

[![Email](https://img.shields.io/badge/📧_hklove1212@naver.com-03C75A?style=for-the-badge&logo=naver&logoColor=white)](mailto:hklove1212@naver.com)
[![GitHub](https://img.shields.io/badge/@yourusername-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yourusername)

**✨ Thanks for visiting! ✨**

![footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=120&section=footer&animation=twinkling)
