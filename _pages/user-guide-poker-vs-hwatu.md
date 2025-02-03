---
permalink: /user-guide-poker-vs-hwatu/
title: "사용자 가이드"
excerpt: "Estimate workload with team members"
header:
  og_image: /assets/images/crowdfunding/crowdfunding-closed-3.png
  overlay_image: /assets/images/header/header-github-pages.png
  overlay_filter: 0.5
author_profile: false
sidebar:
    nav: "user-guide-menu"
---

## 플래닝 포커 vs. 플래닝 화투

플래닝 포커와 플래닝 화투의 차이점은 다음과 같습니다.

### 카드 구성의 차이

카드 구성 상의 차이는 다음과 같습니다.

#### 사용하는 수열

플래닝 포커는 피보나치수열을 응용한 숫자를 사용하고, 플래닝 화투는 2의 거듭제곱을 수열로 사용합니다.

| 항목 | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 수열 | 피보나치수열을 응용한 숫자 | 2의 거듭제곱 |
| 간격 | 뒤로 갈수록 크게 벌어짐 | 뒤의 숫자가 앞 숫자의 2배 |
| 예시 | <img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-0.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-0.5.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-1.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-2.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-3.png" width="45"><br/><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-5.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-8.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-13.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-20.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-40.png" width="45"><br/><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-100.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-infinity.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-question.png" width="45"> | <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-0.5.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-1.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-2.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-4.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-8.png" width="45">|

#### 카드 1개당 사용자 수
스크럼에서 적정 개발자 수는 3명에서 9명입니다. 
플래닝 화투는 개인용 핸드 카드와 공용 그라운드 카드를 분리하여 최대 9명까지 쓸 수 있습니다. (<a href="https://www.flaticon.com/free-icons/tea" title="tea icons">커피잔 아이콘 출처: Flaticon</a>)

| 항목 | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 사용자 | 최대 4명 | 최대 9명 |
| 데크 수 | 최대 3개 필요 | 1개로 충분 |
| 카드<br/> 개수 | 54장<br/>(2장은 설명 카드) | 54장 |
| 예시 | <img alt="플래닝 포커 카드" src="{{ site.baseurl }}/assets/images/goods/planning-poker/planning-poker.png" width="300"> | <img alt="플래닝 화투 카드" src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/planning-hwatu.png" width="300"> |

#### 핸드 카드 / 그라운드 카드 / 엑스트라 카드

플래닝 포커는 모든 카드를 핸드 카드로 손에 쥐어야 합니다.
플래닝 화투는 추정하는 카드를 핸드 카드로, 추정을 멈추는 카드를 그라운드 카드로 분리합니다.

플래닝 포커는 특수 기능을 하는 카드를 별도 구매하거나 1데크에 20장 이상의 제품을 써야 합니다.
플래닝 화투는 1개 데크에 모든 특수 카드를 포함하고 있습니다.

| 항목 | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 핸드<br/> 카드 | 13장 <br/><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-0.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-0.5.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-1.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-2.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-3.png" width="45"><br/><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-5.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-8.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-13.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-20.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-40.png" width="45"><br/><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-100.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-infinity.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-question.png" width="45"> | 5장<br/><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-0.5.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-1.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-2.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-4.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-8.png" width="45">|
| 그라운드<br/> 카드 | 없음 | 9장<br/><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-xs.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-s.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-m.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-l.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-xl.png" width="45"><br/><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-0.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-question.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-infinity.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-asterisk.png" width="45"> |
| 엑스트라<br/> 카드 | 별도 카드 구매 필요<br/>1개 데크에 20장 제품에 포함<br/><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-xs.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-s.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-m.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-l.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-xl.png" width="45"><br/><img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-break.png" width="45"><br/><a href="https://www.flaticon.com/free-icons/tea" title="tea icons">Tea icons created by Freepik - Flaticon</a> | 모든 카드가 포함됨 |

#### 와일드카드

플래닝 포커는 추정 중에 휴식이 필요하면 '커피잔' 카드를 제시합니다. 팀원 중에는 커피를 마시지 않는 사람이 존재할 수 있습니다. 플래닝 화투에서는 명시적인 '커피잔' 카드 대신 의미를 팀에서 재정의할 수 있는 '와일드' 카드를 사용합니다.<br/>
(예: 커피, 피자, 컵라면, 사다리, 탁구 등)

| 항목 | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 휴식 카드 | <img src="{{ site.baseurl }}/assets/images/goods/planning-poker/violet-break.png" width="50"> | <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-asterisk.png" width="50"> |
| 표현 법법 | 손에 쥔 카드를 제시 | 바닥에 놓인 카드를 타격 |

### 카드 재질 / 내구성 / 가격

플래닝 포커는 트럼프 카드를 베이스로 씁니다.
플래닝 화투는 화투 패를 베이스로 씁니다.

| 항목 | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 재질 | 트럼프 카드 재질 | 화투 재질 |
| 내구성 | 보통 | 반영구적 |
| 가격 (데크 당) | 2.5 ~ 6달러 | 1.5만원 | 
| 가격 (9명 기준) | 2.5 ~ 6 달러 x 4 개 | 1.5만원 | 

구매처는 아래와 같습니다.

#### 플래닝 포커 계열

* <a href="https://store.mountaingoatsoftware.com" target="_blank">Planning Poker (Mountain Goat Software store)</a>
* <a href="https://s.click.aliexpress.com/e/_DBoKXyJ" target="_blank">Scrum Card (AliExpress)</a>

#### 플래닝 화투 계열

* <a href="" target="_blank">Planning Hwatu (Smartstore)</a> (준비 중)
* <a href="" target="_blank">Planning Hwatu (Amazon US)</a> (준비 중)
* <a href="" target="_blank">Planning Hwatu (Amazon JP)</a> (준비 중)

### 카드 사용법의 차이

카드 사용법 상의 차이는 다음과 같습니다.

#### 카드를 합산하여 정교하게 추정하기

플래닝 포커는 한 장의 카드만 쓸 수 있습니다. 
플래닝 화투는 여러 장의 카드를 합산해서 쓸 수 있습니다.

| 항목 | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 카드 사용 | 한 장의 카드만 사용  | 여러 장의 카드를 사용 |

#### 카드를 합산하여 강약을 표현하기

그라운드 카드를 타격할 때는 손에 쥔 핸드 카드의 숫자 크기로 강약을 표현할 수 있습니다.

| 그라운드 카드 | 핸드 카드 | 의미 |
| - | - | - |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-asterisk.png" width="45"> | <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-0.5.png" width="45"> | 문의<br/>(좀 쉬었다가 하면 안 될까요?) |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-asterisk.png" width="45"> | <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-1.png" width="45"> | 권유<br/>(쉬었다가 하시죠.) |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-asterisk.png" width="45"> | ... | ... |
| <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/black-asterisk.png" width="45"> | <img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-0.5.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-1.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-2.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-4.png" width="45"><img src="{{ site.baseurl }}/assets/images/goods/planning-hwatu/orange-8.png" width="45"> | 거부하기 힘든 제안<br/>(커피는 제가 쏠테니 제발 쉬어요!)  |

#### 역 앵커링 효과로 작업 방법 구체화하기

플래닝 포커는 앵커링 효과(anchoring effect)를 배제합니다.
플래닝 화투는 앵커링 효과를 배제할 수도, 응용할 수도 있습니다.

| 항목 | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 앵커링 효과 | 배제  | 배제 / 응용 |
| 착안점 | 서로의 생각 차이를 확인<br/> 합의 유도 | 서로의 생각을 보완<br/> 구체화 유도 |

역 앵커링은 다음과 같은 팀에 적용할 수 있습니다.

##### 오래 호흡을 맞추면서 맞추면서 비슷한 경험을 쌓은 팀
앞사람의 의견을 보완하면서 진행합니다.
호흡을 오래 맞춘 팀원끼리는 앵커 되는 정보가 서로 공감하는 내용일 확률이 높습니다. 이때는 뒷사람이 앞사람의 의견에 누락된 내용을 보충하거나 강화하는 등 정보를 구체화하고 보완하는데 더 집중할 수 있습니다. 

참여자가 비슷한 관점과 역량을 가지고 있어 추정 순서는 중요하지 않습니다. 

* 시계 반대 방향으로 추정
* 브레인스토밍 하며 무작위 추정 

특별한 조건이 없다면 시계 반대 방향으로 하고 언급된 의견을 보완할 수 있다면 순서와 상관없이 인터셉트할 수 있습니다.
절차나 형식보다는 작업의 구체화와 공감대 형성에 무게 중심을 둡니다.


##### 입문자를 멘토링 하면서 진행해야 하는 팀
숙련자가 입문자에게 브리핑하면서 진행합니다.
입문자를 멘토링해야 할 때는 숙련자의 의견이 경험으로 검증된 내용일 확률이 높습니다. 이때는 아직 배워야 할 것이 많은 입문자에게는 일종의 '목표치' 역할을 하여 조기 전력화를 위한 동기 부여에 도움이 될 수 있습니다.

추정하는 순서는 개발팀 문화에 맞게 자율적으로 정합니다.

* 숙련자 순서로 추정
* 입문자 순서로 추정

숙련자가 먼저 추정하는 방식에선 입문자는 그걸 목표치로 생각하되 실제로 자신이 맡을 때의 예상치를 말합니다.
입문자가 먼저 추정하는 방식에선 숙련자가 더 효율적이고 구체적인 방법을 제시하며 기술 이전을 합니다.

#### 체감되는 단위로 작업량 추정하기

플래닝 포커는 프로덕트 백로그 항목의 작업량 추정까지만 사용합니다.
플래닝 화투는 스프린트 백로그 항목의 작업량 추정에도 쓸 수 있습니다.

| 항목 | 플래닝 포커 | 플래닝 화투 |
| - | - | - |
| 작업량 | 스토리 포인트  | 스토리 포인트, 소요일, 소요시간 |
| 추정 대상 | 프로덕트 백로그 작업량 추정  | 프로덕트 백로그, 스프린트 백로그 작업량 추정 |

일반적인 플래닝 포커에선 프로덕트 백로그 항목의 스토리 포인트까지 추정합니다.
플래닝 화투는 소요일, 소요시간까지 최소 반일, 30분 단위의 정밀한 추정이 가능하여 스프린트 백로그의 작업 시간까지 확장해서 쓸 수 있습니다. 

플래닝 포커에서도 소요일, 소요시간을 추정하기도 하나 수열의 간격이 균일하지 않고 정밀하지 않으며 상대적인 크기를 직감하기 어려워 표현력이 떨어질 수 있습니다.
플래닝 화투는 균일한 간격, 0.5 단위의 정밀함, 1/2배(반반), 2배(따블)과 같은 직관적인 표현이 가능합니다.

### 정리하기

플래닝 화투는 플래닝 포커를 부정하거나 대적하는 안티테제(antithesis) 도구가 아닙니다. 기존의 플래닝 포커를 사용하면서 팀의 숙련도나 성향과 맞지 않아 적극적인 활용을 꺼리는 상황을 개선하기 위한 진테제(synthesis) 도구입니다.

우리 팀의 상황이나 나와 맞지 않다고 도구의 역할을 부정하기보다는 약간의 확장 포인트를 열어주면 현장에 맞게 응용할 수 있을 거라는 게 ‘플래닝 화투’의 설계 철학입니다.

여러분의 현장에서 ‘플래닝 화투’가 어떻게 활용되는지, 어떤 부분이 좋았고, 어떤 부분에서 아쉬웠는지 경험을 나눠주세요. 해시 태그를 달면 서로가 어떻게 쓰고 있는지 엿볼 수 있을 거예요.

* #PlanningHwatu #플래닝화투

플래닝 화투에 대한 문의나 의견이 있으시면 아래로 연락 주십시오. 여러분의 프로젝트를 응원합니다.

* <a href="mailto:project.zzom@gmail.com">project.zzom@gmail.com</a>

<img alt="Project ZZOM" src="{{ site.baseurl }}/assets/images/zzom-banner-light (1024 x 682).jpg">
