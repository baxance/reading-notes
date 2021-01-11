# Programming with JavaScript

JavaScript is a programming language that forms the final layer on top of your HTML+CSS webside that adds user interactivity. JavaScript interacts directly with your HTML content by targeting specific elements and adding modifiers to them. More advanced JS can completely alter the look and behavior of your website. Organizing pictures in a sliding gallery format, or having the website react to specific inputs from the user.

As the name implies, JavaScript is constructed as a script that can be related to many real-world scripts like recipes or manuals that go through step-by-step instructions, and it's beneficial to construct a script before you get into plugging JS into your website.
- Refer to your HTML+CSS wireframe and see what you want to change or how you want the content to interact with the user or vice versa
- Build a script that will handle each of those changes step by step
  - Computers go through scripts differently than you and I, and very specific and detailed instructions are necessary to effectivley communicate to the machine what you want it to do.
- Start coding in your JS

### Expressions and Operators
Expressions assign value to variables, be it color, mathematical equations or operators combining multiple values.

Arithmetic Operators perform basic math by assigning an equation of known values to a variable ```var area = 2 * 4;``` and can combine multiple string values together to result in a unified statement ```var example = 'like ' + 'this';```

Arithmetic Operator | Purpose | Example
--------------------|---------|---------
`+` | Addition | 1 + 1 = 2
`-`| Subtraction| 2 - 1 = 1
`/`| Division | 10 / 5 = 2
`*`| Multiplication| 5 * 2 = 10
`++`| Increment| i = 1; i++; = 2
`--`| Decrement| i = 2; i--; = 1
`%`| Modulus(divides and gives remainder as value)| 5 % 2 = 1

Standard order of operations remain.

String Operators function differently in that they combine values but not in any mathematical function. Combining '1' and '1' would not make two, it would give you 11, for example.

### Functions
Functions are a handy way to clean up your code. When there is a section of code that you know you are going to be using repeatedly you can classify that entire code as a function. In a way, functions are a higher form of variable in that you can recall not only an assigned value but an entire string of code using only it's identifying marker.

`Function testName() {
    document.write("test");
}` 

Function is the keyword, and is self explanatory like many JS keywords. Next is the Function Name, in this case *testName* which identifies the function and allows you to recall the code contained within it. Within the curled brackets you insert your code block of JS, and when you want to insert this function into your HTML file simply recall it with the `<script testName()></script>` element.

  [<== Back to Readme](README.md)