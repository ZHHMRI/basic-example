# basic-example
Testbed to help get all our research group members on board with code collaboration

Good, it looks like you're reading this!

The object of this example is to take a number defined in a text file, perform a series of mathematical operations on it, and compare it to a predetermined final result.

# The Files

* *start.txt* - The code begins with a value of 2
* *finish.txt* - The code ends with a value of 10
* *step1* - The first script.  It should read the value of *start.txt* and output a result value.  The result value should be 4, regardless of the mathematical method used.
* *step2* - The second script.  It reads from STDIN and outputs triples the value read.  For example, if it reads *100*, it should output *300*.
* *step3* - The third script.  It reads from STDIN and outputs the additive inverse of the value read.  For example, if it reads  *100*, it should output *-100*
* *step4* - The fourth script.  It reads from STDIN and outputs twenty-two more than the given value.  For example, if it reads *100*, it should output *112*
* *step5* - It reads from STDIN.  If the read value is *10*, then it prints "CORRECT".  Otherwise, it prints "LESS CORRECT".

# Testing Methodology

The scripts, which can be written in any programming language, will be run as follows:

$ ./step1 | ./step2 | ./step3 | ./step4 | ./step5

Expected output will be either be "CORRECT" or "LESS CORRECT".  The former is preferred, but the latter without any syntax errors would at least be a start.

