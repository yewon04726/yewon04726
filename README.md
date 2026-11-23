
## Profile

| Category | Details |
| --- | --- |
| University | Sogang University |
| Class | 실전 AI 에이전트 개발 (Decision Pulse) |
| Club | CSPC 학회 (실습실 관리 사이트 백엔드) |
| Contest | 2026 한국관광데이터 활용 공모전 (숨트립 기획·프론트) · KB AI Challenge (백엔드·AI 구현) |
| Certification | SQL Developer |

## 대표 프로젝트

| 프로젝트 | 한 줄 소개 | 내가 한 일 |
| --- | --- | --- |
| [Decision Pulse](https://github.com/yewon04726/Decision-Pulse) | 과거 기술 결정과 재검토 조건을 기억하고, 지표가 조건을 넘으면 알려주는 에이전트 | 문제 정의, 구조 설계, 검증 방식 결정 (개인 프로젝트) |
| [숨트립 (SoomTrip)](https://github.com/yewon04726/soomtrip-mobile) | 취향 월드컵으로 국내 여행지를 추천받고 저장·기록하는 앱 (원스토어 출시) | 서비스 기획, 디자인, 프론트엔드, 배포 |
| [CSPC 관리 사이트](https://github.com/yewon04726/cspc-manage-server-2026) | 학회 실습실 관리 시간표, 컴퓨터 상태, 공지를 관리하는 서비스 | 문제 제안, 백엔드 |
| [KB AI Challenge](https://github.com/yewon04726/KB_AI-Challenge) | 가맹점주를 위한 입지·금융상품 추천 AI 서비스 | 백엔드, [AI 구현 범위] |

---

## Decision Pulse 한눈에 보기

```text
회의록(텍스트 · 문서 · 음성)
  → AI가 결정과 재검토 조건을 후보로 추출
  → 사람이 승인한 결정만 저장
  → 지표를 주기적으로 확인해 조건 충족 시 웹 알림 + 텔레그램 알림
  → 사람이 재검토
```

- AI 추출 결과는 항상 후보로만 저장하고, 승인된 결정만 반영
- 재검토 판정은 LLM이 아닌 코드로 처리해 결과가 재현되도록 설계
- 에이전트는 읽기 전용 도구만 사용하고, 사용한 도구를 감사 기록으로 남김
- 로컬 모델과 외부 모델의 추출 결과를 비교하는 실험 스크립트 포함

---

## 기술 스택

[![Tech Stack](https://skillicons.dev/icons?i=c,cpp,python,js,fastapi,nodejs,nextjs,react,mysql,git&perline=10)](https://skillicons.dev)

| 분류 | 기술 |
| --- | --- |
| Language | C, C++, Python, JavaScript |
| Backend | FastAPI, Node.js |
| Frontend / Mobile | Next.js, React |
| DB | MySQL |
| Tools | Git |

---
