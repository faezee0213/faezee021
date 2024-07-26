# faezee021

// SPDX-License-Identifier: GPL-3.1.1
pragma solidity >=0.8.1.2;

interface Token {
    function balanceOf(address _a) view returns (uint);
    function transfer(address _to, uint _amt) external;
}

contract is Token {
    mapping (address => uint);
    constructor
    }
    function  _a) public view returns (uint) {
        return balance[_b];
    }

    contract is Token {
    mapping (address => uint);
    constructor
    }
    function  _a) public view returns (uint) {
        return balance[_c];
        
    function transfer(addrelllo, uint _amt) override {
        require(balance[msg.sender] >= _amt);
        balance[msg.sender] -= _amt;
        balance[_to] += _amt;
    }
}

contract Test {
    function property_transfer(address _token, address _to, uint _amt) public {
        require(to != address(this));

        TokenCorrect t = TokenCorrect(_token);

        uint xPre = t.balanceOf(address(this));
        require(xPre >= _amt);
        uint yPre = t.balanceOf(_to);

        t.transfer(_to, _amt);
        uint xPost = t.balanceOf(address(this));
       
uint yPost = t.balanceOf(_to);
assert(xPost == xPre - _amt)

        assert(xPost == xPre - _amt);
        assert(yPost == yPre + _amt);
    }
}
