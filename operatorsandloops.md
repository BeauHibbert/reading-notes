#Loops

Loops are a way to get code to repeat itself. If for example, you need someone to enter a password for a web page, you need to add a loop that says retry password, if they enter their password wrong.

The statements for loops provided in JavaScript are:
* for statement
* do...while statement
* while statement
* labeled statement
* break statement
* continue statement
* for...in statement
* for...of statement

A **for loop** repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.
When a for loop executes, the following occurs:
The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. If the value of condition is false, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)
The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.
If present, the update expression incrementExpression is executed.
Control returns to Step 2.

**The do...while** statement repeats until a specified condition evaluates to false.
A do...while statement looks as follows:
statement is always executed once before the condition is checked. (To execute multiple statements, use a block statement ({ ... }) to group those statements.)
If condition is true, the statement executes again. At the end of every execution, the condition is checked. When the condition is false, execution stops, and control passes to the statement following do...while.

A **while statement** executes its statements as long as a specified condition evaluates to true. 
If the *condition *becomes false, statement within the loop stops executing and control passes to the statement following the loop.
The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.
To execute multiple statements, use a block statement ({ ... }) to group those statements.

A **label** provides a statement with an identifier that lets you refer to it elsewhere in your program. For example, you can use a label to identify a loop, and then use the break or continue statements to indicate whether a program should interrupt the loop or continue its execution.
The value of label may be any JavaScript identifier that is not a reserved word. The statement that you identify with a label may be any statement.

Use the **break statement** to terminate a loop, switch, or in conjunction with a labeled statement.
When you use break without a label, it terminates the innermost enclosing while, do-while, for, or switch immediately and transfers control to the following statement.
When you use break with a label, it terminates the specified labeled statement.

The **continue statement** can be used to restart a while, do-while, for, or label statement.
When you use continue without a label, it terminates the current iteration of the innermost enclosing while, do-while, or for statement and continues execution of the loop with the next iteration. In contrast to the break statement, continue does not terminate the execution of the loop entirely. In a while loop, it jumps back to the condition. In a for loop, it jumps to the increment-expression.
When you use continue with a label, it applies to the looping statement identified with that label.

The **for...in** statement iterates a specified variable over all the enumerable properties of an object. For each distinct property, JavaScript executes the specified statements

The **for...of statement** creates a loop Iterating over iterable objects (including Array, Map, Set, arguments object and so on), invoking a custom iteration hook with statements to be executed for the value of each distinct property.

Helpful Links:
* [Expressions and operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
* [Loops and iteration](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)