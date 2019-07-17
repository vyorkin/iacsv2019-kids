**100**

Угадайте алгоритм:

```c
unsigned fun(unsigned a, unsigned b)
{
   if (b == 0)
      return a;

   return fun(b, a % b);
}
```

_Время: 2 минуты_
