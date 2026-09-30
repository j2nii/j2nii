# 김지은 | AI Engineer

> 모델의 출력을 사용자가 믿고 쓸 수 있는 서비스로 만드는 AI 엔지니어

- 기술을 고르기 전에 **이 기술이 누구의 어떤 문제를 푸는가**를, 모델이 결과를 낸 뒤에는 **사용자가 이 결과를 믿고 쓸 수 있는가**를 묻습니다.
- LLM·임베딩 모델을 외부 데이터와 연동해 서비스 파이프라인으로 구현하고, 배포 이후 운영까지 다뤄 왔습니다.
- 관심 분야: Language AI, LLM 에이전트, MLOps

## Projects

| 프로젝트 | 한 줄 설명 | 내 역할 | 키워드 |
|---|---|---|---|
| [Phishing-Break](portfolio/phishing-break.md) | 시니어 금융사기 탐지 AI 에이전트 (FIN:NECT 2026 출품) | 스미싱 탐지 모델 — 데이터셋 설계·전처리·파인튜닝 | XLM-RoBERTa, Hard Negative, 오탐률 1.04% |
| [AI-Insight Estate](portfolio/ai-insight-estate.md) | 자연어로 위성 이미지 속 입지를 찾는 멀티모달 검색 | 인덱싱·실시간 파이프라인·LLM 리포트·성능 최적화 | CLIP, FAISS, Solar LLM, 응답 30초~1분→20초 |
| [QueryTalk](portfolio/querytalk.md) | 자연어 질문을 SQL과 차트로 바꾸는 데이터 분석 에이전트 | Guardrail·Visualization Agent, 공통 LLM 호출 모듈 | Text-to-SQL, LLM Agent, Guardrail |
| [결 (LiteRec)](portfolio/literec.md) | 독서 리뷰의 '결'로 책을 추천하는 서비스 | 백엔드·인프라, 신규 리뷰 처리 CronJob | k3s, CronJob, FastAPI, Solar LLM |

## Tech Stack

- **AI / LLM**: XLM-RoBERTa, CLIP ViT-L/14, Solar LLM(Upstage), FAISS
- **Backend / Data**: Python, FastAPI, Django, SQLite, PostgreSQL
- **Ops**: Kubernetes(k3s) CronJob, GitHub Actions, Docker
- **Demo**: Streamlit

## Education & Activities

- 덕성여자대학교 디지털소프트웨어공학부 (2023.03 ~ 2027.02 졸업 예정)
- 투빅스(TOBIG's) 25기 — AI·빅데이터 연합 동아리, LLM 논문·멀티에이전트 스터디 (2026.01 ~ )
- 피로그래밍(PIROGRAMMING) 23기 부원 · 24기 교육부 운영진 — Django 웹 개발, AI 활용 커리큘럼 개편 (2025.07 ~ 2026.02)
- Synapse 2기 — AI-Insight Estate, 결(LiteRec) 프로젝트 (2025.09 ~ 2026.08)
- 3D 딥러닝 연구실 학부연구생 (Visual AI Media Lab)

## Other Projects

- [rec-system](https://github.com/why-they-leave/rec-system) (투빅스 컨퍼런스) — LLM 페르소나와 그래프 기반 추천 시스템 연구, 설명 가능한 재랭킹 데모. 앱·데모 담당
- [Moodico](https://github.com/pirogramming/Moodico) (피로그래밍 23기) — Django 기반 웹 서비스. 백엔드 전반, 배치(Cron) 처리 ([fork](https://github.com/j2nii/Moodico))
