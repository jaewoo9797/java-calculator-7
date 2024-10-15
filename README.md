# 프리코스 1주차 미션 - 문자열 덧셈 계산기
<p align="center">
    <img src="src/main/resource/logo.png" alt="우아한테크코스" width="250px">
</p>

---

# 문자열 덧셈 계산기
## 🚀 기능 목록 단위
1. 사용자의 입력을 받는다.
다음과 같은 예시 형식으로 출력한다.
```
덧셈할 문자열을 입력해 주세요.
1,2:3
결과 : 6
```

2. 쉼표(,) 또는 콜론(:)을 구분자로 가지는 문자열을 전달하는 경우 구분자를 기준으로 숫자를 분리한다.
```
예 : ""      => "0",
     "1,2"   => "1, 2",
     "1,2,3" => "1,2,3"
```

3. 기본 기분자(쉼표, 콜론) 외에 커스텀 구분자를 지정할 수 있다. 
커스텀 구분자는 문자열 앞부분의 "//"와 "\n" 사이에 위치하는 문자를 커스텀 구분자로 사용한다.
```
예 : "//;\n1;2;3"
커스텀 구분자 = ';' 
```

4. 사용자가 잘못된 값을 입력할 경우 `IllegalArgumentException`을 발생시킨 후 애플리케이션은 종료
