---
description: 관리도구에서 학습을 설정하는 방법에 대해 알아봅니다.
---

# 학습설정

## 1. 학습설정 개념

학습설정에서는 챗봇의 인텐트 학습과 제안센텐스에 대한 상세 설정이 가능합니다. 학습 모델 변경과 그에 따른 정확도 및 신뢰도를 관리할 수 있으며, 제안센텐스에 대한 세부 설정도 변경할 수 있습니다.&#x20;

{% hint style="danger" %}
**기존의 정해져 있는 학습 설정 값을 변경하지 않도록 주의해주시기 바랍니다.**

학습 설정에 대한 값을 변경하는 경우, 챗봇이 정상적으로 동작하지 않을 수 있습니다. 아래 매뉴얼의 내용은 참고용으로 숙지해주시고, 임의로 값을 변경하는 등의 작업은 하지 않도록 유의해주세요.
{% endhint %}

## 2. 학습설정 방법

관리도구 좌측의 **\[설정 > 학습설정] 메뉴**를 통해 챗봇의 학습 설정 및 관리가 가능합니다. 학습설정 화면은 '인텐트 학습설정'과 '제안센텐스 설정'으로 구성되어 있습니다.

![학습설정 경로](<../.gitbook/assets/1.학습설정 경로.png>)



### 2-1. 인텐트 학습설정

인텐트 학습 설정에서는 센텐스학습 모델과 인텐트추론 모델의 사용여부 및 정확도, 신뢰도 등을 설정합니다. '전체'로 설정할 경우에는 두 가지 학습 모델을 이용하여 사용자 발화에 대한 의도를 분석합니다.

![인텐트 학습설정 화면](<../.gitbook/assets/2.인텐트 학습설정.png>)

➊ **학습모델 설정**&#x20;

사용자 발화에 대한 분석모델을 설정합니다.

* **전체 :** 센텐스학습과 인텐트추론 모델을 이용하여 사용자 발화를 이해합니다.
* **센텐스학습 :** 구문학습 기반인 센텐스학습 모델만 이용하여 사용자 발화를 이해합니다.    &#x20;
* **인텐트추론 :** 기계학습 기반인 인텐트추론 모델만 이용하여 사용자 발화를 이해합니다.&#x20;

&#x20;      &#x20;

➋ **센텐스학습**

센텐스 학습 버튼을 누르면 센텐스학습 모델을 이용하여 사용자 발화를 분석합니다. 센텐스 학습 화면에서는 등록 현황과 정확도를 설정합니다.       &#x20;

* **등록현황 :** 등록된 인텐트, 센텐스, 엔티티의 총 개수를 나타냅니다.&#x20;
* **정확도 :** 센텐스 매칭 정확도를 설정합니다. (권장값 : '80')
* **시작 버튼 :** 센텐스 학습 시작 버튼입니다. **** &#x20;

정확도가 높을수록 사용자 발화와 등록된 센텐스의 매칭 규칙이 엄격해지기 때문에 의도 이해 범위가 줄어들어 응답률은 감소합니다.

&#x20;

➌ **인텐트추론**

인텐트추론은 기계학습 기반의 학습과 추론 모델을 의미하며, 학습된 모델을 이용하여 사용자 발화를 분석합니다.

* **학습현황** **:** 추론 학습 시작 전후의 센텐스 개수를 나타냅니다. (신규는 추론 학습 전 센텐스 수를, 완료는 추론 학습 후 센텐스 수를 의미합니다.)
* **신뢰도 :** 인텐트추론 모델의 신뢰도를 설정합니다. (권장값 : '70')

신뢰도가 낮을수록 의도 이해 범위가 넓어지지만, 부정확한 의도로 이해될 수 있습니다.&#x20;

&#x20;          &#x20;

### 2-2. 제안센텐스 설정

제안센텐스 설정에서는 사용자 발화에 대한 대표센텐스 제안 시 센텐스 개수 및 민감도를 설정합니다.

![제안 센텐스 설정 화면   ](<../.gitbook/assets/3.제안센텐스 설정.png>)

➊ **추천수**&#x20;

제안할 센텐스의 개수를 설정합니다. (2\~10개까지 선택 가능)



➋ **민감도**&#x20;

제안할 센텐스의 탐색 범위를 설정합니다. (권장값 : '40'\~'50')

민감도는 사용자 발화와 제안 센텐스 간의 유사도 판단 기준을 의미합니다. 민감도를 높게 설정하는 경우, 사용자 발화와 가장 유사한 제안 센텐스를 탐색하게 됩니다. 그러나 상대적으로 유사도가 낮은 관련 센텐스에 대해서는 제안이 이루어지지 않을 수 있습니다. 따라서 적절한 민감도 설정을 통해 관련성이 있는 발화를 다양하게 제안해주는 것이 좋습니다.
