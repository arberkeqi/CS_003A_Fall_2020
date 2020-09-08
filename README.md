# CS_003A_Fall_2020
###01_code_FizzBuzz
######The first code for the CS 003A class. Is an assignment from leetcode. It is about pushing values in certain places using vectors in a class called Solution. Used the command strings.push_back for all the strings, and for the place where I needed numbers, I did: 
1)first declare the variable - ostringstream nstring
2)then assign the value that I wanted to nstring - nstring << n
3)string.push_back(nstring.str())
And in the end just return strings

###02_code_RomanToInt
######The second code for the CS 003A class. Is an assignment from leetcode. It is about turning a Roman number into an Int. This was made by assigning the value to the map. Maps are associative containers that store elements formed by a combination of a key value and a mapped value, following a specific order. The general formula of map is 	
typedef pair<const Key, T> value_type; Then I made two different functions, 1 where I had only one character as an input, and 2 where I had 2 or more values as input. Number 2 has 2 subfunctions where 1 is when I have 2 or more diff values and 2 when I have the same value repeated.
