---
layout: post
title: "Conventional commits"
date: 2020-06-15 110:00:00 +0900
marp: true
---

# Conventional commits

---

## 공식사이트

[공식사이트](https://www.conventionalcommits.org/ko/v1.0.0/)

> 커밋 메세지에 사용자와 기계 모두가 이해할 수 있는 의미를 부여하기 위한 스펙

위의 내용은 공식사이트에 정의되어 있는 소개글이다.

---

## 도입하게 된 동기

- git 커밋메시지들의 포맷이 작성자마다 다르다.
- changelog 를 자동으로 작성하고 싶다.
- 커밋메시지만으로도 커밋내용을 알고싶다.

---

## 커밋메시지 규격

> <타입>[적용 범위(선택 사항)]: <설명>
> [본문(선택 사항)]
> [꼬리말(선택 사항)]

---

## 사용할 타입

- **fix:** Bug Fix, API 변경 사항 없이 내부 수정
- **feat:** 기능 추가, API 변경(하위 호환)
- **BREAKING CHANGE:** API 의 변경, 큰 변화
- **refactor:** 내부적인 리펙토링
- **docs:** 문서
- **test:** 테스트 코드
- **chore:** 그외 자잘한 수정 사항들

---

## 작성 예제

> feat: conventional-commits 포스트 추가

---

## 도구

---

### standard-version

[공식사이트](https://github.com/conventional-changelog/standard-version)

---

#### npm으로 설치

- 글로벌
  - `npm i -g standard-version`
- 로컬
  - `npm i --save-dev standard-version`

---

#### 사용법

- 최초 버전으로 만들기
  - `standard-version --first-release`
- 특정 버전으로 만들기
  - `standard-version --release-as 1.1.0`

---

## 참고 문서

- [컨벤션 커밋 공식사이트](https://www.conventionalcommits.org/ko/v1.0.0/)
- [쿡앱스 기술 블로그](https://blog.cookapps.io/guide/conventional-commits/#%EC%82%AC%EC%9A%A9%EB%B2%95)
- [standard-version 사이트](https://github.com/conventional-changelog/standard-version)
