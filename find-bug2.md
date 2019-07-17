**200**

Найти ошибку в коде (подобрать такие входные значения, чтобы она
сработала).

```c
int max_in_array(size_t s, int a[s])
{
  int max = INT_MIN;
  for (size_t i = 0; i <= s; ++s)
    if (a[i] > max)
      max = a[i];
  return max;
}
```

_Время: 3 минуты_
