# 2단계 - 문자열 계산기

## 기능 요구 사항
- 사용자가 입력한 문자열 값에 따라 사칙 연산을 수행할 수 있는 계산기를 구현해야 한다.
- 문자열 계산기는 사칙 연산의 계산 우선순위가 아닌 입력 값에 따라 계산 순서가 결정된다.
  - 즉, 수학에서는 곱셈, 나눗셈이 덧셈, 뺄셈 보다 먼저 계산해야 하지만 이를 무시한다.
- 예를 들어 2 + 3 * 4 / 2 와 같은 문자열을 입력할 경우 2 + 3 * 4 / 2 실행 결과인 10을 출력해야 한다.

## 추가 제약 사항
- 소수점은 올 수 없다. 

## 프로그래밍 요구 사항
- 메서드가 너무 많은 일을 하지 않도록 분리하기 위해 노력해보자.

## 기능 구현 리스트
- [ ] 덧셈
- [ ] 뺄셈 
- [ ] 곱셈
- [ ] 나눗셈
- [ ] 사칙 연산을 모두 포함하는 연산
- [ ] 입력값이 null 또는 빈 문자열일 경우 IllegalArgumentException throw
- [ ] 사칙연산 기호가 아닌 경우 IllegalArgumentException throw