# Rent_an_NFT-BE

Back End code for Rent an NFT in mentioned in available on <> Code

1.0 to 1.2 Keeper Contract Iterations
2.0 to 2.3 Rental-NFT Iterations


# Introduction

The Motion Rental project is an exploration of what is possible on web3 for video content on the blockchain. We are researchers, designers, doers, building on current innovation that gives content creators ownership of their video related content while allowing users to partake in the use of the content for a duration of time or by subscription.

# Background

There are several projects in the works (few delivered to date) like the Peer-to-Peer Non-Fungible Rentals, Axies, and Trava focused on the rental of still images and art work. We have also seen the Team Rental concept work out very well in the well renowned Axie Infinity model.

In this project, we aimed to expand this capability by bringing video content into the rental arena. We believe that the capability  with rentals can be achievable with the current tools provided by the BUIDL IT hackathon sponsors and other innovative projects building on web3. 

# Proposed Solution

In this version of our design, we focused specifically on the wellness and fitness industry. We inversion that creators will create their content using the following parameters:

- 10 to 15 minute videos
- High Definition Resolution
- Maximum storage per video at 1.2 GB
- Users will rent videos based on 3 rental duration or stream their rental and set their own limit

To support access (acceptance/denial), we used the **Chainlink Keeper** stack to control the video access itself and used the payment streaming stack **SuperFluid** to control the payment streaming process.


https://imgur.com/a/igoOgSy

Architecture Image link

### Assumptions & Limitation

During the development of the Motion Rental project, we made a number of assumptions and understand we have some limitations given where we are in the web3 development. The following are some of the assumptions and limitations we discussed/noted during this hackathon:

- The file size is large and we must work closely with **Arcana network** to understand what is possible beyond testnet.  The number of people that a file can be shared with is limited to 150 addresses currently during the fetching list of users because of blockchain limits.
- 

### Milestones

Key activities and milestones: 

- Research NFT design solutions on the market
- Develop the backend design and code
- Develop the front end design and UI
- Conduct code audit
- Conduct system testing

## Workflow explainer

https://www.loom.com/share/eeb7a918d9f1464b8d4b06e2800e93ba

The architecture is exemplified mainly by the key useage of the following technologies

- Arcana for privacy based file-storage
- Superfluid for the payment stack
- Chainlink keepers to deny access to NFT based video content based on Nil Wallet balance

# Follow-up Tasks

What needs to be done next for this proposal? 

- [ ]  Research methods to find a workaround to the file share limitation to expand beyond 150 people per video
- [ ]  Continue product improvement and testing
- [ ]  Embed design into a wellness and fitness application
