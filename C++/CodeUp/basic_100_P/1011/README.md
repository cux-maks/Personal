1011
## 문제
#### 문자형(char)으로 변수를 하나 선언하고, 변수에 문자를 저장한 후
#### 변수에 저장되어 있는 문자를 그대로 출력해보자.

###### \<c\>
```c
#include <stdio.h>

int main() {

	char a;
	scanf("%c", &a);
	printf("%c", a);
	return 0;

}
```

###### \<c++\>
```c++
#include <iostream>

using namespace std;

int main() {

	char s;

	cin >> s;
	cout << s << endl;

	return 0;

}

```
