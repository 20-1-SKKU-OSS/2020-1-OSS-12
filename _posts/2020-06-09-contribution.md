---
layout: post
title:  "개인 기여활동"
date:   2020-06-09
---

# 개인별 기여활동 보고

## 박원호
1. 타 사이트에 올라온 이슈 정리해서 github 이슈 등록 (clear)
- 공지: Pull-Request를 통한 개인 기여활동 보고 이슈 등록
- 문제 보고: 국가에서 차단한 영상 재생 관련 문제, 재생목록 리스트 한계 문제 이슈 등록

2. 타 사이트에 올라온 유용한 질답 종합해서 설명서 작성 (clear)
- QA sheet를 정리한 QA.md 작성 계획
- 이후, QA.md 작성 없이 1.의 이슈 정리로 통합

3. 신규 사용자를 위한 플러그인 설치, 사용 설명서 작성 (clear)
- 신규 사용자를 위한 매뉴얼 설명서인 MANUAL.md 작성
- MANUAL.md에 추가로 AIMPYouTube 기능 사용법 추가 작성

4. 추가활동 - 국가 영상 차단 Issue 코드 분석(In progress)
- YouTubeDLL.cpp 신규 contributor을 위한 변수 및 함수 설명본 정리

<hr>
## 노태현

### 2020-06-07
* 기존에 포럼에 올라오는 피드백과 원본 github의 issue들을 직접 구동해보고 현재까지 해결이 되지 않은 문제를 선별해서 12조 issue에 등록함
* https://github.com/20-1-SKKU-OSS/2020-1-OSS-12/issues/6 
* https://github.com/20-1-SKKU-OSS/2020-1-OSS-12/issues/7 기능 추가 제안

### 2020-06-09
* MANUAL.md 업데이트
* README.md 한글화

## 유영조
1. 스킨별 호환성 이슈 해결 (-)
- 커스텀 스킨의 경우 생략된 기능이 있을 수 있음 (예: 재생목록관리 탭)
- 이로 인해 AIMPYoutube 플러그인의 주요 기능인 유튜브 재생목록 관리를 할 수 없는 스킨이 다수 있음
- 유튜브 플러그인은 단순히 유튜브 url을 AIMP 플레이어에 제공하는 역할이므로 이 문제를 해결할 수 없음


2. 플러그인과 호환되는 스킨 목록작성 (clear)
- 플러그인 사용자의 편의를 위해 플러그인과 호환가능한 스킨을 다운로드수 10만 이상 기준 100개의 목록(cmpSkinList.md)으로 제공 

3. 신규 베타버젼(v1.7) 버그 테스트 후 리포트 (In progress)
- 진행 중

4. README.md 작성 (clear)
