# Discord Handle: Arm#7681

# Router Track Mission 1 (09.05-16.05)

## 1.Spinning up a router on the testnet
My router address is: 0x2c2aB8B0a5578b46d887146c8f3a55e6F5566Aaf
URL: https://testnet.amarok.connextscan.io/router/0x2c2aB8B0a5578b46d887146c8f3a55e6F5566Aaf

Add liquidity:
Rinkeby,Kovan,Görli  Completed

Added liquidity:
- Rinkeby TX HASH: https://rinkeby.etherscan.io/tx/0xa7f70f130384c19f6ef3a367c0884e542f0e5fc734fcd529dd4c4ad3449df96c
- Görli TX HASH : https://goerli.etherscan.io/tx/0x5a6b4b3897fa2ce6c1b0c8c734ce1cf73839be41053ab1e8b5e664d3b01ff662
- Kovan TX HASH: https://kovan.etherscan.io/tx/0x941bd06bb54f430e16f2d224782491f3f3dfcdca5a9975879faf41f4d4e42fa8


Test bridge:
Rinkeby, Kovan  Completed
 - Rinkeby URL: https://rinkeby.etherscan.io/tx/0xc63a7c9fb4971e7f5bc18c933004dc5f031b493b73f6a99ba45d8f6244c36a1b
 - Görli URL: https://goerli.etherscan.io/tx/0x2275b016a1f71b6cd10682ca889639603c9b4cd12d1078ce0bbcc60881ae3bf3
 - Kovan URL: https://kovan.etherscan.io/tx/0x6c1e1b84622787db6381a6a780ea9e484be989f3621b8b5d69c2d4cecea556d8

Feedback: 


## 2.Choose the activity which you intend to work on over the course of the program
- I want to share a node operation steps to the community, as well as building some monitoring tool for a node runner to be able to act fast when their node is not operate properly.

## 3.Answer questions and help others to run router in this Discord channel
I'm compling useful information into this single post for new people
- https://discord.com/channels/454734546869551114/966239886829060096/974901491997503508

# Router Track Mission 2 (16.05-23.05)

## 3. Answer questions and help others to run router in this Discord channel
I'm compling useful information into this single post for new people
- https://discord.com/channels/454734546869551114/966239886829060096/974901491997503508

----------------------------------

## 4. Feedback/improvement proposals/building high impact tools 
- Feedback: UI need a bit improvement, example:
1. Manage router turns out to be adding a liquidity to a router, it should said so or move to the same place showing current liquidity for better understanding.
2. Faucet is hidden in a bridge tool, at this testnet stage, faucet plays a major role and deserve a dedicated menu.

- Tools: I'm working on a dashboard tool that can be install in the same server as router and allow user to monitor their node as well as run some simple commands. The tool is build in NodeJS/Express web server and should be very simple to install.


- Improvement proposals: 
1. Native running script, I'm building a few servers on my full time job and most of the time using native program rather than docker. Docker is easy to use but I prefer to install it natviely better.

2. Missing feature shouldn't show as an error in logs, example, log DNA showing a few error here and there for a node that doesn't configure one.