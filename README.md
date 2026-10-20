# 무한매수 관리 (infinityBuy)

"무한매수법"(분할 매수·매도를 반복하는 적립식 전략) 운용 현황을 관리하는 대시보드.

## 구성
- `index.html` — 메인 페이지 (Chart.js로 추이 시각화)
- `index_v260808.html` — 이전 버전 스냅샷

## 동작 방식
백엔드 API(`infinity-api.kgu3405.workers.dev`, Cloudflare Workers)에서 매수/매도 현황 데이터를 받아와 표시. 세부 매매 규칙은 `index.html` 스크립트 참고.
