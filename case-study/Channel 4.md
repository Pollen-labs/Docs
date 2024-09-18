---

title: Channel 4, reviving content discovery with community
menu_order: 3
post_status: publish
post_excerpt: Inspired by the golden age of StumbleUpon, we wanted to bring back the adventure of stumbling upon random, interesting content without algorithmic manipulation. 
featured_image: _images/Channel4-feature.png
taxonomy:
    category:
    - Case Study
    post_tag:
    - State-Channels


---
## Intro

In 2023, Pollen Labs incubated **Channel 4**, a product aimed at reviving the joy of content discovery. Inspired by the golden age of **StumbleUpon**, we wanted to bring back the adventure of stumbling upon random, interesting content without algorithmic manipulation. StumbleUpon’s decline after acquisition taught us a valuable lesson: centralized control can stifle innovation and user experience.

## The Challenge We Addressed

We asked ourselves:

- **How can we create a platform that avoids the pitfalls of centralization?**
- **How can we ensure scalability, speed, and user engagement in a decentralized environment?**

Our hypothesis was to leverage **decentralization** through blockchain technology, specifically utilizing **State Channels** to overcome the limitations of traditional blockchain interactions.

![App landing](/_images/Channel4-landing.png "Leverage TV channels to the app concept")

## Why State Channels? 

We knew with the number of content platforms out there, what users would want is instant interactions—the kind of real-time responsiveness you get when flipping through TV channels. We also needed a transparent and secure way to handle a large number of content submissions, ensuring you could trust the system. Plus, we wanted to encourage active participation by offering real incentives.

**State Channels** were the perfect choice of technology for us back then. It allows us to process transactions off-chain while keeping the security of the blockchain intact. This means we can handle thousands of interactions per second without slowing down the main chain, giving you immediate feedback every time you use the platform. By minimizing gas fees through off-chain settlements, we also reduce costs, making the platform more accessible to everyone.


![Browsing topic/channel in the app](/_images/Channel4-channels.png "Browsing topic/channel in the app")



## Implementation Overview 

Our architecture comprises four main components: the frontend, the backend, the state channels implementation, and the smart contracts.

**Frontend (React & Web3.js):**

The frontend is developed using React and Web3.js, delivering a seamless and intuitive user interface. It recreates a virtual “channel surfing” experience, enhancing the emotional appeal of browsing random content—much like flipping through TV channels. To simplify onboarding for users unfamiliar with blockchain technology, we integrated **Web3Auth**. This allows users to sign in with familiar social accounts, lowering the barrier to entry and making the platform accessible to a broader audience.

**Backend (Render.com):**

Hosted on Render.com, the backend acts as an intermediary, collecting content submissions and user interactions. It employs a centralized hub for temporary data storage before batching and committing these transactions to the blockchain. To handle high traffic efficiently, we implemented a queue system that manages data flow and ensures smooth processing of user interactions. This setup allows us to maintain performance and scalability while preparing data for secure on-chain settlement.

**State Channels Implementation:**

Our state channels implementation is built using the optimistic rollups concept. In this approach, each user submits their state changes to the centralized server, which provides a signed receipt. If the state change is not executed after a predetermined time period, the user can present this signed receipt directly to the smart contract. This mechanism ensures that users have a trustless fallback in case of server failure or dispute, enhancing the reliability of off-chain interactions while preserving scalability and speed. It effectively combines the efficiency of off-chain processes with the security guarantees of the blockchain.

**Smart Contracts (Solidity on Ethereum Sepolia):**

The smart contracts are written in Solidity and deployed on the Ethereum Sepolia testnet. They serve as the on-chain adjudicators for the state channels, handling dispute resolutions and the final settlement of batched transactions. By maintaining the integrity and security of user data and interactions, these contracts ensure that the system remains decentralized and trustworthy. They enforce platform rules and provide a secure foundation for the application’s functionality, safeguarding the interests of all participants.

## Incentive Mechanism: Empowering Users

We want to create a simple yet meaningful way to appreciate your engagement. When you like content shared by others, you earn points proportional to your activity—it’s our straightforward way of saying thank you for being an active part of our community. For those who submit websites, receiving likes means you earn a share of the monthly reward pool. This pool is funded by small fees from advertisers or premium features and is distributed fairly based on a transparent algorithm that considers all likes, shares, and contributions.

### Exploring Funding Avenues

Once we built our MVP, we began to explore sustainable ways to fund these rewards. As a non-profit team, we brainstormed a few options:

- **Community Donations**: We considered harnessing the support of our community by setting up a dedicated wallet. Contributions to this wallet would directly fund the reward pool, allowing users to benefit from the collective generosity of our supporters.
- **Service-Based Funding**: We noticed that many teams require a trusted setup for their projects. Instead of asking the community to contribute directly, we thought Channel 4 could serve a dual purpose. By using the interactions happening on our platform as computational power to generate randomness, we could assist these teams. In return, they might donate funds to our platform, which would, in turn, be used to reward our users.

![Adding a website in the app](/_images/Channel4-add-site.png "Adding a website in the app so others can like")

## Final Thoughts

Channel 4 has been one of exciting exploration and learning. While we haven’t tested all our hypotheses from end to end, we’re excited about the possibilities ahead. Can decentralization truly revive a well-loved project? In today’s competitive landscape, can the element of randomness inspire greater curiosity among users? How have content discovery behaviors evolved since the early 2000s?

We’re eager to answer many questions, and we believe the best way forward is together. If this also excites you, please say hello on our [discord](https://discord.gg/5B3jP2sgWS). We’d be delighted to have you join us on this adventure.

## Resource:

Github org: https://github.com/State-Channel-4

App: https://app.channel4.wtf/landing

## Contributors:

- Jay Gupta, Backend, Smart contract
- Nico Serrano, Smart contract
- Beyondr, Design engineer
- Ian / Mach34, Frontend
- Jack / Mach34, Backend, Smart contract
- Thomas, Marketer
- Chiali, Design