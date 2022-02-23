# Java Basic
## variales
- Variables Types
We use in JAVA something called variables the defention of it from my side is a place to store inforomation this inforomatin have two major categories of data types in the Java language: primitive types and reference types.
primitive type have to be under some rules as example if we want to store integer we have to declare befor the variable name the defention name of integer which iss 'int' 
 primitive could be (integer, floating point, character,short,long,char, and boolean)
 boolean result = true;
char capitalC = 'C';
byte b = 100;
short s = 10000;
int i = 100000;
there is many number system such as
Decimal: Base 10, whose digits [0-9] this is the number system you use every day
Hexadecimal: Base 16, whose digits [0-F]
Binary: Base 2, whose digits [0-1]



 we talked about types of variables now we wan to discuss kindes of variables
* Instance Variables (Non-Static Fields)
declared without the 'static' keyword , it means that each object in the class has a unique valeu from the others
* Class Variables (Static Fields) 
this tells the compiler that there is exactly one copy of this variable in existence,even if we used the variable too many times it's value never changed  it used by type static befor the variable name
* Local Variables
is to declare the variable between the {} it means to use the variable locally inside the block out side it will be meaningful  
* Parameters
some variables that we use it as an input for the class to use inside it as an example "public static void main(String[] args)" we consider args as a parameter 

-Naming Variables
there is some rules we have to follow when we want to name our variables we have to keep in our minds to use camelCase to declare our vairables also we can use the doller sign $ during naming also we can use'_' to name our variables
some times we have to keep in our mind to make the vairables meaningful as much as we can 
we have to becareful to not use reserved words or keywords in declaring  also we don't have to use spaces


## Operators
it will be excuted from left to write and it will be applied according to the priority of the operation there is tow types of them logical & mathmatical operator 

##Expressions, Statements, and Blocks
######Expressions :
When writing compound expressions, be explicit and indicate with parentheses which operators should be evaluated first. This practice makes code easier to read and to maintain.
######Statements :
there are some kinds of statements  
assignment statement
aValue = 8933.234;
increment statement
aValue++;
method invocation statement
System.out.println("Hello World!");
object creation statement
Bicycle myBike = new Bicycle();
######Blocks
A block is a group of zero or more statements between balanced braces and can be used anywhere a single statement is allowed.

##If-Then Statements
we use it to put some conditions and to pass some statements through it if it was true and do another conditions if it was false
the hierarchical of if statement : 


<div class="highlight">
    <pre tabindex="0" class="chroma">
        <code class="language-fallback" data-lang="fallback">
        
           void name() {
    if (condition) {
        statements;
    } else {
        statments;
    } 
}
        </code>
    </pre>
</div>
we can add unlimited else to the else statement passed what we want the program to excute 