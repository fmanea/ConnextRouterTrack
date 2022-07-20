# Flash Challenge and Connext Quests 

The flash challenge is quality based, and the sumissions that are picked for this activity will receive rewards.

The Connext Quests are more complex and are not time based. How does it work?
> Note: ` You need to get approval for starting working on Connext Quests since we want to avoid duplication of work among participants. But Flash Challenges don't require approval `

1. Head out to "proposals" directory within this repository and create a .md file with your github handle, an example of a file would be: "fmanea.md".
The content of the file should contain the discord handle of the participant (or if it's a group of people working on a big feature, their discord handles). Also, the content of the file should contain any kind of proposal that you would want to build.
- Name of the quest you are applying for
- Describe what are you going to do in details
- Roadmap and milestones (if it's long-time project)
3. Send link with your PR in discord directly to "Mateip | bwarelabs.com#1629" or "Vladislav | p2p.org#8449". We will check if nobody has already done this quest, ask about realization if necessary, and approve starting of work
4. The Track Leaders will move the approved proposals into the "approved_proposals" folder where the progress will be tracked;
 

## ~~Flash Challenge 1 - Explore all guides, and gather them in one place in Docs~~ - DONE

1. Create Guides page in Docs https://docs.connext.network/routers/guides
2. Explore every guide written by other routers, group them by type (text/video), running way (AWS/Google/DO, Dedicated server, local home computer, kubernetes),  language, etc. Links to the guides you can find here https://github.com/fmanea/ConnextRouterTrack/tree/main/submissions 
3. Guides should be numbered
4. Brief overviews are welcome for those guides which have something special (highlight uniqueness)

## Flash Challenge 2 - Complete the routers documentation intro

Now we have "page no found" status, when we follow the link https://docs.connext.network/Routers/intro/ 

You should fix it - add detailed info on the following topics:
- who are routers
- why do we need them in Connext
- security assumptions and risks 
- business model

The basic info is presented in the blog but it may be improved, You should review, figure out what information is missing

Github for PR https://github.com/connext/documentation

## Flash Challenge 3 - Propose a custody integration to improve the process for managing keys/liquidity

We are looking for the mechanisms to improve the process for managing keys/liquidity and make it more robust with minimum efforts right now (using a 3rd party custody solution as the recipient of the router liquidity)

Your proposal should include
- description of custody integration
- which projects are already use it?
- how it can improve the current process
- instruction/your experience how to set up it and use for managing keys/liquidity

## Quest 1 - Build Tools (10-500 points)

Build high impact tools to improve the router experience. We are waiting for your proposals:)

## Quest 2 - Quick router setup (10-500 points)

Router setup scripts for quick-running routers on cloud platforms and dedicated servers. 

Examples: 
- Setup based on any kind of scripting language (Ex: Bash Scripts,Python);
- Setup automate deployment using any kind of Infrastructure as a Code;(Ansible, Terraform or any other) 
- Develop a router setup using npm or yarn instead of using docker-compose
- Develop a router setup using helm or any kind of kubernetes manifests



The goal would be a tool for running routers with just 1 click. Don’t hesitate to propose any tools which will simplify the process. Be creative, we are looking for different approaches. 

Every submits needs a guide or documentation on how to use them, submitting without a doc we will be not taken into consideration.

## Quest 3 - Alerting system for Routers (10-500 points)

Create an alerting tool (telegram bot/slack/ etc.)

Examples:
- Integrate Alert Manager into the Docker Compose;
- Use Alert Manager to send alerts to Slack / Telegram/ Discord Channels; 
- Use Grafana to send alerts on slack and integrate with a on-call tools

We are also open the new ideas, please feel free to propose any alerting approaches.

## Quest 4 - Monitoring tools for Routers (10-500 points)

Implement different  monitoring deployments or dashboard for the router

Example:
- Use different tools for deploying an observability stack(Ex: ElasticSearch, Kibana, CloudWatch)
- Create Grafana dashboard

Our dream is to have different approches to monitor the router metrics and logs. Each router deployment can be easily integrate with any kind of infrastructure.

## Quest 5 - Integrade web3signer (10-100 points)

How to integrate web3signer with one of the cloud providers instead of using the key.yaml (aws secret manager, gcp secret manager, aws secrets, ansible vault, k8s etc.). + Bonus points for scripts(cloudformation, terraform, etc.). Note! You need submit a proposal before starting. Expected result is PR with edit in connext docs https://docs.connext.network/routers/intro 

## Quest 6 - Best practices for generating and managing ssh-keys (10-30 points)
Note! You need submit a proposal before starting. Expected result is PR with edit in connext docs https://docs.connext.network/routers/intro 


## Quest 7 - Hardening ssh config (10-30 points)
Note! You need submit a proposal before starting. Expected result is PR with edit in connext docs https://docs.connext.network/routers/intro 


## Quest 8 - Hardening current docker-compose file (10-30 points)
Note! You need submit a proposal before starting. Expected result is PR with edit in connext docs https://docs.connext.network/routers/intro 

## Quest 9 - How to create and use bastion instance for accessing routers infrastructure (10-30 points)
Note! You need submit a proposal before starting. Expected result is PR with edit in connext docs https://docs.connext.network/routers/intro 



