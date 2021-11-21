# three-js-learning

- 전제 지식들

  - CPU는 빠른 연산 속도를 가지고 있으나 one by one 계산. 그래서 스케쥴러 알고리즘이 중요. 반면 GPU는 병렬 컴퓨팅 가능.
  - vertex를 위치시키고 그리고 색을 입히는 등의 작업을 shader라 함.
  - Native WebGL을 직접 다루는 low level의 접근은 컨트롤할 수 있는 범위가 넓지만 역시나 너무 코드가 길어지고 힘든 일이다. 대부분의 개발자가 three.js라던가, babylone.js를 사용하는 이유다.

- scene

  - object, model, light와 같은 여러 요소들을 넣는 컨테이너 같은 곳

- object

  - 객체라는 말이 추상적이듯 많은 것이 객체가 될 수 있다. 빛, 파티클, 모델 등등이 전부 object이다.

- mesh

  - A Mesh is the combination of a geometry (the shape) and a material (how it looks).
    - Mesh = geometry + material
  - geometry에 여러 종류가 있고, material에도 여러 종류가 있다. 문서를 참고해보자.

- camera

  - view의 시점을 담당한다.

- three.js documentation
  - https://threejs.org/docs/index.html#manual/en/introduction/Creating-a-scene
