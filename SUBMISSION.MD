## Submission for Udacity Blockchain Developer Nanodegree

## Postman Screenshots
1. To make sure your application is working fine and it creates the Genesis Block you can use POSTMAN to request the Genesis block
    ![Request: http://localhost:8000/block/height/0 ](https://github.com/myles-hildebrand/private-blockchain/blob/71bdb8ee3b209b65f2abd986f1151e2389c37ceb/postman_screenshots/postman_genesis_block.png)
2. Make your first request of ownership sending your wallet address:
    ![Request: http://localhost:8000/requestValidation ](https://github.com/myles-hildebrand/private-blockchain/blob/71bdb8ee3b209b65f2abd986f1151e2389c37ceb/postman_screenshots/postman_send_wallet_address.png)
3. Sign the message with your Wallet:
    ![Use the Wallet to sign a message](https://github.com/myles-hildebrand/private-blockchain/blob/71bdb8ee3b209b65f2abd986f1151e2389c37ceb/postman_screenshots/bitcoin-qt_sign_message.png)
4. Submit your Star
     ![Request: http://localhost:8000/submitstar](https://github.com/myles-hildebrand/private-blockchain/blob/71bdb8ee3b209b65f2abd986f1151e2389c37ceb/postman_screenshots/postman_submit_star.png)
5. Retrieve Stars owned by me
    ![Request: http://localhost:8000/blocks/<WALLET_ADDRESS>](https://github.com/myles-hildebrand/private-blockchain/blob/9fec72bff3a9cafab46fe9ee16bd97c116d17171/postman_screenshots/postman_retrieve_stars.png)
6. Validate blockchain with endpoint
    ![Request: http://localhost:8000/validateBlockchain](https://github.com/myles-hildebrand/private-blockchain/blob/9fec72bff3a9cafab46fe9ee16bd97c116d17171/postman_screenshots/postman_validate_blockchain.png)