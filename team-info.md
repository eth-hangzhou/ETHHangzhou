# Pinnect
Game-map collaboration, all for gammers.
Pinnect is a visionary platform designed to revolutionize collaborative storytelling within the Ethereum ecosystem. With a seamless blend of interactive map exploration, tag management, and relationship visualization, Pinnect empowers users to co-create immersive narratives and gaming experiences like never before.
![Pinnect.001.png](/img/pinnect-readme-img-rec/Pinnect.001.png)
## Track: Layer 2 Application
Deck: https://docsend.com/view/x64yntk9zrs73uqj
Pitch Video: https://youtu.be/Tr6Xrd_Swys
[![Demo Video](http://img/pinnect-readme-img-rec.youtube.com/vi/Tr6Xrd_Swys/0.jpg)](http://www.youtube.com/watch?v=Tr6Xrd_Swys "Pinnect Eth Hangzhou")

## Key Features
1. Interactive Map Collaboration: Pinnect offers an engaging map interface where users can explore, contribute, and interact with various storytelling locations. Each click on the map initiates a unique narrative journey, connecting users through a shared gaming universe.
2. Efficient Tag Editing: Managing tags has never been easier. Pinnect's tag editing interface allows users to refine titles, descriptions, and relationships effortlessly. Users can create hyperlinks between tags and ensure organized and interconnected storytelling.
3. Relationship Flow: Pinnect's Relationship Flow feature simplifies tag relationship visualization. Users can connect tags, choose direction (preceding or following), and define relationship types, enabling branching storylines and fostering creative collaboration.
4. On-Chain Contribution: Pinnect promotes fairness and transparency through on-chain contributions. Content is securely anchored on the blockchain, ensuring equitable rewards and incentivizing active participation.
5. Cross-Platform Wallet Integration: Our platform offers cross-platform wallet support, allowing users to seamlessly access their Ethereum wallets across various devices and platforms, making transactions and asset management convenient and consistent.

![Pinnect.002.jpeg](/img/pinnect-readme-img-rec/Pinnect.002.jpeg)
## Pinnect contribute to Ethereum ecosystem with
1. **Ethereum Creator Ecosystem**: By attracting **gamers and storytellers** to our platform, Pinnect can introduce **more users** to the Ethereum and Layer2 ecosystems. This increased user adoption strengthens the ecosystems, potentially leading to more participants in other Ethereum and Layer 2-powered projects and games.
2. **Seamless Interoperability and Cross-chain Support**: Ethereum's and Layer 2's architectures, designed for interoperability, align perfectly with **Pinnect's vision**. They allow for horizontal scalability while maintaining a shared state, ensuring seamless connection between Pinnect, gaming communities and various Layer 2 solutions. Gamers and storytellers can effortlessly move between Pinnect and other Ethereum or Layer2-powered games, creating a cohesive and immersive experience. 
3. **Empowering the Metaverse**: With the capabilities of Ethereum, Pinnect can usher in a new era of decentralized marketplaces, **cross-game item integration**, and **fully on-chain storytelling elements**. Users can seamlessly incorporate assets from other Ethereum or Layer2-powered games into their **collaborative narratives**, creating a metaverse where storytelling knows no boundaries.

![PinnectSynergy](/img/pinnect-readme-img-rec/PinnectSynergy2.png)
## Game-map Collaboration
This page allows you to control the display of the map and its tags through filtering, sorting, and other methods to find the information you need.
![Pinnect.003.jpeg](/img/pinnect-readme-img-rec/Pinnect.003.jpeg)
Priority of feature requirements: Understandable but not obvious method
1. Tag List: Display an evenly arranged list of all primary tags and their associated secondary tags. Clicking on any will dim it and no longer display its corresponding tag on the map. Clicking a primary tag will hide all the markers corresponding to its secondary tags.
2. Show/Hide All Switch: This switch controls the visibility of all tags.
3. Search Box: This allows for searching for specific tags or markers.
4. Progress Radio Button: By selecting different chapters (game progress), you can choose different degrees of war fog coverage to prevent spoilers. For example, when selecting the first chapter, markers in the tag data that belong to the second chapter and later will be hidden.
5. Heatmap Display Mode Switch: You can select "Heatmap Priority" to display the markers most frequently visited/submitted by current players. This is useful for viewing the progress of the majority of players.
6. Mini-map and Zoom Buttons: Includes a thumbnail of the map and zoom in/out buttons.

## Tag Editing
Editing interface for tags.
![Pinnect.004.jpeg](/img/pinnect-readme-img-rec/Pinnect.004.jpeg)

The layout, from top to bottom, is as follows:
- Image and its submission button. (Optional)
- Title and its text input box.
- Description and its text input box. (Optional)
- Dropdown single selection box for primary tags.
  This can be tasks, NPCs, items, buildings, regions, or any other types.
- Dropdown single selection box for secondary tags. (Optional)
  Only two levels of tags are set.
- Belonging chapter. (Optional)
- Submission button.

### Function
1. In the description input box, hyperlinks to other tags can be created using [[]] syntax.
2. Transaction bundling: every 'n' transactions should be bundled together for on-chain attestation (this number 'n' needs to be set).
3. AI duplication detection: when a user makes a submission, the content is analyzed to determine if it is a tag that already exists. If it is, a prompt should appear asking if this is a mistake, with two options: 'Yes, submit an updated version' or 'No, submit as a new version'. If 'No' is chosen, the submission should undergo backend review.

## Relationship Flow
Relationship diagram of the current tag is highlighted. When another tag is clicked, a line between the current tag and the clicked tag is displayed, along with an adjacent edit box.
![Pinnect.005.jpeg](/img/pinnect-readme-img-rec/Pinnect.005.jpeg)

The layout of the edit box, from top to bottom, is as follows:
1. Direction and its option box: There are two types, preceding and following, similar to the arrowhead editing box at the end of the line in Keynote.
2. Relationship and its option box: This can be connectors like "owns", "manages", "belongs to", "requires", etc.

## Connect Wallet with cross-platform support on Ethereum
Contribute on-chain for fair incentive and collaboration
![Pinnect.006.png](/img/pinnect-readme-img-rec/Pinnect.006.png)
![Pinnect.007.jpeg](/img/pinnect-readme-img-rec/Pinnect.007.jpeg)
## Team
**Race Li**, co-initiator of magipop, serial entrepreneur, 2nd venture backed founders, previously founded an AI Music startup, made a social app with 1 million+ downloads, Apple WWDC (Worldwide Developers Conference) Scholarship Winner, Hurun U30 Winner, electronic musician.

**Setsukousa**, co-initiator of magipop, senior Web3 researcher, research published in Chaos, Solitons & Fractals, cryptocurrency investors, master in financial physics at ZJU, metaverse consultant at fine arts institute.
### Add Telegram and contribute with us!
![Pinnect.008.jpeg](/img/pinnect-readme-img-rec/Pinnect.008.png)
## Goals for This Hackathon
- The project is an original creation that started from scratch during this hackathon. We aim to create a practical solution in the field of collaborative creativity within gaming communities.
- We plan to integrate and utilize the Ethereum ecosystem, exploring high-performance creative collaboration solutions through Layer2 integrations.
- We look forward to moving forward together with talented buidlers globally.
## Progress in the First Two Days of the Hackathon
- On the Oct 13th and 14th, we discussed and validated concepts, and performed user validation.
- From the Oct 14th to the 15th, we divided tasks and carried out front-end and back-end development, contract deployment, and debugging.
## Github repo
https://github.com/DocRace/pinnect-eth-hangzhou
## Originality Statement
This project, developed from scratch during this hackathon, is a completely original creation.
## Demo links
Deck: https://docsend.com/view/x64yntk9zrs73uqj
Pitch Video: https://youtu.be/Tr6Xrd_Swys
## Contact us
Race Li
Telegram @RaceLi
Twitter @melitosnap
Email callmerace@hotmail.com