# 502 Bad Gateway Token (Z502) smart contract

Z502 is ERC20 ethereum token.

https://etherscan.io/token/0x2cd9324ba13b77554592d453e6364086fbba446a

*total amount of tokens*

`function totalSupply() constant returns (uint256 supply)`

*get current balance of specified address*

`function balanceOf(address _owner) constant returns (uint256 balance)`

*send token specified amount to specified address*

`function transfer(address _to, uint256 _value) returns (bool success)`

*send token specified amount to specified address from specified sender*

`function transferFrom(address _from, address _to, uint256 _value) returns (bool success)`

*approve amount to send token*

`function approve(address _spender, uint256 _value) returns (bool success)`

*get current approved amount of specified address*

`function allowance(address _owner, address _spender) constant returns (uint256 remaining)`

*approve amount to send token with extra datas*

`function approveAndCall(address _spender, uint256 _value, bytes _extraData) returns (bool success)`
