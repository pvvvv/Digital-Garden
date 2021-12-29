마크다운 설명서 간단버전
===
##### MarkDown이란? 일반 텍스트로 서식이 있는 문서를 작성하는 데 사용되며, 일반 마크업 언어에 비해 문법이 쉽고 간단한 것이 특징이다.



# 간단한 사용설명!

### 샵(#)이 많아질수록 글씨 크기가 줄어듭니다.

* 별(*)을 쓰고 띄우면 순서가 없는 리스트가 작성됩니다

  **볼드는 별이 앞뒤로 두개!!**

--- 
마이너스(-) 세개는 위에 보는것처럼 줄이 하나 생깁니다

> '>'이건
>> 개수를 늘려가며
>>> 이렇게 사용하면 됩니다

1. 순서를 나타내주는
2. 문법인데 크게 다를건
3. 없는거 같습니다
5. 여기는 5라고 썼는데 4라고 순서를 맞춰서 나오네요 
   
---

pre + code태그 또는 백틱(`) 세개를 쓰면 코드를 작성 할 수 있는 박스가 나옵니다 
<pre>
    <code>
        여기 안에 코드를 넣으면 된다고 합니다.
    </code>
</pre>

```
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
```
---
백틱(`) 뒤에 언어를 넣으면 문법강조가 가능합니다
```java
public class a {
  public static void main(String[] args) {
    System.out.println("Hello, MarkDown");
  }
}
```

**띄어쓰기 세번**이면 줄이   바뀐다고 하더니 안바뀝니다.

"[markdown](MarkDown.md)"
"[ ]""( )"를 사용하면 링크를 걸수있습니다
