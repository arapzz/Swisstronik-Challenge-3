# Swisstronik Challenge #3

task: 

Make a JSON RPC call using eth_getStorageAt() to get the first storage variable (slot #0) of any deployed smart contract and explain what is the retrieved value or if there is any difference with other blockchains when using this RPC method.


# Introduction

### Smart Contract
```
0xf84Df872D385997aBc28E3f07A2E3cd707c9698a
```
### call provider.getStorageAt()
```
npx hardhat run scripts/getStorageAt.js                                    
```
### Console Log

 <p align="center">
 <img height="250" height="auto" src="https://imgur.com/a/sSwnC9k">
 </p>

```
Getting Message from Swisstronik:
BYTES:  0xc73e7f645a2bf1365a0903afa03a2cb5029ba989df7844b0fe7751b1ba918ea4
string
false

Getting Message from Mumbai:
BYTES:  0x0000000000000000000000000000000000000000000000000000000000000000
string
false

Getting Message from Sepolia:
BYTES:  0x0000000000000000000000000000000000000000000000000000000000000000
string
false
```

# Usage
```shell
npx hardhat test
npx hardhat run scripts/getStorageAt.js
```
