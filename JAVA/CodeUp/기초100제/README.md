# JAVA

1001
```java
public class Main {
	
	public static void main(String[] args) {
		
		System.out.println("Hello");
		
	}
	
}
```

1002
```java
public class Main {
	
	public static void main(String[] args) {
		
		System.out.println("Hello World");
		
	}
	
}
```

1003
```java
public class Main {
	
	public static void main(String[] args) {
		
		System.out.println("Hello\nWorld");
		
	}
	
}
```

1004
```java
public class Main {
	
	public static void main(String[] args) {
		
		System.out.println("\'Hello\'");
		
	}
	
}
```

1005
```java
public class Main {
	
	public static void main(String[] args) {
		
		System.out.println("\"Hello World\"");
		
	}
	
}
```

1006
```java
public class Main {
	
	public static void main(String[] args) {
		
		System.out.println("\"!@#$%^&*()\"");
		
	}
	
}
```

1007
```java
public class Main {
	
	public static void main(String[] args) {
		
		System.out.println("\"C:\\Download\\hello.cpp\"");
		
	}
	
}
```

1008
```java
public class Main {
	
	public static void main(String[] args) {
		
		System.out.print('\u250C');
		System.out.print('\u252C');
		System.out.println('\u2510');
		System.out.print('\u251C');
		System.out.print('\u253C');
		System.out.println('\u2524');
		System.out.print('\u2514');
		System.out.print('\u2534');
		System.out.println('\u2518');
		
	}
	
}
```

1010
```java
import java.util.Scanner;

public class Main {
	
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		
		int num = sc.nextInt();
		
		System.out.println(num);
		
		
	}
	
}
```

1011
```java
import java.util.Scanner;

public class Main {
	
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		
		char c = sc.next().charAt(0);
		
		System.out.println(c);
		
		
	}
	
}
```

1012
```java
import java.util.Scanner;

public class Main {
	
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		
		float c = sc.nextFloat();
		
		System.out.println(String.format("%.6f", c));
		
		
	}
	
}
```

1013
```java
import java.util.Scanner;

public class Main {
	
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		
		int a = sc.nextInt();
		int b = sc.nextInt();
		
		System.out.printf("%d %d", a, b);
		
		
	}
	
}
```

1014
```java
import java.util.Scanner;

public class Main {
	
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		
		char a = sc.next().charAt(0);
		char b = sc.next().charAt(0);
		
		sc.close();
		
		System.out.printf("%c %c", b, a);
		
		
	}
	
}
```

1015
```java
import java.util.Scanner;

public class Main {
	
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		
		float a = sc.nextFloat();
		
		System.out.printf("%.2f", a);
		
		
	}
	
}
```

1017
```java
import java.util.Scanner;

public class Main {
	
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		
		int a = sc.nextInt();
		
		System.out.printf("%d %d %d", a, a, a);
		
		
	}
	
}
```

1018
```java
import java.util.Scanner;

public class Main {
	
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		
		String a = sc.nextLine();
		
		System.out.printf(a);
		
		
	}
	
}
```

1019
```java
import java.util.Scanner;

public class Main {
	
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		
		String str = sc.next();
		String[] arr = str.split("\\.");
		
		int y = Integer.valueOf(arr[0]);
		int m = Integer.valueOf(arr[1]);
		int d = Integer.valueOf(arr[2]);
		
		System.out.printf("%04d.%02d.%02d", y, m, d);
		
	}
	
}
```

1020
```java
import java.util.Scanner;

public class Main {
	
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		
		String str = sc.next();
		String[] arr = str.split("\\-");
		
		System.out.printf("%s%s", arr[0], arr[1]);
		
	}
	
}
```

1021
```java
import java.util.Scanner;

public class Main {
	
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		
		String str = sc.next();
		
		System.out.printf("%s", str);
		
	}
	
}
```

1022
```java
import java.util.Scanner;

public class Main {
	
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);

		String str = sc.nextLine();
		
		System.out.printf("%s", str);
		
	}
	
}
```

1023
```java
import java.util.Scanner;

public class Main {
	
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		
		String str = sc.next();
		String[] arr = str.split("\\.");
		
		System.out.printf("%s\n%s", arr[0], arr[1]);
		
	}
	
}
```

1024
```java
import java.util.Scanner;

public class Main {
	
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		
		String str = sc.nextLine();
		String[] arr = str.split("");
		
		for(int i = 0; i < arr.length; i++) {
			System.out.printf("\'%s\'\n", arr[i]);
		}
		
	}
	
}
```

1025
```java
import java.util.Scanner;

public class Main {
	
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		
		String str = sc.nextLine();
		String[] arr = str.split("");
		
		for(int i = 0; i < arr.length; i++) {
			System.out.printf("[%s", arr[i]);
			for(int j = 0; j < arr.length - 1 - i; j++) {
				System.out.printf("0");
			}
			System.out.printf("]\n");
		}
		
	}
	
}
```
