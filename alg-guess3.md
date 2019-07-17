**300**

Угадайте алгоритм:

```c
void fun(size_t s, int a[s])
{
   for(size_t i = 0; i < s; ++i){
      int ai = a[i];
      for(size_t j = i; j < s; ++j) {
         if (ai > a[j]) {
            swap(a, i, j);
            ai = a[i];
         }
      }
   }
}
```

_Время: 3 минуты_
