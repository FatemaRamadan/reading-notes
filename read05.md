## comparison operators:evaluating conditions pages 151-152
 - you can compare value to what you except it might be.
1.  == is equal to (it compares 2 values numbers strings or Boolean)to see if they are the same 
'hello' == 'goodbye' return false 
'hello' == 'hello' returns true 
2. != is not equal to cheacks two values to see if they are NOT the same .
'hello' != 'goodbye' return true
' hello' != 'hello' return false
3. === strict equal to checks both datatype and value are the same 
'3'=== 3 return false; not the same data type
'3' === '3' returns true ; same data type and value .
4. !== strict not equal to comparest 2 values to cheackboth data type and value are NOT the same
'3' !== 3 returns true
'3'!=='3' returns false
5. > greater than 
 4>3 returns true 
6.< less than 
4<3 returns false
7.>= greator than or equal 
4>= 3 returns true 
8. <= less than oor equal 
4<=3 returns false  
### programmers return tho testing of a condition as EVALUATING. 
- they usually result in a true or false.
- evey value can be treated as  true or false even if its not a boolean
- in short circuit evaluation; conditions might not need to run .\
 

## Logical Operators pages 156-157
unlike comparison operators that return one value , the logical operators allow you to
compare the result of more than one comparison operator 
1. && cheacks if both expressions on the side return true.
 - t && t returns t
 - t && f returns f
 - f && t returns f
 - f && f returns f

2. || logical or this test at least one condition.
  - t || t returns t
  - t|| f returns t
  - f||t returns t
  - f || f returns f
3- ! logical not , this takes a single boolean value and inverts it 
  - !T returns F
  - !F returns T
### short circuit evaluation
logical expressions are evaluated left to right if the first condition can provide enough informations
then no need to evaluate second part.
ex. false && anything ; it has found a false at the begining do no need to continue to other part .


## LOOPS page 170-173
### loops chack conditions if it return true a code block will run then it will cheack again;
### if it still return true the block will run again it will until it returns FALSE .
there are 3 common types of loops :
1. FOR (if u need to run code a specific number of times use a for loop)
   it usually a counter that tells how many imes the loop should run 
2. WHILE  (if you dont know how many times the code should run )
   here the condition is not a counter and it will run as long as the condition is true.
3. DO WHILE  (its vaery similar to the while loop,but is diffrent in that it will always run the statment 
   at least one even if the condition evalutes False)
   
### loops counters 
- FOR loop uses a counter as acondition .
it consist of ; intialization, condition, counter 

###  using while loops 
in while the loop will run as long as the condition is true.