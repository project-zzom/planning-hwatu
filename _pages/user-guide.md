---
permalink: /user-guide/
title: "사용자 가이드"
excerpt: "Estimate workload with team members"
header:
  overlay_image: /assets/images/banner 1280 x 500.png
  overlay_filter: 0.5
---

# 카드 구성 이해하기
플래닝 화투는 다음과 같은 54장의 카드로 구성되어 있습니다.
최대 9명의 플레이어가 사용할 수 있습니다.

* 그라운드 카드: 9장 (검정색 9장)
* 핸드 카드: 45장 (9가지색 x 5장)

![전체 카드 이미지](/assets/images/goods/planning-hwatu-front.png)

## 핸드 카드 
플레이어 모두가 각자 쓰는 개인 카드입니다.
다음과 같은 5장의 카드를 손에 듭니다.
최대 9명의 플레이어가 서로 다른 색의 카드를 사용합니다.

<img src="/assets/images/goods/orange-0.5.png" width="100">
<img src="/assets/images/goods/orange-1.png" width="100">
<img src="/assets/images/goods/orange-2.png" width="100">
<img src="/assets/images/goods/orange-4.png" width="100">
<img src="/assets/images/goods/orange-8.png" width="100">

## 그라운드 카드
플레이어 모두가 함께 쓰는 공용 카드입니다.
다음과 같은 9장의 카드를 바닥에 둡니다.

<img src="/assets/images/goods/black-0.png" width="100">
<img src="/assets/images/goods/black-infinity.png" width="100">
<img src="/assets/images/goods/black-question.png" width="100">
<img src="/assets/images/goods/black-asterisk.png" width="100">
<br/>
<img src="/assets/images/goods/black-xs.png" width="100">
<img src="/assets/images/goods/black-s.png" width="100">
<img src="/assets/images/goods/black-m.png" width="100">
<img src="/assets/images/goods/black-l.png" width="100">
<img src="/assets/images/goods/black-xl.png" width="100">
## 플래닝 포커와의 차이점

플래닝 포커는 피보나치수열을 사용하고, 플래닝 화투는 2의 거듭제곱을 수열로 사용합니다.
플래닝 포커는 모든 카드를 손에 쥐고, 플래닝 화투는 최소한의 카드만 손에 쥐고 나머지는 바닥에 둡니다.

| 관점 | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 수열 | 피보나치수열 | 2의 거듭제곱 |
| 사용자 | 최대 4명 | 최대 9명 |
| 핸드 카드 | 12장 (0, 2, 3, 5, 8, 13, 20, 40, 100, ∞, ?, ☕) | 5장 (1/2, 1, 2, 4, 8)<br/><img src="/assets/images/goods/orange-0.5.png" width="50"><img src="/assets/images/goods/orange-1.png" width="50"><img src="/assets/images/goods/orange-2.png" width="50"><img src="/assets/images/goods/orange-4.png" width="50"><img src="/assets/images/goods/orange-8.png" width="50">|
| 핸드 카드 (옵션) | 5장 (XS, S, M, L, XL) | 없음 |
| 그라운드 카드 | 없음 | 9장 (0, ?, ∞, *, XS, S, M, L, XL)<br/><img src="/assets/images/goods/black-0.png" width="50"><img src="/assets/images/goods/black-infinity.png" width="50"><img src="/assets/images/goods/black-question.png" width="50"><img src="/assets/images/goods/black-asterisk.png" width="50"><img src="/assets/images/goods/black-xs.png" width="50"><img src="/assets/images/goods/black-s.png" width="50"><img src="/assets/images/goods/black-m.png" width="50"><img src="/assets/images/goods/black-l.png" width="50"><img src="/assets/images/goods/black-xl.png" width="50"> |
| 핸드 카드 사용법 | 손에 쥔 카드를 제시 | 손에 쥔 카드를 제시 |
| 그라운드 사용법 | 없음 | 바닥의 카드를 타격 |

그라운드 카드를 타격할 때 손에 쥔 카드의 숫자 크기만큼 강약을 표현할 수 있습니다.
강약 표현 방법은 뒤에서 다룹니다.

---

# 사용 방법 이해하기

추정에 참여하는 플레이어는 다음과 같습니다.

| 역할 | 설명 | 
| - | - |
| 프로덕트 오너 | 프로덕트 백로그 항목을 설명 |
| 스크럼 마스터 | 추정 절차나 방법을 안내 |
| 개발자 | 작업자 관점에서 작업량을 예측 |

추정 순서는 다음과 같습니다.

## 기준 작업 고르기

* 프로덕트 백로그 항목의 내용을 프로덕트 오너가 설명합니다.
* 개발자가 백로그 항목을 작업량 크기로 분류합니다.
* 스크럼 마스터는 중간 크기의 그룹에서 누구나 공감하는 항목을 고릅니다.
* 고른 항목의 작업량을 기준 작업량으로 삼습니다.

![기준 찾기]()


## 작업량 추정하기

* 프로덕트 백로그 항목의 내용을 프로덕트 오너가 상기 시킵니다.
* 개발자는 자신이 생각한 작업량을 카드로 표현합니다.
* 스크럼 마스터는 개발자 간의 인식 차이를 좁혀주면서 합의를 이끕니다.
* 다음 스프린트에서 작업할 만큼만 반복합니다.

![추정 하기]()

---

# 기준 작업 고르기

작업량의 크기를 5단계로 표현할 수 있습니다.
프로덕트 백로그 항목의 작업량 크기를 의류 사이즈로 표현할 수 있습니다.

| 카드 | 의미 | 
| - | - |
| <img src="/assets/images/goods/black-xs.png" width="50"> | 많이 작은 일감 |
| <img src="/assets/images/goods/black-s.png" width="50"> |  조금 작은 일감 |
| <img src="/assets/images/goods/black-m.png" width="50"> |  보통 일감 |
| <img src="/assets/images/goods/black-l.png" width="50"> |  조금 큰 일감 |
| <img src="/assets/images/goods/black-xl.png" width="50"> | 많이 큰 일감 |

M 크기로 분류된 프로덕트 백로그 항목을 살펴봅니다.
그 중에서 팀원 모두가 작업량에 대해 공감하는 걸 고릅니다.
골라낸 작업량을 기준 작업량으로 정합니다.

## 플래닝 포커와의 차이점

플래닝 포커에선 XS, S, M, L, XL 카드가 핸드 카드입니다.
플래닝 화투에선 XS, S, M, L, XL 카드가 그라운드 카드입니다.

|  | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| XS, S, M, L, XL 표현법 | 손에 쥔 카드를 제시 | 바닥에 놓인 카드를 타격 |

플래닝 화투는 핸드 카드 수를 줄여 더 많은 플레이어가 참여할 수 있게 설계되었습니다.

![그라운드 카드]()

---

# 작업량 추정하기 (기본)

## 프로덕트 백로그의 작업량을 포인트로 추정할 때

상대적인 크기를 5단계로 표현할 수 있습니다.
프로덕트 백로그 항목의 작업량 크기를 스토리 포인트로 표현할 수 있습니다.
각 단계는 앞 단계의 2배, 다음 단계의 1/2배 크기입니다.

### 추정할 때 쓰는 카드

플래닝 화투에선 추정에 쓸 카드를 손에 쥡니다.

| 카드 | 의미 | 
| - | - |
| <img src="/assets/images/goods/orange-0.5.png" width="50"> | 다음 단계 작업량의 반 |
| <img src="/assets/images/goods/orange-1.png" width="50"> |  기준 작업량의 반 |
| <img src="/assets/images/goods/orange-2.png" width="50"> |  작업량 기준 |
| <img src="/assets/images/goods/orange-4.png" width="50"> |  기준 작업량의 배 |
| <img src="/assets/images/goods/orange-8.png" width="50"> | 이전 단계 작업량의 배 |

### 추정을 끊을 때 쓰는 카드

플래닝 화투에선 추정을 끊는 카드를 바닥에 놓습니다.

| 카드 | 의미 | 
| - | - |
| <img src="/assets/images/goods/black-0.png" width="50"> | 작업할 필요가 없어 추정이 무의미할 때 |
| <img src="/assets/images/goods/black-question.png" width="50"> | 작업 내용이 불명확해서 추정이 불가능할 때 |
| <img src="/assets/images/goods/black-infinity.png" width="50"> | 작업량이 너무 커서 추정이 불가능할 때 |
| <img src="/assets/images/goods/black-asterisk.png" width="50"> | 추정을 멈추고 휴식이 필요할 때 |

핸드 카드를 바닥에 타격하거나 그라운드 카드를 핸드 카드로 타격하면서 작업량을 표현하세요.
프로덕트 백로그 항목의 작업량 크기를 포인트로 표현할 수 있습니다. 

## 플래닝 포커와의 차이점

플래닝 포커는 가장 작은 수가 0, 가장 큰 수가 100입니다.
플래닝 화투는 가장 작은 수가 0, 가장 큰 수가 8입니다.
와일드 카드(*)의 의미는 팀에서 재정의 가능합니다. (예: 커피, 피자, 사다리, 탁구 등)

|  | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 0 표현법 | 손에 쥔 0 카드를 제시 | 바닥에 놓인 0 카드를 타격 |
| ? 표현법 | 손에 쥔 ? 카드를 제시 | 바닥에 놓인 ? 카드를 타격 |
| ∞ 표현법 | 손에 쥔 ∞ 카드를 제시 | 바닥에 놓인 ∞ 카드를 타격 |
| * 표현법 | 손에 쥔 ☕ 카드를 제시 | 바닥에 놓인 * 카드를 타격 |

그라운드 카드를 타격할 때는 손에 쥔 핸드 카드의 숫자로 강약을 표현할 수 있습니다.

| 그라운드 카드 | 핸드 카드 | 의미 |
| - | - | - |
| <img src="/assets/images/goods/black-asterisk.png" width="50"> | <img src="/assets/images/goods/orange-0.5.png" width="50"> | 좀 쉬었다가 하면 안될까요? |
| <img src="/assets/images/goods/black-asterisk.png" width="50"> | <img src="/assets/images/goods/orange-1.png" width="50"> | 쉬었다가 하시죠. |
| <img src="/assets/images/goods/black-asterisk.png" width="50"> | ... | ... |
| <img src="/assets/images/goods/black-asterisk.png" width="50"> | <img src="/assets/images/goods/orange-0.5.png" width="50"><img src="/assets/images/goods/orange-1.png" width="50"><img src="/assets/images/goods/orange-2.png" width="50"><img src="/assets/images/goods/orange-4.png" width="50"><img src="/assets/images/goods/orange-8.png" width="50"> | 커피는 내가 쏠테니까 제발 쉬자고!  |

크기가 작은 카드로 타격하면서 조심스럽게 의견을 물어볼 수 있습니다.
한번에 여러 장의 카드를 투척하면서 강한 의지를 표현할 수 있습니다.

![폭탄 동영상]()

다른 플레이어도 동의한다면 연타로 타격해도 됩니다.

![연타 동영상]()

---

# 작업량 추정하기 (응용)

## 프로덕트 백로그의 작업량을 포인트로 추정할 때

플래닝 화투에선 1/2에서 8까지 2배 단위로 포인트를 표현할 수 있습니다.
상황에 따라 포인트를 더 정밀하고 더 폭 넓게 표현하고 싶을 수 있습니다.
그럴 때는 여러 장의 카드를 합산해서 써보세요.

| 카드 | 포인트 |
| - | - |
| <img src="/assets/images/goods/orange-0.5.png" width="50"> | 0.5 포인트  |
| <img src="/assets/images/goods/orange-1.png" width="50"> | 1포인트 |
| <img src="/assets/images/goods/orange-0.5.png" width="50"><img src="/assets/images/goods/orange-1.png" width="50"> | 1.5 포인트 |
| <img src="/assets/images/goods/orange-2.png" width="50"> | 2 포인트 |
| ... | ... |
| <img src="/assets/images/goods/orange-1.png" width="50"><img src="/assets/images/goods/orange-2.png" width="50"><img src="/assets/images/goods/orange-4.png" width="50"><img src="/assets/images/goods/orange-8.png" width="50"> | 15 포인트 |
| <img src="/assets/images/goods/orange-0.5.png" width="50"><img src="/assets/images/goods/orange-1.png" width="50"><img src="/assets/images/goods/orange-2.png" width="50"><img src="/assets/images/goods/orange-4.png" width="50"><img src="/assets/images/goods/orange-8.png" width="50"> | 15.5 포인트 |

0.5 단위로 정교하게 포인트를 표현할 수 있습니다.
0.5에서 15.5까지 폭 넓게 포인트를 표현할 수 있습니다.

## 플래닝 포커와의 차이점

플래닝 포커는 한 장의 카드만 쓸 수 있습니다. 
플래닝 화투는 여러 장의 카드를 합산해서 쓸 수 있습니다.

|  | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 카드 사용 | 한 장의 카드만 사용  | 여러 장의 카드를 사용 |

![합산]()

---

# 카드 제시하기 (확장)

작업량 추정 시 카드를 제시하는 방법을 다양하게 확장할 수 있습니다.

## 앵커 효과를 배제한 방법

앵커 효과는 앞 사람의 행동이 뒷 사람에게 영향을 주는 걸 말합니다.
플래닝 포커를 할 때는 앵커 효과를 배제하기 위해 모든 플레이어가 동시에 카드를 제시합니다.

![동시에 카드 제시하기]()

플래닝 포커는 동시에 카드를 제출한 후 생각의 차이를 서로 확인하는 걸 중요시 합니다.
각자의 생각을 공유하고 합의를 유도하는 과정을 반복합니다.

## 앵커 효과를 응용한 방법

플래닝 화투도 앵커 효과를 배제하기 위해 코든 플레이어가 동시에 카드를 제시해도 됩니다.
반대로 앵커 효과를 활용해하는 방법도 있습니다.

![차례대로 카드 제시하기]()

차례대로 카드를 제시하며 각자의 생각을 공유합니다.
다음 사람은 앞 사람의 추정에 의견을 더하거나 빼면서 구체화합니다.
추상적인 작업 내용을 구체화하는 과정을 반복합니다.

## 플래닝 포커와의 차이점

플래닝 포커는 앵커 효과를 배제합니다.
플래닝 화투는 앵커 효과를 배제할 수도, 응용할 수도 있습니다.

|  | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 앵커 효과 | 배제  | 배제 / 응용 |
| 착안점 | 생각의 차이를 확인하고 합의 유도 | 생각을 보완하며 구체화 유도 |

추정하는 순서는 개발팀 문화에 맞게 자율적으로 정합니다.
예를 들면 다음과 같은 방식으로 진행할 수 있습니다.

* 시계 반대 방향으로 추정
* 경험자 순서로 추정
* 미경험자 순서로 추정

![추정 순서]()

---

# 작업량 추정하기 (확장)

## 스프린크 백로그의 작업량을 날짜나 시간으로 추정할 때

추상적인 스토리 포인트보다 구체적인 시간으로 작업량을 표현하고 싶을 수 있습니다.
그럴 때는 팀원과 상의하여 작업 소요일이나 소요 시간으로 단위를 바꿔보세요.
이때도 역시 여러 장의 카드를 합산해서 쓰면 됩니다.


| 카드 | 의미 (소요일) | 의미 (소요 시간) |
| - | - | - |
| <img src="/assets/images/goods/orange-0.5.png" width="50"> | 0.5 일  | 0.5 시간 | 
| <img src="/assets/images/goods/orange-1.png" width="50"> | 1 일 | 1 시간 |
| <img src="/assets/images/goods/orange-0.5.png" width="50"><img src="/assets/images/goods/orange-1.png" width="50"> | 1.5 일 | 1.5 시간 |
| <img src="/assets/images/goods/orange-2.png" width="50"> | 2 일 | 2 시간 |
| ... | ... | ... |
| <img src="/assets/images/goods/orange-1.png" width="50"><img src="/assets/images/goods/orange-2.png" width="50"><img src="/assets/images/goods/orange-4.png" width="50"><img src="/assets/images/goods/orange-8.png" width="50"> | 15 일 | 15 시간 |
| <img src="/assets/images/goods/orange-0.5.png" width="50"><img src="/assets/images/goods/orange-1.png" width="50"><img src="/assets/images/goods/orange-2.png" width="50"><img src="/assets/images/goods/orange-4.png" width="50"><img src="/assets/images/goods/orange-8.png" width="50"> | 15.5 일 | 15.5 시간 |

날짜로 사용 시 반일에서 3주 반일까지 표현할 수 있습니다.
시간으로 사용 시 30분에서 15시간 30분까지 표현할 수 있습니다.

## 플래닝 포커와의 차이점

플래닝 포커는 프로덕트 백로그 항목의 작업량 추정까지만 사용합니다.
플래닝 화투는 스프린트 백로그 항목의 작업량 추정에도 쓸 수 있습니다.

|  | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 작업량 표현 | 스토리 포인트  | 스토리 포인트, 소요일, 소요 시간 |
| 활용 범위 | 프로덕트 백로그 작업량 추정  | 프로덕트 백로그, 스프린트 백로그 작업량 추정 |

스프린트 백로그 항목은 작업을 할당 받은 개발자가 소요 시간을 추정하는 게 보통입니다.
페어 프로그래밍을 하거나 몹 프로그래밍을 할 때 서로가 생각하는 소요 시간을 제시하며 추정해보세요.

![페어 프로그래밍]()