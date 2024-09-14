---

title: VoiceDeck
menu_order: 1
post_status: publish
post_excerpt: VoiceDeck is a platform empowering citizen-led impact journalism through retroactive funding mechanisms.
featured_image: _images/VD-og.png
taxonomy:
    category:
    - Case Study
    post_tag:
    - Hypercert
    - Anon-Aadhaar

---

### Overview

VoiceDeck is a platform empowering citizen-led impact journalism through retroactive funding mechanisms. The project was founded by Devansh Mehta, a journalist who has been building VoiceDeck since 2018 and has extensive experience in journalism and media impact.

Pollen Labs partnered with the [Next Billion Fellowship](https://nxbn.ethereum.foundation/fellowship) to identify VoiceDeck as a suitably aligned project to develop and bring to market as an open-source project.

From November 2023 to March 2024, Pollen Labs worked closely with VoiceDeck to design, build, and launch the [VoiceDeck website](https://voicedeck.org/) and [VoiceDeck app](https://app.voicedeck.org).


![VoiceDeck App](/_images/VD-og.png)



### Objective

Prior to the collaboration, VoiceDeck was a promising project that had received grant funding, won hackathons, and had buy-in from partner reporting organizations. The team was seeking technical support to build out the concept into a ‘**Minimum Lovable Product**’ (MLP). 


Pollen Labs identified VoiceDeck as an ideal fellow to partner with based on the founder’s subject matter expertise, the project’s focus on building in the public goods space, and the potential to integrate PSE tooling.


### Approach

Pollen Labs and Voicedeck collaborated to design a multifaceted approach that balanced resource allocation, synchronous and async communication, and leveraged expertise from internal and external partners.

The team operated by delegating work based on bandwidth and skill set. This ensured that each team member could focus on their areas of focus in a complimentary way. As each of the respective components of the tech stack was built, the team brought external partners to provide their expertise and guidance to ensure that each piece was integrated effectively.

Communication and collaboration involved recurring weekly calls, and async communication occurred on Discord with regular updates on design, engineering, and operations. The team used Notion as the repository for documents and notes, allowing both incumbent and new contributors to access the information they needed easily.

The team set milestones and goals for to track progress and to keep participants accountable. Feedback and app testing were done in a collaborative and iterative manner, with each team member contributing to the process.


### Implmentation

The VoiceDeck MLP involved multiple components:

- **Website:** Marketing website providing an overview of VoiceDeck and the platform
- **VoiceDeck App:** The app allows supporters to donate to individual causes that have driven positive impact to local communities. The app is currently on Testnet and will migrate to Mainnet soon.
- **Content Management System (CMS):** The impact reports from partner organizations are stored in the Directus CMS with additional data fields to categorize the reports in the app. There are currently 27 impact reports that have been uploaded onto the CMS and minted as Hypercerts.
- **Hypercerts:** The reports are minted into Hypercerts, a protocol that provides onchain representation of a piece of work and the associated impact from it. Supporters who donated to a specific report receive a fraction of its corresponding Hypercert as proof of support.
- **Anon Aadhar:** This PSE-developed protocol allows Indian citizens to verify their identity on VoiceDeck in a privacy-preserving manner
- **Safe Multisigs:** The team created multisig wallets to provide transparency and controls for donated funds that would eventually be sent to the partner organizations

![VoiceDeck Implementation](/_images/VD-implmentation.png)

### Impacts & Insights

Through this partnership, Pollen Labs and VoiceDeck successfully built and shipped the VoiceDeck app in a 4-month timeframe. The app was also an early use case for Hypercerts, providing valuable feedback to their team regarding functionality. The team also gained additional insights into how the Pollen Labs supports builders:

**Support goes beyond financial grants**

Financial support is critical to help builders get off the ground with their ideas. However, there is also a need for executional support that involves turning the ideas into reality. Pollen Labs focuses on the latter in a way that makes the financial support more impactful. This execution-focused support allows the partners to show meaningful progress and outcomes of their efforts, creating a positive flywheel for additional funding. In this case, VoiceDeck was able to secure an additional $35k of grant funding from [Hedgey](https://hedgey.finance/grants) thanks to the progress made with the app.  

**Partnership opportunities**

The Ethereum Foundation and PSE network and resource capabilities are vast, which can sometimes be overwhelming for grantees and Fellows to make the most of. The Pollen Labs team helped to connect these resources (Hypercerts, Anon Aadhar, determining and implementing a tech stack to fit the project’s needs) and leverage their network to help VoiceDeck achieve their goal of launching a public app.

**Finding the right opportunities for PSE implementation**

By aligning the goals of VoiceDeck with the capabilities of PSE, the team integrated tooling that enhanced the platform's functionality and impact, especially in the public goods space.

### Where is VoiceDeck today?

As of May 2024, the VoiceDeck team continues to push forward with their mission to provide a platform for decentralized outcome funding for citizens and their local communities. Since the conclusion of the Pollen Labs partnership, Devansh and his team have focused on the following areas:

- **Presenting VoiceDeck at conferences:** Devansh has shared VoiceDeck’s progress at [BlockSplit](https://blocksplit.net/) and [ETHPrague](https://ethprague.com/). The team has also submitted demo papers to [ACM](https://compass.acm.org/) and [CSCW](https://cscw.acm.org/2024/).
- **Growing the team:** Nidhi Harihar has joined the VoiceDeck team full-time. She has a background in urban planning and has extensive experience working with government organizations.
- **User research:** The team is conducting research with potential users to further refine the product. This will help inform the scope of work needed for a v2 refresh of the app.
- **Establishing a nonprofit entity:** The team is in the process of registering as a [DUNA](https://www.fintechanddigitalassets.com/2024/04/wyoming-adopts-new-legal-structure-for-daos/) (Decentralized Unincorporated Nonprofit Association).
- **Deepening the utility of Anon Aadhar:** VoiceDeck is exploring the concept of ‘liquid delegation’ as a form of voting for citizen reporters representing their respective neighborhoods via PIN Codes (the equivalent of a zip code in the US).
- **Migrating to Mainnet:** The VoiceDeck app is expected to migrate to Mainnet around Oct 2024


## Contributors
- Devansh Mehta, Founder
- Siddique Patel, Product LLM
- Filipa Ribeiro, Design
- Beyondr, Design + Frontend Engineering
- Chiali, Design + Product
- CJ Rose, Frontend Engineering
- Daehyun, Backend Engineering + Devop
- Rowdy, Frontend Engineering
- Thomas, Operations + Marketing
- Bitbecker, Hypercert advisor