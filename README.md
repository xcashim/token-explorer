
# Using Ubuntu 16.04 LTS
An ERC20 token explorer based on XCash network.


STEP 1.
Copy config.js.example to config.js.


STEP 2.
Edit arguments in config.js:


  this.tokenShortName = "XCH";

  this.tokenAddress = "0xd8537fcc3f44f5244fe0852b8b8703dba8300774";

  this.tokenDecimals = 18;

  this.tokenName = "XCash Network Token";

  this.tokenDescription = "XCash Network Token";

  this.tokenTotalSupply = -1;



STEP 3.
Install Node.js v8.x:


curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -

sudo apt-get install -y nodejs


STEP 4.
cd token-explorer

npm install


STEP 5.
Change http port at bin/www.

npm start



