# ConGaiRuou
NhuNgoc
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract MessageBox {
    string public text;

    function updateText(string memory _text) public {
        text = _text;
    }
}
