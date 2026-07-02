# Seocheon Birds Guide

서천 조류 관찰 예측 가이드입니다.

## 구성

- `index.html`: 단일 HTML 웹앱
- 에코뱅크 GeoServer WFS 조류 점 자료 기반
- 서천권 조류 전체종, 조사권역, 조류별 상세정보 포함

## 데이터 기준

- 에코뱅크 `mv_map_ntee_birds_point`
- 에코뱅크 `mv_map_ecpe_birds_point`
- 장항 조석 조건과 7월 계절성을 함께 반영한 관찰 우선순위
- 새 대표 사진은 Wikimedia/Wikipedia, GBIF, iNaturalist 공개 이미지 URL 사용

## 실행

브라우저에서 `index.html`을 열면 됩니다.

GitHub Pages에 올릴 경우 저장소의 Pages 설정에서 branch를 `main`, folder를 `/root`로 지정하면 웹 주소로 볼 수 있습니다.

## 주의

예측 점수는 실제 출현 보장이 아니라 관찰 우선순위입니다. 멸종위기종과 민감종 위치는 공개자료에서 제외되거나 흐려질 수 있습니다.
