# StringKeeper.sol
StringKeeper.sol3
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract StringKeeper {
    string public message;

    constructor(string memory _message) {
        message = _message;
    }

    function setMessage(string memory _newMessage) public {
        message = _newMessage;
    }
}
Clean up unused code
Improve readability
Add require for safety
Optimize function calls
Add simple test case
