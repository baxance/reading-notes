# Operators and Loops

You can extract a Boolean *true* or *false* result from the comparison of one value in JS to your expectations throgh Comparison Operators

Comparison Operator | Use
--------------------|-----
`==` | Compares two values
`===` | Compares two values and their associated data types
`!=` | compares two values to see if they are *not* the same
`!==`| Does the above but also takes into account data type of the values
`<, >` | less & greater than
`<=,+>` |less & greater than *or equal to*

Logical Operator | Use | Example
-----------------|----|----------
`&&` | Tests more than one condition | ((2 < 5) `&&` (3 >=2)) = true
`||` | Tests at least one condition | ((2 < 5) `||` (2 < 1>)) = true
`!` | Inverts a single boolean value | `!`(2 < 1) = true

## Loops

Loops can be thought of like a simple switchboard, wherein if an estalbished condition returns true a separate code will run and the condition will be checked again until it reads false which will halt the repetition. There are three main loops...

- *While* loops are for when you don't know how many times the code needs to run itself, and can run indefinetly
- *Do...While* loops are idential to their cousins, the *while* loops with the exception that they will always run their code at least once even if the first evaluation returns *false*
- *For* loops will run a code a specified amount of times.
  - *for* loops use a counter as their condition which is built with three pieces...
    - **Intialization** `var i = 0;` the variable is set to 0 and the variable itself is called `i` and serves as a counter
    - **Condition** `i < 10;` as the value of i was previously set to 0, the loop will return *True* until it has run 10 times and `i < 10` becomes a false statement
    - **Update** `i++` is the condition that adds 1 to the variable i every time the statement in the curly brackets (run during each True statement) in the loop has run. This adds to the counter, eventually bringing it to 10 and making `i < 10` a false statement


  [<== Back to Readme](README.md)