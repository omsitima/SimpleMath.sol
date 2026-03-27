# SimpleMath.sol
How to deploy a contract on Base Chain
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract SimpleMath {
    uint public a;
    uint public b;

    function setNumbers(uint _a, uint _b) public {
        a = _a;
        b = _b;
    }

    function sum() public view returns (uint) {
        return a + b;
    }
}
