## java-calculator-precourse

### 🎯 요구사항
> 입력한 문자열에서 숫자를 추출하여 더하는 계산기

- [x] 문자열 입력받아 저장
- [ ] 숫자 추출하여 배열에 저장
  - 기본 구분자(`:`, `,`)를 기준으로 문자열을 분리하여 숫자 추출
  - 양수만 인식 가능
- [ ] 커스텀 구분자 지정
  - 문자열 앞부분의 `//`와 `\n` 사이에 위치하는 문자를 커스텀 구분자로 사용
  - 커스텀 구분자는 1개의 문자만 입력 가능
  - 커스텀 구분자와 기본 구분자 함께 사용 가능
- [ ] 저장한 숫자를 모두 합하여 반환
- [ ] 빈 문자열 입력 시 0 반환
- [ ] 예외 시 `IllegalArgumentException` 발생