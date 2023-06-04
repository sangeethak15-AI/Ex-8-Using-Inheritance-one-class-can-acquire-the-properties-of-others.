# Ex-8-Using-Inheritance-one-class-can-acquire-the-properties-of-others.
## AIM:
To Write the java program Using Inheritance one class can acquire the properties of others.

## SOFTWARE REQUIRED :
IntelliJ IDEA COMMUNITY EDITION

## ALGORITHM:
1. Create the class and declare the main method so that the JVM will identify the main program to run.

2.Create another class and use the keyword EXTENDS to use the concept of INHERITANCE.

3.Print a statement to check whether the inner class is accessable or not.

4.If the extended class's statement is executed then,this program follows the concept of inheritance.

5.The program will be executed after the compilation and results are printed.

## PROGRAM:
```
package q1;

public class Main {
    public static void main(String[] args) {
        Bird c=new Bird();
        c.fly();
        c.walk();
        c.sing();
    }
}
//CLASS FILE: BIRD
public class Bird extends Animal{
    public void fly(){
        System.out.println("I m flying");
    }
    public void sing(){
        System.out.println(" "+"I m singing");
    }
}
//CLASS FILE: ANIMAL
public class Animal {
    public void walk(){
        System.out.println("I m walking");
    }
}
```
## OUTPUT:
![image](https://github.com/sangeethak15-AI/Ex-8-Using-Inheritance-one-class-can-acquire-the-properties-of-others./assets/93992063/2ac9e814-2d4a-4452-8391-b8178067217f)


## RESULT:
Thus output is verified.
