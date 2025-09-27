

## **Hello and name Printer**

import java.io.\*;

import java.util.\*;



public class Solution {



    public static void main(String\[] args) {

       System.out.println("Hello");

        Scanner a = new Scanner(System.in);

        String b = a.nextLine();

        System.out.println(b);

    }

}









## **Value Performance**

import java.io.\*;

import java.util.\*;



public class Solution {



    public static void main(String\[] args) {

        Scanner a = new Scanner(System.in);

        int b = a.nextInt();

        float c = a.nextFloat();

        System.out.println(b);

        System.out.printf("%.2f",c);

    }

}







## 

## **Execute the word with a Statement**

import java.io.\*;

import java.util.\*;



public class Solution {



    public static void main(String\[] args) {

        Scanner a = new Scanner(System.in);

        String b = a.next();

        System.out.println("May I know how to learn " + b + "!!!...");

        /\* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. \*/

    }

}







## **Execute the String Statement**

import java.io.\*;

import java.util.\*;



public class Solution {



    public static void main(String\[] args) {

        /\* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. \*/

        Scanner a = new Scanner(System.in);

        String b = a.nextLine();

        System.out.println("Hai " + b + "!    Welcome to Programming Language...");

    }

}





## 

## **Math Functions**

import java.io.\*;

import java.util.\*;

import java.math.\*;



 public class Solution {



    public static void main(String\[] args) {

       Scanner a = new Scanner(System.in);

        float b = a.nextFloat();

        int c = a.nextInt();

        int d = a.nextInt();

        double e = a.nextInt();

        System.out.println(+ (int)Math.floor(b));

        System.out.println(+ (int)Math.ceil(b));

        System.out.println(+ (int)Math.sqrt(c));

        System.out.println(+ (int)Math.pow(d,e));

    }

}









## **Float Formation**

import java.io.\*;

import java.util.\*;



public class Solution {



    public static void main(String\[] args) {

        /\* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. \*/

        Scanner a = new Scanner(System.in);

        float b = a.nextFloat();

        System.out.printf("%.6f\\n", b);

        System.out.printf("%.4f\\n", b);

        System.out.printf("%.2f\\n", b);

        System.out.printf("%.0f\\n", b);

    }

}

## **THREE IDIOTS**

import java.io.\*;

import java.util.\*;



public class Solution {



    public static void main(String\[] args) {

    Scanner a = new Scanner(System.in);

        int b = a.nextInt();

        int c = a.nextInt();

        int d = a.nextInt();

        int e = a.nextInt();

        double x = (b + d)/2.0;

        double y = (c + e)/2.0;

        System.out.printf("Binoy's house is located at (%.1f,%.1f)",x,y);

    }

}













## **PROFIT CALCULATOR**

import java.io.\*;

import java.util.\*;



public class Solution {



    public static void main(String\[] args) {

        /\* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. \*/

        Scanner y = new Scanner(System.in);

        int x = y.nextInt();

        int a  = y.nextInt();

        int b = y.nextInt();

        double profit = (x\*a)-(x\*b)-100;

        System.out.println("Number of copies sold:" + x);

        System.out.println("Cost of each copy:" + a);

        System.out.println("Cost spent by agency on each newspaper:" + b);

        System.out.printf("The profit obtained is Rs.%.2f\\n", profit);

    }

}





## **Alice in wonderland**

import java.io.\*;

import java.util.\*;



public class Solution {



    public static void main(String\[] args) {

        Scanner x = new Scanner(System.in);

        int a = x.nextInt();

        int sum = 0;

        System.out.println("Bird said:" + a);

        while(a > 0){

            int digit = a % 10;

            sum += digit;

            a /= 10;

        }

            System.out.println("Alice must go in path-" + sum);

 

        /\* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. \*/

    }

}







## 

## **Area and Perimeter of Triangle**

import java.io.\*;

import java.util.\*;



public class Solution {



    public static void main(String\[] args) {

        Scanner x = new Scanner(System.in);

        int a = x.nextInt();

        int b = x.nextInt();

        int c = x.nextInt();

        int d = x.nextInt();

        int e = x.nextInt();

        double area = (a\*b)/2;

        double perimeter = c + d + e;

        System.out.printf("Area of Triangle is %.2f\\n", area);

        System.out.printf("Perimeter of Triangle is %.2f\\n", perimeter);

 

    }

}







## **Time 24**

import java.io.\*;

import java.util.\*;



public class Solution {



    public static void main(String\[] args) {

       Scanner x = new Scanner(System.in);

        int a = x.nextInt();

        int b = x.nextInt();

        int c = x.nextInt();

        while ( c > 60){

            b++;

            c = c-60;

        }

        while( b > 60){

            a++;

            b = b - 60;

        }

 

        System.out.println("Total Number of hours is " + a);

        System.out.println("Total Number of minutes is " + b);

        System.out.println("Total Number of seconds is " + c);

        }

}





## 

## **Salary Computation**

import java.util.Scanner;

public class Solution {

&nbsp;   public static double calculateGrossSalary(int basicSalary) {

&nbsp;       double hra, da;



&nbsp;       if (basicSalary < 15000) {

&nbsp;           hra = 0.15 \* basicSalary;

&nbsp;           da = 0.90 \* basicSalary;

&nbsp;       } else {

&nbsp;           hra = 5000;

&nbsp;           da = 0.98 \* basicSalary;

&nbsp;       }



&nbsp;       return basicSalary + hra + da;

&nbsp;   }



&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner scanner = new Scanner(System.in);

&nbsp;       int basicSalary = scanner.nextInt();

&nbsp;       scanner.close();



&nbsp;       double grossSalary = calculateGrossSalary(basicSalary);



&nbsp;       // Print output formatted to 2 decimal places

&nbsp;       System.out.printf("%.2f\\n", grossSalary);

&nbsp;   }

}



## **Grading System**

import java.io.\*;

import java.util.\*;



public class Solution {



&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       String a = sc.next();

&nbsp;       int b = sc.nextInt();

&nbsp;       int c = sc.nextInt();

&nbsp;       int d = sc.nextInt();

&nbsp;       int e = sc.nextInt();

&nbsp;       int f = sc.nextInt();

&nbsp;       int Total = b + c + d + e + f;

&nbsp;       float avg = Total/5.0f;

&nbsp;       System.out.println("Name of the Student:"+a);

&nbsp;       System.out.println("Total Mark:"+Total);

&nbsp;       System.out.println("Average Mark:"+avg);

&nbsp;       if(avg >= 95){

&nbsp;           System.out.println("Grade Mark:A");

&nbsp;       }else if(avg >= 75){

&nbsp;           System.out.println("Grade Mark:B");

&nbsp;       }else if(avg >= 50){

&nbsp;           System.out.println("Grade Mark:C");

&nbsp;       }else{

&nbsp;           System.out.println("Grade Mark:Fail");

&nbsp;       }

&nbsp;   }

}



## **Weekdays Using Switchcase**

import java.io.\*;

import java.util.\*;



public class Solution {



&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       int a = sc.nextInt();

&nbsp;       switch(a){

&nbsp;       case 1:

&nbsp;       System.out.println("Monday");

&nbsp;       break;

&nbsp;       case 2:

&nbsp;       System.out.println("Tuesday");

&nbsp;       break;

&nbsp;       case 3:

&nbsp;       System.out.println("Wednesday");

&nbsp;       break;

&nbsp;       case 4:

&nbsp;       System.out.println("Thursday");

&nbsp;       break;

&nbsp;       case 5:

&nbsp;       System.out.println("Friday");

&nbsp;       break;

&nbsp;       case 6:

&nbsp;       System.out.println("Saturday");

&nbsp;       break;

&nbsp;       case 7:

&nbsp;       System.out.println("Sunday");

&nbsp;       break;

&nbsp;       default:

&nbsp;       System.out.println("Enter a valid Input");

&nbsp;       }

&nbsp;   }

}



## **Largest of Three Numbers**

import java.io.\*;

import java.util.\*;



public class Solution {



&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       int a = sc.nextInt();

&nbsp;       int b = sc.nextInt();

&nbsp;       int c = sc.nextInt();

&nbsp;       if(a>b \&\& a>c){

&nbsp;           System.out.println("a is largest then b and c");

&nbsp;       }else if(b>a \&\& b>c){

&nbsp;           System.out.println("b is largest then a and c");

&nbsp;       }else{

&nbsp;           System.out.println("c is largest then a and b");

&nbsp;       }

&nbsp;   }

}



## **Arithmetic Calculation-case**

import java.io.\*;

import java.util.\*;



public class Solution {



&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       float a = sc.nextFloat();

&nbsp;       int b = sc.nextInt();

&nbsp;       char c = sc.next().charAt(0);

&nbsp;       switch(c){

&nbsp;               case '+':

&nbsp;               System.out.println("Addition of two number is "+(a+b));

&nbsp;               break;

&nbsp;               case '-':

&nbsp;               System.out.println("Subtraction of two number is "+(a-b));

&nbsp;               break;

&nbsp;               case '\*':

&nbsp;               System.out.println("Multiplication of two number is "+(a\*b));

&nbsp;               break;

&nbsp;               case '/':

&nbsp;               System.out.println("Division of two number is "+(a/b));

&nbsp;               break;

&nbsp;               default:

&nbsp;               System.out.println("Invalid Input");

&nbsp;       }

&nbsp;   }

}

## 

## **Check Number is Positive, Negative, or Zero**

import java.io.\*;

import java.util.\*;



public class Solution {



&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       int b = sc.nextInt();

&nbsp;       if(b>0){

&nbsp;           System.out.println("positive");

&nbsp;       }else if(b<0){

&nbsp;           System.out.println("negative");

&nbsp;       }else{

&nbsp;           System.out.println("zero");

&nbsp;       }

&nbsp;   }

}



# 



## **Harshad number**

import java.io.\*;

import java.util.\*;



public class Solution {



&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       int num = sc.nextInt();

&nbsp;       int copy = num;

&nbsp;       int sum = 0;

&nbsp;       while(num>0){

&nbsp;           int d = num%10;

&nbsp;           num/=10;

&nbsp;           sum+=d;

&nbsp;       }

&nbsp;       if(copy%sum==0){

&nbsp;           System.out.println("Harshad Number");

&nbsp;       }else{

&nbsp;           System.out.println("Not Harshad Number");

&nbsp;       }

&nbsp;   }

}

## 

## **Abundant number**

import java.io.\*;

import java.util.\*;



public class Solution {



&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       int num = sc.nextInt();

&nbsp;       int s = 0;

&nbsp;       for(int i=1;i<=num/2;i++){

&nbsp;           if(num%i==0){

&nbsp;               s += i;

&nbsp;           }

&nbsp;       }

&nbsp;       if(s>num){

&nbsp;           System.out.println("Abundant Number");

&nbsp;       }else{

&nbsp;           System.out.println("Not Abundant Number");

&nbsp;       }

&nbsp;       sc.close();

&nbsp;   }

}



## **SUM OF DIGIT**

import java.io.\*;

import java.util.\*;



public class Solution {



&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       int num = sc.nextInt();

&nbsp;       int absNum = Math.abs(num);

&nbsp;       if (absNum < 100) {

&nbsp;           System.out.println("Invalid Input");

&nbsp;           return;

&nbsp;       }

&nbsp;       

&nbsp;       int sum = 0;

&nbsp;       while (absNum > 0) {

&nbsp;           sum += absNum % 10;

&nbsp;           absNum /= 10;

&nbsp;       }

&nbsp;       

&nbsp;       System.out.println("Sum of digit is " + sum);

&nbsp;   }

}



## **Fibonacci series**

import java.io.\*;

import java.util.\*;



public class Solution {



&nbsp;   public static void main(String\[] args) {

&nbsp;   Scanner sc = new Scanner(System.in);

&nbsp;       int n= sc.nextInt();

&nbsp;       int m = sc.nextInt();

&nbsp;       if(n<1 || n>20 || m<1 || m>20){

&nbsp;           System.out.println("Invalid Input");

&nbsp;           return;

&nbsp;       }

&nbsp;       if(n>m){

&nbsp;           int temp =n;

&nbsp;           n=m;

&nbsp;           m=temp;

&nbsp;       }

&nbsp;       int \[] fib= new int\[m];

&nbsp;       fib\[0]=0;

&nbsp;       if(m>1) fib\[1]=1;

&nbsp;       for(int i=2;i<m;i++){

&nbsp;           fib\[i]=fib\[i-1]+fib\[i-2];

&nbsp;       }

&nbsp;       int sum=0;

&nbsp;       for(int i=n-1;i<m;i++){

&nbsp;           sum+=fib\[i];

&nbsp;       }

&nbsp;       System.out.println("The Sum of Fibonacci value is "+(sum\*1.0));

&nbsp;   }

}



## **Multiplication table**

import java.io.\*;

import java.util.\*;



public class Solution {



&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       int n = sc.nextInt();

&nbsp;       if(n>=1 \&\& n<=9){

&nbsp;           for(int i=1;i<=n;i++){

&nbsp;               System.out.println(n+" x "+i+" = "+(n\*i)+" ");

&nbsp;           }

&nbsp;       }else{

&nbsp;            System.out.println("Invalid Input");

&nbsp;       }

&nbsp;   }

}





## **Youngest-oldest**

import java.io.\*;

import java.util.\*;



public class Solution {



&nbsp;   public static void main(String\[] args) {

&nbsp;     Scanner sc = new Scanner(System.in);

&nbsp;     int n = sc.nextInt();

&nbsp;     int a\[] = new int\[n];

&nbsp;     for(int i=0;i<n;i++){

&nbsp;         a\[i] = sc.nextInt();

&nbsp;     }

&nbsp;       int Youngest = a\[0];

&nbsp;       int Oldest = a\[0];

&nbsp;       for(int i=1;i<n;i++){

&nbsp;           if(a\[i]>Oldest){

&nbsp;               Oldest=a\[i];

&nbsp;           }if(a\[i]<Youngest){

&nbsp;               Youngest = a\[i];

&nbsp;           }

&nbsp;       }

&nbsp;       System.out.println("Youngest="+Youngest);

&nbsp;       System.out.println("Oldest="+Oldest);

&nbsp;   }

}

## 

## **Array 176**

import java.io.\*;

import java.util.\*;



public class Solution {



&nbsp;   public static void main(String\[] args) {

&nbsp;        Scanner sc = new Scanner(System.in);

&nbsp;       int n = sc.nextInt();

&nbsp;       int a\[] = new int\[n];

&nbsp;       for(int i=0;i<n;i++){

&nbsp;           a\[i] = sc.nextInt();

&nbsp;       }

&nbsp;           int add = sc.nextInt();

&nbsp;           int index = -1;

&nbsp;       for(int i=0;i<n;i++){

&nbsp;           if(a\[i]==add){

&nbsp;               index = i;

&nbsp;           }

&nbsp;       }

&nbsp;       if(index==-1){

&nbsp;           System.out.println("-1");

&nbsp;       }else{

&nbsp;   System.out.printf("Door Number is %03d-DN\\n",index);

}

&nbsp;   }

}



## **Count the Positive and Negative Integer Number**

import java.io.\*;

import java.util.\*;



public class Solution {



&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       int n = sc.nextInt();

&nbsp;       int\[] a = new int\[n];

&nbsp;       for(int i=0;i<n;i++){

&nbsp;           a\[i] = sc.nextInt();

&nbsp;       }

&nbsp;       int s=0;

&nbsp;       int t=0;

&nbsp;       for(int num:a){

&nbsp;           if(num>0){

&nbsp;               s++;

&nbsp;       }else if(num<0){

&nbsp;               t++;

&nbsp;           }

&nbsp;       }

&nbsp;           System.out.printf("Count of Positive Integer is %.2f\\n",(double)s);

&nbsp;           System.out.printf("Count of Negative Integer is %.2f\\n",(double)t);

&nbsp;       }

&nbsp;   }





## **Reverse of String 2**



import java.io.\*;

import java.util.\*;

import java.text.\*;

import java.math.\*;

import java.util.regex.\*;



public class Solution {



&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       String s=sc.next();

&nbsp;        for( int i=s.length()- 1;i>=0;i--)

&nbsp;        {

&nbsp;         System.out.print(s.charAt(i));   

&nbsp;        }

&nbsp;       

&nbsp;   }

}









## **Delete the blank space 1**



import java.io.\*;

import java.util.\*;



public class Solution {



&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       String input = sc.nextLine();           

&nbsp;       String output = input.replace(" ", ""); 

&nbsp;       System.out.println(output);            

&nbsp;       sc.close();

&nbsp;   }

}



## **Delete the vowels 1**



import java.util.\*;



public class Solution {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       String input = sc.nextLine();  

&nbsp;       

&nbsp;       String output = input.replaceAll("\[aeiouAEIOU]", "");

&nbsp;       

&nbsp;       System.out.println(output);  

&nbsp;       sc.close();

&nbsp;   }

}





## 

## **Concatenate the string 1**





import java.io.\*;

import java.util.\*;



public class Solution {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       String first = sc.hasNextLine() ? sc.nextLine() : "";

&nbsp;       String second = sc.hasNextLine() ? sc.nextLine() : "";

&nbsp;       System.out.println(first.trim() + second.trim());

&nbsp;       sc.close();

&nbsp;   }

}





## **Count the vowels 7**





import java.io.\*;

import java.util.\*;



public class Solution {



&nbsp;   public static void main(String\[] args) {

&nbsp;       

&nbsp;       Scanner scanner = new Scanner(System.in);

&nbsp;       

&nbsp;       

&nbsp;       String inputString = scanner.nextLine();

&nbsp;       

&nbsp;      

&nbsp;       int vowelCount = 0;

&nbsp;       

&nbsp;    

&nbsp;       String lowerCaseString = inputString.toLowerCase();

&nbsp;       

&nbsp;     

&nbsp;       for (int i = 0; i < lowerCaseString.length(); i++) {

&nbsp;           char ch = lowerCaseString.charAt(i);

&nbsp;           

&nbsp;           

&nbsp;           if (ch == 'a' || ch == 'e' || ch == 'i' || ch == 'o' || ch == 'u') {

&nbsp;               vowelCount++;

&nbsp;           }

&nbsp;       }

&nbsp;       



&nbsp;       System.out.println(vowelCount);

&nbsp;       

&nbsp;       

&nbsp;       scanner.close();

&nbsp;   }

}









## **Count each character in the string 1**









import java.io.\*;

import java.util.\*;



public class Solution {



&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner scanner = new Scanner(System.in);

&nbsp;       String inputString = scanner.nextLine();

&nbsp;       Map<Character, Integer> charCountMap = new LinkedHashMap<>();

&nbsp;       for (char ch : inputString.toCharArray()) {

&nbsp;           charCountMap.put(ch, charCountMap.getOrDefault(ch, 0) + 1);

&nbsp;       }



&nbsp;       for (Map.Entry<Character, Integer> entry : charCountMap.entrySet()) {

&nbsp;           System.out.println(entry.getKey() + "   " + entry.getValue());

&nbsp;       }



&nbsp;       

&nbsp;       System.out.println();

&nbsp;       scanner.close();

&nbsp;   }

}









## **Count vowels, consonants, digits, special characters**













import java.io.\*;

import java.util.\*;



public class Solution {



&nbsp;   public static void main(String\[] args) {

&nbsp;       /\* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. \*/

&nbsp;       Scanner scanner = new Scanner(System.in);

&nbsp;       String str = scanner.nextLine();

&nbsp;       

&nbsp;       int vowels = 0;

&nbsp;       int consonants = 0;

&nbsp;       int digits = 0;

&nbsp;       int specialCharacters = 0;

&nbsp;       

&nbsp;       str = str.toLowerCase();

&nbsp;       

&nbsp;       for (int i = 0; i < str.length(); i++) {

&nbsp;           char ch = str.charAt(i);

&nbsp;           

&nbsp;           if (ch >= 'a' \&\& ch <= 'z') {

&nbsp;               if (ch == 'a' || ch == 'e' || ch == 'i' || ch == 'o' || ch == 'u') {

&nbsp;                   vowels++;

&nbsp;               } else {

&nbsp;                   consonants++;

&nbsp;               }

&nbsp;           } else if (ch >= '0' \&\& ch <= '9') {

&nbsp;               digits++;

&nbsp;           } else {

&nbsp;               specialCharacters++;

&nbsp;           }

&nbsp;       }

&nbsp;       

&nbsp;       System.out.println("vowels:" + vowels);

&nbsp;       System.out.println("consonants:" + consonants);

&nbsp;       System.out.println("digits:" + digits);

&nbsp;       System.out.println("special characters:" + specialCharacters);

&nbsp;       

&nbsp;       scanner.close();

&nbsp;   }

}





## **Check if string contains only digits 2**







import java.io.\*;

import java.util.\*;



public class Solution {



&nbsp;   public static void main(String\[] args) {

&nbsp;       /\* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. \*/

&nbsp;       Scanner scanner = new Scanner(System.in);

&nbsp;       String input = scanner.nextLine();

&nbsp;       

&nbsp;       boolean onlyDigits = true;

&nbsp;       

&nbsp;       for (int i = 0; i < input.length(); i++) {

&nbsp;           char ch = input.charAt(i);

&nbsp;           if (!Character.isDigit(ch)) {

&nbsp;               onlyDigits = false;

&nbsp;               break;

&nbsp;           }

&nbsp;       }

&nbsp;       

&nbsp;       if (onlyDigits) {

&nbsp;           System.out.println("only digits");

&nbsp;       } else {

&nbsp;           System.out.println("no");

&nbsp;       }

&nbsp;       

&nbsp;       scanner.close();

&nbsp;   }

}





## **String anagram 6**



import java.io.\*;

import java.util.\*;



public class Solution {



&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner scanner = new Scanner(System.in);

&nbsp;       String input1 = scanner.nextLine();

&nbsp;       String input2 = scanner.nextLine();



&nbsp;       

&nbsp;       if (input1.length() != input2.length()) {

&nbsp;           System.out.println("The given strings are not an anagram");

&nbsp;           scanner.close();

&nbsp;           return;

&nbsp;       }

&nbsp;       char\[] array1 = input1.toCharArray();

&nbsp;       char\[] array2 = input2.toCharArray();



&nbsp;       Arrays.sort(array1);

&nbsp;       Arrays.sort(array2);



&nbsp;       if (Arrays.equals(array1, array2)) {

&nbsp;           System.out.println("The given strings are an anagram");

&nbsp;       } else {

&nbsp;           System.out.println("The given strings are not an anagram");

&nbsp;       }

&nbsp;       scanner.close();

&nbsp;   }



}









## &nbsp;       **Practice Questions**



## **1)**

public class Main

{

&nbsp;	public static void main(String\[] args) {

&nbsp;		System.out.println("Hello World");

&nbsp;	}

}

## **2)**

public class Main{

&nbsp;   public static void main(String\[] args)

&nbsp;   {

&nbsp;       for(int i = 0 ; i < 3 ; i++){

&nbsp;           System.out.println("I need coffee too!!");

&nbsp;       }

&nbsp;   }

}

## **3)**

import java.util.Scanner;

public class Main{

&nbsp;   public static void main(String\[] args){

&nbsp;       Scanner scanner = new Scanner(System.in);

&nbsp;       String name = scanner.nextLine();

&nbsp;   

&nbsp;       System.out.println("Welcome " +name);

&nbsp;   }

}

## **4)**

{

&nbsp;   public static void main(String\[] args)

&nbsp;   {

&nbsp;       System.out.println("Enter the details");

&nbsp;       Scanner a = new Scanner(System.in);

&nbsp;       String name = a.nextLine();

&nbsp;       int age = a.nextInt();

&nbsp;       float cgpa = a.nextFloat();

&nbsp;       System.out.println("Name: " + name);

&nbsp;       System.out.println("Age: "  + age);

&nbsp;       System.out.println("CGPA " + cgpa);

&nbsp;   }

}

## 5\)

import java.util.Scanner;

public class Main{

&nbsp;   public static void main(String\[] args){

&nbsp;       Scanner a = new Scanner(System.in);

&nbsp;       int age = a.nextInt();

&nbsp;       String name = a.next();

&nbsp;       System.out.println("User Details: ");

&nbsp;       System.out.println("Name: " + name);

&nbsp;       System.out.println("Age: " + age);

&nbsp;   }

## }

## **6)**

import java.util.Scanner;

public class Main{

&nbsp;   public static void main(String\[] args){

&nbsp;       Scanner a = new Scanner(System.in);

&nbsp;       String name = a.nextLine();

&nbsp;       String membership = a.nextLine();

&nbsp;       System.out.println("Member Name: " + name);

&nbsp;       System.out.println("Selected Membership: " + membership);

&nbsp;   }

}

## **7)**

import java.util.Scanner;

public class Main{

&nbsp;   public static void main(String\[] args){

&nbsp;       Scanner a = new Scanner(System.in);

&nbsp;       int length = a.nextInt();

&nbsp;       int breadth = a.nextInt();

&nbsp;       int perimeter = 2\*(length + breadth);

&nbsp;       int area = length \* breadth;

&nbsp;       System.out.println("The required length is: " + perimeter + "m");

&nbsp;        System.out.println("The required of carpet is: " + area + "sqm");

&nbsp;   }

}

## **8)**

import java.util.Scanner;

public class Main{

&nbsp;   public static void main(String\[] args){

&nbsp;       Scanner a = new Scanner(System.in);

&nbsp;       int r = a.nextInt();

&nbsp;       int h = a.nextInt();

&nbsp;       double ans =3.14 \* r \* r \* h;

&nbsp;       System.out.println(ans);



&nbsp;   }

}

## **9)**

import java.util.Scanner;

public class Main{

&nbsp;   public static void main(String\[] args){

&nbsp;       Scanner a = new Scanner(System.in);

&nbsp;       int N = a.nextInt();

&nbsp;      

&nbsp;       double ans = N \* 60;

&nbsp;       System.out.println(ans);



&nbsp;   }

## }

## **10)**

import java.util.Scanner;

public class Main{

&nbsp;   public static void main(String\[] args){

&nbsp;       Scanner a = new Scanner(System.in);

&nbsp;       int N = a.nextInt();

&nbsp;       int M = a.nextInt();

&nbsp;       int O = N \* M;

&nbsp;       if(O <= 12){

&nbsp;       System.out.println(O);

&nbsp;       }else{

&nbsp;           System.out.println(O-12);

&nbsp;       }

&nbsp;       

}

}

















