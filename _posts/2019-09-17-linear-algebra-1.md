---
title: "선형대수 1일차"
categories:
  - Linear Algebra
tags:
  - 선형대수
---


머신러닝을 공부하면서 선형대수에 대해 복습해볼 필요를 느껴서 블로그에 정리해보고자 합니다.

수학적인 내용보다는 선형대수와 다른 분야, 특히 공학과의 연계성을 탐색하고 고찰할 수 있는 내용을 담고자 합니다.

선형대수를 시작하면 가장 먼저 벡터라는 말이 나옵니다. 벡터는 운반하다를 뜻하는 라틴어에서 비롯되었다고 합니다.

벡터는 순서가 있고 유한한 수들의 목록입니다. 우리가 알고 있는 수는 스칼라로 부릅니다.

벡터는 수의 양적인 확장입니다. 보통 정수론, 기하 등 수학 분야에서는 수 자체의 성질에 대한 이해에 관심이 있지 수들의 목록을 개념으로 도입해서 다룰 일은 거의 없습니다.

그럼 벡터는 왜 필요할까요?

누군가의 호기심으로 만들어진 개념일 뿐일까요?

어떤 물체의 무게를 표현한다고 합시다. 수 하나면 됩니다.

그럼 위치를 표현한다고 합시다. 가로, 세로, 높이 아니면 위도, 경도, 높이 등 3종류 값이 필요합니다.

움직이는 방향을 표현한다고 합시다. 해당 방향이 가로, 세로, 높이 각각 어느만큼인가에 대한 값들이 필요합니다.

생각보다 현실 세계에는 수 하나로 표현되지 않는 정보들이 아주 많습니다.

그렇다면 이 정보들 간의 관계, 경향 등을 파악하기 위해 수학의 힘을 빌리려면 그에 맞는 개념이 도입될 필요가 있습니다.

그것이 바로 벡터입니다.

그럼 아까 봤던 개념을 다시 보겠습니다.

1. 순서

순서는 결국 벡터를 구성하는 요소들의 순서입니다. 벡터는 각 요소들이 어떤 값을 가지는지를 표현하기 때문에 순서가 필요합니다.
즉, [1 2]와 [2 1]은 서로 다릅니다.

2. 유한

앞서 본 현실 세계의 정보를 표현하고자 한다면 요소 수가 유한할 수 밖에 없으니 굳이 무한 벡터를 고려해서 이론을 어렵게 할 필요가 없을겁니다.
물론 도입 이유가 생긴다면 무한한 경우도 고려해 볼 수 있겠습니다.

벡터와 관련해서 공간, 방향이라는 용어를 많이 씁니다. 아무래도 수학이 아주 예전부터 활용되어온 분야가 물리이다보니 위치, 힘을 벡터로 표현했을 때 이해하기 쉽기 위함이라고 볼 수 있겠습니다.

또한 벡터 간의 연산을 2차원 또는 3차원 공간에서 표현하면 이해하기 수월합니다.

그리고 벡터의 선형 결합에 대해 생각해봅시다.

선형적이라는건 두 요소 사이의 관계가 y=ax+b와 같다고 볼 수 있습니다. 이는 합과 곱의 연산으로 표현이 되며 수학적으로 표현할 수 있는 가장 단순한 관계입니다.

선형대수는 이런 기본에서부터 시작합니다.



