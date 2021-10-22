# Fungible Token Crowdsale

This solidity file establishes an ERC-20 compliant fungible token that is minted using the Crowdsale contracts from OpenZeppelin.

---

## Technologies

This project uses the Solidity Programming language in a solidity file (.sol)
    
    - Solidity
    - Remix IDE
    - MetaMask
    - Ganache
    - OpenZeppelin

---

## Installation Guide

To install you will want to pull the entire Kasei_Crowdale folder from github. Then follow the next steps
  1. Import KaseiCoin.sol into the Remix IDE
  2. Import KaseiCoinCrowdsale.sol into the Remix IDE
  3. Compile KaseiCoin.sol using Remix IDE
  4. Compile KaseiCoinCrowdsale.sol using Remix IDE
  5. Activate Ganache
  6. Load Ganache accounts into MetaMask Using the Private keys
  7. Deploy the ```KaseiCoinCrowdsaleDeployer``` using injected web3 and your MetaMask Accounts
  8. Connect the addresses provided by ```KaseiCoinCrowdsaleDeployer``` to both the ```KaseiCoin``` and ```KaseiCoinCrowdsale``` contracts



---

## Evaluation Evidence

Here is an example of how my crowdsale works

  1) You compile the ```KaseiCoin``` contract

  ![kaseicoin compile](https://user-images.githubusercontent.com/84096312/138531839-5ed09810-0354-4826-b9b8-31651becf8a8.png)
  
  2) You compile the ```KaseiCoinCrowdsale``` contract

  ![Kaseicoincrowdsale compile](https://user-images.githubusercontent.com/84096312/138531918-d08f2589-e448-4a4d-8aaa-a6970baeb692.png)
  
  3) You compile the ```KaseiCoinCrowdsaleDeployer``` contract

  ![crowdsaledeployer compile](https://user-images.githubusercontent.com/84096312/138531995-f89ba3b3-87dc-4b49-a775-0b5997afea3e.png)
  
  4) You connect to your MetaMask Accounts
  
  ![connect accounts option 2](https://user-images.githubusercontent.com/84096312/138532061-66af9286-ad10-4c14-8af8-03358cc68143.png)
  
  5) You deploy your crowdsale contract

  ![deployment](https://user-images.githubusercontent.com/84096312/138532118-cb0c9fb9-41fe-46af-b9b2-184e8befb739.png)
  
  6) Using your MetaMask Accounts you make a few transactions (buy some coin)

  ![3 successful transactions](https://user-images.githubusercontent.com/84096312/138532162-2baa41e5-65aa-469a-9555-a7febee31e4c.png)
  
  7) Here is a view of the total Wei raised by selling our Kasei coin (KSI)

  ![wei raised](https://user-images.githubusercontent.com/84096312/138532205-d7a7312c-91e5-42ed-91f9-d90025eb0721.png)
  
  8) and finally here is the total supply of our KSI coin! (you will notice the supply of coin is larger than the Wei raised shown above, that is because I did one more transaction of 4 ether inbetween the two images to further test my crowdsale contract. The 4 ether transaction accounts for the difference)

  ![total supply](https://user-images.githubusercontent.com/84096312/138532238-254ca0a1-b4ff-4cf6-9d6d-87f1104e4f4e.png)




---

## Usage

Overall it should be a very simple application to use, all you need to do is import the .sol file into the Remix IDE, compile and then deploy the contracts following the steps above. 

---

## Contributors

Colin Benjamin

Linkedin: [Colin Benjamin](https://www.linkedin.com/in/colinbenjamin/)
    
email: cbenjamin33@gmail.com

---

## License

(c) Copyright 2021 Colin Benjamin

Licensed under the MIT license:

    http://www.opensource.org/licenses/mit-license.php


Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
