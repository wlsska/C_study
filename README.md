# C
.[네이버]_(https://naver.com)_
```c
#include <stdio.h>

int main()
{
  int a = 10;
  int b = 20;
  int c = a + b;
  
  printf("%d + %d = %d\n", 10, 20,30);
  printf("%d - %d = %d\n", a,b,c);

  
  return 0;
}

#include <stdio.h>

int main()
{
  int a ;
  int b ;
  int c = 0;
  scanf("%d %d", &a, &b);
  
  printf("%d + %d = %d\n", a, b,c);
  c = a - b;
  printf("%d - %d = %d\n",  a, b,c);
  c = a * b;
  printf("%d * %d = %d\n", a, b,c);
  c = a / b;
  printf("%d / %d = %d\n", a, b,c);
  
  
  
  
  return 0;

}


#include <stdio.h>

int main()
{
  int a ;
  int b;
  printf ("두 수를 입력하시오.");
  scanf("%d %d ", &a ,&b);

  printf("%d + %d = %d\n", a,b , a+b);
  printf("%d * %d= %d\n", a,b, a*b);
 
  
  
  
  
  return 0;
}
조건문 조건이 참일떄 특정 코드를 실행시킴
반복문 조건이 참일떄 특정 코드를 반복시킴
변수: 변하는 수를 컴퓨터 메모리 담아 놓을 수 있는 공간
%d -> 정수
%f -> 실수 (flat)
%lf -> 실수 (double)
%c -> 문자(char)
%s -> 문자열 (char [] 배열)
