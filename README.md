# OOP2026
### Homework1
```java
public class homework1{

	public static void main(String[] args) {
        int i , j;
        for(i=0; i<=10; i++) {
            for(j=0; j<=i; j++) {
            System.out.print("#");
        }
            System.out.print(" ");
            System.out.println();
            }
        for(i=10; i>=0; i--) {
            for(j=0; j<i; j++) {
            System.out.print(" ");
        }
            for(; j<=10; j++) {
            System.out.print("#");
            }
            System.out.println();
        }
        for(i=10; i>=0; i--) {
            for(j=0; j<=i; j++) {
            System.out.print("#");
        }
            for(; j<=10; j++) {
            System.out.print(" ");
        }
            System.out.println();
            }
        for(i=0; i<=10; i++) {
            for(j=0; j<=i-1; j++) {
            System.out.print(" ");
        }
            for(; j<=10; j++) {
            System.out.print("#");
        }
            System.out.println();
            }

	}

}
```
![Alt homework11](./homework1.jpg)
# OOP2026
### Homework2
```java
public class homework2 {
    public static void main(String[] args) {
        long[] fib = new long[20];
        fib[0] = 1;
        fib[1] = 1;

        for (int i = 2; i < 20; i++) {
            fib[i] = fib[i - 1] + fib[i - 2];
        }

        for (int i = 0; i < 20; i++) {
            System.out.print(fib[i] + " ");
        }
    }
}
```
![Alt homework11](./homework2.jpg)
# OOP2026
### Homework3
```java
public class homework3 {
    public static void main(String[] args) {
        long[] fib = new long[22];
        fib[0] = 1;
        fib[1] = 1;

        for (int i = 2; i < 22; i++) {
            fib[i] = fib[i - 1] + fib[i - 2];
        }

        for (int i = 1; i <= 20; i++) {
            double ratio = (double) fib[i + 1] / fib[i];
            System.out.println(fib[i + 1] + "/" + fib[i] + "=" + ratio);
        }
    }
}
```
![Alt homework11](./homework3.jpg)
# OOP2026
### Homework4
```java
public class homework4 {
    public static void main(String[] args) {
        for (int row = 1; row <= 9; row++) {
            for (int col = 1; col <= 9; col++) {
                System.out.print(col + "*" + row + "=" + (col * row) + "\t");
            }
            System.out.println();
        }
    }
}
```
![Alt homework11](./homework4.jpg)
# OOP2026
### Homework5-1
```java

public class homework5 {
	public static void main(String []args){
		int n;
		int j =1;
		int i= 4;
		double pi =(double) i / j;
		System.out.println(i + '/'+ j);
		for(n=1;n<10000;n++) {
			j += 2;
			if (n % 2 == 1) {
				System.out.println(" - " + i+ '/'+ j);
				pi -= (double) i / j;
			} else {
				System.out.println(" + " + i+ '/'+ j);
				pi +=(double) i / j;
			}
			

		}
		System.out.println("\n");
		System.out.println("pi = "+ pi);
	}


}
```
![Alt homework11](./homework5-1.jpg)
# OOP2026
### Homework5-2
```java
public class homework6 {
	public static void main(String []args){
		int n;
		int j =1;
		int i= 3;
		double pi =(double) i / j;
		System.out.println(Math.sqrt(12));
		System.out.println("(1");
		pi = 1;
		for(n=1;n<50;n++) {
			if (n % 2 == 1) {
				System.out.println(" - " + 1+ '/'+ i * Math.pow(3,j));
				pi -= (double) 1 / (i * Math.pow(3,j));
			} else {
				System.out.println(" + " + 1+ '/'+ i * Math.pow(3,j));
				pi +=(double) 1 / (i * Math.pow(3,j))
						;
			}
			i += 2;
			j += 1;
		}
		
		System.out.print(')');
		System.out.println("\n");
		pi = Math.sqrt(12) * pi;
		
		System.out.println("pi = "+ pi);
	}


}
```
![Alt homework11](./homework5-2.jpg)

