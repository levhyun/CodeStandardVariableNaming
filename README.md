# CodeStandardVariableNaming

- [**Snakecase**](snaker-case)
- [**Pascal case**](pascal-case)
- [**Camel case**](camel-case)
- [**Kebab case**](kebab-case)
- [**Hungarian Notation**](hungarian-notation)

#

<br>
<br>
<br>

# Snaker Case
### [ 스네이크 케이스 ]
<br>
모든 문자는 소문자이며 복합어(단어) 사이를 ‘_‘를 사용하여 구분(연결)한다.<br>
포트홀 케이스라고도 합니다.
<br>
<br>

```

snake_case = "This is snake case."

```

<br>
<br>
<br>

# Pascal Case
### [ 파스칼 케이스 ]
<br>
모든 새 복합어(단어)의 첫 글자와 함께 변수의 첫 글자는 대문자를 사용한다.<br>
일부 언어는 관습적으로 클래스명만 대문자로 시작하는 암묵적인 규칙이 있기에 주위하야 한다.
<br>
<br>

```

SnakeCase = "This is pascal case."

```

<br>
<br>
<br>

# Camel Case
### [ 카멜 케이스 ]
<br>
첫 단어의 첫글자는 소문자를 이용하고 두번째 단어부터 첫글자를 대문자로 이용한다. 
<br>
<br>

```

snakeCase = "This is camel case."

```

<br>
<br>
<br>

# Kebab Case
### [ 케밥 케이스 ]
<br>
모든 문자는 소문자이며 복합어(단어) 사이를 ‘-‘를 사용하여 구분(연결)한다.
<br>
<br>

```

snake-case = "This is kebab case."

```

<br>
<br>
<br>

# Hungarian Notation
### [ 헝가리안 표기법 ]
<br>
변수 이름의 시작 부분에 변수 유형 또는 목적을 설명하고 변수의 기능을 나타낸다.
<br>
<br>

```

szText = "This is Hungarian Notation."

```
<br>

### [ 접두어 ]

<br>

**- 공통**

|접두어|데이터 타입|
|:---:|:---:|
|b|byte, boolean|
|n|int, short|
|i|int, short (주로 인덱스로 사용)|
|c|int, short (주로 크기로 사용)|
|l|long|
|f|float|
|d, db|double|
|ld|long double|
|w|word|
|dw|double word|
|qw|quad word|
|ch|char|
|sz|NULL로 끝나는 문자열|
|str|C++ 문자열|
|arr|배열 (문자열 제외): 다른 접두어와 조합 가능|
|p|포인터 (16비트, 32비트): 다른 접두어와 조합 가능|
|lp|포인터 (32비트, 64비트): 다른 접두어와 조합 가능|
|psz|NULL로 끝나는 문자열을 가리키는 포인터 (16비트, 32비트)|
|lpsz|NULL로 끝나는 문자열을 가리키는 포인터 (32비트[2], 64비트)|
|fn|함수 타입|
|pfn|함수 포인터 (16비트, 32비트)|
|lpfn|함수 포인터 (64비트)|

<br>

**- OOP**

|접두어|데이터 타입|
|:---:|:---:|
|g_|네임스페이스의 글로별 변수|
|m_|클래스의 멤버 변수|
|s_|클래스의 static 변수|
|c_|함수의 static 변수|

<br>

**- Windows API**

|접두어|데이터 타입|
|:---:|:---:|
|h|리소스 핸들 (HWND를 제외한 모든 HANDLE 타입)|