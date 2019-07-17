**300**

Угадайте алгоритм:

```c
int *fun(int *base, int n, int key)
{
   int l = 0;
   int h = n - 1;

   while (l <= h) {
      int m = (l + h) / 2;
      int val = base[m];

      if (val < key) {
         l = m + 1;
      } else if (val > key) {
         h = m - 1;
      } else {
         return base + m;
      }
   }

   return NULL;
}
```

_Время: 3 минуты_
