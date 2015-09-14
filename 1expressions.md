* **Number literals**
  No difference between numbers w/without decimal points
  must be real numbers.
* **Operators**
  Used to combine operations to form new expressions.
  + = addition
  - = subtraction
  / = division
  * = multiplication
  % = modulo
  () = grouping
  JS follows PEMDAS but use parentheses whenever possible

##PRIMITIVE TYPES##
* **String Literals**
  A string represented in 'single quotes' or "double quotes"
  + = the lone string operator, concatenates strings
  `1 + "1" * 2` number interaction w/ strings
* **Expressions have type**
  Weak-type language: the type of expression is determined *when* it gets evaluated
  + is the only operator with a special purpose for strings, it is the only operator that implicitly converts operands into strings
  `Number + String => String` = Number is converted implicitly into a string
* **Boolean Literals**
  Boolean = a type with two possible values: true and false
  && (Logical AND)
  || (Logical OR)
  ! (Logical NOT)
  *Examples*
  !false => true
  true && true || false => true
  true + false && true => true
* **Type Conversion**
  `true` to number is `1`, to string is `true`
  `false` to number is `0`, to string is `false`
  *Examples*
  true + true => 2
  "true" + false => "truefalse"
  "Get to the chopper!" -1 && true => ???
* **Truthiness**
  ALL expressions are either *truthy* or *falsy*
  0 and NaN are falsy
  "" is falsy
  All other numbers and strings are truthy
* **Equality Operators**
  == *equality after type conversion**
  === *strict equality w/o type conversion**
  != *not equal*
  !== *not identical*
* **Wrap-Up**
  We can *combine expressions* using *operators* to form new *expressions*
  The *type* of an operator is determined at runtime, and we can *mix types with operations*
