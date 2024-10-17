# 문자열 덧셈 계산기

## 기능

- [ ]  `덧셈할 문자열을 입력해 주세요.` 메세지를 출력한다.
- [ ]  문자열을 입력받는다.
- [ ]  구분자를 통해 구분한다.
    - [ ]  기본 구분자를 통해 구분할 수 있다. (`,` , `:` )
    - [ ]  커스텀 구분자를 통해 구분할 수 있다.
    - [ ]  기본/커스텀 구분자 외의 구분자가 들어올 경우 "지정되지 않은 구분자입니다."메세지를 출력하고 `IllegalArgumentException` 을 발생시켜 종료한다.
- [ ]  구분된 문자에서 숫자를 추출한다.
    - [ ]  숫자가 아니라면 "숫자 형식이 아닙니다." 메세지를 출력하고 `IllegalArgumentException` 을 발생시킨다.
    - [ ]  양수가 아닐 경우 "숫자가 양수가 아닙니다." 메세지를 출력하고 `IllegalArgumentException` 을 발생시킨다.
    - [ ]  숫자의 범위에 대한 언급 X ⇒ `Long` 범위를 벗어날 경우, `계산기의 성능을 초과했습니다.` 메세지 제공하고 종료시킨다.

- [ ]  추출한 숫자들을 더한다.
    - [ ]  숫자들의 합이 `Long` 범위를 벗어날 경우, `계산기의 성능을 초과했습니다.` 메세지를 출력하고 `IllegalArgumentException`을 발생시킨다.
- [ ]  `결과 :`  메세지와 함께 결과값을 출력한다.
- [ ] `IllegalArgumentException`이 발생할 경우 애플리케이션을 종료시킨다.

