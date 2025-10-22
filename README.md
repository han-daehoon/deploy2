# deploy2

fix it

// SPDX-License-Identifier: MIT

pragma solidity ^0.8.0;

contract Greeting {
    string public message;

    function setGreeting(string memory newMessage) public {
        message = newMessage;
    }

    function getGreeting() public view returns (string memory) {
        return message;
    }
}
