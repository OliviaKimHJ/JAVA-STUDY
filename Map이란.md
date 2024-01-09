# # Map이란 무엇인가?
> Map인터페이스 : 키와 값을 하나의 쌍으로 저장하는 방식(key-value) 사용
> key-실질적인 값을 찾기 위한 이름의 역할 / value-실질적인 값

### 특징
> key : 중복 값 허용하지 않음
> value : 중복값 허용


## Put
### # HashMap을 통한  put 
```java
HashMap<String, String> map = new HashMap<String, String<();
map.put("cat", "고양이");
map.put("dog", "개");
```
> ### Map Table
> |타입|key|value|
> |-----|----|----|
> |String|cat|고양이|
> |String|dog|개|
>
> Map은 리스나 배욜 처럼 순차적으로 해당 요소 값을 구하지 않고 key를 통해 value를 얻는다.
> 고양이라는 값을 얻고 싶으면 순차적으로 값을 찾는 것이 아닌 cat만 들여다보면 된다.


## get
### # HashMap을 통한 get
> key에 해당하는 값을 얻기 위해서는  map.get("key명")으로 구한다.

```java
System.out.println(map.get("cat"));

```

## containsKey
### # HashMap을 통한 containsKey
> containsKey 메소드는 맵(Map)에 해당 키(key)가 있는지를 조사하여 그 결과값을 리턴한다.

```java
System.out.println(map.containsKey("cat"));

```
> cat이 존재하므로  true를 출력

/*참고 사이트 https://devlogofchris.tistory.com/41 */
