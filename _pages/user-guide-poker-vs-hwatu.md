---
permalink: /user-guide-poker-vs-hwatu/
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

# 플래닝 포커와 플래닝 화투의 특징과 차이점

## 카드 구성

### 수열

플래닝 포커는 피보나치수열을 응용한 숫자를 사용하고, 플래닝 화투는 2의 거듭제곱을 수열로 사용합니다.

| 항목 | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 수열 | 피보나치수열을 응용한 숫자 | 2의 거듭제곱 |
| 간격 | 뒤로 갈수록 크게 벌어짐 | 뒤의 숫자가 앞 숫자의 2배 |

![비교]()

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

![비교]()

<br/>

## 사용 방법

플래닝 포커는 가장 작은 수가 0, 가장 큰 수가 100입니다.
플래닝 화투는 가장 작은 수가 0, 가장 큰 수가 8입니다.
와일드 카드(*)의 의미는 팀에서 재정의 가능합니다. (예: 커피, 피자, 사다리, 탁구 등)

| 항목 | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 0 표현법 | 손에 쥔 0 카드를 제시 | 바닥에 놓인 0 카드를 타격 |
| ? 표현법 | 손에 쥔 ? 카드를 제시 | 바닥에 놓인 ? 카드를 타격 |
| ∞ 표현법 | 손에 쥔 ∞ 카드를 제시 | 바닥에 놓인 ∞ 카드를 타격 |
| * 표현법 | 손에 쥔 ☕ 카드를 제시 | 바닥에 놓인 * 카드를 타격 |

![비교]()

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
![연타 동영상]()

## 작업량 추정 (응용)

플래닝 포커는 한 장의 카드만 쓸 수 있습니다. 
플래닝 화투는 여러 장의 카드를 합산해서 쓸 수 있습니다.

| 항목 | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 카드 사용 | 한 장의 카드만 사용  | 여러 장의 카드를 사용 |

![비교]()

## 카드 제시 방법

플래닝 포커는 앵커 효과를 배제합니다.
플래닝 화투는 앵커 효과를 배제할 수도, 응용할 수도 있습니다.

| 항목 | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 앵커 효과 | 배제  | 배제 / 응용 |
| 착안점 | 생각의 차이를 확인하고 합의 유도 | 생각을 보완하며 구체화 유도 |

추정하는 순서는 개발팀 문화에 맞게 자율적으로 정합니다.
예를 들면 다음과 같은 방식으로 진행할 수 있습니다.

* 시계 반대 방향으로 추정
* 경험자 순서로 추정
* 미경험자 순서로 추정

![순서]()

## 작업량 추정 (응용)

플래닝 포커는 프로덕트 백로그 항목의 작업량 추정까지만 사용합니다.
플래닝 화투는 스프린트 백로그 항목의 작업량 추정에도 쓸 수 있습니다.

| 항목 | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 작업량 표현 | 스토리 포인트  | 스토리 포인트, 소요일, 소요시간 |
| 활용 범위 | 프로덕트 백로그 작업량 추정  | 프로덕트 백로그, 스프린트 백로그 작업량 추정 |

![비교]()

## 온라인에서 사용하기

플래닝 포커는 프로덕트 백로그를 관리하는 온라인 서비스나 협업 툴과 연동할 수 있습니다.<br/>
플래닝 화투는 웹캡으로 각자가 제시하는 카드를 보여줄 수 있습니다.

| 항목 | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 사용 방법 | 협업 툴 연동 | 화면만 공유 |

![비교]()