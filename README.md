# Glacier_node
# Run Glacier Verifier Node 

 #Step-by-Step tutorial
 
 #Hardware Requirement

![Screenshot 2024-11-22 104713](https://github.com/user-attachments/assets/161c348c-3ba1-4735-b56d-1f267cb38590)


Reward: $GLS + $GLS Points + Whitelists

1. Register your wallet:
[https://www.glacier.io/points](https://www.glacier.io/points/?inviter=0x8C5Ee78fcfBeb0B6832b61289D412de38A458A75)

2.  Complete Galxe Task:
https://app.galxe.com/quest/glacierlabs/GChNBtVG6A

3. Bridge BNB Testnet to OpBNB Testnet : 
https://opbnb-testnet-bridge.bnbchain.org/deposit

If you don't have BNB Testnet claim faucet or go to BNB Chain discord faucet channel to claim

1. Create New Wallet
2. Visit [Faucet](https://docs.bnbchain.org/bnb-smart-chain/developers/faucet/#claim-tbnb-from-online-faucet) and get some tBNB in new wallet
3. Visit [Bridge](https://opbnb-testnet-bridge.bnbchain.org/deposit) and bridge tBNB from BNB testnet to opBNB testnet
4. Copy private_key of node wallet (without 0x)

Run the node: 
```bash
wget -O Glacier.node.sh https://raw.githubusercontent.com/CryptoAirdropHindi/Glacier_node/refs/heads/main/Glacier.node.sh && chmod +x Glacier.node.sh && ./Glacier.node.sh
```
once your docker is created to see it, Use the below command.
```bash
docker ps -a
```
Check logs:
```bash
docker logs -f glacier-verifier
```

Check your node status (wait for 30 minutes to appear after node is activated):
https://testnet.nodes.glacier.io/status
