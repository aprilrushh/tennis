# 🎾 테니스는 즐거워 - 대회 관리 시스템

2024년 6월 27일 자체대회를 위한 웹 기반 테니스 대회 관리 시스템입니다.

## ✨ 주요 기능

### 📅 경기 일정표
- 7경기, A/B코트 동시 진행 일정
- 실시간 스코어 표시
- 경기 상태 (대기/완료) 시각적 표시
- 반응형 테이블 디자인

### 👥 조 편성 현황
- **1조**: 현숙, 지혜, 병수, 석환, 성무 (5명)
- **2조**: 이현, 용무, 종명, 용국, 정수, 상현 (6명)
- **3조**: 경은, 재성, 승윤, 영기, 양규, 영민 (6명)
- **4조**: 정언, 남희, 자우, 승호, 진석, 승윤 (6명)

### 📊 스코어 관리
- 모든 14경기 스코어 입력 기능
- 실시간 일정표 업데이트
- 로컬 스토리지 자동 저장
- 입력 유효성 검사 (0-99 범위)

### 📈 대회 통계
- 총 23명 참가 선수
- 진행률 시각화 (프로그레스 바)
- 완료된 경기 수 실시간 표시
- 대회 진행률 퍼센트 표시

## 🚀 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: 
  - Flexbox & Grid 레이아웃
  - CSS 애니메이션
  - 반응형 디자인
  - 모던 UI/UX
- **JavaScript (ES6+)**:
  - 모듈화된 코드 구조
  - 로컬 스토리지 활용
  - 이벤트 리스너
  - DOM 조작

## 📱 모바일 최적화

- 반응형 디자인
- 터치 이벤트 지원
- 모바일 친화적 UI
- 크로스 브라우저 호환성

## 🎨 디자인 특징

- 그라데이션 배경
- 카드 기반 레이아웃
- 부드러운 애니메이션
- 직관적인 색상 체계
- 현대적인 UI/UX

## 📋 사용 방법

1. **경기 일정 확인**: 첫 번째 탭에서 전체 경기 일정을 확인
2. **조 편성 확인**: 두 번째 탭에서 각 조별 선수 현황 확인
3. **스코어 입력**: 세 번째 탭에서 경기 결과 입력
4. **통계 확인**: 네 번째 탭에서 대회 진행 상황 확인

## 🔧 설치 및 실행

```bash
# 저장소 클론
git clone https://github.com/aprilrushh/tennis.git

# 프로젝트 폴더로 이동
cd tennis

# 브라우저에서 파일 열기
open index.html
```

또는 직접 [index.html](index.html) 파일을 브라우저에서 열어 사용하세요.

## 💾 데이터 저장

- 모든 스코어 데이터는 브라우저의 로컬 스토리지에 자동 저장됩니다
- 페이지를 새로고침해도 데이터가 유지됩니다
- 브라우저 캐시를 지우면 데이터가 초기화됩니다

## 🎯 경기 일정

| 경기 | 시간 | A코트 | B코트 |
|------|------|-------|-------|
| 1경기 | 5:00-5:30 | 석환/성무 vs 종영/용무 | 경은/재성 vs 정언/남희 |
| 2경기 | 5:30-6:00 | 현숙/병수 vs 정은/승윤 | 이현/용국 vs 정언/승호 |
| 3경기 | 6:00-6:30 | 성무/석환 vs 자우/남희 | 용국/정수 vs 재성/영기 |
| 4경기 | 6:30-7:00 | 지혜/병수 vs 정언/진석 | 상현/용무 vs 승윤/양규 |
| 5경기 | 7:00-7:30 | 석환/현숙 vs 영기/경은 | 종명/정수 vs 자우/승호 |
| 6경기 | 7:30-8:00 | 지혜/성무 vs 이현/상현 | 영민/재성 vs 진석/남희 |
| 7경기 | 8:00-8:30 | 지혜/현숙 vs 영민/양규 | 이현/용국 vs 정언/자우 |

## 🤝 기여하기

프로젝트 개선을 위한 제안이나 버그 리포트는 언제든 환영합니다!

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.

---

**테니스는 즐거워! 🎾✨** 