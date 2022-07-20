
# Discord Handle: pongchai#2968
## Router Track Mission 1 (09.05-16.05)

1) Spinning up a router on the Testnet

    - Router address is: 0xd7FbE8856DC391468373b422f469d1A30879431b

    - Added liquidity  100,000 on Rinkeby: 

      Transaction Hashes:    
        - 0xa1312207b53551abc4bdd1d37c33597d2411db999500683b76e7c2709b4e6b21
   
    - Added liquidity on 100,000 Kovan:

        Transaction Hashes:    
        - 0xc21b4be419b839daaf63c8a5d7438b131fa511f84450e3a43384ce9a5159b666
    - Test bridge on amarok-testnet.
    
    I think the guide is good for devops engineers who have some experience in setup a validator node/server, but for new newcomers have some confusion.
    For another improve, it's good if you have detail in step by step and explain more details why do this step.

2) Choose the activity which you intend to work on over the course of the program
    -  Write technical/document article.
    - Develop tools to help validator track their status. 

3) Answer questions and help others to run router in this Discord channel (1-10 points)

    Some of my contributions:
    
https://discord.com/channels/454734546869551114/966239886829060096/976175679378972672
https://discord.com/channels/454734546869551114/966239886829060096/976151447735521280
https://discord.com/channels/454734546869551114/966239886829060096/974944525304868904

## Router Track Mission 3 (23.05 - 30.05)
1) Testnet Upgrade - Add liquidity to the new contract (10-30 points)
  - Router address: 
    - https://testnet.amarok.connextscan.io/router/0xd7FbE8856DC391468373b422f469d1A30879431b
  - Liquidity on Kovan: 
    - https://kovan.etherscan.io/tx/0xd8031a12bcc72fc80f03bc113c03f5f61586837577a671a2d03911b1122b73a2
  - Liquidity on Goerli: 
    - https://goerli.etherscan.io/tx/0x658b0ac82f19d7040a421b4bb40d6f794db279180af72ab7708692efd990d6f4
  - Liquidity on Rinkeby: 
    - https://rinkeby.etherscan.io/tx/0x29e1733b2c174f69d16f44b0a4fab67687f479611a4cc40e6cee58260ee4802b
2) Flash Challanges (10-100 points) 
  - N/A
3) Router Connext Quests (10-500 points)
  - Quest 2 - Quick router setup (10-500 points)
	- Provision the Connext router via AWS infrastructure https://github.com/llPorZall/connext-cloud-formation
  - Quest 4 - Monitoring tools for Routers (10-500 points)
	- Provision cloduwatch dashboard and SNS alert to customer email  https://github.com/llPorZall/connext-cloud-formation

## Router Track Mission 4 (08.06-19.06)
1) Quest 5 How to integrate web3signer with one of the cloud providers instead of using the key.yaml (aws secret manager, gcp secret manager, aws secrets, ansible vault, k8s etc.) + Bonus points for scripts(cloudformation, terraform)
  - Integrated with Azure secret to protect router private key https://github.com/llPorZall/connext-cloud-formation 
2) Quest 6 - Best practices for generating and managing ssh-keys
  - Allow user access to router server only with public key (AWS Key pair) and whitelist firewall (Security group) https://github.com/llPorZall/connext-cloud-formation 
