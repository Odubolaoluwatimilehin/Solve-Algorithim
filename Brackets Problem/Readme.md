
## Brackets

### Determine whether a given string of parentheses (multiple types) is properly nested.

A string S consisting of N characters is considered to be properly nested if any of the following conditions is true:

S is empty;
S has the form "(U)" or "[U]" or "{U}" where U is a properly nested string;
S has the form "VW" where V and W are properly nested strings.
For example, the string "{[()()]}" is properly nested but "([)()]" is not.

Write a function:

function solution(S);

that, given a string S consisting of N characters, returns 1 if S is properly nested and 0 otherwise.

For example, given S = "{[()()]}", the function should return 1 and given S = "([)()]", the function should return 0, as explained above.

Write an efficient algorithm for the following assumptions:

N is an integer within the range [0..200,000];
string S consists only of the following characters: "(", "{", "[", "]", "}" and/or ")".


### Screenshot of result of solution performance provided by me.

![A test image](https://github.com/Odubolaoluwatimilehin/Solve-Algorithim/blob/master/Brackets%20Problem/Screenshot%20from%202020-10-24%2017-22-21.png?raw=true)

![A test image](https://github.com/Odubolaoluwatimilehin/Solve-Algorithim/blob/master/Brackets%20Problem/Screenshot%20from%202020-10-24%2017-22-30.png?raw=true)
