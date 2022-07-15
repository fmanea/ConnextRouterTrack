# Discord Handle: landeros#9587
## Router Track Mission 1 (09.05-16.05)

1) Spinning up a router on the testnet

    - Router address is: 0x3e0C9A84f2285Dd2dD0665689873ff79cbc67AD8
      https://testnet.amarok.connextscan.io/router/0x3e0C9A84f2285Dd2dD0665689873ff79cbc67AD8

    - Added on Rinkeby:
	Transaction Hashes: 0x588c1b1fd0240eb6d7c91aac34704d165570c7bd0cff16f746f1980fd29a8785

    - Added liquidity on Kovan: 
	Transaction Hashes: 0xb70b56eb4df5a9d79bc8efc23aa509a2009b6fcd599cd9d5502188df5b777130 
	
    - Test Bridge Complete:
	Successful transaction: https://testnet.amarok.connextscan.io/tx/0x154edd3f75bd8f6a8811395c4c5ea2da5009c1249ef745c763fdf897d0ffcd59
      Also while testing, I encountered an error during the transaction:"Warning! Error encountered during contract execution [execution reverted]"
	Transaction Hashes:0x645f6755128803813354e152cee24af532616a22084ebc40cbea00db82d52498

2) Choose the activity which you intend to work on over the course of the program

    - I want to create a guide in my native language, post it on my twitter and post it on discord for other members.

    - If possible, I will try to help other participants with the installation and configuration of the router.

    - I also plan to launch additional infrastructure, such as graph indexers.

3) Answer questions and help others to run router in this Discord channel

    - This week I helped the participants with the installation in the profile discords, next week I will try to devote more time to the main discord of the project.

4) Proposals: Adding more networks to test, for example, you can add Ropsten network.

## Router Track Mission 2 (16.05-23.05)

1) Video guide with a step-by-step running router in any language

    - Made a video in my native language about the launch of the Connext Router!
	https://youtu.be/2_OAz9nIls8

2) Guides and your experience articles about running router in socials (medium etc.) in any language

   - I wrote a guide in Russian, link:  
	https://teletype.in/@landeros/zd69DV9Z1lY
   - Also posted this guide on my twitter:
	https://twitter.com/landerosua_/status/1528740796534513666

3) Answer questions and help others to run router in this Discord channel

   - I actively follow the discord, I hope my guide can help the community.

4) Feedback/improvement proposals/building high impact tools

   - In general, everything is fine.It would be a good idea to evaluate the work for the past period and update it after each period of work (week) so that each participant can evaluate their efforts.

   - Unfortunately, I still cannot add liquidity to the Goerli network, I get an error.

## Router Track Mission 3 (23.05-30.05)

1) Testnet Upgrade - Add liquidity to the new contract (10-30 points)

    - Added on Rinkeby:
	Transaction Hashes: 0x4a016eea0885840e4fc20a184e0a1b83bc0b0e58e87f9bdaa832e3202221f928

    - Added liquidity on Kovan: 
	Transaction Hashes: 0xcd15e16cbca418cfdd204ddd0c551f34fd651d53fa5cdcfc8384609afc55f9c8

    - Added liquidity on Goerli: 
	Transaction Hashes: 0xd8b155c338a9b8d120a7c4ff3f2d61f317516b5895b970a3adae4e1625cf9fb9

2) Flash Challanges

    - My text guide is in Articles-Russian at number 3

    - My video guide is in Videos-Russian at number 1

## Router Track Mission 5
# Router Connext Quests

# Quest 5 - Alert for low gas (participated in team quest)
https://github.com/fmanea/ConnextRouterTrack/pull/422/commits/70702ab44fba823abe8242882036632bdb09245e

# Briefly describe your project:
- This agent detects low gas usage for the specified contracts in specified chains.

# Detailed project proposal:
Agent usage:
- CONNEXT_LOW_GAS
    - Fired when a transaction's gas in less than threshold
    - Severity depends on the gas:
        - `Critical` if the gas is below critical gas threshold
        - `High` if the gas is below high gas threshold
        - `Medium` if the gas is below gas threshold
    - Type is always set to "Suspicious"
    - Metadata contains:
        - `timestamp`: timestamp of the block that contains suspicious transaction
        - `gas`: the amount of used gas
        - `contract_address`: contact address related to the transaction
        - `sender`: sender of the transaction
  - All chains are supported    


