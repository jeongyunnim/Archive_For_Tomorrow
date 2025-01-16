---
날짜: 2025-01-14
넘버: 
태그: 프로그래밍
출처: 
aliases:
---
### 날짜:  2025-01-14 00:46

### 태그: #프로그래밍 

>[!메모]
>

### 원문
---
# printf()에서 double을 f로 읽기 가능한가
double은 지수 부분만 늘린 것이기 때문에, float으로 읽어도 상관 없다.
하지만 printf의 가변 인자의 작동은 문제가 없는가?
- 없다. 왜냐하면 가변인자로 float을 전달받은 경우, double로 형변환이 일어나서 8바이트를 갖게 된다.
### ft_printf()로 구조를 되새겨보자.
```c
static int	converse_char(va_list ap, int c, int *count)
{
	char	print_char;
	int		temp;

	temp = *count;
	if (c == 'c')
	{
		print_char = va_arg(ap, int);
		*count += write(1, &print_char, 1);
		if (*count < temp)
			return (-1);
		return (0);
	}
	else if (c == 's')
		ft_putstr(va_arg(ap, char *), count);
	else if (c == 'd' || c == 'i' || c == 'u')
		ft_itoa(va_arg(ap, int), count, c);
	else if (c == 'x' || c == 'X')
		ft_htoa(va_arg(ap, int), c, count);
	else if (c == 'p')
		ft_ptoa(va_arg(ap, void *), c, count);
	else
		return (-1);
	if (*count < temp)
		return (-1);
	return (0);
}
```


---
### 생각(파생된 질문/생각)

### 출처

### 연결 문서 (연결 이유)
