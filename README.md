# shepherdinu
Shepherd Inu A Decentralized Joke Meme Token
--
Shepherd Inu ($SHEPHERD) is a community-focused, decentralized cryptocurrency meme coin, Meme coins have surged in popularity since Elon Musk endorsed the use of Dogecoin, one of the first meme coins.The best of them is shepherd inu, who is the shepherd dog of Meme coins.
<br>
https://www.shepherdinu.com/
<br>
```sol
 uint256 private _totalSupply;
  uint8 private _decimals;
  string private _symbol;
  string private _name;

  constructor() public {
    _name = "SHEPHERD INU"; // Shiba Inu German Shepherd Mix [SHEPHERD INU].
    _symbol = "SHEPHERD"; // Shepherd dog of Meme coins.
    _decimals = 0; // Unique.
      /**
   * Earth formed around 4.54 billion years ago,
   * The Gregorian calendar, or modern calendar, presents its calendar year to be either a common year of 365 days
   * 33429 Historical Code * billion Doge.
   */
    _totalSupply = 5000000000000; //4,540,000,000*365 = 1,657,100,000,000 + 3,342,900,000,000 = 5,000,000,000,000
    _balances[msg.sender] = _totalSupply;

    emit Transfer(address(0), msg.sender, _totalSupply);
  }
  ```
