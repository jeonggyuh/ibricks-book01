---
description: 관리도구에서 응답 메시지를 설정하는 방법을 알아봅니다.
---

# 응답 메시지 설정하기

## 1. 응답 메시지 정의

응답 메시지란 챗봇이 사용자 발화에 답변할 때 출력되는 메시지를 뜻합니다.

![응답 메시지 출력 화면](<../../../.gitbook/assets/응답메시지 출력화면.png>)

## 2. 응답 메시지 관리

파라미터 관리 화면 하단에 위치한 **응답 메시지 설정** **화면**은 응답 메시지 생성을 위한 '응답 메시지 추가'와 생성된 응답 메시지의 세부 설정을 할 수 있는 '응답 메시지 설정 창'으로 구성됩니다.

아래는 해당 화면의 각 기능에 대한 상세 안내입니다. &#x20;

### 2-1. 응답 메시지 추가

응답 메시지 설정에서 원하는 메시지를 입력한 후 <img src="../../../.gitbook/assets/image (373).png" alt="" data-size="line">버튼을 누르면 응답 메시지가 생성됩니다. 응답 메시지 입력 시 텍스트 도구 모음을 사용하여 텍스트 꾸미기도 가능합니다.&#x20;

![응답 메시지 설정 화면    ](<../../../.gitbook/assets/image (424).png>)

메시지가 생성된 후에는 수정하거나 삭제할 수 있습니다. 응답 메시지 목록에서 커스텀, 템플릿 여부를 확인할 수 있습니다.&#x20;

![응답 메시지 생성 화면](<../../../.gitbook/assets/1.응답메시지 생성.png>)



### 2-2. 응답 메시지 설정

응답 메시지 설정 창에서는 메시지를 수정/추가 시에 템플릿, 커스텀 코드, 감정 표현 설정이 가능합니다. 응답 메시지 설정 창의 각 기능에 대한 상세 안내입니다.

![응답 메시지 설정 화면](<../../../.gitbook/assets/2.응답메시지 설정.png>)

➊ **사용여부**

응답 메시지의 사용여부 ON/OFF를 체크합니다.   ****  &#x20;

****

➋ **응답 메시지 생성**

메시지 내용 입력 후에 **+메시지 추가** 버튼을 클릭하면 응답 메시지가 생성됩니다. 텍스트 도구 모음을 통해 텍스트 굵기, 기울기, 취소선, 색 변경 등 세부사항을 설정할 수 있습니다. 텍스트뿐만 아니라 표, 이미지, 하이퍼링크 등 응답 메시지 안에 필요한 자료들을 삽입하는 기능도 탑재되어 있습니다.



➌ **랜덤 답변 설정**

생성된 응답 메시지가 여러 개인 경우, 랜덤 답변을 ON으로 설정하면 랜덤으로 답변이 출력됩니다. OFF로 설정한 경우에는 등록한 순서대로 답변이 출력됩니다.&#x20;

****

➍ **수정 및 삭제**

기존에 생성된 응답 메시지를 수정하거나 삭제할 수 있습니다.

&#x20;   &#x20;

➎ **템플릿, 커스텀 코드, 감정 표현 설정**

템플릿, 커스텀 코드, 감정 표현을 설정할 수 있습니다. 각 기능의 세부 내용은 아래 2-3\~2-5 목차를 참고해주세요.           &#x20;



➏ **적용 버튼**&#x20;

응답 메시지를 수정한 후에는 반드시 적용 버튼을 눌러야 합니다. 적용 버튼을 누르지 않으면 저장되지 않거나 수정사항이 반영되지 않습니다.



### 2-3. 템플릿 설정

텍스트 외에 추가적인 기능 요소가 필요할 때, 템플릿을 직접 커스텀해서 응답 메시지에 적용할 수 있습니다. 템플릿의 개념과 제작에 대한 상세한 정보는 아래의 "자세히 알아보기" 버튼을 눌러주시길 바랍니다.

****[**템플릿 자세히 알아보기 >**](../../undefined-2/undefined-1.md) ****&#x20;

응답 메시지 설정 창에서 템플릿 사용 여부를 ON으로 체크하면 **템플릿 선택 화면**이 나타나며, 용도에 맞는 템플릿을 선택할 수 있습니다. 템플릿 관리 페이지에서 만든 템플릿들이 이 선택 화면에 나타납니다.

![템플릿 선택 창 ](<../../../.gitbook/assets/image (183).png>)

#### 버튼 템플릿 설정 예시

![버튼 템플릿 예시](<../../../.gitbook/assets/3. 템플릿 예시.png>)

위 예시는 응답 템플릿 중 버튼을 사용할 때의 설정값입니다. 버튼 템플릿은 사용자에게 특정 시나리오나 URL 등의 정보를 버튼 형태로 제공하는 템플릿으로, 기본적으로 button 컴포넌트로 구성되어 있습니다. 버튼 생성을 위해서는 label, value, action 값을 설정해야 합니다.

* label : 챗봇 화면에 출력되는 버튼의 이름
* value : 버튼 선택 시 챗봇에 전달되는 값 (value는 보통 label과 동일한 값을 입력해줍니다.)
* action : 버튼의 타입 (query, url, param 으로 구분)

{% hint style="info" %}
**query와 param의 차이**

query는 텍스트 값을 그대로 챗봇에게 전달하고, param은 해당 텍스트에 부여된 고유값을 전달합니다. 예를 들어 text가 "시집"일 때 query는 "시집"이라는 텍스트 값을, param은 "시집"에 부여한 \[0001]이라는 숫자값을 챗봇에게 전달합니다. query를 활용하여 재질의에 대한 선택지를 만들거나, 다른 인텐트로 넘어가는 버튼을 만들 수 있습니다.                                    &#x20;
{% endhint %}



### 2-4. 커스텀 코드 설정

주로 글로벌 파라미터로 주고 받을 코드를 정의하는 경우에 사용하며, 파라미터 명과 파라미터 값을 입력 할 수 있습니다. ![](<../../../.gitbook/assets/image (439).png>)버튼을 클릭해야만 입력되며 여러 개의 코드를 입력 할 수 있습니다. 동일한 파라미터 명을 반복해서 사용할 경우, 관리도구의 **\[대화관리 > 템플릿]** **메뉴**에서 작성된 템플릿을 활용하면 커스텀 코드를 보다 쉽게 정의할 수 있습니다.



### 2-5. 감정 표현

감정 표현을 통해 챗봇의 감정(emotion) 상태를 정의할 수 있습니다. 응답 메시지를 통해 "기쁘다", "슬프다" 등을 표현한 경우, '기쁨', '슬픔' 등의 감정 표현 값을 매핑하여 챗봇의 이미지를 출력할 수 있습니다.     &#x20;

&#x20; &#x20;