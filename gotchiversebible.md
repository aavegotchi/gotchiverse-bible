[//]: # (Title: The Gotchiverse Game Bible)  
[//]: # (Author: Pixelcraft Studios)     

# The Gotchiverse Game Bible
## What is this document?
The Gotchiverse Game Bible is an external-facing Game Design document that gives detailed information about gameplay, economy, and building within the Gotchiverse game.

The information published within this document may generally be considered to fall into two categories: **confirmed and immutable**, and **confirmed, but not immutable**.

**Confirmed and immutable** means that the published information will **not** change, except via DAO vote.

**Confirmed, but not immutable** means the information is generally confirmed, but could change if underlying assumptions change. Any changes will be published on all official channels.

---

## 📖 Chapter 1: Gotchiverse Release Schedule
*Confirmed, but not immutable* 

The Gotchiverse is a cutting-edge piece of software that features real time gameplay across an open world, combined with onchain "play-to-earn" game mechanics, powered by the blockchain.

Our development team was originally shooting for a launch date of December 2021 for the first release of the Gotchiverse, but this proved to be overly-ambitious, as multiple issues were uncovered during the first Stress Test (ST1), held on December 20th.

These issues are mainly related to building out infrastructure capable of scaling the enormous Gotchiverse with thousands of players, Alchemica pickups, and parcels each taking up significant amounts of computing resources.

We are excited to announce that R&D on these fronts has proven fruitful, and our development team is confident in the following release schedule.

### Gotchiverse Citaadel Release Schedule
#### Stress Test 2 - January 28th
A replica of Stress Test 1 (ST1) that should be much smoother, with less lag and fewer bugs. \
*Map size: Small test area*

#### Stress Test 3 - Mid-February
An initial test of "Area of Interest" scaling that breaks the map into smaller chunks for scaling. \
*Map size: One District*

#### Gotchiverse Land Auction / Raffle 3 - Late February
The third Aavegotchi Land Auction / Raffle combo will be held in late February and feature 10,000 Parcels up for grabs in various Districts.

#### Citaadel Live Test - Early-Mid March
The first release of the Citaadel with real Alchemica. Will support Alchemica pickups and "Save Points" to exit Alchemica from ingame to onchain. No Parcels or Installation equipping will be supported in this release. \
*Map size: One District*

#### Gotchi Lending is Live! - March
Audited and perfected, Gotchi Lending will be launched in March to allow us to scale up the number of players that can be online at any time.

#### The Gotchiverse - Late March / Early April
The Full Citaadel you've all been waiting for! Parcel access, installations, and harvesting will all be live in this release. \
*Map size: Entire Citaadel*

#### Traits Release - April
Aavegotchi traits (explained in an upcoming chapter) will be added to gameplay in this release. Support for weapons will also be added, time permitting.

#### Grid Release 1 - Early Q3 2022
The first release of the Grid (and Lickquidators) will come in early Q3 2022.


## 📖 Chapter 2: On Alchemica Tokenomics, Installation Recipes, and Gotchi trait mappings

### Part 1: Alchemica Tokenomics
*Confirmed and immutable*

Gotchus Alchemica are a crucial part of the Gotchiverse Economy. These four raw elements (FUD, FOMO, ALPHA, and KEK) are also completely on-chain ERC20 tokens, freely tradable between players. Many hours of detailed work has gone into their tokenomics, and the total supplies, distribution schedules and vested allocations below are each proposed with great care. Read on to learn how Gotchus Alchemica touch every corner of the Gotchiverse! 

Alchemica Supplies and Allocation [Graphic]

#### Total Supplies
* FUD: 100,000,000,000 (100 Billion)
* FOMO: 50,000,000,000 (50 Billion)
* ALPHA: 25,000,000,000 (25 Billion)
* KEK: 10,000,000,000 (10 Billion)

#### Channeling (25%)
The budget for Alchemical and Communal Channeling, to be distributed throughout the lifetime of the Gotchiverse is 25% of total supply for each token. To prevent excessive inflation, new Alchemica are only minted when the balance of the Great Portal is less than its capacity (see Crafting Revenue Distribution section below). 

Initial amounts of Alchemical Channeling will be discussed in the Alchemical Channeling section of Chapter 3. 

#### Ecosystem (10%)
Managed by AavegotchiDAO, 10% of the total supply of Alchemica are set aside for an assortment of onboarding and liquidity activities outside of the Gotchiverse. These tokens will be minted then released via a vesting contract over a thirty year period. giving predictability and transparency to the usage of Alchemica within the Gotchiverse ecosystem for years to come.

#### Gameplay (15%)
Managed by Pixelcraft Studios and the REALM smart contract, these 15% of the total supply of Alchemica represent the budget for Alchemica to be distributed ingame over the lifetime of the Gotchiverse. 

Of the 15% total allocation, 33.3% (or 5% of total supply) will be allocated via the smart contract “Boost” system for adjacent alchemica. These tokens are not vested, but can only be minted via Gotchiverse gameplay. 

The remaining 66.6% (or 10% of total supply) will be vested via the same schedule as the Ecosystem allocation above, and used primarily for Alchemical bubble ups, Dungeons, and other in-game rewards that are not distributed via smart contract. 

#### Parcel Allocations (50%)
50% of all Alchemica has been earmarked for Parcels in the Gotchiverse, including all three Acts and replenishings in each Act. 

Act 1 will distribute roughly 25% of the total supply, whereas Act 2 and Act 3 will distribute 15% and 10%, respectively. 

#### Average Alchemica Per Parcel (Confirmed in Paatch v0.1)
Similar to the “Portal” mechanic in Aavegotchi, REALM Parcels must be surveyed before they finally reveal the quantity of Alchemica that rests inside them. The surveying process is an onchain call to Chainlink VRF, a truly randomized number generator.

When the Gotchiverse is released, all available REALM Parcels can be surveyed if their owners choose to, or the surveying process can be delayed until a future date. 

The range of Alchemica available for each Parcel Type is listed below, for the entire Act 1, and for Round 1 of Act 1, which distributes roughly 25% of the Alchemica contained within.

Note that total Alchemica within a Parcel is cumulative, which means future Surveyings will add additional Alchemica on top of the total. 

#### Surveying Alchemica Range 
The range of possible Alchemica that can be discovered during each surveying round. To prevent a bad player experience, the “minimum” that can be surveyed is 20% of the average, and the “maximum” is 1.8x of the average. 

For example, the range of values of FUD for a Humble parcel for the entire Act 1 will be 5694 to 51251, averaging out to 28,473. 

We believe this provides for interesting gameplay, while also providing a sufficient “safety net” for even the unluckiest of players. 

#### Crafting Revenue Distribution
Whenever an Installation, upgrade or other item is crafted within the Gotchiverse, the underlying Alchemica are sent to four distinct places.

* **The Great Portal** is the heartbeat of the Gotchiverse. Whenever items are crafted in the Gotchiverse, 35% of that Alchemica is captured by the most important Portal in the game. As the Great Portal’s treasury balloons, a great prophecy waits to be fulfilled…  Any Alchemica in excess of the Great Portal Capacity will be recycled back into the ecosystem via Alchemical and Group Channeling, slowing the minting rate for new tokens. Initially, the Great Portal Capacity will be 1% of total supply, but this can be altered by AavegotchiDAO. Speaking of AavegotchiDAO…

* **AavegotchiDAO**, the governing body of the Aavegotchi Protocol, receives 30% of the crafted Alchemica split. This Alchemica balance represents a powerful opportunity for the community to have a direct stake in treasury management and put these tokens to work on the protocol’s behalf.

* **Pixelcraft Studios**, the Gotchiverse’s dev house, also receives 30% of crafted Alchemica. These Alchemica balances can quickly be put to work in any endeavor supporting the growth of the Aavegotchi protocol and Gotchiverse game. Besides just diamond-handing, user acquisition, strategic allocations and marketing initiatives are some of the ways Alchemica can be put to work. 

* **A 5% token burn** is the cherry on top of this Crafting Revenue Distribution plan. A burn of this significance will help to offset the various ebbs and flows of Alchemica inflation, whether it be from player adoption spikes, planned Alchemical events like The Great Battles, or very lucky surveyed REALM Parcels.


#### Parcel Boosts
Parcel Boosts are spots of Alchemica directly adjacent to REALM Parcels within the Gotchiverse. Unlike surveyed Alchemica, which is randomly given by VRF, Parcel Boosts are base amounts of Alchemica that are added to the total Alchemica of a Parcel after surveying. 

Alchemica Boost amounts are 1000, 500, 250, and 100 for FUD, FOMO, ALPHA, and KEK respectively. 


#### Replenishings
After each Great Battle in Act 1, players will be able to survey their Parcel again, rolling to get more Alchemica. The Boost amount above will be added onto the amount rolled by the player for each surveying round.

#### Alchemica Bubble Ups
The Bubble Ups concept grew out of the debated Paatch 0.1c where Increase Boost Amounts failed to pass. Alchemica Bubble Ups provide additional utility to boosts, while still requiring the player to actively harvest the Alchemica that bubbles up.

Alchemica Bubble-ups are sporadic (but not infrequent) events where Alchemica pickups appear on top of deposits of Alchemica in the Gotchiverse, especially near active parcels. Notably, it is Pixelcraft’s Gameplay vested release allocation that will support these Alchemical releases, although AavegotchiDAO can also vote to supplement the amount.

## Part 2: Installation Traits and Recipes
*Confirmed but not immutable*

### Recipes
Crafting Installations and upgrading them to become more powerful is an important part of the Gotchiverse experience. Different Installations require different “recipes” to craft and upgrade, which is why the Aadepts provided us with a handy Recipe Book for reference! You can find the latest Recipes here. 

Installations and their upgrades also have a “Craft Time”, which is measured in blocks on the Polygon network. One block equals roughly 2.2s in human time. Most (but not all) Level 1 Installations have a craft time of “Instant”, which means they are crafted immediately, while those with craft times longer than “Instant” will enter into a crafting queue and get sent to their owner upon completion. 

This crafting/upgrading process can be accelerated by spending an ingame currency currently known as “GLMR” (but which will likely be renamed before launch). GLMR can be acquired by providing liquidity between GHST and Gotchus Alchemica tokens on the Gotchus Alchemica Exchange. 

Harvest Rate, Capacity, and Spillover
Haarvesters and Reservoirs are special Installations that allow mining of Alchemica from beneath the Gotchiverse surface.

Each type Haarvester is capable of harvesting one type of Alchemica, and each Reservoir can hold a certain amount of one type of Alchemica. As the Installation level increases, Harvest Rate and Capacity both increase. 

Spillover is another property of Reservoirs that determines how much and how far Alchemica spills when it is claimed from the Reservoir. Lower level Reservoirs have higher Spillover Amount and Spillover Radius, and these amounts are reduced with further upgrades. 

You can consult the Recipe Book [here](https://github.com/aavegotchi/gotchiverse-bible/blob/main/RecipeBook.pdf) to see exact Harvest Rates, Capacities, and Spillover Rates. 
Removing Installations
Once an Installation is added to a Parcel, it can be upgraded or removed. Removing the Installation destroys the underlying NFT, but returns 50% of all Alchemica spent on the Installation and its upgrades to the original owner. 

## Part 3: Aavegotchi Trait Mappings
*Confirmed but not immutable*

***IMPORTANT NOTE:** These traits have not been tested yet, they are theoretical applications of Aavegotchi traits to various mechanics of the game. It is possible that during actual gameplay testing, Pixelcraft or the community discover that some traits are underpowered or overpowered, and thus vote to change them.* 

Are you ready to see what your favorite Gotchi can do, uniquely, within the Gotchiverse? Speed, carrying capacity and even handling are influenced by your Aavegotchi’s six traits. Special attention was paid to balancing the pros and cons of each trait's influence. For example, a Gotchi with high aggression deals boosted melee damage but also sees a reduction in armor. Read on to discover what your Gotchi’s traits mean in the Gotchiverse!

### Trait Definitions

* Health Points: Your Gotchi’s total health. Also doubles as a Stamina meter.
* Armor: Reduces how much damage your Gotchi takes when attacked.
* Attack Speed: Your Gotchi’s attack rate (how many attacks per second).
* Carrying Capacity: How much Alchemica your Gotchi can carry before needing to unload.
* Ethereality: Your Gotchi’s chance to evade enemy attacks and to reduce wall knockback.
* Handling: Your Gotchis’s degree of inertia in movement and acceleration/deceleration.
* Health Regen Speed: Your Gotchi’s speed of health / stamina regeneration.
* Melee Damage: How much damage your Gotchi’s melee attacks will inflict.
* Movement Speed: Your Gotch’s speed of movement.
* Ranged Damage: How much damage your Gotch’s ranged attacks will inflict.
* Vision Range: How far out your Gotchi can see the world (zoom level).

### Trait Mappings
*Confirmed but not immutable*

In the spirit of game balancing, NRG, AGG, SPK, BRN, and EYC all provide benefits while simultaneously lowering another trait. This mechanism helps ensure that no Gotchi is too overpowered, while also creating a unique gameplay experience for almost every Gotchi.

Note that the EYS category currently does not have this tradeoff – the benefits conferred by Eye Shape traits are the icing on top of the cake!

### General Trait Mappings

General Trait Mappings [Graphic]

### Eye Shape Specific Mappings

Eye Shape Specific Mappings [Graphic]

### Collateral-Specific Mappings

Collateral-Specific Mappings [Graphic]

### Rarity Score
The Rarity Score of an Aavegotchi directly affects its traits on the curve, but Gotchis with higher Rarity Score (using the original BRS formula) also enjoy one more benefit in the Gotchiverse – more Health Points! As an Aavegotchi’s traits approach (and even go beyond) the extremes of 0 and 99, its base Health Points increase non-linearly (exact values to come in the Gotchi Traits 2 Chapter).  

### Experience Levels
In Aavegotchi, for every three on-chain levels an Aavegotchi gains, it earns one Spirit Point that can be applied towards increasing NRG, AGG, SPK, or BRN permanently. 

The Gotchiverse also offers benefits for leveling up, but instead of one point per three levels, it is three points per level, and the points can be put towards increasing Health Points, Damage, and/or Armor. 

Note that these trait points are not stored onchain and do not affect the onchain state of your Aavegotchi.

Get a head start on leveling up your Gotchi by ranking in minigame leaderboards, voting in AavegotchiDAO, and participating in the Discord's XP events.

---

**That’s it for this second chapter!**

Look forward to Chapters 3 and 4 where we’ll start diving into Alchemica Channeling, Wearable Traits, Guilds and more!


## Get Involved

Use the [Issues](https://github.com/aavegotchi/gotchiverse-bible/issues) feature of Github to ask questions, make suggestions, or share your thoughts on the GB! 
