---
title: "NGUI vs UGUI"
date: 2018-10-04 10:00:28 -0400
categories: Unity
---
## NGUI (Next-Gen UI)

* UGUI가 나오기 이전부터 많은 개발사가 사용하던 플러그인
* 레퍼런스가 많다
* 다양한 크기의 화면에 최적화시키기 쉽다 (비교적)
* 정적인 화면에 최적화가 잘되어 있다.
* 동적 할당을 할 때 Sprite를 다시 그리기 때문에 비효율적

## UGUI (Unity GUI)

* Unity Engine (4.6 이후부터) 내에서 제공하는 UI System
* 추가 구매 없이 바로 사용 가능
* 직관적인 UI 구성요소 간의 Depth 조절
* Canvas 단위로 Draw Call이 관리됨
* Sprite Atlas 관리 (폴더 단위로도 가능)
* Particle Rendering 문제가 있음
* Tweening을 기본으로 지원하지 않음
* 소스 코드가 공개되어 있음 (https://bitbucket.org/Unity-Technologies/ui)
* UI 확장 Asset도 쉽게 구할 수 있음
* 비공식 UI 확장 Component도 소스가 공개되어 있음 (https://bitbucket.org/UnityUIExtensions/unity-ui-extensions)
* 동적 할당이 편함
* 아직 버그가 많다고 하다


상황에 맞춰서 사용하면 될듯하다.
