# Exception Handling
       /*
             * What is Exception Handling?
             * it's a way to prevent your program to throw an error when using it 
             * simply you try to avoid erros ocuers in runtime 
             * 
             * Steps : 
> [!TIP]
 >* You need to Write a protective Code then you can use try catch at the end if you have doubt about 
             * your code.
>   
             * What is an Exceptions?
             * simple it's like a man who warning you about something in your program to fix the problem 
             * and the user of the program shouldn't know about this Thing
             * we Can save the exceptions that will occured in LogFile - Database
             */

            /*
             * Exceptions Hierarchy
             * All Exceptions in C# come from the Parent class Exception 
             * there is two types of Exceptions : 
             * 1 - SystemExceptions : built in - the Parent of SystemExceptions
             * 2 - ApplicationException : user Defined Exceptions
             */

         
![csharp-exception-hierarchy](https://github.com/Ebrahemots-lab/What-I-Learn/assets/79811814/260bf91d-c499-4cfc-a5b1-82ab08fc4c33)

## Exception Handling Examples

``` c#
         string[] colors = { "red", "green", "blue" };
         Console.WriteLine(colors[6]);
 ```
            Notice it will not give a warining or error because the exception will be ocured in the run time
            We are try to access index number 5 in the colors array which size is 3 
            First we need to write a protective code 
            we need to check if the Length of the array is larger than or equal 6 
            if no Do nothing.
            If yes print the element 
