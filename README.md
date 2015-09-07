# Porgramming Interviews 101
In this repository we will be posting sample problems for you to practice. We have added you all as contributors (if we forgot someone, feel free to add them) so you can push your changes. The idea is for you to create your own branch and work on the problems, after everyone has come up with a solution and pushed it, we will discuss and choose which of the solutions are better and merge them into master. 

This will also allow you to look at your peers' work, be it to help them or to be helped by them, which is great since you'll be working in teams during the competition. However, we advise you to really work on the problems on your own before you start looking at other people's code.

The problem set is organized as follows:
- Each folder is named after a problem
- Inside each folder you will find:
    - problem_name.txt: A brief description of the problem and what the expected inputs and outputs are
    - inputs: A folder containing a set of sample inputs with which you can test your solutions
    - outputs: A folder containing the expected outputs corresponding to the tests found in the inputs folder
    - hint[n].txt: You may find several of these files inside the folder. These contain hints that will point you to the right solution

# Interviews_101
This repository will is your homework server and programming interview questions bank

##Stock Picker

Your Task
Implement a method #stock_picker that takes in an array of stock prices, one for each hypothetical day. It should return a pair of days representing the best day to buy and the best day to sell. Days start at 0.

    > stock_picker([17,3,6,9,15,8,6,1,10])
    => [1,4]  # for a profit of $15 - $3 = $12
Quick Tips:

You need to buy before you can sell
Pay attention to edge cases like when the lowest day is the last day or the highest day is the first day.
