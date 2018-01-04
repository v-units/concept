# Whitepaper
Version 0.9 (04.01.2017)

## Pending Tasks

- Add some graphics explaining better some concepts.

## Table of Contents

- [Introduction](#introduction)
- [Overview](#overview)
- [Network](#network)
- [Blockchain](#blockchain)
- [Trusted Parties](#trusted-parties)
- [Addresses & Certification](#addresses-and-certification)
- [Voting](#voting)
- [Value Units Foundation Fund](#value-units-foundation-fund)
- [Emission Price](#emission-price)
- [Block Target & Reward](#block-target-reward)
- [Licensed Certification Authority](#licensed-certification-authority)
- [Licensed Emitter](#licensed-emitter)
- [Licensed Depositary](#licensed-depositary)
- [Licensed Precious Metal Dealer](#licensed-precious-metal-dealer)
- [Identity Provider](#identity-provider)
- [Consensus Algorithm](#consensus-algorithm)
- [Genesis Block](#genesis-block)
- [Emission & Destruction](#emission-destruction)
- [Value Instructions (vInstructions)](#value-instructions)
- [Value Parameters (vParameters)](#value-parameters)
- [Glossary](#glossary)
- [References](#references)

<a name="introduction"/>

## Introduction

In this technology and media-driven age, the stratospheric rise of cryptocurrencies, electronic currencies which are decentralised, anonymous, and freely tradable, is not surprising. Currencies such as Bitcoin and Ethereum have demonstrated that it is possible to use the internet, now ubiquitous and fast in many countries, to make a decentralised value-transfer system which is virtually free to use and can be shared across the world at very fast speeds. It can seem that there is an ideological gap between hard-asset investors, such as those preferring to invest in precious metals such as gold and silver, and the early adopters of electronic currencies. However, there are many similarities between these two currencies, such as the finite supply (both precious metals and most cryptocurrencies need to be mined and are limited) and durability (both of these value-storage methods retain their value almost indefinitely). The time is therefore ripe for a cryptocurrency based on precious metals, retaining the security of the latter, while adding the flexibility of an electronic currency.

Value Units, is such a currency, based on precious metals which represent the Value Basket (the book value of the cryptocurrency). Additionally to this most iconic feature, Value Units want to provide other distinct capabilities, by taking the best approaches of other cryptocurrencies and combining them with new breakthrough ideas to build the best available cryptocurrency in the market.

<a name="overview"/>

## Overview

The Value Units Foundation (VUF) has been working for month in designing a first class unique cryptocurrency that offer many interesting and innovative features that can't be found in other alternatives in the diverse cryptocurrency world. Value Units (vUnits) besides being a currency system will have a governance system included in the blockchain that will allow anyone holding vUnits to participate and help shaping the future of Value Units. The VUF will premine 100'000 Value Shares (vShares) which will be distributed to it's members and will be used for monitoring the correct operation of the system. Most proposals are initiated by the VUF but need to be approved by the majority of vUnits holders before being enacted. Most vUnits on the other hand are emitted by depositing precious metals into the licensed depositaries and only a small percentage (0.8%) per year are provided to the super-nodes (for running the networks that support the system), miners (for mining new blocks) and licensed depositories (for storing the precious metals). The Value Units emission process requires a party to purchase a quantity of precious metal from a licensed emitter. The precious metal is then transported to a licensed depositary which then certifies that the precious metals have been received. Finally the members of the VUF, by using their vShares approve the emission. In each emission an additional percentage of vUnits is emitted and distributed between the licensed emitter, licensed precious metal dealers, licensed certification authority and the Value Units Foundation Fund (VUFF). This fund is used for paying developers and members of the foundation that operate in the day to day operations that support the Value Units system. This rule as many other can be changed by the VUF in cooperation with the community (the starting rules for the distribution of vUnits in the emission process are found further down in this document under the description of the available blockchain parameters and their default values). The emission is the only process in the Value Units governance system that can occur without the consent of the community, but requires always the cooperation between a licensed emitter, a licensed depositary and 66% of the members of the VUF. The approval of new emitters/depositary and all other changes to the parameters in the blockchain are proposed by the VUF and vetted by the community.  

**Security:** most cryptocurrencies are secure by definition and as seen with Bitcoin after 8 years the technology has proven this. This security is provided by a correct use of the underlying technology, but as human are operating the servers, wallets, keys and clients involved in the operations of these cryptocurrencies experience has shown that they are often stolen and hacked and because their irreversible nature often used in scams and frauds. Additionally most cryptocurrencies requires a running worldwide network. In the last 20 years we got used to expect internet to be available almost always and everywhere (even in planes and satellites), but we don't know what would happen if a major war would rip the world apart. Without the network that sustains these cryptocurrencies, their real value would be 0. We can also not foresee what will happen in the future regarding government regulation and possible implosion of the cryptocurrency bubble. Value Units addresses these concerns with two main strategies: 

First, vUnits when emitted are backed by precious metals which are stored decentralized around the world. In the event of a major disturbance of the internet and by hoping that there still is some kind of government and law enforcement, a recovery of the precious metals can be organized and returned to the vUnits holders based on the last consensus blockchain that was kept by all parties before the network collapsed. 

Second, Value Units requires every party holding vUnits to go through an identification process by a decentralized Licensed Certification Authority (LCA). The identity of the vUnits holder is only know to the corresponding LCA that issued his identity certificate and in case of scams and fraud can be subpoenaed by the corresponding law enforcement authority accordingly. Value Units build upon existing and proven cryptocurrency capabilities and as such with this additionally measures can provide a top secure and trusted environment to the community.

**Community:** the community is a key factor in the Value Units ecosystem and something that is less relevant in most cryptocurrencies. The majority of them is controlled by different groups of interest (miners, exchanges, wallets and developers) and the only vetting that is available to the community only holding the digital asset is selling it and not participating in the network. They can give their opinions in forums and chat groups but there is not voting involved and the interest groups have the final vote in most situations. The history has shown that in this cases the community can split and two different cryptocurrencies can emerge (Bitcoin, Bitcoin Cash and Bitcoin Gold, Ethereum and Ethereum Classic). In 100% digital currencies this is disrupting, but not the end of the networks, the new currencies tend to coexist and the value is splitted between them. It's a bit confusing for the end user, because they don't understand which of the new currencies is the real thing and which one he should continue using from that moment on. In the case of Value Units with the collateral of precious metals, such a split would be very complicate, confusing and legally challenging. Because of this the VUF will put all the effort to always find consensus and let the community vote on almost everything. Most consensus rules are part of the blockchain and can be changed by a proposal from the VUF and an approval from the community. Each member of the community has one vote per identity certificate that he holds. 

The LCA is responsible of issuing one identity certificate per user. In a perfect scenario (when all rules are met) and taking in consideration a community member that goes full lengths and requests a identity certificate from every existing LCA, he would have the same number of votes (per voting) as the number of valid LCA's.  The VUF agrees this isn't a perfect solution, but they have selected this approach over a vote count based on the vUnits holdings, because they feel it's more democratic.
         
**Decentralization:** like all cryptocurrency the primary focus of Value Units is to provide a decentralized currency system that doesn't need of any type central authority. This is achieved by the common characteristic shared with all cryptocurrencies and supported by the blockchain technology. Value Units have a further challenge because the precious metals which back the digital units should also be distributed around the world, without risking the theft of those securities. 

For this purpose the community relies on well established companies that are responsible for storing the precious metals in a secure manner. These companies are willing to comply with the rules of the Value Units blockchain and are responsible on signing new emissions (when receiving precious metals) and destroying vUnits (when returning precious metals). To avoid fraud and scams, these companies need to pass a thorough audit by the VUF and will be recorded in the blockchain as a valid Licensed Depositary (LD) after successfully passing the audit and a 2-week voting where an approval of 66% of all valid votes is required. The cap on cost of the audit needs to be paid in full by the LD to the VUFF. Once the audit is finished the unspent costs of the audit are returned to the company applying for the depositary license. The VUF will be responsible for appointing an impartial public notary that will audit the precious metals in regular intervals and the public documents will be published regularly into the blockchain. 

Should the VUF discover a problem with a depositary, by an audit or information provided by a community member then the VUF can suspend the LD immediately (adding them in the blockchain to the suspension list and therefore disabling any emission that they are currently or in the future participating) and submit the decision to a 2-week voting where a simple majority (66%) can approve or reject the decision of the VUF. Should the suspension be approved by the community then it's final and the depositary has to reapply to the license and follow the proper audit process if they want to continue as a depositary of vUnits. Otherwise they can continue being a depositary and the VUF can't re-suspend them until the corresponding waiting period (1 Month) has passed. In the case a license of a depositary is suspended indefinitely, The VUF will try to find a solution to recover as much as possible from the stored precious metals and distribute them to other depositories or sell them and destroy the corresponding vUnits. 

The VUF itself is decentralized and all their voting are based on vShares that are distributed between it's members.

**Privacy/Anonymity:** the current version of most cryptocurrencies aren't very anonymous. The main problem is that every transaction is publicly logged. Anyone can see the flow of coins from address to address. Alone, this information can't identify anyone because the addresses are just random numbers. However, if any of the addresses in a transaction's past or future can be tied to an actual identity, it might be possible to work from that point and guess who may own all of the other addresses. This identity information might come from network analysis, surveillance, or just Googling the address [1536]. The VUF is studying two approaches regarding privacy and this will be an important feature of the next planned major release of Value Units. The first approach is similar to Private Send from Dash which adds privacy to transactions by combining identical inputs from multiple users into a single transaction with several outputs. Due to the identical inputs, transactions usually cannot be directly traced, obfuscating the flow of funds. PrivateSend makes Dash "fungible" by mixing the coins in the same denomination with other wallets, ensuring that all coins are of the same value [1520]. The second approach is to introduce zero-knowledge proofs like Zcash does, to guarantee that the transactions are valid despite the fact that information about the sender, the recipent, and the amount transacted all remain hidden [1138].

**Legality:** theft, scams and frauds are easier because of the structure and lack of regulation of cryptocurrencies. There is no way to retrieve coins that are stolen or conned and no way of revert transactions. Additionally cryptocurrency can be used for money laundering and participants vulnerable to accusations of aiding criminals and terrorists. Because the blockchain is public, most cryptocurrencies still allows the movement of funds to be viewed by the public, so the cryptocurrency is not completely at the mercy of criminals [1141]. Value Units want to take the regulation one step further and require that every involved party is known and in case of an criminal act, the funds related to the activity can be traced back to the responsible. The identity of the vUnits holders will be kept private and not included in the blockchain, but every receiving address in the Value Units system will have an related identity certificate that is used for validating that the recipient is know to a specific LCA, that will hold the identity of the parties in a secure manner. This will allow law enforcement authorities to know which entity is the safekeeper of the identity involved in a criminal activity and subpoena it accordingly.

**Speed:** cryptocurrencies rely heavily on confirmation through mining to stop double spending attacks. Although, a huge accomplishment in technology, it fails to compete with the near instant transaction speed of credit cards due to their use of a centralized authority. Value Units will is working on two concepts to match the speed of credit card transactions. The VUF has a prototype that is based on the concept of Masternodes from Dash and are called super-nodes. Fast validation of payment via transaction locking and super-node consensus could be achieved, avoiding the need to wait for confirmation via a new block. This approach can reach speeds nearly as fast as credit cards. In most cases a transaction should be validated by the network within a few seconds of originally being broadcasted. Clients will respect the authority of the super-node network and as a result the network can come into consensus without a block event happening. By using the super-node network as an authority and selecting super-nodes via a deterministic algorithm powered based on the proof-of-work, we gain a system that give us comparable transaction time to a credit card transaction while also being tamper resistant, backwards compatible and secure [1911]. The the need of speed is one of the most important characteristics of vUnits, an as such the VUF wants to invest in other approaches to be able to find the best solution in the long term. The concept of an Hashgraph proposed by Leemon Baird is gaining traction in the community and it's an interesting alternative to the blockchain. The VUF will invest in a prototype based on an Hashgraph and will do extensive tests to determine which concept will be used in the next major release of vUnits.

**Efficiency/Cost:** the original promise from most cryptocurrency was that the transactions cost of a blockchain system would be far less that those of the most common payment systems used by the world. This promise hasn't been met by all cryptocurrency and in the case of Bitcoin a transaction can cost at times dozens of dollars. These transactions fees would be even higher if there wasn't a block reward for the miners in each block. The amount of electricity used to power the Bitcoin network is currently enormous and in the last couple of years there has been a vicious cycle that is making Bitcoin less and less eco-friendly. The price has sky-rocketed and because of this more and more miners are interested in participating adding more and more power to the network, by this the price has increased even further. Many analyst have tried to estimate the real daily electric consumption of the Bitcoin network and some have went so far to say that worldwide Bitcoin mining could power the daily needs of more than 800'000 average american homes [1622]. There are different approaches that could reduce the efficiency of the network.  The VUF has the goal to provide a zero fee transaction network. There are two problems that need to be solved to achieve this goals. 

First, a consensus algorithm is required that is better than the current proof-of-work algorithms that are based solely on brute force solving algorithms which are directly related to the amount of electrical consumption. Proof of Stake currencies can be several thousand times more cost effective than Proof of Work; which relies on energy use but some authors argue that proof-of-stake is not an ideal option for a distributed consensus protocol. One problem is usually called the "nothing at stake" problem, where (in the case of a consensus failure) block-generators have nothing to lose by voting for multiple blockchain-histories, which prevents the consensus from ever resolving. Because there is little cost in working on several chains (unlike in proof-of-work systems), anyone can abuse this problem to attempt to double-spend (in case of blockchain reorganization) "for free". [1645]. Another alternative would be moving from a blockchain into an hashgraph, which wouldn't require neither proof of work nor a leader. Moreover, it promises to deliver low-cost and good performance with no single point of failure. This superior distributed ledger technology would eliminate the requirement for massive computation and unsustainable energy consumption like those of proof-of-work cryptocurrencies [1308].

Second, a anti-spam measure to avoid an attacker of floating the network with transactions because they have zero fee and as such zero cost for the sender. Value Units will start as a proof-of-work system with low fees and we will then investing heavily in selecting the best solution to achieve a eco-friendly network with zero fees transactions. There are many proven solutions already in the cryptocurrency world and is just a matter of taking the most adequate of these approaches for the Value Units system.

**Stability:** the need for stability is not unique to cryptocurrency. Any currency needs to be stable in order to be used as a trusted medium of exchange. The more that prices rise and fall, the more ordinary people will shy away from using the coins for everyday transactions. Whether they hoard the coins in the hope that prices will rise sharply soon, or they avoid using them altogether for fear that they will lose all of their value, people are not yet accustomed to seeing cryptocurrency as real money. Worse, the unpredictability of prices wreaks havoc on regular money services, like remittance, currency conversion, and the use of ATMs. In order to use cryptocurrencies, businesses have to hedge their risks by charging exorbitant fees. Bitcoin ATMs can charge up to 15 percent just to convert to fiat currency. This totally defeats the original purpose of cryptocurrencies, which was to offer a cheaper and more flexible alternative to other payment methods. With no advantage over government-printed money, why would the average person use them? [1421] 

The original intention of the creator of Bitcoin isn't clear if it was to create a stable or deflationary currency. In an email to a colleague he wrote "If the supply of money increases at the same rate that the number of people using it increases, prices remain stable. If it does not increase as fast as demand, there will be deflation and early holders of money will see its value increase. Coins have to get initially distributed somehow, and a constant rate seems like the best formula." [2351]. 

Value Units should be used as currency and as such we will take many measures to achieve price stability in the medium term. The emission of new vUnits is tied to the deposit of precious metals as collateral, but this emission can be also steered by the price at which the vUnits will be emitted. In the long-term the emission price will be capped at 6.58% over the Value Basket price (more on this in the emission chapter of this document). By this Value Units will have a price stability band, because if the market price goes under the Value Basket price, users would destroy the units and convert them back into precious metals, if the market price goes over the emission price, users would prefer emitting at emission price then buying from the market (increasing the supply in the process).

**Fungibility:** the current version of most cryptocurrencies aren't perfectly fungible. Fungibility is an attribute of money, that dictates that all units of a currency should remain equal. When you receive money within a currency, it should not come with any history from the previous users of the currency or the users should have an easy way to disassociate themselves from that history, thus keeping all coins equal. At the same time, any user should be able to act as an auditor to guarantee the financial integrity of the public ledger without compromising others privacy [1521]. 

In the current cryptocurrency world all coins aren't equal, when coins are stolen the receiver addresses are informed to all relevant parties and they are capable of blocking or seizing coins from such sources. An innocent person may not be full aware if the received coins are marked as stolen or not. With the proposed functionality for private transactions or zero-knwowledge proof the origin of the vUnits can't be traced and they become fungible by definition.   

<a name="network"/>

## Network

The Value Units network will start with client-nodes and depending on the decision for the second major release, will either move to a blockchain with super-nodes or an hashgraph. To run a super-node, the users would need to store 1'000 vUnits as something akin to collateral, although unlike traditional collateral, the Value Units never leaves the user's possession and has no chance of being forfeited. It can be moved or spent at any time by the user - doing so simply removes the super-node from service and makes it ineligible to receive rewards.

An addition to the core protocol is made to support a second P2P network, which propagates messages synchronizing a list of all known super-nodes across the network. In result, all clients on the network know about all super-nodes and can utilize their services at any time.

Unlike Gnutella which uses a hierarchical network of client-node and super-nodes, where client-nodes only make a connection to one super-node:

![Hierarchical Network](http://www.v-units.com/assets/images/supernodes-hierarchical.png)

Super-nodes and normal peers are equal in their connection behaviour, forming a classical P2P network:

![P2P Network](http://www.v-units.com/assets/images/supernodes-p2p.png)
 
Running the appropriate peer software and matching the requirement (static IP, 1'000 vUnits) actually each node/peer can turn into a super-node.

Having a network of incentivized peers opens the possibility for further applications.  

<a name="blockchain"/>

## Blockchain

The Value Units system builds on top of existing concepts and technologies. In the Value Units Blockchain many parameters that are hard coded into other blockchains are variable and can change during the lifetime of the blockchain. These Value Parameters (vParameters) can be proposed by the VUF and approved by the community. Additionally the Bitcoin protocol includes a concept called scripts that can be used for "smart contracts". UTXO in Bitcoin can be owned not just by a public key, but also by a more complicated script expressed in a simple stack-based programming language. In this paradigm, a transaction spending that UTXO must provide data that satisfies the script. Indeed, even the basic public key ownership mechanism is implemented via a script: the script takes an elliptic curve signature as input, verifies it against the transaction and the address that owns the UTXO, and returns 1 if the verification is successful and 0 otherwise. Other, more complicated, scripts exist for various additional use cases. For example, one can construct a script that requires signatures from two out of a given three private keys to validate ("multi-sig"), a setup useful for corporate accounts, secure savings accounts and some merchant escrow situations. Scripts can also be used to pay bounties for solutions to computational problems, and one can even construct a script that says something like "this Bitcoin UTXO is yours if you can provide an SPV proof that you sent a Dogecoin transaction of this denomination to me", essentially allowing decentralized cross-cryptocurrency exchange [1602]. 

However, the scripting language as implemented in Bitcoin has several important limitations [1602]:

- **Lack of Turing-completeness:** that is to say, while there is a large subset of computation that the Bitcoin scripting language supports, it does not nearly support everything. The main category that is missing is loops. This is done to avoid infinite loops during transaction verification; theoretically it is a surmountable obstacle for script programmers, since any loop can be simulated by simply repeating the underlying code many times with an if statement, but it does lead to scripts that are very space-inefficient. For example, implementing an alternative elliptic curve signature algorithm would likely require 256 repeated multiplication rounds all individually included in the code [1602].
- **Value-blindness:** there is no way for a UTXO script to provide fine-grained control over the amount that can be withdrawn. For example, one powerful use case of an oracle contract would be a hedging contract, where A and B put in $1'000 worth of BTC and after 30 days the script sends $1'000 worth of BTC to A and the rest to B. This would require an oracle to determine the value of 1 BTC in USD, but even then it is a massive improvement in terms of trust and infrastructure requirement over the fully centralized solutions that are available now. However, because UTXO are all-or-nothing, the only way to achieve this is through the very inefficient hack of having many UTXO of varying denominations (eg. one UTXO of 2k for every k up to 30) and having O pick which UTXO to send to A and which to B [1602].
- **Lack of state:** UTXO can either be spent or unspent; there is no opportunity for multi-stage contracts or scripts which keep any other internal state beyond that. This makes it hard to make multi-stage options contracts, decentralized exchange offers or two-stage cryptographic commitment protocols (necessary for secure computational bounties). It also means that UTXO can only be used to build simple, one-off contracts and not more complex "stateful" contracts such as decentralized organizations, and makes meta-protocols difficult to implement. Binary state combined with value-blindness also mean that another important application, withdrawal limits, is impossible [1602].
- **Blockchain-blindness:** UTXO are blind to certain blockchain data such as the nonce and previous block hash. This severely limits applications in gambling, and several other categories, by depriving the scripting language of a potentially valuable source of randomness [1602].

Thus, there are three approaches to building advanced applications on top of cryptocurrency: building a new blockchain, using scripting on top of Bitcoin, and building a meta-protocol on top of Bitcoin. Building a new blockchain allows for unlimited freedom in building a feature set, but at the cost of development time, bootstrapping effort and security. Using scripting is easy to implement and standardize, but is very limited in its capabilities, and meta-protocols, while easy, suffer from faults in scalability [1602]. 

Value Units goal is to become a strong focused cryptocurrency, which supports the main user stories that are exposed in this whitepaper and should not be used for building decentralized applications. With that in mind, we don't require all the capabilities of scripting and can reduce overhead by changing the concept of a transaction containing scripts into a transaction containing a set of instructions. These instructions are called Value Units Instructions (vInstructions) and provide common functionality which are less flexible but easier to test and will reduce the risk of programming errors generating financial losses. The parameters used by the vInstructions to operate on the blockchain are called Value Units Parameters (vParameters) and can be changed by the VUF and the community through the governance system that is part of the Value Units system.

The Value Units blockchain like most cryptocurrencies are composed of blocks that have a number of transactions which contain one to many vInstructions. The instructions that are available in the Value Units blockchain are explained in the Value Units Specification and can be categorized in the following types:

**Emission Instructions:** are used for the emission process. The  involved parties need to use the corresponding instructions for fulfilling all steps (request, issuing proof-of-precious-metal, issuing proof-of-depositary and issuing proof-of-emission) in the process.
 
**Payment Instructions:** are used for transferring vUnits from one address to another address. These instruction provide complex scenarios like multi-sig addresses or timed payment instructions. As previously explained we will not implement a smart contract platform but will be monitoring the requirements of the users and implement features based on the community feedback. The instructions also include a special subset for starting a payment out of the VUFF.

**Voting Instructions**: are used for using the voting rights that each VUF and community member has. 

**Certification Instructions**: are used by the LCA to issue certificates, to validate addresses so they can be used for voting or payment purposes..

**Auditing Instructions**: are used by the VUF and the involved parties for requesting and managing the audit process of LE's, LPMD's, LCA's and LD's.

**Publication Instructions**: are used by the VUF to submit important documents into the blockchain for public review by the community.

The VUF is responsible for publishing Guidelines, Procedures, Rules, Public Notarial Documents and Audits. These documents will be always published on the VUF Website, but to reduce the centralization and risk of an attack, important document will also be published into the blockchain. The publication proposal will be issued by the VUF and will be approved by the community through a standard voting procedure. The entire document or a link with a corresponding hash to a torrent or other file sharing platform can be published into the blockchain. Highly important documents should be published entirely into the blockchain, but to reduce the size in storage, lesser important documents should be stored using the link option.

Should the Value Units Network replace the blockchain with an hashgraph in the future, the same instructions and transactions would be supported in the network and just the consensus algorithm and the way the data is stored will be changed.

<a name="trusted-parties"/>

## Trusted Parties

The Value Units ecosystem is based on several parties that need to be trusted and are audited before being accepted into the network. The LE's, LPMD's, LCA's and LD's request to be accepted into the network by following theses steps:

1. A new party broadcast a request instruction (RequestEmitterLicense, RequestPreciousMetalDealerLicense, RequestCertificationAuthorityLicense or RequestDepositaryLicense) into the blockchain. These requests need be signed with a private key that has access to the fee required for initiating the auditing process. The public/private key pair used for this request is highly confidential, because if the audit process is successful is the key used for signing all further instruction and certifying the identity of the trusted party. 
2. The VUF appoints an external entity for performing the audit on the new party.
3. The results of the audit are published into the blockchain (using the publication process specified in the Value Units Specification)
4. All vShares holders can then vote on the audit by broadcasting the corresponding instruction (ApproveEmitterAudit, ApprovePreciousMetalDealerAudit, ApproveCertificationAuthorityAudit or ApproveDepositaryAudit, including their addresses and signed with the private key; the amount of vShares they have is also the weight of their vote). Only vShares that have not being used after the timestamp of the request instruction (RequestEmitterLicense, RequestPreciousMetalDealerLicense, RequestCertificationAuthorityLicense, RequestDepositaryLicense) can approve the trusted party. 
5. If the threshold of total shares is met, then the audit approval instruction (EmitterAuditApproved, PreciousMetalDealerAuditApproved, CertificationAuthorityAuditApproved or DepositaryAuditApproved) is broadcasted into the blockchain to officially start the voting round for the community. 
6. The community can vote by broadcasting an (ApproveEmitterLicense, ApprovePreciousMetalDealerLicense, ApproveCertificationAuthorityLicense or ApproveDepositaryLicense, including their addresses and signed using their identity keys). 
7. If the threshold is met after one month (or before) the new parameter is then valid and any node can broadcast the EmitterLicenseApproved, PreciousMetalDealerLicenseApproved, CertificationAuthorityLicenseApproved or DepositaryLicenseApproved). Otherwise the license is dismissed.

Once their audit has been approved by the community their public key is part of the blockchain and from that moment on they are capable of broadcasting the instructions related to their area of concern and signing them with their private key.

<a name="addresses-and-certification"/>

## Addresses & Certification

The Value Units system uses public addresses like most cryptocurrencies as recipient for payments. Due to privacy concern a new address should be used for each payment. To be able to delegating address generation to an untrusted peer we are using a similar approach as Bitcoin by implementing a deterministic wallet.  

A deterministic wallet is a system of deriving keys from a single starting point known as a seed. The seed allows a user to easily back up and restore a wallet without needing any other information and can in some cases allow the creation of public addresses without the knowledge of the private key. Seeds are typically serialized into human-readable words in a Mnemonic phrase. [1831]

Certain types of deterministic wallet additionally allow for the complete separation of private and public key creation for greater security and convenience. In this model a server can be set up to only know the Master Public Key of a particular deterministic wallet. This allows the server to create as many public keys as is necessary for receiving funds, but a compromise of the MPK will not allow an attacker to spend from the wallet. They can alternatively be used to enable completely offline storage and spending, where an offline computer knows the private key and an online one knows only the MPK. Transactions spending coins are ferried between the two computers via USB storage which avoids exposing the offline computer to a network-based attack. [1831]

The Value Units addresses require a further component, which identifies the recipient of the address. A Value Units user need to generate a two public/private identification key pairs which he needs to use to sign a certification request to the LCA. The LCA will then broadcast into the blockchain a certification instruction containing the first public key of the user and sign it by their own root or intermediate certificate, explaining that they hold the identity of the person which own the corresponding public/private key. With the first private key the user will be able to vote on the blockchain. Because the same public/private key is used for each vote, the community can observe the voting patterns, but will not be able to correlate them with an identity or addresses holding fund. The second public key will not be published in the blockchain but kept by the LCA in their identity profile.

When the Value Units user want to generate an address for receiving a payment, he or an untrusted peer, will create, like in most cryptocurrencies, a derived key using the deterministic key generation process. In Value Unites an additional key for proving his identity is required. The second public/private key pair which hasn't been published into the blockchain can be used for generating an additional key by an untrusted peer using a deterministic key generation process. The new public key can then be broadcasted by the user or the untrusted peer into the blockchain or directly to the LCA. Because the LCA holds on record the master public key they will be capable of verifying the address and can confirm that they hold the identity of the person which owns the parent public key. They can then broadcast that information into the blockchain or return it directly to the user or untrusted peer so they can compose the payment reception address with those two components.

The certification process is only required when generating payment addresses and can be  done beforehand. The user can also use the same identification key for many payment but then his privacy would be at risk. When spending the vUnits no involvment of the LCA is required. 

<a name="voting"/>

## Voting

The Value Units governance system provides several different instance where voting is required. VUF decisions are voted using vShares, community decisions are voted using the identity keys of each user. It's important to notice that to protect from vShares to double-vote, these vShares need to be unspent before the vote is casted. This means that new acquired vShares (during the voting period) are blocked from participating in the voting procedure.

Normally LCA's need to issue one identity key per user, but they could manipulate the system by producing many keys and changing the outcomes of a voting. To reduce the impact of such an attack, the votes casted by identities generated by an LCA's can't reach more than 50% (parameter that can be changed in the blockchain). In the case the votes coming from identities of a particular LCA represent more than 50%, their votes will be distributed proportionally. Let's consider the following example:

|LCA  |  For  | Against| Total| Total (%)|
|-----| :----:| :-----:| :---:| :-------:| 
|LCA 1|  1'259| 621    | 1'880| 69.66%   |
|LCA 2|  75   | 333    | 408  | 15.11%   |
|LCA 3|  22   | 128    | 150  | 7.98%    |
|LCA 4|  41   | 220    | 261  | 9.67%    |
|Total|  1'897| 802    | 2'699| 100%     |

In this case the users of  LCA 1 have casted more than 69.66%, so the vote of LCA 1 will be distributed proportionally and capped at the vote of the other LCA's (819 Votes). The new tally would be the following:

|LCA  |  For| Against| Total| Total (%)|
|-----| :--:| :-----:| :---:| :-------:| 
|LCA 1|  548| 271    | 819  | 50.00%   |
|LCA 2|  75 | 333    | 408  | 24.90%   |
|LCA 3|  22 | 128    | 150  | 9.15%    |
|LCA 4|  41 | 220    | 261  | 15.93%   |
|Total|  686| 952    | 1'638| 100%     |

The blockchain provides a set of instructions that can be used for voting and are explained in detail in the Value Units Specification.

<a name="value-units-foundation-fund"/>

## Value Units Foundation Fund (VUFF)

The VUFF is used by the VUF to support their operation. The responsibilities of the Foundation include:

- Continuous Development of the Technology
- Marketing and Advertisement
- Moderation of Community Forums, Chats and Discussions
- Give Support to the Community 
- Propose changes to Improve Value Units
- Controlling of New Emissions
- Audit of Certification Authorities, Emitters and Depositaries

Whenever new vUnits are emitted, some additional vUnits are emitted and distributed to the LE, LCA, LPMD and the VUFF address. The VUFF is a special address in the Blockchain, which requires a vote of the Value Units Foundation members (based on vShares) to transfer units into another address (threshold of 66%). The amount received by the VUFF depends on the quantity of units that are in circulation.

|Emitted Units          |  Distribution| VUFF   | LE     | LCA    | LPMD   |
|-----------------------| :-----------:| :-----:| :-----:| :----: | :----: |
|< 100'000'000 vUnits   |  25.00%      | 12.500%| 11.250%| 0.625% | 0.625% |
|< 200'000'000 vUnits   |  23.45%      | 11.725%| 10.553%| 0.586% | 0.586% |
|< 300'000'000 vUnits   |  21.95%      | 10.975%| 9.878% | 0.549% | 0.549% |
|< 400'000'000 vUnits   |  20.48%      | 10.240%| 9.216% | 0.512% | 0.512% |
|< 500'000'000 vUnits   |  19.04%      | 9.520% | 8.568% | 0.476% | 0.476% |
|< 600'000'000 vUnits   |  17.64%      | 8.820% | 7.938% | 0.441% | 0.441% |
|< 700'000'000 vUnits   |  16.27%      | 8.135% | 7.322% | 0.407% | 0.407% |
|< 800'000'000 vUnits   |  14.94%      | 7.470% | 6.723% | 0.374% | 0.374% |
|< 900'000'000 vUnits   |  13.63%      | 6.815% | 6.134% | 0.341% | 0.341% |
|< 1'000'000'000 vUnits |  12.35%      | 6.175% | 5.558% | 0.309% | 0.309% |
|< 10'000'000'000 vUnits|  11.11%      | 5.555% | 5.000% | 0.278% | 0.278% |
|Afterwards             |  5.26%       | 2.630% | 2.367% | 0.132% | 0.132% |

The amount of vUnits that are received by the VUFF decreases when the total supply of vUnits increases.

<a name="emission-price"/>

## Emission Price

The rules for calculating the emission price are defined in the blockchain and they pursue the following goals:

- The emission price should increase if there is strong demand and otherwise fall when the demand is weak.
- Price stability is an important long term characteristic for Value Units and as such a price band (between Value Basket and emission price) of 6.58% is the long term target. This would guarantee a collateral of precious metals of more than 90%.    
- In the short term to reward early adopters, the price band will be more flexible fixing the minimum emission price at 31.25%.

The Value Basket Value is the key for any price calculation and can be determined on the basis of the daily precious metals prices. The VUF will define for each precious metal which index will be used. As an example the gold value in the basket will be calculated on the basis of the London Bullion Market. The guidelines will be published by the VUF and approved by the community. The gold price itself will not be available in the blockchain. Using the total Value Basket Value the Value Basket Price (VBP) can be determined, which is the the collateral amount per vUnits which have been emitted until then. 

The Value Basket Price can be calculated taking the amount of precious metals stored by the LD and calculate their daily price based on the London Bullion Market published price and dividing it by the amount of vUnits that have been emitted until that moment. 

The minimum price band will change based on the total supply of vUnits. With an increment in the total emitted vUnits, the VBP per units will be more stable and the distribution to trusted parties will decrease. As a result the minimum price band can be narrowed by increasing the price stability further. 

|Emitted Units          |  Distribution| Minimum Emission Price| 
|-----------------------| :-----------:| :--------------------:| 
|< 100'000'000 vUnits   |  25.00%      | VBP + 31.250%         | 
|< 200'000'000 vUnits   |  23.45%      | VBP + 29.313%         | 
|< 300'000'000 vUnits   |  21.95%      | VBP + 27.438%         | 
|< 400'000'000 vUnits   |  20.48%      | VBP + 25.600%         | 
|< 500'000'000 vUnits   |  19.04%      | VBP + 23.800%         | 
|< 600'000'000 vUnits   |  17.64%      | VBP + 22.050%         | 
|< 700'000'000 vUnits   |  16.27%      | VBP + 20.338%         | 
|< 800'000'000 vUnits   |  14.94%      | VBP + 18.675%         | 
|< 900'000'000 vUnits   |  13.63%      | VBP + 17.038%         | 
|< 1'000'000'000 vUnits |  12.35%      | VBP + 15.438%         | 
|< 10'000'000'000 vUnits|  11.11%      | VBP + 13.888%         | 
|Afterwards             |  5.26%       | VBP + 6.575%          | 

The price stability band can be implemented, because if the market price goes under the Value Basket price (VBP), users would destroy the units and convert them back into precious metals, if the market price goes over the emission price, users would prefer emitting at emission price then buying from the market (increasing the supply in the process).

To add a further incentive to early adopter, the emission price will have flexibility component which will be reduced as the total supply increased. We already set the minimum emission price, that will be the target if within 90 days no new emissions have taken place, but if new emissions take place the emission price will increase by the total daily new emitted units in proportion to the total emitted units since the first block and the target reset to 90 days. The decrease will be distributed constantly over the 90 days.

Let's explain this using an example. There are 50'000'000 emitted vUnits with a Value Basket Price of 1.000 and the last emission price is fixed after the emissions on 27.12.2017 at 1.400. So the target emission price would be at 1.3125 (VBP + 31.250%) and should be reached by the 31.03.2018. If there is no emission until the 30.01.2018 the price will decrease constantly and will be set at 1.3416 on that date. If on the 31.01.2018 a new emission of 5'000'000 vUnits is successfully completed, the emission price would increase by 10% to Value Basket Price would rise to 1.4757 (1.3416 + 10%), the Value Basket Price will be at 1.0310 ([50'000'000 x 1.000 + 5'000'000 x 1.3416] / 55'000'000) and the new 90 target for the 01.05.2018 at 1.3532 (VBP + 31.250%).

This algorithm will provide new supply when it's needed and giving space to some healthy flexibility at the start. The emission price will be calculated when the VUF finishes approving the emission, an the nodes in the network need to consider the official precious metals prices to approve or reject a block containing an emission.

<a name="block-target-reward"/>

## Block Target and Reward

The block target is set at 30 seconds and the block reward is 0.000000761% of all existing vUnits at that moment. 25% of the reward goes to all LD's distributed by the amount of precious metals they have in store until that moment, 75% is distributed to the miner that mined the block. Should vUnits move forward to introduce super-nodes in to the network then the 75% would be shared between all super-nodes (37.5%) and the miner (37.5).

If the Value Units network moves to a hashgraph, the block reward could be removed altogether or replaced by another reward system.

<a name="licensed-certification-authority"/>

## Licensed Certification Authority (LCA)

The Licensed Certification Authority (LCA) is responsible for the identification of a subset of all users in the Value Units ecosystem. A company wishing to become a LCA requires to pay the cost of the audit by the VUF and needs to pass the audit and be approved by 66% of the community. The VUF defines for which countries the Certification Authority can issue certificates. It requires to fulfil the KYC (Know your customer) and AML (Anti-Money-Laundry) procedures defined by the VUF for each country which are communicated and published into the blockchain. The controls can include such things as the following [0408]:

- Collection and analysis of basic identity information such as Identity documents (referred to in US regulations and practice as a "Customer Identification Program" or CIP)
- Name matching against lists of known parties (such as "politically exposed person" or PEP)
- Determination of the customer's risk in terms of propensity to commit money laundering, terrorist finance, or identity theft
- Creation of an expectation of a customer's transactional behavior
- Monitoring of a customer's transactions against expected behavior and recorded profile as well as that of the customer's peers

These procedures are regularly audited by the VUF and if problems are found and not promptly corrected a suspension request is broadcasted into the blockchain, which needs to be approved by 66% of the community. The identities need to be kept secure and in cold storage. They aren't responsible on providing this information in real time so they don't need to be available on servers connected to the network. 

Once a LA is suspended, all the identity addresses generated by that LCA aren't capable of receiving vUnits any more. Funds already in those addresses can be transferred to other addresses at any moment.

Each payment transaction in the Value Units blockchain is signed by two private keys. The private key verified by the LCA and a self generated private key. The LCA is just capable of checking if they hold identity information for a particular address, but will not under any circumstance be capable of spending the vUnits assigned to that address. 

<a name="licensed-emitter"/>

## Licensed Emitter (LE)

The Licensed Emitter (LE) is responsible for initializing the process of Value Units emission. They are responsible of reaching agreements with precious metals dealers and organizing the transport to the depositaries. A company wishing to become an LE requires to pay the cost of the audit by the VUF and needs to pass the audit and be approved by 66% of the community.

Additionally the LE requires to have an amount of vUnits in custody and the amount of open emissions (calculated on the actual emission price) in the blockchain must always be less then the amount in custody. This amount in custody is paid to the VUFF and managed by the VUF. 

If the LE has 100'000 vUnits in the custody account with an emission price of 0.50, he will be able to initiate emissions for 50'000. If the emission price changes, it may fall into "minus" (more open emissions than security). The LE will not be able to initiate new emissions until either his custody amount has been increased or enough emissions have been fully processed.

To start an emission, the LE needs to specify the address of the LPMD and LD when creating the emission request. Only the selected LPMD and LD can approved the request.

They are regularly audited by the VUF and if problems are found and not promptly corrected a suspension request is broadcasted into the blockchain, which needs to be approved by 66% of the community.  

<a name="licensed-depositary"/>

## Licensed Depositary (LD)

The Licensed Depositary (LD) is responsible for holding the precious metals. A company wishing to become a LD requires to pay the cost of the audit by the VUF and needs to pass the audit and be approved by 66% of the community. The VUF defines for which countries the LD can hold precious metals. The VUF defines the procedures for each country which are communicated and published into the blockchain. The LD's are responsible of receiving and returning precious metals based on requests that are broadcasted in the blockchain. All these procedures are part of the Value Units protocol.

These procedures are regularly audited by the VUF and if problems are found and not promptly corrected a suspension request is broadcasted into the blockchain, which needs to be approved by 66% of the community. 

Once a LD is suspended, the VUF is responsible to find a solution regarding the precious metals that are being held in the LD.

<a name="licensed-precious-metal-dealer"/>

## Licensed Precious Metal Dealer (LPMD)

The Licensed Precious Metal Dealer (LPMD) is responsible for providing the precious metals that are used for emitting vUnits. A company wishing to become an LPMD requires to pay the cost of the audit by the VUF and needs to pass the audit and be approved by 66% of the community.

They are regularly audited by the VUF and if problems are found and not promptly corrected a suspension request is broadcasted into the blockchain, which needs to be approved by 66% of the community.  

<a name="identity-provider"/>

## Identity Provider

The certificates that are used for identifying a user could be used in the future to extend the capabilities of the Value Units Blockchain as an Identity Provider. Additionally a user could have an agreement to pass his private information (KYC and AML) to a third party. Let's say that the user wants to trade Value Units on an exchange. Normally these exchanges require to perform a KYC after a certain amount of money has been deposited into the account. A user of the Value Units ecosystem would be capable of sending vUnits to the Exchange address and automatically request to add his personal information with the transfer. The exchange would receive everything in one package and can certify that the user is who he says he is and that the funds are really coming from his personal address.

<a name="consensus-algorithm"/>

## Consensus Algorithm

The consensus algorithm used by Value Units is PoW (Proof-of-Work) but the VUF expects to change to another consensus algorithm within 1-2 years.

<a name="genesis-block"/>

## Genesis Block

Normally cryptocurrencies mine their units and don't require a complicated procedure to issue them. Because the Value Units system is different, there needs to be a special setup in the genesis block and some special consensus rules for it, because of the following issue that would otherwise arrise:

- If there hasn't been any emission, the miner would receive a fix amount over the total supply, if the supply is 0 the distribution will be also 0. So no vUnits can be mined until there has been an emission.
- To be able to emit vUnits, there needs to be at least one of each trusted parties (LE, LCA, LD and LPMD) and those parties would require to pay the audit fee to be voted on and because there aren't any vUnits emitted they are not able to pay the fee.
- Without an LCA nobody is capable of creating payment addresses and as such nobody is able to spend vUnits.

The list goes on and on. The genesis block requires to have a special set of instructions to setup the network so it can work accordingly. The VUF is working with several companies that will participate in the launch of vUnits, so there will be a registration phase where all interested parties can express their interest in being either a LE, LCA, LD, LPMD or miner. Super-nodes will be introduced later into the network.

With the registered parties a testphase (more on this on the roadmap) will be started, where the genesis block will be issued and start operating the blockchain with all trusted parties.

The current version of Value Units uses a closed blockchain based on Peershares and has as of the 25.12.2017 a total circulation of 9'125'957.90 vUnits with a Value Basket that hold 13.647 Kg Gold and 255.996 Kg Silver. These holdings will be included into the Genesis Block.

<a name="emission-destruction"/>

## Emission & Destruction 

The following workflow describe an emission and destruction procedure.

**Emission**

1. A licensed Emitter proposes a new emission by broadcasting a UnitsEmissionRequest instruction (signed with the private key of the LE and including the address of the selected LPMD and LD).
2. The LPMD sees the UnitsEmissionRequest and waits until he receives the payment for the precious metals. If the payment doesn't match the received request they can either contact the Emitter and wait for the missing amount or broadcasts a UnitsEmissionPurchaseCancel instruction. Otherwise if everything is ok they broadcast a UnitsEmissionPurchaseConfirm instruction.
3. The licensed Depositary sees the UnitsEmissionPurchaseConfirm instruction and waits until he receives the specified amount of precious metals. If the deliver doesn't match the received request they can either contact the LPMD and wait for the missing amount or broadcasts a UnitsEmissionDepositCancel instruction. Otherwise if everything is ok they broadcast a UnitsEmissionDepositConfirm instruction.
4. Once the precious metals deposit has been confirmed, the member of the VUF must vote on the emission. 
5. During one month all vShares holders can then vote on the emission by broadcasting an UnitsEmissionVote instruction (including their addresses and signed with the private key; the amount of vShares they have is also the weight of their vote). Only vShares that have not being used after the timestamp of the UnitsEmissionDepositConfirm instruction can vote on the proposal. 
6. If the threshold of total shares is met before the conclusion of the one month voting period, the proposal is instantly approved and the voting of the emission closed.  
7. If the the emission is approved, any node can then broadcast a UnitsEmissionConfirmed instruction to officially emit the vUnits. 

The emission price is calculated when the emission is approved (see Emission Price chapter). The VUF must vote on the emissions in a FIFO order, to avoid the possibility of price manipulation.

**Destruction**

1. A user proposes a destruction by broadcasting a UnitsDestructionRequest instruction (signed with the private key of the user and including the LD that he wants to use for the precious metals withdrawal and and process identification that was issued by the LD). The network checks that the corresponding LD has enough precious metals stored.
2. The vUnits are transferred to the LD's and could be returned at any moment to the the user by broadcasting a UnitsDestructionCancel instruction (signed with the private key of the LD) 
3. The LD can issue an invoice to the customer directly for the transport cost of the precious metals, once these are paid, the precious metals are dispatched and an UnitsDestructionConfirmed instruction reduces the stored amount of precious metals by the LD and officially destroys the vUnits.

<a name="value-instructions"/>

## Value Instructions (vInstructions)

All instructions that are used for the performing functionality in the blockchain are explained in more detail in the Value Units Specification.   

Instructions that can be executed more than once have a daily limit that need to be respected by the trusted parties. This is for avoiding misuse of the system by code bugs or hacks.

<a name="value-parameters"/>

## Value Parameters (vParameters)

The VUF (either by own initiative or by recommendation of the community) can recommend to change any of these parameters that are recorded in the blockchain. The following workflow is required to change a blockchain value parameter:

1. The change request has to be proposed into the blockchain by broadcasting a ParameterChangeProposal instruction (signed with the private key with any amount bigger than zero of vShares). 
2. During one month all vShares holders can then vote on the Proposal by broadcasting an ParameterChangeVote instruction (including their addresses and signed with the private key; the amount of vShares they have is also the weight of their vote). Only vShares that have not being used after the timestamp of the ParameterChangeProposal instruction can vote on the proposal. 
3. If the threshold of total shares is met before the conclusion of the one month voting period, the proposal is instantly approved and the voting of the proposal closed.  
4. If the the proposal is approved, any node can then broadcast a ParameterApprovalProposal instruction to officially start the voting round for the community. 
5. The community can vote by broadcasting an ParameterApprovalVote instruction (including their addresses and signed with the private key; the amount of vUnits they have is also the weight of their vote). Only vUnits that have not being used after the timestamp of the ParameterApprovalProposal instruction can vote on the proposal. 
6. If the threshold is met after one month (or before) the new parameter is then valid and any node can broadcast the ParameterApproved instruction and starting the next block the new parameter value is valid. Otherwise the parameter change is dismissed.

Following Value Parameters are part of the Value Units blockchain:

**Foundation Document Publication Proposal Period:** The period in which a document proposal can be voted on by the VUF members using vShares. (Default Value: 1 Month)
 
**Foundation Document Publication Proposal Threshold of Total Shares:** The voting threshold of all existing shares, that needs to be met to successfully approve a document publication proposal and release it to the community for voting. If the threshold of all existing shares is met the voting is closed and approved instantly. (Default Value: 66%)

**Foundation Document Publication Proposal Threshold of Total Votes:** The voting threshold of all votes, that needs to be met to successfully approve a document publication proposal and release it to the community for voting. This threshold is only required if the threshold of all existing shares is not met before the voting period ends. (Default Value: 66%)

**Community Document Publication Approval Period:** The period in which a document publication approval can be voted on by the community members using their identity key. (Default Value: 1 Month)
 
**Community Document Publication Approval Threshold of Total Keys:** The voting threshold of all existing identity keys, that needs to be met to successfully approve a document publication. If the threshold of all existing identity keys is met the voting is closed and approved instantly. (Default Value: 66%)

**Community Document Publication Approval Threshold of Total Votes:** The voting threshold of all votes, that needs to be met to successfully approve a document publication. This threshold is only required if the threshold of all existing identity keys is not met before the voting period ends. (Default Value: 66%)

**Foundation Parameter Proposal Period:** The period in which a parameter change proposal can be voted on by the VUF members using vShares. (Default Value: 1 Month)
 
**Foundation Parameter Proposal Threshold of Total Shares:** The voting threshold of all existing shares, that needs to be met to successfully approve a parameter change proposal and release it to the community for voting. If the threshold of all existing shares is met the voting is closed and approved instantly. (Default Value: 66%)

**Foundation Parameter Proposal Threshold of Total Votes:** The voting threshold of all votes, that needs to be met to successfully approve a parameter change proposal and release it to the community for voting. This threshold is only required if the threshold of all existing shares is not met before the voting period ends. (Default Value: 66%)

**Community Parameter Approval Period:** The period in which a parameter change approval can be voted on by the community members using their identity keys. (Default Value: 1 Month)
 
**Community Parameter Approval Threshold of Total Keys:** The voting threshold of all existing identity keys, that needs to be met to successfully approve a parameter change. If the threshold of all existing identity keys is met the voting is closed and approved instantly. (Default Value: 66%)

**Community Parameter Approval Threshold of Total Votes:** The voting threshold of all votes, that needs to be met to successfully approve a parameter change. This threshold is only required if the threshold of all existing identity keys is not met before the voting period ends. (Default Value: 66%)

**Foundation Emission Share:** The percentage of vUnits that are issued to be distributed to the emitting parties (Licensed Emitter - LE, Licensed Certification Authority - LCA, Licensed Precious Metal Dealer - LPMD) and the Value Units Foundation Fund (VUFF). Default Values:

|Emitted Units          |  Distribution| VUFF   | LE     | LCA    | LPMD   |
|-----------------------| :-----------:| :-----:| :-----:| :----: | :----: |
|< 100'000'000 vUnits   |  25.00%      | 12.500%| 11.250%| 0.625% | 0.625% |
|< 200'000'000 vUnits   |  23.45%      | 11.725%| 10.553%| 0.586% | 0.586% |
|< 300'000'000 vUnits   |  21.95%      | 10.975%| 9.878% | 0.549% | 0.549% |
|< 400'000'000 vUnits   |  20.48%      | 10.240%| 9.216% | 0.512% | 0.512% |
|< 500'000'000 vUnits   |  19.04%      | 9.520% | 8.568% | 0.476% | 0.476% |
|< 600'000'000 vUnits   |  17.64%      | 8.820% | 7.938% | 0.441% | 0.441% |
|< 700'000'000 vUnits   |  16.27%      | 8.135% | 7.322% | 0.407% | 0.407% |
|< 800'000'000 vUnits   |  14.94%      | 7.470% | 6.723% | 0.374% | 0.374% |
|< 900'000'000 vUnits   |  13.63%      | 6.815% | 6.134% | 0.341% | 0.341% |
|< 1'000'000'000 vUnits |  12.35%      | 6.175% | 5.558% | 0.309% | 0.309% |
|< 10'000'000'000 vUnits|  11.11%      | 5.555% | 5.000% | 0.278% | 0.278% |
|Afterwards             |  5.26%       | 2.630% | 2.367% | 0.132% | 0.132% |

**Foundation Emission Period:** The period in which an emission can be voted on by the VUF members using vShares. (Default Value: 1 Month)
 
**Foundation Emission Threshold of Total Shares:** The voting threshold of all existing shares, that needs to be met to successfully approve an emission and emit the vUnits. If the threshold of all existing shares is met the voting is closed and approved instantly. (Default Value: 66%)

**Foundation Emission Threshold of Total Votes:** The voting threshold of all votes, that needs to be met to successfully approve an emission and emit the vUnits. This threshold is only required if the threshold of all existing shares is not met before the voting period ends. (Default Value: 66%)

**Emission Minimum Price:** The minimum emission price that is calculated base on the Value Basket Price (VBP) and the current emitted units in circulation. Default Values:

|Emitted Units          |  Distribution| Minimum Emission Price| 
|-----------------------| :-----------:| :--------------------:| 
|< 100'000'000 vUnits   |  25.00%      | VBP + 31.250%         | 
|< 200'000'000 vUnits   |  23.45%      | VBP + 29.313%         | 
|< 300'000'000 vUnits   |  21.95%      | VBP + 27.438%         | 
|< 400'000'000 vUnits   |  20.48%      | VBP + 25.600%         | 
|< 500'000'000 vUnits   |  19.04%      | VBP + 23.800%         | 
|< 600'000'000 vUnits   |  17.64%      | VBP + 22.050%         | 
|< 700'000'000 vUnits   |  16.27%      | VBP + 20.338%         | 
|< 800'000'000 vUnits   |  14.94%      | VBP + 18.675%         | 
|< 900'000'000 vUnits   |  13.63%      | VBP + 17.038%         | 
|< 1'000'000'000 vUnits |  12.35%      | VBP + 15.438%         | 
|< 10'000'000'000 vUnits|  11.11%      | VBP + 13.888%         | 
|Afterwards             |  5.26%       | VBP + 6.575%          | 

**Emission Price Decline Period:** The period of time that has to pass without an emission until the emission price reaches it's minimum. (Default Value: 3 Months)

**Foundation Withdrawal Period:** The period in which a withdrawal from the VUFF can be voted on by the VUF members using vShares. (Default Value: 1 Month)
 
**Foundation Withdrawal Threshold of Total Shares:** The voting threshold of all existing shares, that needs to be met to successfully approve a withdrawal from the VUFF. If the threshold of all existing shares is met the voting is closed and approved instantly. (Default Value: 66%)

**Foundation Withdrawal Threshold of Total Votes:** The voting threshold of all votes, that needs to be met to successfully approve a withdrawal from the VUFF. This threshold is only required if the threshold of all existing shares is not met before the voting period ends. (Default Value: 66%)

**Cost of LCA Audit:** The amount of vUnits that need to be transferred into the VUFF to start an auditing process to become a LCA. If the cost incurred by the VUF is less than the paid amount, the remaining vUnits are transferred back to the the requester. (Default Value: 100'000 vUnits)

**List of LCA's per Country:** The List of LCA's per Countries includes all companies that successfully passed the VUF auditing and community approval for becoming a LCA. (Default Value: None)
 
**List of Suspended LCA's:** The List of LCA's includes all companies that are currently suspended from acting as a LCA. (Default Value: None) 

**LCA Foundation Voting Period:** The period in which the result of the audit for a LCA can be voted on by the VUF members using vShares. (Default Value: 1 Month)
 
**LCA Foundation Voting Threshold of Total Shares:** The voting threshold of all existing shares, that needs to be met to successfully approve the audit for a LCA. If the threshold of all existing shares is met the voting is closed and approved instantly. (Default Value: 66%)

**LCA Foundation Voting Threshold of Total Votes:** The voting threshold of all votes, that needs to be met to successfully approve an audit for a LCA. This threshold is only required if the threshold of all existing shares is not met before the voting period ends. (Default Value: 66%)

**LCA Community Voting Period:** The period in which the community can approve the LCA using their identity keys. (Default Value: 2 Weeks)
 
**LCA Community Voting Threshold of Total Keys:** The voting threshold of all existing identity keys, that needs to be met to successfully approve a LCA. If the threshold of all existing identity keys is met the voting is closed and approved instantly. (Default Value: 66%)

**LCA Community Voting Threshold of Total Votes:** The voting threshold of all votes, that needs to be met to successfully approve a LCA. This threshold is only required if the threshold of all existing identity keys is not met before the voting period ends. (Default Value: 66%)

**LCA Suspension Foundation Voting Period:** The period in which the suspension of a LCA can be voted on by the VUF using vShares. (Default Value: 1 Month)

**LCA Suspension Foundation Voting Threshold of Total Shares:** The voting threshold of all existing shares, that needs to be met to successfully approve the suspension of a LCA. If the threshold of all existing shares is met the voting is closed and approved instantly. (Default Value: 66%)

**LCA Suspension Foundation Voting Threshold of Total Votes:** The voting threshold of all votes, that needs to be met to successfully approve the suspension of a LCA. This threshold is only required if the threshold of all existing identity keys is not met before the voting period ends. (Default Value: 66%)
 
**LCA Suspension Foundation Waiting Period:** The period that the VUF has to wait to start another suspension process against a LCA which was recommended for suspension but overturned by the community. (Default Value: 1 Month)

**LCA Suspension Community Voting Period:** The period in which the suspension of a LCA can be voted on by the community using their identity keys. (Default Value: 2 Weeks)

**LCA Suspension Community Voting Threshold of Total Keys:** The voting threshold of all existing keys, that needs to be met to successfully approve the suspension of a LCA. If the threshold of all existing identity keys is met the voting is closed and approved instantly. (Default Value: 66%)

**LCA Suspension Community Voting Threshold of Total Votes:** The voting threshold of all votes, that needs to be met to successfully approve the suspension of a LCA. This threshold is only required if the threshold of all existing identity keys is not met before the voting period ends. (Default Value: 66%)

**Cost of LE Audit:** The amount of vUnits that need to be transferred into the VUFF to start an auditing process to become an LE. If the cost incurred by the VUF is less than the paid amount, the remaining vUnits are transferred back to the the requester. (Default Value: 100'000 vUnits)

**List of LE's:** The List of LE's includes all companies that successfully passed the VUF auditing and community approval for becoming a LE. (Default Value: None)
 
**List of Suspended LE's:** The List of Suspended LE's includes all companies that are currently suspended from acting as a LE. (Default Value: None) 

**LE Foundation Voting Period:** The period in which the result of the audit for a LE can be voted on by the VUF members using vShares. (Default Value: 1 Month)
 
**LE Foundation Voting Threshold of Total Shares:** The voting threshold of all existing shares, that needs to be met to successfully approve the audit for a LE. If the threshold of all existing shares is met the voting is closed and approved instantly. (Default Value: 66%)

**LE Foundation Voting Threshold of Total Votes:** The voting threshold of all votes, that needs to be met to successfully approve an audit for a LE. This threshold is only required if the threshold of all existing shares is not met before the voting period ends. (Default Value: 66%)

**LE Community Voting Period:** The period in which the community can approve the LE using their identity keys. (Default Value: 2 Weeks)
 
**LE Community Voting Threshold of Total Keys:** The voting threshold of all existing identity keys, that needs to be met to successfully approve a LE. If the threshold of all existing identity keys is met the voting is closed and approved instantly. (Default Value: 66%)

**LE Community Voting Threshold of Total Votes:** The voting threshold of all votes, that needs to be met to successfully approve a LE. This threshold is only required if the threshold of all existing keys is not met before the voting period ends. (Default Value: 66%)

**LE Suspension Foundation Voting Period:** The period in which the suspension of a LE can be voted on by the VUF using vShares. (Default Value: 1 Month)

**LE Suspension Foundation Voting Threshold of Total Shares:** The voting threshold of all existing shares, that needs to be met to successfully approve the suspension of a LE. If the threshold of all existing shares is met the voting is closed and approved instantly. (Default Value: 66%)

**LE Suspension Foundation Voting Threshold of Total Votes:** The voting threshold of all votes, that needs to be met to successfully approve the suspension of a LE. This threshold is only required if the threshold of all existing shares is not met before the voting period ends. (Default Value: 66%)
 
**LE Suspension Foundation Waiting Period:** The period that the VUF has to wait to start another suspension process against a LE which was recommended for suspension but overturned by the community. (Default Value: 1 Month)

**LE Suspension Community Voting Period:** The period in which the suspension of a LE can be voted on by the community using vUnits. (Default Value: 2 Weeks)

**LE Suspension Community Voting Threshold of Total Keys:** The voting threshold of all existing identity keys, that needs to be met to successfully approve the suspension of a LE. If the threshold of all existing units is met the voting is closed and approved instantly. (Default Value: 66%)

**LE Suspension Community Voting Threshold of Total Votes:** The voting threshold of all identity keys, that needs to be met to successfully approve the suspension of a LE. This threshold is only required if the threshold of all existing identity keys is not met before the voting period ends. (Default Value: 66%) 

**Cost of LD Audit:** The amount of vUnits that need to be transferred into the VUFF to start an auditing process to become a LD. If the cost incurred by the VUF is less than the paid amount, the remaining vUnits are transferred back to the the requester. (Default Value: 200'000 vUnits)

**List of LD's:** The List of LD's includes all companies that successfully passed the VUF auditing and community approval for becoming a LD. (Default Value: None)
 
**List of Suspended LD's:** The List of Suspended LD's includes all companies that are currently suspended from acting as a LD. (Default Value: None) 

**LD Foundation Voting Period:** The period in which the result of the audit for a LD can be voted on by the VUF members using vShares. (Default Value: 1 Month)
 
**LD Foundation Voting Threshold of Total Shares:** The voting threshold of all existing shares, that needs to be met to successfully approve the audit for a LD. If the threshold of all existing shares is met the voting is closed and approved instantly. (Default Value: 66%)

**LD Foundation Voting Threshold of Total Votes:** The voting threshold of all votes, that needs to be met to successfully approve an audit for a LD. This threshold is only required if the threshold of all existing shares is not met before the voting period ends. (Default Value: 66%)

**LD Community Voting Period:** The period in which the community can approve the LD using their identity keys. (Default Value: 2 Weeks)
 
**LD Community Voting Threshold of Total Keys:** The voting threshold of all existing identity keys, that needs to be met to successfully approve a LD. If the threshold of all existing shares is met the voting is closed and approved instantly. (Default Value: 66%)

**LD Community Voting Threshold of Total Votes:** The voting threshold of all votes, that needs to be met to successfully approve a LD. This threshold is only required if the threshold of all existing units is not met before the voting period ends. (Default Value: 66%)

**LD Suspension Foundation Voting Period:** The period in which the suspension of a LD can be voted on by the VUF using vShares. (Default Value: 1 Month)

**LD Suspension Foundation Voting Threshold of Total Shares:** The voting threshold of all existing shares, that needs to be met to successfully approve the suspension of a LD. If the threshold of all existing identity keys is met the voting is closed and approved instantly. (Default Value: 66%)

**LD Suspension Foundation Voting Threshold of Total Votes:** The voting threshold of all votes, that needs to be met to successfully approve the suspension of a LD. This threshold is only required if the threshold of all existing shares is not met before the voting period ends. (Default Value: 66%)
 
**LD Suspension Foundation Waiting Period:** The period that the VUF has to wait to start another suspension process against a LD which was recommended for suspension but overturned by the community. (Default Value: 1 Month)

**LD Suspension Community Voting Period:** The period in which the suspension of a LD can be voted on by the community using their identity keys. (Default Value: 2 Weeks)

**LD Suspension Community Voting Threshold of Total Keys:** The voting threshold of all existing identity Keys, that needs to be met to successfully approve the suspension of a DL. If the threshold of all existing identity keys is met the voting is closed and approved instantly. (Default Value: 66%)

**LD Suspension Community Voting Threshold of Total Votes:** The voting threshold of all votes, that needs to be met to successfully approve the suspension of a LD. This threshold is only required if the threshold of all existing identity keys is not met before the voting period ends. (Default Value: 66%)

**Cost of LPMD Audit:** The amount of vUnits that need to be transferred into the VUFF to start an auditing process to become a LPMD. If the cost incurred by the VUF is less than the paid amount, the remaining vUnits are transferred back to the the requester. (Default Value: 10'000 vUnits)

**List of LPMD's:** The List of LPMD's includes all companies that successfully passed the VUF auditing and community approval for becoming a LPMD. (Default Value: None)
 
**List of Suspended LPMD's:** The List of Suspended LPMD's includes all companies that are currently suspended from acting as a LPMD. (Default Value: None) 

**LPMD Foundation Voting Period:** The period in which the result of the audit for a LPMD can be voted on by the VUF members using vShares. (Default Value: 1 Month)
 
**LPMD Foundation Voting Threshold of Total Shares:** The voting threshold of all existing shares, that needs to be met to successfully approve the audit for a LPMD. If the threshold of all existing shares is met the voting is closed and approved instantly. (Default Value: 66%)

**LPMD Foundation Voting Threshold of Total Votes:** The voting threshold of all votes, that needs to be met to successfully approve an audit for a LPMD. This threshold is only required if the threshold of all existing shares is not met before the voting period ends. (Default Value: 66%)

**LPMD Community Voting Period:** The period in which the community can approve the LPMD using their identity keys. (Default Value: 2 Weeks)
 
**LPMD Community Voting Threshold of Total Units:** The voting threshold of all existing units, that needs to be met to successfully approve a LPMD. If the threshold of all existing shares is met the voting is closed and approved instantly. (Default Value: 66%)

**LPMD Community Voting Threshold of Total Votes:** The voting threshold of all votes, that needs to be met to successfully approve a LPMD. This threshold is only required if the threshold of all existing identity keys is not met before the voting period ends. (Default Value: 66%)

**LPMD Suspension Foundation Voting Period:** The period in which the suspension of a LPMD can be voted on by the VUF using vShares. (Default Value: 1 Month)

**LPMD Suspension Foundation Voting Threshold of Total Shares:** The voting threshold of all existing shares, that needs to be met to successfully approve the suspension of a LPMD. If the threshold of all existing shares is met the voting is closed and approved instantly. (Default Value: 66%)

**LPMD Suspension Foundation Voting Threshold of Total Votes:** The voting threshold of all votes, that needs to be met to successfully approve the suspension of a LPMD. This threshold is only required if the threshold of all existing shares is not met before the voting period ends. (Default Value: 66%)
 
**LPMD Suspension Foundation Waiting Period:** The period that the VUF has to wait to start another suspension process against a LPMD which was recommended for suspension but overturned by the community. (Default Value: 1 Month)

**LPMD Suspension Community Voting Period:** The period in which the suspension of a LPMD can be voted on by the community using their identity keys. (Default Value: 2 Weeks)

**LPMD Suspension Community Voting Threshold of Total Shares:** The voting threshold of all existing identity keys, that needs to be met to successfully approve the suspension of a LPMD. If the threshold of all existing units is met the voting is closed and approved instantly. (Default Value: 66%)

**LPMD Suspension Community Voting Threshold of Total Votes:** The voting threshold of all votes, that needs to be met to successfully approve the suspension of a LPMD. This threshold is only required if the threshold of all existing identity keys is not met before the voting period ends. (Default Value: 66%)

**Maximal Percentage of Votes Originated From One LCA:** The maximal percentage of votes that can be casted from users of one specific LCA. (Default Value: 50%)

<a name="roadmap"/>

## Roadmap

Currently the VUF is working with several companies that have supported the Value Units project until now and there is a least one of each required trusted party that is implementing the protocols described on this whitepaper on their systems. So the planned roadmap is the following:

### 01.01.2018

Start receiving applications to be a LE, LPMD, LD, LCA or miners.

### 1Q 2018

- Implement the Value Units specifications with the involved parties.
- Setup the genesis block and launch a testnet with all involved parties for 2-3 weeks.
- Launch the Value Units network with all involved parties.
- Evaluate if super-nodes are required or will be replaced by another concept.

### 2Q 2018

- Start the operation of super-nodes if these are required.
- Create a new roadmap based on the feedback of all involved parties.

<a name="glossary"/>

## Glossary

**LCA**: Licensed Certification Authority
**LD**: Licensed Depositary
**LCA**: Licensed Emitter
**LPMD**: Licensed Precious Metal Dealer
**vInstructions**: Value Instructions
**vParameters**: Value Parameters
**vUnits**: Value Units
**vShares**: Value Shares
**VB**: Value Basket
**VBP**: Value Basket Price
**VUF**: Value Units Foundation
**VUFF**: Value Units Foundation Fund

<a name="references"/>

## References

1. "Bitcoin: A Peer-to-Peer Electronic Cash System" [https://bitcoin.org/bitcoin.pdf](https://bitcoin.org/bitcoin.pdf) Retrieved 2017-12-16. [2350]
2. "Re: Bitcoin P2P e-cash paper" [http://satoshi.nakamotoinstitute.org/emails/cryptography/5/#selection-7.0-7.28](http://satoshi.nakamotoinstitute.org/emails/cryptography/5/#selection-7.0-7.28) Retrieved 2017-12-16. [2351]
3. "Bitcoin - Anonymity" [https://en.bitcoin.it/wiki/Anonymity](https://en.bitcoin.it/wiki/Anonymity) Retrieved 2017-12-03. [1536]
4. "The Dark Side of Bitcoin: Illegal Activities, Fraud, and Bitcoin" [https://blog.blockonomics.co/the-dark-side-of-bitcoin-illegal-activities-fraud-and-bitcoin-360e83408a32](https://blog.blockonomics.co/the-dark-side-of-bitcoin-illegal-activities-fraud-and-bitcoin-360e83408a32) Retrieved 2017-12-16 [1141]
5. "A Mind-Bending Cryptographic Trick Promises to Take Blockchains Mainstream" [https://www.technologyreview.com/s/609448/a-mind-bending-cryptographic-trick-promises-to-take-blockchains-mainstream/](https://www.technologyreview.com/s/609448/a-mind-bending-cryptographic-trick-promises-to-take-blockchains-mainstream/) Retrieved 2018-04-01 [1138]
6. "What is Hashgraph? How is it different from Blockchain?" [http://www.thewindowsclub.com/what-is-hashgraph](http://www.thewindowsclub.com/what-is-hashgraph) Retrieved 2018-04-01 [1308]
7. "Deterministic wallet" [https://en.bitcoin.it/wiki/Deterministic_wallet](https://en.bitcoin.it/wiki/Deterministic_wallet) Retrieved 2017-12-25 [1831]
8. "Ethereum - Whitepaper" [https://github.com/ethereum/wiki/wiki/White-Paper](https://github.com/ethereum/wiki/wiki/White-Paper) Retrieved 2017-12-13. [1602]
9. "Dash - Wikipedia" [https://en.wikipedia.org/wiki/Dash_(cryptocurrency)](https://en.wikipedia.org/wiki/Dash_(cryptocurrency)) Retrieved 2017-12-11. [1520]
10. "Dash - Whitepaper" [https://github.com/dashpay/dash/wiki/Whitepaper](https://github.com/dashpay/dash/wiki/Whitepaper) Retrieved 2017-12-11. [1521]
11. "Dash - Transaction Locking and Masternode Consensus: A Mechanism for Mitigating Double Spend Attacks" [https://dashpay.atlassian.net/wiki/spaces/DOC/pages/1146928/InstantSend?preview=/75530298/75530300/Dash%20Whitepaper%20-%20InstantTX.pdf](https://dashpay.atlassian.net/wiki/spaces/DOC/pages/1146928/InstantSend?preview=/75530298/75530300/Dash%20Whitepaper%20-%20InstantTX.pdf) Retrieved 2017-12-16. [1911]
12. "Proof-of-stake - Wikipedia" [https://en.wikipedia.org/wiki/Proof-of-stake](https://en.wikipedia.org/wiki/Proof-of-stake) Retrieved 2017-12-09. [1645]
13. "One Bitcoin Transaction Now Uses as Much Energy as Your House in a Week" [https://motherboard.vice.com/en_us/article/ywbbpm/bitcoin-mining-electricity-consumption-ethereum-energy-climate-change](https://motherboard.vice.com/en_us/article/ywbbpm/bitcoin-mining-electricity-consumption-ethereum-energy-climate-change) Retrieved 2017-12-09. [1622]
14. "What’s keeping cryptocurrencies from mass adoption?" [https://techcrunch.com/2017/04/20/whats-keeping-cryptocurrencies-from-mass-adoption/](https://techcrunch.com/2017/04/20/whats-keeping-cryptocurrencies-from-mass-adoption/) Retrieved 2017-12-08 [14213]
15. "Know your customer - Wikipedia" [https://en.wikipedia.org/wiki/Know_your_customer](https://en.wikipedia.org/wiki/Know_your_customer) Retrieved 2017-12-17 [0408]





 
