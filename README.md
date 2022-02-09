# wordle reverse engineering in python
 
how i did it :
 opening the wordle site : https://www.powerlanguage.co.uk/wordle/
using the dev tools in firefox, i found main.******.js
downloaded it then found the huge list of all possible solutions for wordle 
and that the way it choose one is find the diffrence between a presise date and the current day ("which will get a new wordle each day automaticly")
then after calculating the diffrence just use it ass an array index and find the wordle

<H1>usage : </H1>
python3 script.py
offset : 0 for the current wordle
         1 for the next days wordle
         2 ....
         3 ....