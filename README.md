# Java Coding Tip


#### Bit shift
```java
int a = 2_000_000_000;
int b = 1_000_000_000;
System.out.println((a + b) / 2);
System.out.println((a + b) >> 1);
System.out.println(a + (b - a) / 2);
System.out.println((a + b) >>> 1);
```
```
OUTPUT:
-647483648
-647483648
1500000000
1500000000
```
