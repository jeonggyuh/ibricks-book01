---
description: 관리도구에서 엔티티를 생성하는 방법을 알아봅니다.
---

# 엔티티 생성하기

> 엔티티(Entity)는 챗봇이 센텐스의 의미를 이해하기 위하여 작성된 체계적인 용어의 집합입니다. 엔티티에 대한 상세한 정보는 아래의 "자세히 알아보기" 버튼을 눌러주시기 바랍니다.
>
> ****[**엔티티 자세히 알아보기 >**](../../undefined-1/undefined-2.md)****

## 1. 엔티티 설정

대화 설계에 필요한 엔티티를 연결하고 태깅하기 위해서는 먼저 엔티티를 생성해야 합니다. 관리도구 좌측의 **\[지식관리 > 엔티티] 메뉴**에서 엔티티 생성 및 관리가 가능합니다.

![엔티티 경로](<../../.gitbook/assets/1.엔티티 경로.png>)

### 1-1. 엔티티 추가

엔티티 목록 화면에서 **+엔티티 추가** 버튼을 클릭한 후 엔티티 명을 설정하고 ![](<../../.gitbook/assets/image (439).png>) 버튼을 클릭하거나 엔터를 누르면, 신규 엔티티가 생성됩니다. 엔티티 추가는 엔티티 태깅을 통해서도 가능합니다.

![\[아이브릭스\] 엔티티 추가](<../../.gitbook/assets/엔티티 추가 (2).gif>)



### 1-2. 엔티티 목록

엔티티 목록 화면에서는 생성된 엔티티 리스트, 총 엔티티 수, 엔티티 안에 작성된 엔트리/유의어 수를 확인할 수 있습니다. 아래는 엔티티 목록 화면의 각 기능에 대한 상세 안내입니다.

![엔티티 목록 화면](<../../.gitbook/assets/2.엔티티 목록 (1).png>)

➊ **엔티티 정렬** &#x20;

엔티티 리스트를 등록순이나 가나다순으로 정렬할 수 있는 기능입니다.



➋ **엔티티 검색**&#x20;

찾으려는 엔티티 이름을 입력 후 엔터 또는 ![](<../../.gitbook/assets/image (134).png>) 아이콘을 클릭하면 검색 결과가 나옵니다.



➌ **엔티티 조회 및 설정**

해당 도메인의 엔티티 총 개수를 확인할 수 있고, 한 페이지에 보여지는 엔티티의 조회건수를 설정할 수 있습니다.

****

➍ **엔티티 삭제** &#x20;

삭제하고 싶은 엔티티의 휴지통 아이콘을 클릭하면 목록에서 삭제됩니다.&#x20;



➎ **엔티티 상세 내용 확인 및 수정**

엔티티 목록 내의 엔티티 명을 클릭하면 각 엔티티별 세부 관리 화면으로 이동합니다.&#x20;



> 엔티티를 일일이 작성하지 않고, 엑셀 템플릿에 작성하여 일괄 업로드할 수도 있습니다. 대량의 엔티티 추가 및 관리가 필요한 경우, 관리도구 우측 상단의 엑셀 업로드 기능<img src="../../.gitbook/assets/image (190).png" alt="" data-size="line">을 활용해 지식을 일괄 업로드할 수 있습니다.&#x20;
>
> ****[**엔티티 일괄 업로드 자세히 알아보기 >**](undefined-2.md#2.)&#x20;



### 1-3. 엔티티 세부 관리

엔티티 목록 화면에서 특정 엔티티 명을 클릭하면 해당 엔티티 관리 화면으로 진입할 수 있습니다. 엔티티 관리 화면에서는 엔티티 명 변경, [**엔트리**](../../undefined-1/undefined-2.md#1-1.) 추가 및 관리가 가능합니다. 아래는 엔티티 관리 화면의 각 기능에 대한 상세 안내입니다.&#x20;

![엔티티 관리 화면     ](<../../.gitbook/assets/3.엔티티 관리.png>)

➊ **엔티티 명 확인 및 수정**&#x20;

수정 아이콘 <img src="../../.gitbook/assets/image (371).png" alt="" data-size="line"> 을 클릭하고 엔티티 명을 변경한 후 <img src="../../.gitbook/assets/image (311).png" alt="" data-size="line">버튼을 눌러야 저장됩니다.



➋ **엔트리 추가 **<mark style="color:red;">**(필수값)**</mark>

엔티티를 생성하기 위해서는 최소 1개의 엔트리를 등록해야 합니다. 원하는 엔트리를 입력한 후 엔터 또는<img src="../../.gitbook/assets/image (373).png" alt="" data-size="line">버튼을 클릭하면 신규 엔트리가 생성됩니다.   &#x20;



➌ **엔트리 검색**&#x20;

찾으려는 엔트리 이름을 입력한 후 엔터 또는 ![](<../../.gitbook/assets/image (134).png>) 아이콘을 클릭하면 검색 결과가 나옵니다.



➍ **엔트리 정렬**&#x20;

엔트리 리스트를 등록순이나 가나다순으로 정렬할 수 있는 기능입니다.



➎ **유의어 입력**&#x20;

입력한 엔트리의 유의어를 입력한 후 엔터 또는 <img src="../../.gitbook/assets/image (2).png" alt="" data-size="line">버튼을 클릭하면 등록됩니다.&#x20;



➏ **유의어 삭제** &#x20;

삭제하고 싶은 유의어의 <img src="../../.gitbook/assets/image (72).png" alt="" data-size="line"> 버튼 클릭하면 목록에서 삭제됩니다. &#x20;



➐ **엔트리 삭제**&#x20;

삭제하고 싶은 엔트리의 휴지통 아이콘을 클릭하면 목록에서 삭제됩니다.



{% hint style="info" %}
**엔티티 상속 · 정규표현식**

엔티티 상속은 이전에 만들어진 엔티티를 현재 엔티티에 포함시킬 경우에 사용합니다.&#x20;

예를 들어, A라는 엔티티에 B 엔티티의 모든 엔트리 및 유의어를 포함시킬 경우 활용 가능합니다. 엔트리에 결합하고 싶은 '@엔티티 명'를 입력하면 자동으로 설정됩니다.

정규표현식이란 특정 패턴에 일치하는 엔트리를 매칭하기 위한 표현식입니다. 엔트리 앞/뒤에 '#'를 붙이며, [JAVA 8 정규식](https://docs.oracle.com/javase/8/docs/api/java/util/regex/Pattern.html)을 지원합니다.
{% endhint %}

&#x20;                &#x20;
