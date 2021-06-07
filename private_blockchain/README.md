# Requirements

Download project 

cd into project directory

npm install dependencies

node app.js to run application


# Complete unfinished block.js implementation

Implemented `validate()` and `getBData()` under `block.js`



# Complete unfinished blockchain.js implementation

Implemented `_addBlock(block)`, `requestMessageOwnershipVerification(address)`, `submitStar(address, message, signature, star)`, `getBlockHeight(hash)`, `getStarsByWalletAddress(address)` and `validateChain()` under `blockchain.js`


Added `validateChain()` to `_addBlock()` based on rubrics requirements.


Created `validateChain()` trigger with endpoint http://localhost:8000/validateChain


Demonstration - errorLog empty = valid chain
![validate](POSTMAN/validate.png)



# Test your App functionality

* must use a GET call to request the Genesis block
![step1](POSTMAN/step1.png)
* must use a POST call to requestValidation
![step2](POSTMAN/step2.png)
* must sign message with your wallet
![step3](POSTMAN/step3.png)
* must submit your Star
![step4](POSTMAN/step4.png)
* must use GET call to retrieve starts owned by a particular address
![step5](POSTMAN/step5.png)

