# 별자리 운세실

타로 카드와 사주로 보는 나의 운세 웹앱입니다.

- **타로**: 1장 · 3장 · 켈틱 크로스(10장) 배열, 78장 카드 정방향·역방향 해설, 종합 해설
- **카드 사전**: 78장 카드의 뜻 모아 보기
- **사주**: 양력 생년월일(음력은 변환 버튼 제공)·시각으로 일주·시주·띠를 계산해 타고난 성향과 2026년 흐름 풀이

사주 풀이는 전통 사주명리학 이론(10천간·12지지·60갑자·십신·12운성·합충형해파)을 바탕으로 정리한 해석입니다. 월주는 절기 계산이 필요해 아직 넣지 않았습니다. 재미와 참고용입니다.

만든이: 최하용

## 사용한 공개 라이브러리

- [korean-lunar-calendar](https://github.com/usingsky/korean_lunar_calendar_js) v0.4.0 (MIT) — 음력→양력 변환, 한국천문연구원 기준. 라이선스: `vendor/korean-lunar-calendar.LICENSE`
- [astronomy-engine](https://github.com/cosinekitty/astronomy) v2.1.19 (MIT) — 24절기 시각 계산(월주·입춘). 한국천문연구원 달력자료 2021·2024·2026·2028년 절기 96개와 1분 이내 일치 확인. 라이선스: `vendor/astronomy-engine.LICENSE`
