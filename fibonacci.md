# What is Fibonacci sequence?
수학에서 다루는 수열. 이 수열의 항들을 피보나치 수(Fibonacci number)라 부른다.

## recurrence relation
F(0) = 0, F(1) = 1, F(n+2) = F(n+1) + F(n)

## Example fibonacci

```java
public class fibonacci {
	public static void main(String[] args) {

		int num1 = 1;
		int num2 = 1;
		int num3 = 0;
	        System.out.print(num1 + ", " + num2);

       		for (int i = 0; i < 8; i++) {
            		num3 = num1 + num2;
            		System.out.print(", " + num3);
            		num1 = num2;
            		num2 = num3;
       		}
	}
}
```
