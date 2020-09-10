 
#  |Java Practice Programs |


### 1. *Write a Program to Addition of two Number in Java* .

```java
import java.util.Scanner;

public class Main
{
	public static void main(String[] args) {
	    Scanner input=new Scanner(System.in);
	    System.out.println("************SUM OF TWO NUMBER*************");
	
		System.out.print("ENTER THE FIRST NUMBER :");
		int num1=input.nextInt();
		
		System.out.print("ENTER THE SECOND  NUMBER :");
		int num2=input.nextInt();
		
		int sum=num1+num2;
		
		System.out.println("Sum is : "+sum);
	}
}
```
**OutPut**  : 

```java 
************SUM OF TWO NUMBER*************

ENTER THE FIRST NUMBER :23
ENTER THE SECOND NUMBER :2

Sum is : 25
```
### 2 . *Write a Program to Find the Factorial Of Number in Java*.
```java
import java.util.Scanner;
public class Main
{
  public static void main (String[]args)
  {
    Scanner a = new Scanner (System.in);
      System.out.println (".............FACTORIAL FINDER..............");
      System.out.print ("ENTER THE NUMBER :");
    int number = a.nextInt ();
    int i, f = 1;
    for (i = 1; i <= number; i++)
      {
	     f *= i;
      }
    System.out.println ("FACTORIAL IS :" + f);
  }
}
```
**OutPut** :
```java
.............FACTORIAL FINDER................

ENTER THE NUMBER :6
FACTORIAL IS :720
```

| Sr No.       | Program  | Developed By   |Year|Sr No.       | Program  | Developed By   |Year| Uses For |
| :-:| :------: | :------------: |:--:| :-:| :------: | :------------: |:--:|:-:|
| 1 | Java Program|  **James Gosling** |1994|1 | Java Program|  **James Gosling** |1994| Android app |
| 2         | C Program    |  **Dennis Ritchie** |1970|2         | C Program    |  **Dennis Ritchie** |1970| Compilers and Assemblers|
 


