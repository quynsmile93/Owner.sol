# Owner.sol
Owner.sol
pragma solidity ^0.8.20;

contract Owner {
    address public owner;

    constructor() {
        owner = msg.sender;
    }
}
