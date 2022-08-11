#pragma solidity 0.8.7;

contract MyContract {
    string value;

    function get() public returns(string memory) {
        return value;
    }

    function set(string memory _value) public {
        value = _value;
    }
}
