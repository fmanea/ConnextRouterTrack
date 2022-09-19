Project repository:
https://github.com/Vgk88/Forta-Connext-main

#  I propose to build a tool that would help:
- Build Forta agent for Connext

# Discord handle: 
- cyberG#4889
- bramz#0364
- landeros#9587
- Ivan62#7522
- Adelinka_0405#4611
- sAriel#5642

# Name of the challenge/quest you are applying for: 
- Quest 5 - Alert for low gas

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
# KPIs (how can we measure the success of your project?)
- Successful work of an agent
- Build more agents for Connext





