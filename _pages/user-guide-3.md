---
permalink: /user-guide-3/
title: "사용자 가이드"
excerpt: "Estimate workload with team members"
header:
  overlay_image: /assets/images/header/header-github-pages.png
  overlay_filter: 0.5
author_profile: false
sidebar:
    nav: "user-guide-menu"
---

(작성 보완 중)

'플래닝 화투'는 '플래닝 카드'와 비슷한 역할을 하면서 더 다양하게 활용할 수 있도록 리팩토링된 도구입니다.

# 카드 구성 이해하기

카드를 설명하기 전에 용어를 먼저 정리합니다.

* 핸드 카드: 참여자가 손에 쥐는 개인 카드
* 그라운드 카드: 테이블 위에 올려두는 공용 카드
* 설명 카드: 카드 사용법이 기재된 카드

## 플래닝 포커의 카드 구성
플래닝 포커 구성은 다음과 같습니다.<br/>
총 54장으로 1개 데크로 최대 4명의 참여자가 쓸 수 있습니다. 

* 핸드 카드: 52장 (4가지 색 x 개인용 13장)
* 설명 카드: 2장 (사용법 안내)

<img alt="플래닝 포커 카드" src="{{ site.baseurl }}/assets/images/goods/planning-poker/planning-poker.png" width="60%">
<br/>

## 플래닝 화투의 카드 구성
플래닝 화투 구성은 다음과 같습니다.<br/>
총 54장으로 1개 데크로 최대 9명의 참여자가 쓸 수 있습니다.

* 핸드 카드: 45장 (9가지 색 x 개인용 5장)
* 그라운드 카드: 9장 (검정 색 공용 9장)

<img alt="플래닝 화투 카드" src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/planning-hwatu.png" width="60%">
<br/>

### 핸드 카드 
참여자는 다음과 같은 5장의 개인 카드를 손에 듭니다.<br/>
참여자마다 카드 색이 달라 최대 9명까지 쓸 수 있습니다.

<img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-0.5.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-1.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-2.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-4.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-8.png" width="100">


핸드 카드는 다음과 같은 기능이 있습니다

#### 작업량을 추정

작업량은 2의 거듭제곱으로 표현합니다.
(예: 기준 작업량의 반, 기준 작업량의 배)<br/>
기본적인 작업량 단위는 '포인트'지만 응용하면 '소요일', '소요시간'으로 쓸 수 있습니다.
(응용 방법은 뒤에서 설명)

| 카드 | 의미 | 
| - | - |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-0.5.png" width="50"> | 0.5 포인트 |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-1.png" width="50"> | 1 포인트 |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-2.png" width="50"> | 2 포인트 (기준 작업량) |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-4.png" width="50"> | 4 포인트 |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-8.png" width="50"> | 8 포인트 |

### 그라운드 카드
참여자 모두가 함께 쓰는 공용 카드입니다.
다음과 같은 9장의 카드를 바닥에 둡니다.

<img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-xs.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-s.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-m.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-l.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-xl.png" width="100">
<br/>
<img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-0.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-question.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-infinity.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-asterisk.png" width="100">

#### 개략적인 크기로 분류

작업량을 포인트로 추정하기 전에 크기별로 분류할 때 사용합니다.

| 카드 | 의미 | 
| - | - |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-xs.png" width="50"> | 많이 작은 일감 |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-s.png" width="50"> |  조금 작은 일감 |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-m.png" width="50"> |  보통 일감 |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-l.png" width="50"> |  조금 큰 일감 |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-xl.png" width="50"> | 많이 큰 일감 |

#### 추정을 멈춤

작업량 추정을 멈춰야 할 때 사용합니다.

| 카드 | 의미 | 
| - | - |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-0.png" width="50"> | 작업할 필요가 없어 추정이 무의미할 때<br/>(예: 이미 끝난 작업, 하지 않기로 한 작업) |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-question.png" width="50"> | 작업 내용이 불명확해서 추정이 불가능할 때<br/>(예: 추가 설명이 필요한 작업)  |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-infinity.png" width="50"> | 작업량이 너무 커서 추정이 불가능할 때<br/>(예: 더 작게 분해해야 하는 작업) |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-asterisk.png" width="50"> | 추정을 멈추고 휴식이 필요할 때<br/>(예: 커피, 간식, 사다리) |

## 플래닝 포커와의 차이점

### 수열

플래닝 포커는 피보나치수열을 응용한 숫자를 사용하고, 플래닝 화투는 2의 거듭제곱을 수열로 사용합니다.

| 항목 | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 수열 | 피보나치수열을 응용한 숫자 | 2의 거듭제곱 |

### 데크당 참여 인원 수
플래닝 화투는 개인용 핸드 카드와 공용 그라운드 카드를 분리하여 최대 9명까지 쓸 수 있습니다.

| 항목 | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 사용자 | 최대 4명<br/>(개발자 9명인 경우 3개 데크 필요 | 최대 9명<br/>(개발자 9명인 경우 1개 데크 필요) |
| 카드<br/> 개수 | 54장<br/>(2장은 설명 카드) | 54장 |
| 핸드<br/> 카드 | 13장 <br/><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-0.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-0.5.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-1.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-2.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-3.png" width="50"><br/><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-5.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-8.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-13.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-20.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-40.png" width="50"><br/><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-100.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-infinity.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-question.png" width="50"> | 5장<br/><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-0.5.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-1.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-2.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-4.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-8.png" width="50">|
| 그라운드<br/> 카드 | 없음 | 9장<br/><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-xs.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-s.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-m.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-l.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-xl.png" width="50"><br/><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-0.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-question.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-infinity.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-asterisk.png" width="50"> |
| 엑스트라<br/> 카드 | 별도 카드 구매 필요<br/>1개 데크에 20장 제품에 포함<br/><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-xs.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-s.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-m.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-l.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-xl.png" width="50"><br/><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-break.png" width="50"><br/><a href="https://www.flaticon.com/free-icons/tea" title="tea icons">Tea icons created by Freepik - Flaticon</a> | 모든 카드가 포함됨 |
| 핸드<br/> 카드<br/> 사용법 | 핸드 카드를 제시<br/>1장만 사용 가능 | 핸드 카드로 바닥을 타격<br/>2장 이상 사용 가능<br/>(뒤에서 설명) |
| 그라운드<br/> 카드<br/> 사용법 | 없음 | 핸드 카드로 그라운드 카드를 타격<br/>2장 이상 사용 가능<br/>(뒤에서 설명) |

---

# 사용 방법 이해하기

## 참여자

추정에 참여하는 사람은 다음과 같습니다.

| 역할 | 설명 | 
| - | - |
| 프로덕트 오너 | 프로덕트 백로그 항목을 설명 |
| 스크럼 마스터 | 추정 절차나 방법을 안내 |
| 개발자 | 작업자 관점에서 작업량을 예측 |

## 기준 작업 / 기준 포인트 고르기

작업량 추정 전에 기준 작업을 고릅니다. 기준 작업은 작업량이 크지도, 작지도 않은, 참여자 전원이 비슷하게 작업량을 짐작하는 작업입니다.

### 포스트잇을 사용하는 경우

1 프로덕트 백로그 항목의 내용을 프로덕트 오너가 설명합니다.

<img alt="설명하기" src="{{ site.baseurl }}/assets/images/user-guide/프로덕트_백로그_항목_설명하기.png" width="60%">
<br/>

2 개발자가 백로그 항목을 작업량 크기로 분류합니다.

<img alt="분류하기" src="{{ site.baseurl }}/assets/images/user-guide/카드_쓰지_않고_기준_작업_정하기_1.png" width="60%">
<br/>

3 스크럼 마스터는 중간 크기의 그룹에서 모두가 작업량에 공감하는 항목을 고릅니다.

<img alt="기준잡기" src="{{ site.baseurl }}/assets/images/user-guide/카드_쓰지_않고_기준_작업_정하기_2.png" width="60%">
<br/>

4 고른 항목의 작업량을 기준 작업량으로 삼습니다. 

일반적으로 기준 작업량은 3 정도로 잡고 단위는 '소요일'이나 '소요시간'과 같은 구체적인 단위가 아닌 '포인트'라는 상대적인 크기를 표현하는 단위를 씁니다. (예: 기준 작업량은 3 포인트)

### 플래닝 포커를 사용하는 경우

플래닝 포커 제품 중에는 XS, S, M, L, XL 카드를 포함한 확장판이 있습니다. (핸드 카드가 20장) 작업량을 추정할 때 포스트잇이 아닌 핸드카드로 크기를 표현합니다.

1 프로덕트 백로그 항목의 내용을 프로덕트 오너가 설명합니다.

<img alt="설명하기" src="{{ site.baseurl }}/assets/images/user-guide/플래닝_포커로_기준_작업_정하기_1.png" width="60%">
<br/>

2 개발자는 자신이 생각한 작업량을 카드로 표현합니다.

<img alt="분류하기" src="{{ site.baseurl }}/assets/images/user-guide/플래닝_포커로_기준_작업_정하기_2.png" width="60%">
<br/>

3 스크럼 마스터는 개발자 간의 인식 차이를 좁혀주면서 합의를 이끕니다.

4 다음 스프린트에서 작업할 만큼만 반복합니다.

### 플래닝 화투를 사용하는 경우

플래닝 화투에선 XS, S, M, L, XL 카드를 모두가 함께 쓰는 그라운드 카드로 둡니다. 작업량을 추정할 때는 핸드 카드로 그라운드 카드를 타격하여 크기를 표현합니다.

1 프로덕트 백로그 항목의 내용을 프로덕트 오너가 설명합니다.

<img alt="설명하기" src="{{ site.baseurl }}/assets/images/user-guide/플래닝_화투로_기준_작업_정하기_1.png" width="60%">
<br/>

2 개발자는 자신이 생각한 작업량을 카드로 표현합니다. 이때 숫자의 크기로 의지의 강약을 표현할 수 있습니다. 여러 장의 카드를 합산할 수 있습니다. (예: S는 3, M은 14이므로 M으로 판정)

<img alt="분류하기" src="{{ site.baseurl }}/assets/images/user-guide/플래닝_화투로_기준_작업_정하기_2.png" width="60%">
<br/>

3 스크럼 마스터는 개발자 간의 인식 차이를 좁혀주면서 합의를 이끕니다.

4 다음 스프린트에서 작업할 만큼만 반복합니다.

---

## 작업량 추정하기 (기본)

프로덕트 백로그의 작업량을 포인트로 추정합니다.

### 플래닝 포커를 사용하는 경우

1 각자 생각한 작업량의 크기를 카드로 표현합니다. 이때 모든 참여자가 동시에 제시합니다.

<img alt="산정하기" src="{{ site.baseurl }}/assets/images/user-guide/플래닝_포커로_작업량(포인트)_산정하기.png" width="60%">
<br/>

2 추정한 작업량의 차이가 크면 서로의 생각을 공유합니다.

<img alt="조율하기" src="{{ site.baseurl }}/assets/images/user-guide/플래닝_포커로_작업량(포인트)_산정하기_2.png" width="60%">
<br/>

3 참여자의 생각 차이가 줄어들 때까지 반복합니다.

### 플래닝 화투를 사용하는 경우

1 각자 생각한 작업량의 크기를 카드로 표현합니다. 이때 모든 참여자가 동시에 제시합니다.

<img alt="산정하기" src="{{ site.baseurl }}/assets/images/user-guide/플래닝_화투로_작업량(포인트)_산정하기_1.png" width="60%">
<br/>

2 추정한 작업량의 차이가 크면 서로의 생각을 공유합니다.

<img alt="조율하기" src="{{ site.baseurl }}/assets/images/user-guide/플래닝_화투로_작업량(포인트)_산정하기_2.png" width="60%">
<br/>

3 참여자의 생각 차이가 줄어들 때까지 반복합니다.

상대적인 크기를 5단계로 표현할 수 있습니다.
프로덕트 백로그 항목의 작업량 크기를 스토리 포인트로 표현할 수 있습니다.
각 단계는 앞 단계의 2배, 다음 단계의 1/2배 크기입니다.


## 플래닝 포커와의 차이점

플래닝 포커는 가장 작은 수가 0, 가장 큰 수가 100입니다.
플래닝 화투는 가장 작은 수가 0, 가장 큰 수가 8입니다.
와일드카드(*)의 의미는 팀에서 재정의 가능합니다. (예: 커피, 피자, 사다리, 탁구 등)

| 항목 | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 0 표현법 | 손에 쥔 0 카드를 제시 | 바닥에 놓인 0 카드를 타격 |
| ? 표현법 | 손에 쥔 ? 카드를 제시 | 바닥에 놓인 ? 카드를 타격 |
| ∞ 표현법 | 손에 쥔 ∞ 카드를 제시 | 바닥에 놓인 ∞ 카드를 타격 |
| * 표현법 | 손에 쥔 ☕ 카드를 제시 | 바닥에 놓인 * 카드를 타격 |

그라운드 카드를 타격할 때는 손에 쥔 핸드 카드의 숫자로 강약을 표현할 수 있습니다.

| 그라운드 카드 | 핸드 카드 | 의미 |
| - | - | - |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-asterisk.png" width="50"> | <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-0.5.png" width="50"> | 좀 쉬었다가 하면 안될까요? |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-asterisk.png" width="50"> | <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-1.png" width="50"> | 쉬었다가 하시죠. |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-asterisk.png" width="50"> | ... | ... |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-asterisk.png" width="50"> | <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-0.5.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-1.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-2.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-4.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-8.png" width="50"> | 커피는 내가 쏠테니까 제발 쉬자고!  |

크기가 작은 카드로 타격하면서 조심스럽게 의견을 물어볼 수 있습니다.
한번에 여러 장의 카드를 투척하면서 강한 의지를 표현할 수 있습니다.

![폭탄 동영상]()

다른 참여자도 동의한다면 연타로 타격해도 됩니다.

![연타 동영상]()

---

# 작업량 추정하기 (응용)

## 프로덕트 백로그의 작업량을 포인트로 추정할 때

플래닝 화투에선 1/2에서 8까지 2배 단위로 포인트를 표현할 수 있습니다.
상황에 따라 포인트를 더 정밀하고 더 폭넓게 표현하고 싶을 수 있습니다.
그럴 때는 여러 장의 카드를 합산해서 써보세요.

| 카드 | 포인트 |
| - | - |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-0.5.png" width="50"> | 0.5 포인트  |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-1.png" width="50"> | 1포인트 |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-0.5.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-1.png" width="50"> | 1.5 포인트 |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-2.png" width="50"> | 2 포인트 |
| ... | ... |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-1.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-2.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-4.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-8.png" width="50"> | 15 포인트 |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-0.5.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-1.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-2.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-4.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-8.png" width="50"> | 15.5 포인트 |

0.5 단위로 정교하게 포인트를 표현할 수 있습니다.
0.5에서 15.5까지 폭넓게 포인트를 표현할 수 있습니다.

## 플래닝 포커와의 차이점

플래닝 포커는 한 장의 카드만 쓸 수 있습니다. 
플래닝 화투는 여러 장의 카드를 합산해서 쓸 수 있습니다.

| 항목 | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 카드 사용 | 한 장의 카드만 사용  | 여러 장의 카드를 사용 |

![합산]()

---

# 카드 제시하기 (확장)

작업량 추정 시 카드를 제시하는 방법을 다양하게 확장할 수 있습니다.

## 앵커링 효과(anchoring effect)를 배제한 방법

앵커링 효과(anchoring effect)는 앞사람의 행동이 뒷사람에게 영향을 주는 걸 말합니다.
플래닝 포커를 할 때는 앵커링 효과(anchoring effect)를 배제하기 위해 모든 참여자가 동시에 카드를 제시합니다.

![동시에 카드 제시하기]()

플래닝 포커는 동시에 카드를 제출한 후 생각의 차이를 서로 확인하는 걸 중요시 합니다.
각자의 생각을 공유하고 합의를 유도하는 과정을 반복합니다.

## 앵커링 효과(anchoring effect)를 응용한 방법

플래닝 화투도 앵커링 효과(anchoring effect)를 배제하기 위해 코든 참여자가 동시에 카드를 제시해도 됩니다.
반대로 앵커링 효과(anchoring effect)를 활용해하는 방법도 있습니다.

![차례대로 카드 제시하기]()

차례대로 카드를 제시하며 각자의 생각을 공유합니다.
다음 사람은 앞사람의 추정에 의견을 더하거나 빼면서 구체화합니다.
추상적인 작업 내용을 구체화하는 과정을 반복합니다.

## 플래닝 포커와의 차이점

플래닝 포커는 앵커링 효과(anchoring effect)를 배제합니다.
플래닝 화투는 앵커링 효과(anchoring effect)를 배제할 수도, 응용할 수도 있습니다.

| 항목 | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 앵커링 효과(anchoring effect) | 배제  | 배제 / 응용 |
| 착안점 | 생각의 차이를 확인하고 합의 유도 | 생각을 보완하며 구체화 유도 |

추정하는 순서는 개발팀 문화에 맞게 자율적으로 정합니다.
예를 들면 다음과 같은 방식으로 진행할 수 있습니다.

* 시계 반대 방향으로 추정
* 경험자 순서로 추정
* 미경험자 순서로 추정

![추정 순서]()

---

# 작업량 추정하기 (확장)

## 스프린트 백로그의 작업량을 날짜나 시간으로 추정할 때

추상적인 스토리 포인트보다 구체적인 시간으로 작업량을 표현하고 싶을 수 있습니다.
그럴 때는 팀원과 상의하여 작업 소요일이나 소요시간으로 단위를 바꿔보세요.
이때도 역시 여러 장의 카드를 합산해서 쓰면 됩니다.


| 카드 | 의미 (소요일) | 의미 (소요시간) |
| - | - | - |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-0.5.png" width="50"> | 0.5 일  | 0.5 시간 | 
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-1.png" width="50"> | 1 일 | 1 시간 |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-0.5.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-1.png" width="50"> | 1.5 일 | 1.5 시간 |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-2.png" width="50"> | 2 일 | 2 시간 |
| ... | ... | ... |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-1.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-2.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-4.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-8.png" width="50"> | 15 일 | 15 시간 |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-0.5.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-1.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-2.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-4.png" width="50"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-8.png" width="50"> | 15.5 일 | 15.5 시간 |

날짜로 사용 시 반일에서 3주 반일까지 표현할 수 있습니다.
시간으로 사용 시 30분에서 15시간 30분까지 표현할 수 있습니다.

## 플래닝 포커와의 차이점

플래닝 포커는 프로덕트 백로그 항목의 작업량 추정까지만 사용합니다.
플래닝 화투는 스프린트 백로그 항목의 작업량 추정에도 쓸 수 있습니다.

| 항목 | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 작업량 표현 | 스토리 포인트  | 스토리 포인트, 소요일, 소요시간 |
| 활용 범위 | 프로덕트 백로그 작업량 추정  | 프로덕트 백로그, 스프린트 백로그 작업량 추정 |

스프린트 백로그 항목은 작업을 할당받은 개발자가 소요시간을 추정하는 게 보통입니다.
페어 프로그래밍을 하거나 몹 프로그래밍을 할 때 서로가 생각하는 소요시간을 제시하며 추정해보세요.

![페어 프로그래밍]()

## 온라인에서 사용하기

효율적인 사용을 위해 온라인용 플래닝 포커를 추천합니다. 단 재택이나 원격 근무 중에도 아날로그 감성을 만끽하고 싶다면 별도의 웹캠으로 각자의 테이블에 놓인 카드를 비춰보세요. 
나중에 누군가가 이미지를 인식하는 서비스를 만들어 줄지도 모르니까요!

![웹캠]()