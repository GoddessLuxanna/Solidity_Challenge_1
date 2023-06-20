# Solidity_Challenges created by Caelestis Myojo also known as Luxanna from the National Teachers College

# Challenge 1: Write a simple contract and declare four different types of variables. Write get and set functions for each of these variables. Return the value of the variable in the “set function”.

# Challenge 2: Write a smart contract that takes some ether from the user. Find out its value in units of:

- wei
- ether
- gwei

# Challenge 3: Now let's see these concepts into action. We'll give you the code this time, and then in the next lesson you can write it.
For this challenge, uncomment the commented piece of code in this example and run it to produce an output.

// SPDX-License-Identifier: MIT
pragma solidity ^0.8.17;

contract IfElse {
    function foo(uint x) public pure returns (uint) {
        if (x < 10) {
            return 0;
        } else if (x < 20) {
            return 1;
        } else {
            return 2;
        }
    }

    function ternary(uint _x) public pure returns (uint) {
        // if (_x < 10) {
        //     return 1;
        // }
        // return 2;

        // shorthand way to write if / else statement
        // the "?" operator is called the ternary operator
        return _x < 10 ? 1 : 2;
    }
}

# Challenge 4: Now let's practice what you have been learning.

Write a Solidity contract with 4 functions; add, subtract, multiply and divide 2 numbers.

Run your contract and make sure it works.
