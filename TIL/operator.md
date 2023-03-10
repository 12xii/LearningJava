# 연산자 Operator

---

## 연산자의 종류

+ 산술 연산자 ( arithmetic operator )
+ 대입 연산자 ( assignment operator )
+ 증감 연산자 ( increment and decrement operators )
+ 비교 연산자 ( comparsion operator )
+ 논리 연산자 ( logical operator )
+ 비트 연산자 ( bitwise operator )
+ 삼항 연산자 ( ternary operator )
+ instanceof 연산자

---

### 산술 연산자 arithmetic operator

사칙연산을 다루는 이항연산자

왼쪽에서 오른쪽으로 결합한다

| 산술연산자 | 설명                                        |
| ------- | ------------------------------------------ |
| +       | 왼쪽의 피연산자에 오른쪽의 피연산자를 더함            |
| -       | 왼쪽의 피연산자에서 오른쪽의 피연산자를 뺌            |
| *       | 왼쪽의 피연산자에 오른쪽의 피연산자를 곱함            |
| /       | 왼쪽의 피연산자를 오른쪽의 피연산자로 나눔            |
| %       | 왼쪽의 피연산자를 오른쪽의 피연산자로 나눈 나머지를 반환 |

---

### 대입 연산자 assignment operator


오른쪽에서 왼쪽으로 결합하는 이항연산자



| 대입 연산자      | 설명                                                                                |
| ------------- | ---------------------------------------------------------------------------------- | 
| =             | 오른쪽의 피연산자를 왼쪽의 피연산자에 대입                                                    |
| +=            | 왼쪽의 피연산자를 오른쪽의 피연산자에 더해 왼쪽의 피연산자에 대입                                   |
| -=            | 왼쪽의 피연산자에서 오른쪽의 피연산자를 뺀 후 결괏값을 왼쪽의 피연산자에 대입                          |
| *=            | 왼쪽의 피연산자에 오른쪽의 피연산자를 곱한 후 결괏값을 왼쪽의 피연산자에 대입                          |
| /=            | 왼쪽의 피연산자를 오른쪽의 피연산자로 나눈 뒤 결괏값을 왼쪽의 피연산자에 대입                          |
| %=            | 왼쪽의 피연산자를 오른쪽의 피연산자로 나눈 나머지를 왼쪽의 피연산자에 대입                            |
| &=            | 왼쪽의 피연산자와 오른쪽의 피연산자를 비트 AND 연산한 이후 결괏값을 왼쪽의 피연산자에 대입               | 
| \|=           | 왼쪽의 피연산자와 오른쪽의 피연산자를 비트 OR 연산한 이후 결괏값을 왼쪽의 피연산자에 대입                |
| ^=            | 왼쪽의 피연산자와 오른쪽의 피연산자를 비트 XOR 연산한 이후 결괏값을 왼쪽의 피연산자에 대입               |
| <<=           | 왼쪽의 피연산자를 오른쪽의 피연산자만큼 비트 시프트 연산한 후 결괏값을 왼쪽의 피연산자에 대입              |
| >>=           | 왼쪽의 피연산자를 오른쪽의 피연산자만큼 부호를 유지한 채 비트 시프트 연산한 후 결괏값을 왼쪽의 피연산자에 대입 |
| >>>=          | 왼쪽의 피연산자를 오른쪽의 피연산자만큼 부호에 상관없이 비트 시프트 연산한 후 결괏값을 왼쪽의 피연산자에 대입  |

---

### 증감 연산자 increment and decrement operators

피연산자를 1씩 증감시킬 때 사용하는 단항연산자

피연산자의 위치에 따라 의미가 달라짐

| 증감 연산자      | 설명                                           |
| ------------- | ----------------------------------------------|
| ++x           | 피연산자의 값을 증가시킨 후 연산 수행                  |
| x++           | 연산 수행 후 피연산자의 값 증가                      |
| --x           | 피연산자의 값을 감소시킨 후 연산 수행                  |
| x--           | 연산 수행 후 피연산자의 값 감소                      |

---

### 비교 연산자 comparsion operator / relational operator

왼쪽에서 오른쪽으로 결합하는 이항연산자

피연산자 사이의 상대적인 크기 비교

| 비교 연산자       | 설명                                             |
| -------------- | ----------------------------------------------- |
| ==             | 왼쪽의 피연산자가 오른쪽의 피연산자와 같으면 참을 반환        |
| !=             | 왼쪽의 피연산자가 오른쪽의 피연산가와 같지 않으면 참을 반환    |
| >              | 왼쪽의 피연산자가 오른쪽의 피연산자보다 크면 참을 반환        |
| >=             | 왼쪽의 피연산자가 오른쪽의 피연산자보다 크거나 같으면 참을 반환 |
| <              | 왼쪽의 피연산자가 오른쪽의 피연산자보다 작으면 참을 반환      |
| <=             | 왼쪽의 피연산자가 오른쪽의 피연산자보다 작거나 같으면 참을 반환 |

---

### 논리 연산자

주어진 논리식을 판단하여 참과 거짓을 결정하는 이항 / 단항 연산자

| 논리 연산자 | 설명                                    |
| -------- | -------------------------------------- |
| &&       | 논리식이 모두 참이면 참을 반환 ( AND 연산 )     |
| \|\|     | 논리식이 하나라도 참이면 참을 반환 ( OR 연산 )   |
| !        | 논리식의 결과가 참이면 거짓을, 거짓이면 참을 반환 ( NOT 연산 ) |

---

### 비트 연산자

비트 단위로 논리 연산 / 비트 시프트 / 1의 보수를 만들 때 사용하는 연산자

| 비트 연산자 | 설명                                            |
| -------- | ---------------------------------------------- |
| &        | 대응되는 비트가 모두 1일 경우 1을 반환함 ( 비트 AND 연산 )|
| \|       | 대응되는 비트 중에서 하나라도 1일 경우 1을 반환함 ( 비트 OR 연산 ) |
| ^        | 대응되는 비트가 서로 다르면 1을 반환함 ( 비트 XOR 연산 ) |
| ~        | 비트가 1이면 0으로, 0이면 1로 반전시킴 ( 비트 NOT 연산 ) |
| <<       | 명시된 수만큼 비트를 지정한 수만큼 전부 왼쪽으로 이동시킴 (left shift 연산 ) |
| >>       | 부호를 유지하면서 지정한 수만큼 전부 오른쪽으로 이동시킴 ( right shift 연산 ) |
| >>>      | 지정한 수만큼 비트를 오른쪽으로 전부 이동시키며 새로운 비트는 모두 0이 됨 |

---

### 삼항 연산자

자바에서 유일하게 피연산자가 3개인 조건 연산자

```

조건식 ? 반환값 1 : 반환값 2

```

조건식이 참일 경우 반환값 1, 거짓일 경우 반환값 2를 반환

---

### instanceof 연산자

참조 변수가 참조하고 있는 인스턴스의 실제 타입을 반환

=> 해당 객체가 어떤 클래스 / 인터페이스로부터 생성되었는지 판별

```

인스턴스이름 instanceof 클래스또는인터페이스이름

```

* 상속에 대한 이해 필요