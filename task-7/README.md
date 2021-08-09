# Task 7: Port An Existing Ethereum DApp To Polyjuice
https://gitcoin.co/issue/nervosnetwork/grants/8/

1) Screenshots or video of your application running on Godwoken.
https://youtu.be/_7dpwqIbSzg
![Dapp](./dapp.png)

2) Link to the GitHub repository with your application which has been ported to Godwoken. This must be a different application than the one covered in this guide.
https://github.com/phungnm/polyjuice-ported-voting-dapp

3) If you deployed any smart contracts as part of this tutorial, please provide the transaction hash of the deployment transaction, the deployed contract address, and the ABI of the deployed smart contract. (Provide all in text format.)

    - Transaction hash
    ```
    0x69a524b010b0120c1cef37ae6256d4471c074c948d0b6a5ea85fd4c2c6a8a974
    ```
    - Deployed contract address
    ```
    0xA1571836da4e66DBB1368324F9a7Aa090b8D57ae
    ```
    - ABI
    ```
    [
        {
        "constant": true,
        "inputs": [
            {
            "name": "",
            "type": "bytes32"
            }
        ],
        "name": "votesReceived",
        "outputs": [
            {
            "name": "",
            "type": "uint8"
            }
        ],
        "payable": false,
        "stateMutability": "view",
        "type": "function"
        },
        {
        "constant": true,
        "inputs": [
            {
            "name": "",
            "type": "uint256"
            }
        ],
        "name": "candidateList",
        "outputs": [
            {
            "name": "",
            "type": "bytes32"
            }
        ],
        "payable": false,
        "stateMutability": "view",
        "type": "function"
        },
        {
        "inputs": [
            {
            "name": "candidateNames",
            "type": "bytes32[]"
            }
        ],
        "payable": false,
        "stateMutability": "nonpayable",
        "type": "constructor"
        },
        {
        "constant": true,
        "inputs": [
            {
            "name": "candidate",
            "type": "bytes32"
            }
        ],
        "name": "totalVotesFor",
        "outputs": [
            {
            "name": "",
            "type": "uint8"
            }
        ],
        "payable": false,
        "stateMutability": "view",
        "type": "function"
        },
        {
        "constant": false,
        "inputs": [
            {
            "name": "candidate",
            "type": "bytes32"
            }
        ],
        "name": "voteForCandidate",
        "outputs": [],
        "payable": false,
        "stateMutability": "nonpayable",
        "type": "function"
        },
        {
        "constant": true,
        "inputs": [
            {
            "name": "candidate",
            "type": "bytes32"
            }
        ],
        "name": "validCandidate",
        "outputs": [
            {
            "name": "",
            "type": "bool"
            }
        ],
        "payable": false,
        "stateMutability": "view",
        "type": "function"
        }
    ]
    ```
