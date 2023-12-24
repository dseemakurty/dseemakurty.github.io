---
title: "Part 4: Architecting “Forever Software” Today"
categories:
  - web3
---

The idea of “forever software” speaks to me because I spent years of my life working to provide technological solutions to a challenging market segment. I focused on bringing IoT medical devices and cloud software solutions to emerging market hospitals. It was straining to see the divide of what the customer would say, and how they would actually buy. Or more importantly, how they wouldn’t be able to buy.

<img src="/assets/images/web3/web3_4.png" width="500"/>

This buyer profile may seem specific to my experience, but my time in emerging markets showed me that most B2B buyers have the same mindset. New is risky. Change is tough, and reverting change is painful. The end users would be ready to start, but the management were concerned by the golden handcuffs. Would the blood, sweat, and tears invested into building their hospital be risked by you, a startup, disappearing? Would the hospital maintain pricing control, or would the company be able to twist their arm with a grip of their data? These SMB’s and Enterprises would beg for solutions to reduce dependency on your hosting, even if they paid you for maintenance and upgrades. The questions would go on and on.

There is clearly a large market of buyers who see software products as utilities. Simply seen as a part of their bigger hypothesis and narrative. They are interested in the cloud for storage, remote access, and collaboration. However, they would prefer an alternative to moving everything towards a SaaS if its just adding the hosting layer.

The structure of “Forever Software” is simple. The goal would be to leverage web3 technologies to ensure that you can trust that the pieces of your application can never disappear. The software would be built with platforms with high social trust of long-term survival. 

<img src="/assets/images/web3/web3_5.png" width="500"/>

The key components to any standard application can be remodeled in a decentralized manner:

- **Authorization/Licensing** - login/accounts to be connected to wallet address, software licensing can be provided via NFTs (transferrable or non-transferrable)
    - Few Options: Magic, Auth0
- **Client Software** - web application / downloadable native application that is stored and distributed via IPFS (decentralized storage)
    - Few Options: Any standard front end language - React, Flutter
- **Server Compute** - smart contracts / general compute for global state on L1 or L2 chain
    - Few Options: Eth2.0, Solana, Avalanche, Near, Polygon
- **Data Storage** - all assets stored on IPFS with content addressing
    - Few Options: Filecoin, Storj
- I**ndexing & Search** - blockchain indexing servers to provide search
    - Few Options: The Graph
- **Upgradability** - built in proxy contract to update server contracts for versioning
    - Few Options: OpenZepplin Proxy Contracts, Diamond Methodology
- **Payment** - usage-based or time-based
    - Few Options: Superfluid, Tokens Launch/Burning
    

For a deeper dive into the architecture of decentralized applications, Preethi Kasireddy has a great article breaking it down: 

[The Architecture of a Web 3.0 application](https://www.preethikasireddy.com/post/the-architecture-of-a-web-3-0-application)

Now, I am not silly to think that complex software will be efficient in this architecture. However, it’s shocking how much enterprise softwares today would be utilities programs a few decades ago. There are many applications that became SaaS that really didn’t need to be:

- Note-taking apps / Wiki / Docs with cloud sync
- Task management app with cloud sync
- Password manager apps with cloud sync - note: 1password used to be one-time pay software
- Accounting software with cloud sync
- Inventory software with cloud sync
- Document signing software with cloud sync

Let’s be honest, the shift to SaaS for these applications is more of an investor decision than a customer requirement. Often times putting functionality behind a recurring pay-wall instead of being customer centric. There are countless examples which only further validate those hesitant to adopt software:

[1Password 8 will be subscription only and won't support local vaults | Hacker News](https://news.ycombinator.com/item?id=28145247)

Forever Software is unique because decentralized technologies inherently provide  many cloud features that we take for granted when using SaaS:

- My account is in the cloud - can just login anytime
- Data/State is synchronized across devices - my files show up even on a new device
- Software works on multiple devices - website/app can be opened on any of my device
- Data security and reliability - my files should be encrypted and always available
- Updates and upgrades - my app knows if it should ask me to update

With decentralized applications, companies can provide software as a utility that works forever while providing the primary benefits that users expect from cloud-driven solutions. 

What does the future of global software market look like?

We explore that in the final part.