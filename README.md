# sit737-2025-prac4p

For Part II

Step 1: Install express "npm install express"
Step 2: Add the four endpoints "add, subtract, multiply, divide"
Step 3: For each endpoint, create the function for each operation and test it
Step 4: After all is working, add error handling for invalid inputs for each operations and test it again for errors

For Part III

Step 1: Install Winston through terminal
Step 2: Copy the window logger and insert to "calculator.js"(creates files for errors and information)
Step 3: Add logger.log() to each end points with suitable messages
Step 4: I tried to enter "tail -f logs/combined.log" into terminal but it came with errors.

PS C:\Users\Jyols\Documents\sit737\sit737-2025-prac4p> tail -f logs/combined.log
tail : The term 'tail' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ tail -f logs/combined.log
+ ~~~~
    + CategoryInfo          : ObjectNotFound: (tail:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

(I did not know how to fix it so I just left it alone for now. From what I understand, it is a command line to the terminal but if I am mistaken, let me know. I could see logs through the 'combined.log' anyways.)