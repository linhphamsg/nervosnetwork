## Gitcoin: 3) Issue A Smart Contract Call To The Deployed Smart Contract

1. A screenshot of the console output immediately after you have successfully issued a smart contract call.

![alt text](https://github.com/linhphamsg/nervosnetwork/blob/main/task_3/call_contract.png?raw=true)


2. The transaction hash from the console output (in text format).

0x3faaeef98685f075e004080ccf93aea8f2341aa5da024606b14e837833af8f58

3. The contract address that you called (in text format).

0x059Fb7fFC3d95F4B46D6C82d322F33fEc89b1E4A


4. The ABI for contract you made a call on (in text format).

```
abi = [
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ];
  ```
