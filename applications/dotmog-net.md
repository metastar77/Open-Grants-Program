# Open Grant Proposal

> This document is referenced in the terms and conditions and therefore needs to contain all the required information. Don't remove any of the mandatory parts presented in bold letters or as headlines! See the [Open Grants Program Process](https://github.com/w3f/Open-Grants-Program/blob/master/README_2.md) on how to submit a proposal.

> This page is also available in [Chinese (中文)](./application-template-cn.md).

* **Project Name:** DOTMog NET
* **Team Name:** DOTMog Team
* **Payment Address:** 1FgaH4sRHF4boR4Fw316ddKMJbFpsDXGeL

*The above combination of your GitHub account submitting the application and payment address will be your unique identifier during the program. Please keep them safe.*

![LOGO](https://i.imgur.com/cS6Xj0v.png)

## Project Overview :page_facing_up: 

We believe that the promising substrate blockchain technology enables us to bring a new way of gamification to a broad audience in a responsive, playful and immersive way. Our unique technical base allows us and the community to create independent games that can be deployed as enrichment to any substrate based chain.

### Overview

#### Introduction (A brief description of the project.)

***Click for a demo of our alpha release from 16.01.2021***
[![MOBILE](https://dotmog.com/wp-content/uploads/2021/02/DOTMog_game2.png)](https://youtu.be/GKWigHkaTxA)

DOT Mog (substrate based Unity3D Game) - Immerse yourself in the futuristic universe of the Mogwais. Lead them to glory and honor. Experience epic and thrilling adventures & duels. Explore the infinite universe & mysteries.

As probably the first substrate based Unity3D game using our open-sourced (SubstrateNetApi) we bring the functionalities and benefits of this promising technology to a broad audience in a playful and immersive way.

* Breed, create your own unique Mogwais based on the highly sophisticated Paring DNA Algorithmus.
* Care, learn the language of the Mogwais and respond optimally to their needs and gain a competitive advantage.
* Duel, prepare your Mogwai and fight in the Arena against other Mogwais from all over the world and achieve glory and honour. Move up to master leagues and compete with the best.
* NFT's, trade Mogwais and their precious goods and become a fortuned merchant.
* Explore, travel with interstellar spaceships into the vastness of space to unexplored and mythical places and experience exciting and challenging adventures.
* Innovative, the self-developed SubstrateNetApi allows for the first time full substrate integration in Unity 3D for game development. Benefit from the full stack of substrates blockchain technology.

![LOGIN SCREEN](https://dotmog.com/wp-content/uploads/2021/02/login_screen-2.png)
![MAIN SCREEN](https://dotmog.com/wp-content/uploads/2021/02/Screenshot_1612460593-1.png)
![EXPLORER](https://dotmog.com/wp-content/uploads/2021/02/Screenshot_1612460682-1.png)


DOTMog, is the follow-up project from the creators of "The world of Mogwais" on the mogwaicoin blockchain.

#### Integration of the game into Substrate (An indication of how you will integrate this project into Substrate / Polkadot / Kusama)

The goal is currently to provide a pallet with the full functionality of the game, which can be independently deployed on any Substrate based chain. It is currently active as a reference implementation on its own chain ([DOTMog.com NET](https://polkadot.js.org/apps/?rpc=wss%3A%2F%2Fmogiway-01.dotmog.com#/explorer)). 
One of our big goals is to create further creatures in addition to the Mogwai, which have different characteristics depending on the universe on which they are located. So in a future step not only mogwais, but also kusamais or polkadais will populate the universe of the game and create a big community of gamers that loves to dive into this immersive experience.

#### Motivation (An indication of why your team is interested in creating this project.)

We love the way we can matrialize our ideas. Our small team consists of game and technology enthusiasts, who work in their leisure time with great dedication, passion and great intrinsic motivation on the project. Everyone inevitably has several hats on, we are developer, graphic designer, project manager, web designer and so on. We try to make up for this deficiency with our great enthusiasm and conviction in our almost daily work for the project.

### Project Details 

#### Mockups/designs of any UI components

https://dotmog.com/gallery/

![Mogwai Life-Cylce](https://lucid.app/publicSegments/view/54cde0fa-754d-4472-96b0-d7ae32f8d41a/image.png)

#### API specifications of the core functionality

https://github.com/dotmog/SubstrateNetApi

#### An overview of the technology stack to be used

![Application Architecture](https://i.imgur.com/fSkrw46.png)

* https://github.com/dotmog/SubstrateNetApi
* https://github.com/dotmog/substrate/tree/dotmog/bin/node/pallets/dotmog
* https://github.com/dotmog/DOTMogCore (GameEngine, currently private)
* https://github.com/dotmog/DOTMogClient (Unity3D Client, currently private)

#### Documentation of core components, protocols, architecture etc. to be deployed

We have been working on the World of Mogwais for a long time gaining experience in technology and game design, we where stopped by the limitations of the technology we where using, problems like freezing chain due to hash power spikes or no available storage made our live hard. Just when we where giving up, we learned about substrate, so we digged into it and started to work on migrating and transforming our project in to this new world of 3 sec block times and responsive storage access.

We differentiate the gamelogic into two parts, base logic which is not heavy computing intense which will run inside the node and intense computing gamelogic for example for a dungeon event, which we plan to outsource with an Off-Chain worker to a trusted computing environement.

#### PoC/MVP or other relevant prior work or research on the topic

Our alpha MVP is already running, check out our webpage (https://dotmog.com/).

A lot of our previous work on the World of Mogwais is beeing used as PoC for the current project, the gamelogic we created [WoMNetCore](https://github.com/WorldOfMogwais/WoMNetCore) is reused where it makes sense or refactored to match better, here an [old PoC](https://github.com/WorldOfMogwais/WoM-Releases/releases). We used the CryptoKitties on Substrate as our first crash course into Rust and luckily it had a theme in common with our vision from 2017 [old whitepaper](https://github.com/mogwaicoin/mogwai-doc/raw/master/doc/Mogwai_Whitepaper.pdf). 

### Ecosystem Fit 
I think currently there is no such projects in the substrate ecosystem, at least we don't know of any. The full game logic is written down in our confluence, but for the sake of this file, we don't copy & paste it into here, but we can add it if necessary.

## Team :busts_in_silhouette:

### Team members
* Cedric Decoster ([darkfriend77](https://github.com/darkfriend77))
* Rene Windegger ([rwindegger](https://github.com/rwindegger))
* André Schneider ([metastar77](https://github.com/metastar77))

Artists:
* Patrik Bundeli ([2much](https://www.instagram.com/2much_ch/))
* Tim Kramarz ([timkramarz](https://www.timkramarz.com/))

### Contact
* **Contact Name:** Cedric Decoster
* **Contact Email:** cedric.decoster@gmail.com
* Website www.dotmog.com

### Legal Structure 
* **Registered Address:** There is no legal structure.
* **Registered Legal Entity:** There is no legal structure.

### Team's experience
The team consists of two experienced developpers, one project manager / designer and additionally two supplying artists working on illustrations and 3D models.
In past projects the team has already worked together on different projects one of them is [mogwaicoin](https://github.com/mogwaicoin) which has been live since 2018 and on the game on top [The World of Mogwais](https://github.com/WorldOfMogwais/WoM-Releases/releases). Besides that both devs have a background in reverse engineering of games and creating automations or simulators, like sabberstone. Our project manager is working in the financial sector in the same role for years as he is supporting the team. Based on the work of darkfriend77 Sabberstone simulator a lot of research and publications have been done in the AI domain (google: [sabberstone research ai](https://www.google.com/search?rlz=1C1CHBF_deCH914CH914&sxsrf=ALeKk006zio57YXebBkFf5i5F96dp67ePA%3A1612994036885&ei=9FUkYOvDNePEgwfIyLm4Ag&q=sabberstone+research+ai&oq=sabberstone+research+ai&gs_lcp=CgZwc3ktYWIQAzIHCCMQsAMQJ1AAWABg5RZoAXAAeACAAUeIAUeSAQExmAEAqgEHZ3dzLXdpesgBAcABAQ&sclient=psy-ab&ved=0ahUKEwjrjd-Ep-DuAhVj4uAKHUhkDicQ4dUDCA0&uact=5)) or even [ai competitions](https://hearthstoneai.github.io/index.html). Our passion is about creating games and/or enhancing the gaming experience for us. 

### Team Code Repos

* https://github.com/dotmog/SubstrateNetApi
* https://github.com/dotmog/substrate/tree/dotmog/bin/node/pallets/dotmog
* https://github.com/dotmog/DOTMogCore (GameEngine, currently private)
* https://github.com/dotmog/DOTMogClient (Unity3D Client, currently private)
* https://github.com/darkfriend77/Unity3DExample

Other projects lead and maintained by the teammembers
* https://github.com/HearthSim/SabberStone
* https://github.com/WorldOfMogwais/WoMNetCore
* https://github.com/WorldOfMogwais/WoM-Releases/releases
* https://github.com/mogwaicoin/mogwai
* https://github.com/mogwaicoin/NeoScryptCSharp
* https://github.com/rwindegger/RabbitExpress
* https://github.com/rwindegger/UnityMainThreadDispatcher
* https://github.com/darkfriend77/CoinMillions

Adding a polkadot related commit here ..
https://github.com/usetech-llc/polkadot_api_dotnet/pull/10

Active organisations of the teammebers
* https://github.com/dotmog
* https://github.com/WorldOfMogwais
* https://github.com/mogwaicoin
* https://github.com/HearthSim

### Team LinkedIn Profiles
* https://www.linkedin.com/in/cedric-decoster-3a004510b/
* https://www.xing.com/profile/Andre_Schneider90
* https://www.linkedin.com/in/renewindegger/
* https://www.linkedin.com/in/2much/
* https://www.linkedin.com/in/tim-kramarz-80345aba/

## Development Roadmap :nut_and_bolt: 

This section should break out the development roadmap into a number of milestones. Since the milestones will appear in the grant contract, it helps to describe the functionality we should expect, plus how we can check that such functionality exists in the product. Whenever milestones are delivered, we refer to the contract to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions it should be clear how the project is related to Substrate and/or Polkadot. We recommend that the scope of the work can fit within a 3 month period and that teams structure their roadmap as 1 month = 1 milestone. 

For each milestone:
* Please be sure to include a specification of your software. Treat it as a contract - the level of detail must be enough to later verify that the software meets the specification.
To assist you in defining it, we created a document with examples for some grant categories [here](../src/grant_guidelines_per_category.md).
* Please include total amount of funding requested per milestone.
* Please note that we require documentation (e.g. tutorials, API specifications, architecture details) in each milestone. This ensures that the code can be widely used by the community.
* Please provide a test suite, comprising unit and integration tests, along with a guide on how to run these.
* Please commit to providing a dockerfiles for the delivery of your project. 
* Please indicate the milestone duration, as well as number of Full-Time Employees working on each milestone, and include the number of days along with their cost per day.
* Deliverables 0a-0d are mandatory and should not be removed, unless you explicitly specify a reason within the PR's `Additional Notes` section (e.g. Milestone X is research oriented and as such there is no code to test)

### Overview
* **Total Estimated Duration:** 3 months MVP 1: Milestones 1 - 6
* **Full-time equivalent (FTE):** 2 FTE
* **Total Costs:** 5.000 USD

### Milestone 1 SubstrateNetApi — Implement Basic Substrate .NET Standard 2.0 API 
* **Estimated Duration:** 1 month
* **FTE:**  1
* **Costs:** 1000 USD 

| Number | Deliverable | Specification |
| ------------- | ------------- | ------------- |
| 0a. | License | Apache 2.0 / MIT / Unlicense |
| 0b. | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how a user can (for example) spin up one of our Substrate nodes. Once the node is up, it will be possible to send test transactions that will show how the new functionality works. |
| 0c. | Testing Guide | The code will have unit-test coverage (min. 70%) to ensure functionality and robustness. In the guide we will describe how to run these tests | 
| 0d. | Article/Tutorial | We will write an article or tutorial that explains the work done as part of the grant. 
| 1. | Basic API | Create a solid base for the API, to be reusable, easy to use and simple to maintain |
| 1a. | MetaData Model | read & parse metadata v11, v12 to json |  
| 1b. | Connection | Connect & disconnect to node, with StreamJsonRpc, avoid reinventing the wheel where possible |  
| 1c. | Class Model | Create basic class model, for the API |  
| 1d. | Logging | Basic NLog implementation, make sure it's usable with Unity3D |  
| 1e. | Errorhandling | Implement specific errorhandling | 
| 1f. | Unit Tests | Create unit test cases | 
| 2. | Storage Call | Implement basic storage call | 
| 2a. | Generic Call | Implement generic type read from metadata |
| 2b. | Type Converter | Add type converter logic for basic types |
| 2c. | Unit Tests | Create unit test cases |
| 3. | Refactoring | First Round of refactoring and restructure the API |
| 4. | Submit Extrinsic | Implement basic extrinsic submits | 
| 4a. | Generic Call | Implement typed extrinsic submits, to make access easier |
| 4b. | Encoding | Add type encoding to the type converter class |
| 4c. | Unit Tests | Create unit test cases, with payload testing signed and unsigned |
| 5. | Testing | Add overall tests including connection to a node | 

### Milestone 2 SubstrateNetApi & Pallet DotMog
* **Estimated Duration:** 0.5 month
* **FTE:**  1
* **Costs:** 500 USD 

| Number | Deliverable | Specification |
| ------------- | ------------- | ------------- |
| 0a. | License | Apache 2.0 / MIT / Unlicense |
| 0b. | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how a user can (for example) spin up one of our Substrate nodes. Once the node is up, it will be possible to send test transactions that will show how the new functionality works. |
| 0c. | Testing Guide | The code will have unit-test coverage (min. 70%) to ensure functionality and robustness. In the guide we will describe how to run these tests | 
| 0d. | Article/Tutorial | We will write an article or tutorial that explains the work done as part of the grant. |
| 1. | Second Round of refactoring and restructure the API |
| 2. | Subscriptions | Implement basic subscriptions |
| 2a. | Subscriptions | Implement generic Callback for handling multiple subscriptions with subscriptionId |
| 2b. | Subscriptions | Added storage subscriptions, with pageing |
| 2c. | Unit Tests | Create unit test for subscribtions |
| 3. | Refactoring | Refactor type converters to be generic and reusable inheriting from IType, BaseType & Struct Type |
| 4. | Pallet | DotMogPallet add base functionality, MogwaiStruct, AccountConfig & BreedType |
| 5. | Pallet | DotMogPallet add pairing algorithm and MogwaiBios |
| 6. | Update | Update to Substrate v3.0/0.9 – Apollo 14, adjust types |

### Milestone 3 SubstrateNetWallet — Implement basic wallet & example Unity3D applications
* **Estimated Duration:** 0.5 month
* **FTE:**  1
* **Costs:** 500 USD 

| Number | Deliverable | Specification |
| ------------- | ------------- | ------------- |
| 0a. | License | Apache 2.0 / MIT / Unlicense |
| 0b. | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how a user can (for example) spin up one of our Substrate nodes. Once the node is up, it will be possible to send test transactions that will show how the new functionality works. |
| 0c. | Testing Guide | The code will have unit-test coverage (min. 70%) to ensure functionality and robustness. In the guide we will describe how to run these tests | 
| 0d. | Article/Tutorial | We will write an article or tutorial that explains the work done as part of the grant. 
| 1. | Wallet | Add basic wallet functions to be used in the game |  
| 1a. | Wallet | AES wallet file necryption, make sure that it is usable on Unity3D Mobile deployments, Android & iOs. |
| 1b. | Wallet | Wallet unlock and create, subscription to account and updates |
| 1c. | Wallet | Add events so game can register to changes, like mogwai creation, or extrinsic finalization |
| 2. | Examples | Provide basic examples of Unity3D application using the SubstrateNetApi |
| 2a. | Examples | Simple connection example |
| 2b. | Examples | Small wallet example |
| 3. | Documentation | Add documentation to the usage of the SubstrateNetApi |

### Milestone 4 DOTMog Client — Features Login/Create/Remove/Breeding/Paring/Morph/Explorer/Auction/Trade/Sacrifice/Phases/GameEvents
* **Estimated Duration:** 1 month
* **FTE:**  1
* **Costs:** 1000 USD 

| Number | Deliverable | Specification |
| ------------- | ------------- | ------------- |
| 0a. | License | Apache 2.0 / MIT / Unlicense |
| 0b. | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how a user can (for example) spin up one of our Substrate nodes. Once the node is up, it will be possible to send test transactions that will show how the new functionality works. |
| 0c. | Testing Guide | The code will have unit-test coverage (min. 70%) to ensure functionality and robustness. In the guide we will describe how to run these tests | 
| 0d. | Article/Tutorial | We will write an article or tutorial that explains the work done as part of the grant. 
| 1. | Login/Create/Remove/Breeding/Paring | Implement those features |
| 1a. | Pallet Enhancment (Rust) | Add missing functions, check pairing algorithm & create breeding random for types |  
| 1b. | Substrate .NET API (API) | Added storage calls and chain specific types needed. |  
| 1c. | DOTMogCore (GameEngine) | Add controller functionality for the features Login/Create/Remove/Breeding/Paring |  
| 1d. | DOTMogClient (UI) | Implement Features in the client view. |  
| 1e. | Graphics (UI) | Create GUI Interaction for the features. |
| 2. | Morph/Explorer/Auction/Trade/Sacrifice/Phases & GameEvents | Implement those features |
| 2a. | Pallet Enhancment (Rust) | Add morphing function, enable exploring all mogwais and add sacrifice function, implement game event system, add initial phase |  
| 2b. | Substrate .NET API (API) | Added storage calls and chain specific types needed. |  
| 2c. | DOTMogCore (GameEngine) | Add controller functionality for the features Morph/Explorer/Auction/Trade/Sacrifice/Phases & GameEvents |  
| 2d. | DOTMogClient (UI) | Implement Features in the client view. |  
| 2e. | Graphics (UI) | Create GUI Interaction for the features. |
| 3. | Testing | The new features. |
| 4. | Relase | Release alpha version.|

### Milestone 6 (GFX) Enhancement of 3D Models 
* **Estimated Duration:** 3.5 day
* **FTE:** 1 (external supplier)
* **Costs:** 1.900 USD

| Number | Deliverable | Specification |
| ------------- | ------------- | ------------- |
| 0a. | License | Copyright |
| 0b. | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how a user can (for example) spin up one of our Substrate nodes. Once the node is up, it will be possible to send test transactions that will show how the new functionality works. |
| 0c. | Testing Guide | The code will have unit-test coverage (min. 70%) to ensure functionality and robustness. In the guide we will describe how to run these tests | 
| 0d. | Article/Tutorial | We will write an article or tutorial that explains the work done as part of the grant. 
| 1. | Body | Enhancements, to individualize mogwai more |
| 2. | Horn | 10 Horn-Variations |
| 3. | Eyes | Eyelids independently controllable | 
| 4. | Ears | Movable ears |
| 5. | Items | Bangle, leg bracelet, earring, tattoo, cyborg implant/augmentation (10 each) |  
| 6. | Egg | Mogwai 3D Egg for the hatching phases |  
| 7. | Adjustments | Which will be found in the iteration process after delivery | 

### Milestone 7 MVP 2 — Features (Stash/Item/Skills)
* **Estimated Duration:** 1 month
* **FTE:**  1
* **Costs:** 1.000 USD 

| Number | Deliverable | Specification |
| ------------- | ------------- | ------------- |
| 0a. | License | Apache 2.0 / MIT / Unlicense |
| 0b. | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how a user can (for example) spin up one of our Substrate nodes. Once the node is up, it will be possible to send test transactions that will show how the new functionality works. |
| 0c. | Testing Guide | The code will have unit-test coverage (min. 70%) to ensure functionality and robustness. In the guide we will describe how to run these tests | 
| 0d. | Article/Tutorial | We will write an article or tutorial that explains the work done as part of the grant. 
| 1. | Update 3.0.0 | We will create a Substrate module that will... (Please list the functionality that will be coded for the first milestone) |  
| 2. | Wallet module: Y | We will create a Substrate module that will... |  
| 3. | AES module: Z | We will create a Substrate module that will... |  
| 4. | Subscriptions chain | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |  
| 5. | Generic Approach | We will provide a dockerfile to demonstrate the full functionality of our chain |

### Milestone 8 MVP 2 — Features (Combatsystem, Duells, League)
* **Estimated Duration:** 1 month
* **FTE:**  1
* **Costs:** 1.000 USD 

| Number | Deliverable | Specification |
| ------------- | ------------- | ------------- |
| 0a. | License | Apache 2.0 / MIT / Unlicense |
| 0b. | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how a user can (for example) spin up one of our Substrate nodes. Once the node is up, it will be possible to send test transactions that will show how the new functionality works. |
| 0c. | Testing Guide | The code will have unit-test coverage (min. 70%) to ensure functionality and robustness. In the guide we will describe how to run these tests | 
| 0d. | Article/Tutorial | We will write an article or tutorial that explains the work done as part of the grant. 
| 1. | Update 3.0.0 | We will create a Substrate module that will... (Please list the functionality that will be coded for the first milestone) |  
| 2. | Wallet module: Y | We will create a Substrate module that will... |  
| 3. | AES module: Z | We will create a Substrate module that will... |  
| 4. | Subscriptions chain | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |  
| 5. | Generic Approach | We will provide a dockerfile to demonstrate the full functionality of our chain |

### Milestone 9 DOTMog Client — Extensions (Battlegrounds/Interstellar Travel/)
* **Estimated Duration:** 1 month
* **FTE:**  1
* **Costs:** 1.000 USD 

| Number | Deliverable | Specification |
| ------------- | ------------- | ------------- |
| 0a. | License | Apache 2.0 / MIT / Unlicense |
| 0b. | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how a user can (for example) spin up one of our Substrate nodes. Once the node is up, it will be possible to send test transactions that will show how the new functionality works. |
| 0c. | Testing Guide | The code will have unit-test coverage (min. 70%) to ensure functionality and robustness. In the guide we will describe how to run these tests | 
| 0d. | Article/Tutorial | We will write an article or tutorial that explains the work done as part of the grant. 
| 1. | Update 3.0.0 | We will create a Substrate module that will... (Please list the functionality that will be coded for the first milestone) |  
| 2. | Wallet module: Y | We will create a Substrate module that will... |  
| 3. | AES module: Z | We will create a Substrate module that will... |  
| 4. | Subscriptions chain | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |  
| 5. | Generic Approach | We will provide a dockerfile to demonstrate the full functionality of our chain |

## Future Plans
Please include the team's long-term plans and intentions.

## Additional Information :heavy_plus_sign: 
Any additional information that you think is relevant to this application that hasn't already been included.

### ETA of the PROJECT

#### Currently we already have implemented the following Milestones

:white_check_mark: **Milestone 1: SubstrateNetApi — Implement Basic Substrate .NET Standard 2.0 API**  
:white_check_mark: **Milestone 2: SubstrateNetApi — Implement Advanced Substrate .NET Standard 2.0 API**    
:white_check_mark: **Milestone 4: DOTMog Client — Implement Basic DOTMog Client (Login/Create/Remove/Breeding/Paring)**  

#### On going work

:construction: **Milestone 3: SubstrateNetWallet — Implement basic wallet & example Unity3D application**  
:construction: **Milestone 5: DOTMog Client — Advanced Features (Morph/Explorer/Auction/Trade/Sacrifice/Phases & GameEvents)**  
:construction: **Milestone 6 (GFX) Enhancement of 3D Models**  

#### Future Plans for MVP 2

:rocket: **Milestone 7 MVP 2 — Features (Stash/Item/Skills)**  
:rocket: **Milestone 8 MVP 2 — Features (Combatsystem, Duells, League)**  
:rocket: **Milestone 9 MVP 3 — Extensions (Battlegrounds/Interstellar Travel/)**  
 
