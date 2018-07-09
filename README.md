# token-explorer
An ERC20 token explorer based on XCash network.


1.
Copy config.js.example to config.js.


2.
Edit arguments in config.js:


  this.tokenShortName = "XCH";

  this.tokenAddress = "0xd8537fcc3f44f5244fe0852b8b8703dba8300774";

  this.tokenDecimals = 18;

  this.tokenName = "XCash Network Token";

  this.tokenDescription = "XCash Network Token";

  this.tokenTotalSupply = -1;



3.
Install Node.js v8.x:

# Using Ubuntu
curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -

sudo apt-get install -y nodejs


4.
cd token-explorer

npm install


5.
Change http port at bin/www.

npm start



