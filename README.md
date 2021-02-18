### java 实现 笛卡尔积

参考地址：https://www.cnblogs.com/rollenholt/p/3628362.html

```java
public class CartesianProductUtil {
 
    public static void main(String[] args) {
        ImmutableSet<Character> charList = ImmutableSet.of('a', 'b', 'c');
        Set<List<Character>> set = Sets.cartesianProduct(charList, charList, charList);
        for (List<Character> characters : set) {
            System.out.println(characters);
        }
    }
}
```

### 效果图

![](https://i.loli.net/2021/02/18/lkBJtLOMg9ve3Xs.png)
