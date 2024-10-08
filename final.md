# Field 'something' may be 'final'

인텔리제에에서 다음과 같은 문제를 만났다.

```java
private String name;
```

위와 같이 변수를 선언하고 파일을 저장하면 인텔리제이에서 자동으로 wanring을 나타내고는 변수 앞에 final을 붙인다.

```java
private final String name;
```

이때 경고창은 보고 싶지만 내가 직접 컨트롤을 하고 싶다면

![스크린샷 2024-10-08 오전 10 49 17](https://github.com/user-attachments/assets/7f9f9043-c2fe-4596-b530-5c2b082a5c4a)

Severity 가 기본으로 warning 이라고 되어 있는데 이것을 Consideration이라고 변경한다.

그러면 경고로 노란 밑줄은 보이지만 인텔리제이가 강제로 final로 변경하지 않는다.
