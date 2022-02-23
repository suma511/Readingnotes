# Arrays,Loops,Imports
## Arrays 
An array is a container object that holds a fixed number of values of a single type Each item in an array is called an element, and each element is accessed by its numerical index
to deal with the index and the elemnts inide the array we use (For , While ,and do-While loops)
The types of Arrays 
byte[] anArrayOfBytes;
short[] anArrayOfShorts;
long[] anArrayOfLongs;
float[] anArrayOfFloats;
double[] anArrayOfDoubles;
boolean[] anArrayOfBooleans;
char[] anArrayOfChars;
String[] anArrayOfStrings;
we can fill or access or edit or search the arrays using the loops


##The while and do-while Statements
to excute some lines of any code with number of repeation passed on the condition if it was true it will be excuited otherwise it will break the wile loop and it will stop repeating

<div class="highlight">
    <pre tabindex="0" class="chroma">
        <code class="language-fallback" data-lang="fallback">
        
           void name() {
   while (condition) {
            code;
            count++;
        }
        </code>
    </pre>
</div>

Or
<div class="highlight">
    <pre tabindex="0" class="chroma">
        <code class="language-fallback" data-lang="fallback">
        do {
     statement(s)
} while (expression);
        }
        </code>
    </pre>
</div>

##for Statement
we use it to do a reaptation and for accessing arrays
<div class="highlight">
    <pre tabindex="0" class="chroma">
        <code class="language-fallback" data-lang="fallback">
        for (initialization; termination;
     increment) {
    statement(s)
}
        </code>
    </pre>
</div>

####branching statements
-break ;
it take us out of the loop it is combined with if statemant if the condition was true it will break the loop
-countinuie
it skip some steps in the code under a certain condition it is combined with true if statement
-return
tow types of return ,first return it returns for us a value and the other one dosen't 
to calculate a value put the operation after the return code 

## imports
To import java package into a class, we need to use java import keyword which is used to access package and its classes into the java program.

Use import to access built-in and user-defined packages into your java source file so that your class can refer to a class that is in another package by directly using its name.