# Props-Getter-Components

## 특징

> Custom Hook Pattern는 훌륭한 제어 기능을 제공하지만 개발자가 많은 네이티브 후크 소품을 처리하고 개발자 측에서 로직을 다시 만들어야 하기 때문에 구성 요소를 통합하기 어렵게 만듭니다.

> Props Getters Pattern패턴은 이 복잡성을 숨기려고 시도합니다 . props getters기본 소품을 노출하는 대신 후보 목록을 제공합니다 .

> A getter는 많은 props를 반환하는 함수이며 의미 있는 이름을 가지고 있어 getter어떤 JSX 요소에 해당하는지 개발자에게 명확하게 알 수 있습니다.

## 장점

> 사용 용이성: 복잡성이 숨겨져 있습니다. 개발자는 getter주어진 useCounter 권한을 올바른 JSX 요소에 연결하기만 하면 됩니다.

카운터에 대한 로직은 커스텀 훅에 숨겨져 있으니 Usage 컴포넌트는 무엇을 보여줄지에 집중 할수 있다.

## 단점

> 가시성 부족: getters 구성 요소를 통합하기 쉽게 만드는 추상화를 가져오지만 더 불투명하고 "마술"이 됩니다. 개발자는 노출된 getter 소품과 영향을 받는 내부 논리를 제대로 이해해야 이를 올바르게 재정의할 수 있습니다(이를 Typescript지원해야 함).

기준

제어 역전: 3/4
통합 복잡성: 3/4
