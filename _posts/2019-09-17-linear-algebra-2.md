---
title: "선형대수 2일차"
categories:
  - Linear Algebra
tags:
  - 선형대수
use_math: true
---

벡터의 내적과 외적에 대해 얘기해보겠습니다.

수의 곱은 배수입니다. $a$만큼의 양이 $b$개 있으면 $a \times b$ 인거죠

그럼 수의 목록인 벡터 간의 곱은 어떻게 해석해야 할까요?

$a$ 벡터가 $b$ 벡터만큼 있다?

뭔가 이상합니다. 벡터가 양이 아닌 방향도 포함하기 때문이죠

앞에서 선형결합에 대해 얘기를 해보았습니다.

$[x_1, x_2]$ 벡터가 있고 이 벡터의 요소들과 y라는 값과의 관계가 선형적이라고 해봅시다.

그럼 다음과 같은 관계가 될 수 있을겁니다.

$$ y = a_1 \times x_1 + a_2 \times x_2 + b $$

이걸 좀 더 말로 풀어보면 $[x_1, x_2]$라는 벡터와 $y$와의 관계가 선형적이려면 $a_1 \times x_1 + a_2 \times x_2$ 형태의 연산이 필요하다고 결론내릴 수 있습니다.

$a_1$, $a_2$를 벡터 $[a_1, a_2]$라고 하면 두 벡터의 같은 위치 요소의 곱들의 합이라는 연산이 필요하다고도 표현할 수 있습니다.

우리는 이 연산을 벡터의 내적이라고 부릅니다.

이 개념을 도입하면 $y$는 두 벡터의 내적에 스칼라 값 하나를 더한다고 아주 단순하게 표현할 수 있습니다.

내적 연산은 $\cdot$으로 표시하니 짧은 수식으로 표현이 가능해집니다. 따라서 이를 기초로 전개한 이론들도 더 함축적이게 되죠

이렇게 보면 수학은 참 기능적이고 실용적인 특징을 갖고 있습니다.

외적에 대해서 보겠습니다.

외적은 내적보다 좀 더 복잡합니다.

외적은 두 벡터를 변으로 하는 평행사변형의 넓이만큼의 크기를 갖고 두 벡터를 포함하는 평면에 수직인 방향을 갖는 벡터입니다.

단번에 이해하기 어렵습니다. 일단 넓이가 있고 평면에 수직이라는게 등장하는 것부터가 3차원으로 제한시키고 있습니다.

외적이 3차원만 해당되는건 아니지만 기본적으로 3차원에서 얻은 수학적 결론을 확장하여 일반화시켰습니다.

전자기학, 역학 등 물리에서 외적이 활용됩니다.

이 개념도 수학적으로 표현하면 내적과 같은 단순함이 있지만 선형대수에서 깊게 활용될만한지 잘 모르겠습니다.






