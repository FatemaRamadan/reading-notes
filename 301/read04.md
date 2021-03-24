CSS Grid Garden 
![grid garden ](301/grid.jpg)

### Regrx 
-	It stands for regular expression, which is a way in extracting information from ant text by searching for specific pattern like ASCII code or Unicode chareecters.
-	Its applicable in validating or parsing or replacing strings .
-	It used in almost all languages .
-	When we use `^the` here it matches anything that starts with **the**.
-	`end$` finds strings that ends with **end**.
-	`^the end$` finds what begins with **the** and ends  with **end**.
-	`roar` to match strings that has roar in it.

### Qualifiers 
![Quantifires list]( https://4.bp.blogspot.com/-BtT_vGTUA9k/WiF1sm0GYSI/AAAAAAAAQjg/6Th80JqcglEcilrdMHRb5_o5v_LtJ6roQCLcBGAs/s1600/What%2Bare%2BRegex%2Bquantifiers%2Band%2Bexamples%2B%2BJava%2BRegex%2B%2BJava%2BRegular%2BExpressions%2BRegex%2Bin%2Bjava.jpg)

![quantifires]( https://images.slideplayer.com/47/11682913/slides/slide_21.jpg)

###Flags:
-	Regex use this form `/abc/` where the search pattern is between the 2 forword slach and at the end we spacify a flag with the values .
-	`g` global doesn’t return after first match but restart the subsequent search.
-	`m` when enabled `^ $` it will match the start and end of line .
-	`i` make the whole expression case intensive .
Grouping and capturing :
Using this`()` operator is helpful when we need to extract info from strings or data.
>a(bc)           parentheses create a capturing group with value bc 
>a(?:bc)*        using ?: we disable the capturing group 
>a(?<foo>bc)     using ?<foo> we put a name to the group 

-	Bracket expression [] :
>[abc]            matches a string that has either an a or a b or a c -> is the same as a|b|c 
>[a-c]            same as previous
>[a-fA-F0-9]      a string that represents a single hexadecimal digit, case insensitively 
>[0-9]%           a string that has a character from 0 to 9 before a % sign
>[^a-zA-Z]        a string that has not a letter from a to z or from A to Z. In this case the ^ is used as negation of the expression
          
-	greedy and lazy match  ` +* {} ` are greedy operators they expand the match as far as they can .
-	 boundaries `\band\B`  it matches positions where one side is a word character and the other is not.
-	It comes with the negation `\B` 
###A Complete Guide to Grid
-	It’s a 2 dimensional grid-based layout system that change the way we design grid based user interfaces.
-	Grid has properties such as :
-	`display` it takes 2 values grid and inline grid 
-	`grid-template-column `  `grid-template-row` 

![grid]( https://devopedia.org/images/article/179/4150.1559055642.svg)

