---
layout: single 
title: "Python은 어떤 언어인가?"
categories: 
  - Python
tags:
  - [Programming Language, Python, Python History, Python Characteristic]
author_profile: false
search: false
redirect_from:
  - /language/about_python/ 
use_math: true
sidebar:
    nav: "nav_list_main"
---
Python(파이썬)은 직관적이고 간결한 문법으로, 프로그래머들은 물론 비전공자들 사이에서도 가장 주목받는 언어입니다. 

<div style="text-align:center">
    <img src="/images/language/python/about_python/python2.png" alt="python_icon" width="200" />
    <p style="font-size: smaller;"><em>이미지 출처: FLATICON</em></p>
</div>

간단한 유틸리티 제작을 넘어 웹 프로그래밍, 데이터 분석, 머신러닝, 딥러닝, 사물 인터넷(IoT) 등 다양한 분야에서 활용되고 있습니다. 

이번 시간에는 파이썬으 어떤 언어이고, 어떤 특징을 가지고 있는지 알아보도록 하겠습니다. 

## Python 소개
### Python의 탄생 
Python은 네덜란드 암스테르담의 "귀도 반 로섬(Guido van Rossum)"이 개발한 프로그래밍 언어입니다. 1991년에 출시하며 이름을 Python이라고 지었죠. 귀도는 자신이 좋아하던 코미디 프로그램 <Monty Python's Flying Circus>에서 Python이라는 이름을 따왔다고 합니다.

<div style="text-align:center">
    <img src="/images/language/python/about_python/van_rossum_monty_pythons.png" alt="python_history" width="700" />
    <p style="font-size: smaller;"><em>이미지 출처: school.coding-x.com</em></p>
</div>

프로그래밍 언어 중에서도 오래전에 만들어진 '포트란'은 1954년에 탄생했고, 지금도 많이 사용하는 C언어는 1972년에 공개된 언어입니다. 해당 언어들과 비교하면 1991년에 탄생한 Python은 비교적 최신에 만들어진 언어라고 할 수 있습니다.

Python은 신화속에 나오는 비단뱀이라는 뜻이기 때문에 로고에 두 마리의 뱀이 들어간 것 입니다(특별한 의미는 없다고 합니다).

### Python을 휴가 중에 만들었다고?
누구나 영어로 이해할 수 있는 코드와 일상적인 업무에 적합한 빠른 개발을 원했던 "귀도 반 로섬"은 1989년, 네덜란드 국립 연구소에 근무하던 당시 두 달의 휴가 동안 취미로 만들어본 프로젝트의 하나로 Python을 개발하게 됩니다. 이후 모두를 위한 컴퓨터 프로그래밍이라는 이름으로 투자를 받아 파이썬이 개발되었습니다. 

현재 검색량을 기준으로 프로그래밍 언어 선호도를 조사하는 "TIOBE index"에서 2024년 9월 기준 파이썬은 선호하는 프로그래밍 언어 1위(20.17%)를 차지했으며, 오라일리 미디어가 온라인 학습 플랫폼의 학습 과정 및 사용자 선호도를 분석해 발표한 프로그래밍 언어 순위에서는 파이썬이 Java와 C++을 제치고 가장 높은 사용률을 보였습니다.

<div style="text-align:center">
    <img src="/images/language/python/about_python/2024_09_ranking.png" alt="python_ranking" width="700" />
    <p style="font-size: smaller;"><em>이미지 출처: TIOBE Index for September 2024</em></p>
</div>

## Python 특징
### Python의 기본 철학
[PEP 20](https://peps.python.org/pep-0020/) 문서에 보면 Python의 철학이 나오는데 핵심 철학은 아래와 같습니다. 

<div class="notice--success">
<ul>
    <li>"아름다운 게 추한 것보다 낫다." (Beautiful is better than ugly)</li>
    <li>"명시적인 것이 암시적인 것 보다 낫다." (Explicit is better than implicit)</li>
    <li>"단순함이 복잡함보다 낫다." (Simple is better than complex)</li>
    <li>"복잡함이 난해한 것보다 낫다." (Complex is better than complicated)</li>
    <li>"가독성은 중요하다." (Readability counts)</li>
</ul>
</div>

이런 철학들 때문에 Python은 "복잡하지 않으면서 의미가 명확하고, 코드의 축약보다 뚜렷하게 보이는 흐름을 중시하는 파이썬의 철학을 중시"하는 언어로 알려져 있습니다. 

그럼 여기서 Python에서 대표하는 특징들을 살펴보겠습니다. 

### Python의 대표적 특징 
#### 1) 스트립트 언어 
Python은 컴파일 과정 없이 인터프리터가 소스 코드를 한 줄씩 읽어 곧바로 실행하는 스크립트 언어입니다. 스크립트 언어의 특성상 컴파일 과정이 필요하지 않기 때문에, 실행 결과를 바로 확인하고 수정할 수 있으며, 코드 작성의 난이도 또한 낮습니다. 

> **&#8251; 컴파일 언어 vs 스크립트 언어** \
> 컴파일 언어는 컴파일 과정(전처리, 컴파일, 어셈블, 링크)을 통해, 작성한 코드를 기계어로 번역해 실행하는 방식입니다.\
> 반면, 스크립트 언어는 별도의 컴파일 과정 없이 인터프리터(프로그래밍 언어 해석기)가 소스 코드를 한 줄씩 읽어가며 바로 실행하는 방식입니다.\
> 컴파일 언어는 소스 코드를 컴파일 하는 과정을 거쳐야 하므로, 실행 및 수정에 비교적 많은 시간이 소요되지만, 한 번 기계어로 번역된 이후에는 빠른 실행 속도를 보입니다.\
> 이와 달리, 스크립트 언어는 컴파일 없이 곧바로 실행되므로, 결과를 바로 확인하고 수정할 수 있지만, 번역과 실행이 동시에 이루어지므로, 실행 속도가 컴파일 언어에 비해 느립니다. 

> **&#8251; 스크립트 언어 & 인터프리터 언어** \
> 스크립트 언어와 인터프리터 언어는 비슷한 개념으로 사용되고 있지만, 엄밀히 말하면 다른 개념입니다. \
> 스크립트 언어는 코드를 Iterpret(해석)하는 방식으로 동작하는 언어를 의미하고, 인터프리터 언어는 소스 코드를 실행할 때, 컴파일 단계를 거치지 않고 바로 해석하여 실행하는 언어를 의미합니다. \
> 물론, 두 언어의 차이점이 명확하지는 않기 때문에 같은 개념처럼 사용되는게 일반적이며, 실제로 Python은 스크립트 언어이면서, 인터프리터 언어입니다. \
> 하지만, 스크립트 언어이면서 인터프리터 언어가 아니거나, 반대로 인터프리터 언어이면서 스크립트 언어가 아닌 경우도 있을 수 있습니다. 대표적으로 **MATLAB**은 스크립트 형태로 작성되지만, 컴파일 단계를 거쳐 실행파일을 생성하기 때문에, 스크립트 언어지만 인터프리터 언어가 아닙니다. 또한 Java는 컴파일 언어와 인터프리터 언어의 특징을 모두 갖는 하이브리드 언어로 스크립트 언어는 아니지만, 인터프리터 언어의 특징이 가지고 있습니다. 

#### 2) 동적 타이핑
Python은 동적 타이핑(Dynamic Typing) 언어 입니다. 여기서 동적 타이핑이란, 변수의 자료형을 지정하지 않은 상태에서, 단순히 선언하는 것만으로 값을 지정할 수 있음을 의미합니다. 이 때, 변수의 자료형은 코드가 실행되는 시점에 결정됩니다. 형변환을 위한 번거로운 과정이 불필요해진다는 장점이 있지만, 예상치 못한 타입이 할당되어 런타임 에러가 발생할 수도 있습니다.

이와 상반되는 개념으로 정적 타이핑(Static Typing) 언어도 있습니다. 정적 타이핑 언어는 컴파일 시점에서 변수의 타입이 명시적으로 선언되어야 합니다(대포적 언어로 Java가 있습니다). 하지만 그렇다고 해서 컴파일 언어이면 무조건 정적 타이핑이고, 스크립트 언어면 무조건 정적 타이핑인 것은 아닙니다.

#### 3) 플랫폼 독립성
Python은 Linux, Unix, Window, Mac 등 대부분의 운영체제에서 모두 동작합니다. 운영체제 별로 컴파일할 필요가 없다는 것은 곧, 한 번 소스 코드를 작성하면, 어떤 운영체제에서도 활용할 수 있다는 것을 의미합니다. 

대표적인 특징을 알아보았으니 이제 Python의 장, 단점을 살펴볼까요? 

### Python의 장점 
#### 1) 간결하고 쉬운 문법 
Python을 흔히 "인간다운 언어"라고 이야기 합니다. 그 이유는 Python의 문법이 인간의 사고와 유사하기 때문입니다. 이러한 이유에서 Python 문법을 학습하는 데에 많은 시간을 할애할 필요가 없으며, 프로그래밍 전공자의 경우, Python 문법이 얼마나 쉽고 간결한지를 몸소 느낄수 있습니다. 여기서 쉽고 간결하다는 것은 코드가 직관적이고, 길이가 짧아 가독성이 높다는 의미입니다. 

#### 2) 빠른 개발 속도 
쉽고 간결한 문법 덕분에 Python은 높은 생산성을 자랑합니다. Python을 활용할 경우 더 적은 코드로 더 많은 작업을 수행할 수 있으며, 이는 복잡한 구문으로 인해 발생할 수 있는 오류를 줄여줄 수도 있습니다. 

#### 3) 높은 확장성 및 이식성
Python은 대표적인 접착제 언어(Glue Language) 입니다. 적, 다른 언어나 라이브러리에 쉽게 접근해 연동이 가능합니다. 실제로, 고성능의 어플리케이션 개발에 C나 C++ 같은 언어를 Python과 결합해 사용하기도 합니다. 이로써 애플리케이션의 성능은 보장되면서, 동시에 별도 설치나 구성과정 없이 스크립트 언어의 장점도 누릴수 있게 됩니다. 

#### 4) 활발한 생태계 
파이썬은 다양한 분야에 대한 라이브러리와 프레임워크를 제공하기 때문에 프로그래머가 모든 코드를 일일이 작성할 필요가 없습니다. 또한 폭 넓은 생태계와 활발한 커뮤니티 활동으로 인해 문제 해결과 협업이 매우 빠르게 이루어질 수 있습니다.

### Python의 단점
#### 1) 느린 실행 속도
인터프리터 언어로 컴파일 언어에 비해 실행 속도가 느립니다. 따라서 성능이 중요한 애플리케이션, 예를 들어 게임 엔진이나 고성능의 수치 계산에는 적합하지 않을 수 있습니다. 

#### 2) 모바일 및 웹 클라이언트 개발
웹 서버 측 스크립트나 데이터 처리에 주로 사용되지만, 웹 클라이언트 측 개발에는 JavaScript 등 다른 언어가 더욱 선호됩니다(Streamlit 이나 FastHTML이 나왔지만 한계가 명확합니다). 또한, IOS나 Android와 같은 모바일 환경에서의 앱 개발에는 잘 사용되지 않습니다. 

#### 3) 멀티코어 CPU 활용 
Python의 GIL(Global Interpreter Lock) 때문에 멀티코어 CPU를 효율적으로 활용하는 것이 어렵습니다. 이는 병렬 처리가 필요한 고성능 애플리케이션에서는 문제가 될 수 있습니다. 

#### 4) 데이터베이스 접근 
데이터베이스 접근에 있어서 다른 언어들에 비해 제한적인 측면이 있습니다. Python의 데이터베이스 연동 기능은 상대적으로 느리고, 대규모 트래픽과 데이터를 처리하기 위한 엔터프라이즈급 애플리케이션에는 제한적일 수 있습니다.

## Python의 활용 사례 
지금까지 살펴본 Python의 특징을 바탕으로 과연 Python은 어디에 활용되었는지 살펴보겠습니다. 

### 기업에서의 활용
#### 1) Google

<div style="text-align:center">
    <img src="/images/language/python/about_python/google_logo.png" alt="python_history" width="300" />
    <p style="font-size: smaller;"><em>이미지 출처: google</em></p>
</div>

구글은 백엔드에서 C++과 Python을 결합해 활용하고 있습니다. 짧은 대기시간과 엄격한 메모리 제어가 중요한 스택에는 C++을 프그램의 빠른 전달과 유지 관리가 필요한 부분에서는 Python을 사용합니다. 

#### 2) Instagram

<div style="text-align:center">
    <img src="/images/language/python/about_python/instagram.png" alt="python_history" width="400" />
    <p style="font-size: smaller;"><em>이미지 출처: Business Insider</em></p>
</div>

Python으로 작성된 오픈 소스 웹 프레임워크인 Django를 기본 서버 측 언어로 사용하고 있습니다. 

#### 3) Netflix 

<div style="text-align:center">
    <img src="/images/language/python/about_python/Netflix-Logo.jpg" alt="python_history" width="400" />
    <p style="font-size: smaller;"><em>이미지 출처: Netfilx</em></p>
</div>

방대한 표준 라이브러리, 간결하고 깔끔한 구문, 대규모 커뮤니티, 풍부한 타사 라이브러리 등을 이유로 Python을 자사 서비스에 적극적으로 활용하고 있습니다. 

#### 4) Spotify 

<div style="text-align:center">
    <img src="/images/language/python/about_python/spotify-logo.jpg" alt="python_history" width="400" />
    <p style="font-size: smaller;"><em>이미지 출처: Belwood music</em></p>
</div>

음악 스트리밍 및 미디어 서비스 제공 업체 Spotify는 Python을 활용해 빌드 되었으며, 백앤드의 80%가 Python으로 작성되어 있다고 알려져있습니다.

#### 5) Dropbox 

<div style="text-align:center">
    <img src="/images/language/python/about_python/dropbox.png" alt="python_history" width="400" />
    <p style="font-size: smaller;"><em>이미지 출처: Dropbox</em></p>
</div>

외부 오픈 소스 코드와 자체 작성한 코드 모두 Python을 사용하고 있습니다(귀도 반 로썸도 Dropbox 개발자 출신이기도 합니다). 

### Python의 활용 영역 
#### 1) 시스템 유틸리티 제작
운영체제의 시스템 명령어를 사용할 수 있는 각종 도구를 갖추고 있습니다. 파일 관리, 로그 분석, 시스템 모니터링 등과 같은 여러 시스템 유틸리티를 만드는데 유리합니다. 

#### 2) GUI 프로그래밍
GUI 프로그래밍을 위한 도구들이 잘 갖추어져 있다. 대표적으로 PyQt5, PyGUI, Tkinter 등이 있습니다. 

#### 3) C/C++과의 결합
C나 C++로 만든 프로그램을 파이썬에서 사용할 수 있고, 반대로 파이썬으로 만든 프로그램을 C나 C++에서 사용하는 것도 가능합니다. 

#### 4) 웹 프로그래밍 
웹 클라이언트를 만드는 것은 어려우나 웹 프로그램를 제작하기에 매우 적합하여, 파이썬으로 웹 사이트를 제작하는 경우가 많습니다(주로 프론트 영역은 JavaScript, 백엔드를 Python으로 사용하는 경우 입니다).

#### 5) 수치 연산 프로그래밍
수치 연산 프로그래밍에는 사실 C언어가 적합합니다. 하지만 Python의 NumPy라는 수치 연산 모듈이 C로 작성되었기 때문에 Python에도 빠른 수치 연산을 수행할 수 있습니다.

#### 6) 데이터 분석 
Numpy, Pandas, Matplotlib 등의 라이브러리를 활용하여 데이터 처리, 통계 분석, 시각화를 수행할 수 있습니다. 아직까지는 데이터분석에 특화된 R이라는 언어가 더 많이 사용되고 있지만, 최근 들어 파이썬을 사용하는 추세가 굳어지고 있습니다.

#### 7) 데이터 베이스 프로그래밍
Sybase, Infomix, Oracle, MySQL, PostgreSQL 등의 데이터베이스에 접근하기 위한 도구를 제공합니다. 

#### 8) 인공지능과 머신러닝
Python을 활용하여 자연어 처리, 음성 인식, 이미지 인식과 같은 인공지능 기술을 구현할 수 있습니다. 인공지능과 머신러닝 프로그래밍에는 Scikit-Learn, TensorFlow, PyTorch, Keras 등의 라이브러리가 사용됩니다. 

## 마무리 
오늘은 파이썬의 역사, 특징, 활용 분야까지 살펴봤습니다. Python이 널리 사용된 이유는 간결하고 쉽기 때문입니다. 문법이 다른 프로그래밍 언어에 비해 어렵지 않으며, 표현하는 구조도 사람이 대화하는 형식을 이용함으로서 초보자도 쉽게 배울 수 있다는 강점이 있습니다. 또한, 개발자가 누구든지 무료로 쓸 수 있도록 오픈 소스로 제공한 것도 큰 역할을 했다고 볼 수 있습니다. 현재 Python은 속도를 높이기 위해 지속적으로 업데이트를 진행하고 있습니다. 앞으로도 파이썬은 더 많은 분야에서 사용될 것으로 예상되며, 특히 인공지능 분야에 더 많이 활용될 것으로 보입니다. 프로그래밍 언어를 배우고자 하시는 분들에게 Python은 좋은 선택이 될 것입니다. 한번 배워보시는 것은 어떨까요? 