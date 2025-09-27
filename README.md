# solidity-hello-world
README.md
# Solidity Hello World
Basit Solidity kontrat örneği.
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract HelloWorld {
    string public message = "Hello, Blockchain!";
    function setMessage(string memory _m) public {
        message = _m;
    }
}
