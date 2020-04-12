## 기능요구사항
- 사다리 게임에 참여하는 사람의 이름을 최대 5글자까지 부여할 수 있음
 - 다섯 글자가 넘어가거나 아무것도 입력하지 않으면 exception 발생
 
- 사람이름은 쉼표(,)를 기준으로 구분한다.

- 사람이름을 5자 기준으로 출력하기 때문에 사다리 폭도 넓어져야한다함
  -  5자 기준이므로 ----- 가로폭도 그기준으로 맞춘다.

- 최대 사다리 높이를 받는다
  - 높이만큼 라인을 그리는 행위를 반복
  - 높이만큼 | 줄이 생겨야됨

- 라인의 첫번째 그리거나 그리지 않거나 두가지 선택해서 임의로 그린다. 그다음부터는 아래와 같이
- 사다리 타기가 정상적으로 동작하려면 라인이 겹치지 않도록 해야된다
 - |-----|-----| 모양과 같이 가로 라인이 겹치는 경우 어느 방향으로 이동할지 결정할 수 없다.
 - 라인이 겹치지 않으려면 그리기전에 앞에 라인이 그려졌는지 안그려졌는지 알아야 됨
 - 앞에 라인이 그려졌다면 (O) 라인을 무조건 그리지 않아야함(X), 선택 할 수 없음
 - 만약에 앞에 라인이 그려지지 않음(X)
    - 그리거나 그리지 않거나 두개를 선택 할 수있음

- 실행 결과를 입력받는다 쉼표(,)를 기준으로 자른다.
- 결과를 보고싶은 사람을 입력받는다.

- 참여한 유저는 모두 결과값을 가지게 됨 
- 사다리 실제 결과를 계산하여 유저 result를 만들어준다.
- 만든다음 전체결과를 results 생성한다.
- 결과 계산을 한다.
    
- 사다리의 실행 결과를 출력해야함
 - 개인별 이름을 입력시 개인별 결과를 출력
 - "all"을 입력하면 전체 참여자의 실행결과를 출력    
    

## 프로그래밍 요구사항
- 자바 8의 스트림과 람다를 적용해 프로그래밍한다.
- 모든 엔티티를 작게 유지한다.