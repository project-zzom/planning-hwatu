---
permalink: /user-guide-overview/
title: "사용자 가이드"
excerpt: "Estimate workload with team members"
header:
  overlay_image: /assets/images/banner 1280 x 500.png
  overlay_filter: 0.5
author_profile: false
sidebar:
    nav: "user-guide-menu"
---

(작성 보완 중)

## 플래닝 포커

 소프트웨어를 개발할 때 팀원의 개발 경험을 기반으로 작업량을 추정하는 도구로 '스크럼 포커', '스크럼 카드'라고도 합니다.<br/>
대표적인 제품으론 <a href="https://www.mountaingoatsoftware.com/" target="_blank">마운틴 고트 소프트웨어</a>의 'PLANNING POKER'가 있습니다.

![플래닝 포커 사진]()

### 플래닝 포커를 왜 하나요?

작업량을 추정하기 위해 사용합니다.<br/>
개발할 소프트웨어에 대한 팀원 간의 인식 차이를 확인하고, 팀원 간의 대화를 통해 시각차를 줄이는 데 유용합니다.

## 플래닝 화투

'플래닝 화투'는 '플래닝 포커'의 기능을 승계하여 리팩터링한 도구면서 기존 룰을 살짝 비틀어서 쓸 수 있게 재설계한 도구입니다.

![플래닝 화투 사진]()

### 플래닝 화투를 왜 하나요?

플래닝 포커보다 더 많은 사람이 참여할 수 있고, 더 정밀하게 추정할 수 있으며, 추정하는 과정에서 타격감을 맛보고 싶을 때 사용합니다.

### 플래닝 화투의 기능

#### 플래닝 포커와 같은 기능

기존의 플래닝 포커처럼 사용할 수 있습니다.

* 프로덕트 백로그의 작업량 크기 분류 (XS, S, M, L, XL)
* 프로덕트 백로그의 작업량 추정 (포인트)
* 앵커링 효과를 배제한 카드 제시 방법

#### 플래닝 포커를 확장한 기능

기존의 플래닝 포커 기능을 확장해서 쓸 수 있습니다.
플래닝 포커와 팀원 간의 협업에 경험이 쌓여서 더 공격적이고 구체적으로 추정할 때 유용합니다.

* 스프린트 백로그의 작업량 추정 (소요일, 소요시간)
* 최소 1/2 단위의 정밀한 작업량 추정
* '반', '따블', '따따블'과 같은 직관적인 작업량 추정
* 앵커링 효과를 역이용한 카드 제시 방법
* 다이나믹한 타격감
* 핸드 카드 개수 최소화
* 1개 데크로 9명까지 사용 가능 (적정 개발자 3~9명)

자세한 내용은 다음 문서를 참고하세요.

* [플래닝 포커]({{ site.baseurl }}/user-guide-planning-poker)
* [플래닝 화투]({{ site.baseurl }}/user-guide-planning-hwatu)
* [플래닝 포커 vs 플래팅 화투]({{ site.baseurl }}/user-guide-planning-poker-vs-hwatu)