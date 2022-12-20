---
permalink: /user-guide-planning-poker/
title: "사용자 가이드"
excerpt: "Estimate workload with team members"
header:
  overlay_image: /assets/images/banner 1280 x 500.png
  overlay_filter: 0.5
author_profile: false
sidebar:
    nav: "user-guide-menu"
---

<div class="notice--info" markdown="1">
**용어 설명**
* 설명 카드: 카드 사용법이 기재된 카드
* 핸드 카드: 참여자가 손에 쥐는 개인 카드
* 엑스트라 카드: 별도 판매되거나 확장된 제품에서 쓰는 카드
</div>

<br/>

플래닝 포커의 일반적인 사용 방법은 아래 자료를 참고하세요.

* <a href="https://bit.ly/3WRZRjM" target="_blank">A brief overview of planning poker</a>

여기서는 플래닝 화투의 설명 내용에 앞서 플래닝 포커에 대해 간단히 설명합니다.

# 카드 구성 이해하기

## 플래닝 포커의 카드 구성
플래닝 포커 구성은 다음과 같습니다.<br/>
총 54장으로 1개 데크로 최대 4명의 참여자가 쓸 수 있습니다. 

* 핸드 카드: 52장 (4가지 색 x 개인용 13장)
* 설명 카드: 2장 (사용법 안내)

<figure>
<img alt="플래닝 포커 카드" src="{{ site.baseurl }}/assets/images/goods/planning-poker/planning-poker.png">
<figcaption>플래닝 포커의 전체 카드 구성</figcaption>
</figure>

### 핸드 카드 
참여자는 다음과 같은 13장의 개인 카드를 손에 듭니다.<br/>
참여자마다 카드 색이 달라 최대 4명까지 쓸 수 있습니다.

<img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-0.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-0.5.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-1.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-2.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-3.png" width="100"><br/>
<img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-5.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-8.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-13.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-20.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-40.png" width="100"><br/>
<img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-100.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-infinity.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-question.png" width="100">
<figcaption>핸드 카드 구성</figcaption>

### 핸드 카드의 기능

#### 작업량을 추정

작업량은 피보나치수열을 응용한 숫자로 표현합니다. 뒤로 갈수록 숫자 간격이 크게 벌어지는 게 특징입니다.<br/>
기본적인 작업량 단위는 '포인트'입니다.

| 카드 | 의미 | 
| - | - |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-0.png" width="50"> | 작업할 필요가 없어 추정이 무의미할 때<br/>(예: 이미 끝난 작업, 하지 않기로 한 작업) |
| ... | ... |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-3.png" width="50"> | 3 포인트<br/>(기준 작업량) |
| ... | ... |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-100.png" width="50"> | 100 포인트 |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-infinity.png" width="50"> | 작업량이 너무 커서 추정이 불가능할 때<br/>(예: 더 작게 분해해야 하는 작업) |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-question.png" width="50"> | 작업 내용이 불명확해서 추정이 불가능할 때<br/>(예: 추가 설명이 필요한 작업) |

### 엑스트라 카드
별도로 구매하거나 한 사람이 20장을 쓰는 제품에 포함되는 카드입니다.
다음과 같은 카드를 추가로 손에 쥡니다. (<a href="https://www.flaticon.com/free-icons/tea" title="tea icons">커피잔 아이콘 출처: Flaticon</a>)

<img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-xs.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-s.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-m.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-l.png" width="100">
<img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-xl.png" width="100">
<br/>
<img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-break.png" width="100">
<figcaption>엑스트라 카드 구성</figcaption>



### 엑스트라 카드의 기능

#### 개략적인 크기로 분류

작업량을 포인트로 추정하기 전에 크기별로 분류할 때 사용합니다.

| 카드 | 의미 | 
| - | - |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-xs.png" width="50"> | 많이 작은 일감 |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-s.png" width="50"> |  조금 작은 일감 |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-m.png" width="50"> |  보통 일감 |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-l.png" width="50"> |  조금 큰 일감 |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-xl.png" width="50"> | 많이 큰 일감 |

#### 추정을 멈춤

작업량 추정을 멈춰야 할 때 사용합니다.

| 카드 | 의미 | 
| - | - |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-break.png" width="50"> | 추정을 멈추고 휴식이 필요할 때<br/>(예: 커피, 간식, 사다리) |

<br/>

# 사용 방법 이해하기

## 참여자

추정에 참여하는 사람은 다음과 같습니다.

| 역할 | 설명 | 
| - | - |
| 프로덕트 오너 | 프로덕트 백로그 항목을 설명 |
| 스크럼 마스터 | 추정 절차나 방법을 안내 |
| 개발자 | 작업자 관점에서 작업량을 예측 |

## 기준 작업(기준 포인트) 고르기

작업량 추정 전에 기준 작업을 고릅니다. 기준 작업은 작업량이 크지도, 작지도 않은, 참여자 전원이 비슷하게 작업량을 짐작하는 작업입니다.

### 포스트잇을 사용하는 경우

1 프로덕트 백로그 항목의 내용을 프로덕트 오너가 설명합니다.

<figure>
<img alt="설명하기" src="{{ site.baseurl }}/assets/images/user-guide/프로덕트_백로그_항목_설명하기.png">
<figcaption>백로그 항목을 설명하는 프로덕트 오너</figcaption>
</figure>

2 개발자가 백로그 항목을 작업량 크기로 분류합니다.

<figure>
<img alt="분류하기" src="{{ site.baseurl }}/assets/images/user-guide/카드_쓰지_않고_기준_작업_정하기_1.png">
<figcaption>프로덕트 백로그 항목을 크기별로 분류하기</figcaption>
</figure>

3 스크럼 마스터는 중간 크기의 그룹에서 모두가 작업량에 공감하는 항목을 고릅니다.

<figure>
<img alt="기준잡기" src="{{ site.baseurl }}/assets/images/user-guide/카드_쓰지_않고_기준_작업_정하기_2.png">
<figcaption>중간 크기에서 기준 작업 고르기</figcaption>
</figure>

4 고른 항목의 작업량을 기준 작업량으로 삼습니다. 

일반적으로 기준 작업량은 3 정도로 잡고 단위는 '소요일'이나 '소요시간'과 같은 구체적인 단위가 아닌 '포인트'라는 상대적인 크기를 표현하는 단위를 씁니다. (예: 기준 작업량은 3 포인트)

### 플래닝 포커를 사용하는 경우

플래닝 포커 제품 중에는 XS, S, M, L, XL 카드를 포함한 확장판이 있습니다. (한 사람이 20장을 사용)<br/>
개인이 쓸 수 있게 핸드 카드로 손에 쥡니다.<br/>
작업량을 분류할 때는 포스트잇이 아닌 핸드카드로 크기를 표현합니다.

1 프로덕트 백로그 항목의 내용을 프로덕트 오너가 설명합니다.

<figure>
<img alt="설명하기" src="{{ site.baseurl }}/assets/images/user-guide/플래닝_포커로_기준_작업_정하기_1.png">
<figcaption>백로그 항목을 설명하는 프로덕트 오너</figcaption>
</figure>

2 개발자는 자신이 생각한 작업량을 카드로 표현합니다.

<figure>
<img alt="분류하기" src="{{ site.baseurl }}/assets/images/user-guide/플래닝_포커로_기준_작업_정하기_2.png">
<figcaption>프로덕트 백로그 항목을 크기별로 분류하기</figcaption>
</figure>

3 스크럼 마스터는 개발자 간의 인식 차이를 좁혀주면서 합의를 이끕니다.

4 작업이 크기별로 분류되면 중간 크기의 그룹에서 모두가 작업량에 공감하는 항목을 고릅니다.

5 고른 항목의 작업량을 기준 작업량으로 삼습니다. (예: 기준 작업 3 포인트)

<br/>

## 작업량 추정하기

프로덕트 백로그의 작업량을 포인트로 추정합니다.

### 플래닝 포커를 사용하는 경우

플래닝 포커는 합의를 보기 쉽도록 작업량이 커질 수록 추정값의 간격이 벌어집니다.

1 각자 생각한 작업량의 크기를 카드로 표현합니다. 이때 모든 참여자가 동시에 제시합니다.
<figure>
<img alt="산정하기" src="{{ site.baseurl }}/assets/images/user-guide/플래닝_포커로_작업량(포인트)_산정하기_1.png">
<figcaption>작업량이 커질수록 넓은 간격으로 추정</figcaption>
</figure>

2 추정한 작업량의 차이가 크면 서로의 생각을 공유합니다.

3 참여자의 생각 차이가 줄어들 때까지 반복합니다.

4 추정을 멈춰야 할 때는 그에 맞는 핸드 카드를 제시합니다.<br/>

<figure>
<img alt="추정멈추기" src="{{ site.baseurl }}/assets/images/user-guide/플래닝_포커로_작업량(포인트)_산정하기_2.png">
<figcaption>작업을 할 필요 없다고 생각하는 경우</figcaption>
</figure>

<figure>
<img alt="추정멈추기" src="{{ site.baseurl }}/assets/images/user-guide/플래닝_포커로_작업량(포인트)_산정하기_3.png">
<figcaption>설명이 필요하다고 생각하는 경우</figcaption>
</figure>

<figure>
<img alt="추정멈추기" src="{{ site.baseurl }}/assets/images/user-guide/플래닝_포커로_작업량(포인트)_산정하기_4.png">
<figcaption>분할이 필요하다고 생각하는 경우</figcaption>
</figure>

5 여러 사람이 같은 카드를 제시하면 가중치가 생깁니다.<br/>

<figure>
<img alt="가중치주기" src="{{ site.baseurl }}/assets/images/user-guide/플래닝_포커로_작업량(포인트)_산정하기_5.png">
<figcaption>휴식이 필요하다고 생각하는 경우</figcaption>
</figure>

<br/>

### 카드 제시하는 방법

작업량 추정 시 카드를 제시하는 방법에는 나름의 노림수가 있습니다.

#### 동시에 카드를 제시하는 방법
참여하는 사람은를 배제한 방법입니다.<br/>
앵커링 효과는 앞사람의 행동이 뒷사람에게 영향을 주는 걸 말합니다. 
플래닝 포커를 할 때는 앵커링 효과를 배제하기 위해 모든 참여자가 동시에 카드를 제시합니다.

<figure>
<img alt="카드 제시하기" src="{{ site.baseurl }}/assets/images/user-guide/플래닝_포커로_작업량(포인트)_산정하기_1.png">
<figcaption>앵커링 효과를 배제하기 위해 동시에 카드를 제시하기</figcaption>
</figure>

플래닝 포커는 동시에 카드를 제출한 후 생각의 차이를 서로 확인하는 걸 중요시 합니다.
각자의 생각을 공유하고 합의를 유도하는 과정을 반복합니다.

# 분산 환경에서 온라인으로 추정하기

플래닝 포커는 팀원 간의 원활한 커뮤니케이션에 도움이 되지만 분산된 환경에선 함께하기 어려울 수 있습니다.
참여자가 분산된 공간에 흩어져 있다면 효율적인 사용을 위해 온라인용 플래닝 포커를 추천합니다. 

<figure>
<img alt="원격으로 추정하기" src="{{ site.baseurl }}/assets/images/user-guide/플래닝_포커로_원격_추정하기.png">
<figcaption>재택근무 중에 원격으로 추정하기</figcaption>
</figure>