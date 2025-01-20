# Operators 

public class OPERATORS {
    public static void main(String[] args) {
        // TODO code application logic here
        Scanner sc=new Scanner(System.in);
        System.out.print("enter the first value:");
        int a=sc.nextInt();
        System.out.print("enter the second value:");
        int b=sc.nextInt();
        System.out.print("enter the thrid value:");
        int c=sc.nextInt();
        System.out.print("ARITHMETIC OPERATORS");
        System.out.println("the value of a:"+a);
        System.out.println("the value of b:"+b);
        System.out.println("the value of c:"+c);
        System.out.println("Addition:"+(a+b));
        System.out.println("Subtraction:"+(a-b));
        System.out.println("Multiplication:"+(a*b));
        System.out.println("Division:"+(a/b));
        System.out.println("Modulus:"+a%b);
        System.out.println("RELATIONAL OPERATORS");
        if(a==b)
            System.out.println(+a+"is equal to"+b);
        else
            System.out.println(+a+"is not equal to"+b);
        if(a!=b)
            System.out.println(+a+"is not equal to"+b);
        else
            System.out.println(+a+"is equal to"+b);
        if(a>b)
            System.out.println(+a+"is greater than"+b);
        else
            System.out.println(+a+"is not greater than"+b);
        if(a<b)
            System.out.println(+a+"is lesser than"+b);
        else
            System.out.println(+a+"is not lesser than"+b);
        System.out.println("LOGICAL OPERATORS");
        System.out.println("AND OPERATOR");
        System.out.println((a>b)&&(c>a));
        System.out.println("OR OPERATOR");
        System.out.println((a>b)||(c>a));
        System.out.println("NOT OPERATOR");
        System.out.println(!(a==b));
        System.out.println("TERNARY OPERATOR");
        System.out.println((a==c)?"It is equal":"It is not equal");
    }
    
}

output-

enter the first value:2
enter the second value:3
enter the third value:4
ARITHMETIC OPERATORSthe value of a:2
the value of b:3
the value of c:4
Addition:5
Subtraction:-1
Multiplication:6
Division:0
Modulus:2
RELATIONAL OPERATORS
2is not equal to3
2is not equal to3
2is not greater than3
2is lesser than3
LOGICAL OPERATORS
AND OPERATOR
false
OR OPERATOR
true
NOT OPERATOR
true
TERNARY OPERATOR
It is not equal

