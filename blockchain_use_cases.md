Fork from https://github.com/dprophet/blockchain_use_cases

Erik Anderson
Bloomberg

### For the purpose of this document lets replace Blockchain with DLT (Distributed Ledger Technology). DLT is:
  - A ledger that generally runs in a hostile environment like the public internet
  - It uses cryptography to try and solve identity and ownership problems in this public environment
  - It uses cryptography to try and automate business processes & reduce latency to accelerate the value of money
  - Assets are on and managed on the ledger. Off ledger interactions are considered legacy, slow, and inefficient.
  - Most real use cases of this technology are theoretical discussions, unimplemented, without a single live use case with enough scalability, security, or appropriate regulatory framework in place.
  - Data on the DLT can be permissioned/private but all transactions on this ledger are public and all parties can see those transactions.
  - DLT is the technology not the actual asset. The asset is the application utilizing the DLT (Stock trades, payments, swap trade, currencies, bonds & coupons, etc).
  - Transactions are absolute, there is no reverting the transaction. Chargebacks/returns are a business process because the ledger cannot be reversed. You must initiate a transaction back to the originating party.
  - Current DLT Identity & Data security mechanisms is 'relatively unused' cryptography built for financial services in 1990's. These mathematics has a certain lifetime because computers and distributed calculations are getting faster & more efficient. The current cryptography is not resistive to quantum computer attacks, 5-10yr max additional lifetime, target window 2021-2026.

### Use Case, Direct Financial Services beneficiaries of Blockchain & Distributed Ledger Technology-DLT, Including Identity & Data Security
  - Directly lending
    - Middle market direct lending
    - End consumer direct lending
    - Crowd source lending
  - Insurance
    - Claims:
      - Claims will require verifiable assets tied back to identity & proof of purchases
      - Personal insurance. Chain of a lifetime. Buying a diamond you had a complete record of the crimes and claims against it?
    - Codifying Contracts (ie Smart Contracts)
      - Financial Services is expecting Smart Contracts to be a container for the execution of financial business transactions. These containers need stronger security and identity to assure all parties are known, trusted.
      - Existing business models can be coded into Smart Contracts to accelerate the value of money.
  - Legacy financial services
    - Securely embeddable Identity elements in ISO 20022, FpML, FIX, ISO 8583, etc
    - Wrap security around these legacy financial services message formats will give you the non-reversible feature of a ledger to solve non-repudiation issues.
  - Trades
    - Real-time valuation of assets and settlement
    - Scoring, ranking, trustworthiness, and other compliant-obligatory algorithms to categorize 'codes of conduct'. This applies to organizations and individuals.
        Even if Settlement occurs real-time, collateral still moves at a future date. We still need to score trustworthiness and bind that identities.
    - Posting of collateral for OTC trades. The posting of collateral & verified assets needs to be tied back to real world identities. Currently 3rd parties (ie clearing houses) are required as part of this step to validate real world ID and asset ownerships. Without DLT+Identity+VerifiableAssets it will be impossible to construct consensus algorithms to facilitate real-time settlement and measure trustworthiness.
  - Verifiable assets placed on a public ledger becomes a utility to servicing of other Instruments
    - Assets are on and managed on the ledger. Off ledger interactions are considered legacy, slow, and inefficient.
    - Verifiable assets, by themselves, arent as valuable as the channels they create for servicing of other instruments.
      - Corporate actions
      - Bond coupons
      - Dividends
      - Corporate Debt
      - Syndicated loans
      - Private securities
      - Asset back instruments
    - Many financial instruments are asset backed. The algorithmic version of "hard linking of the verified assets to the instruments/securities" and placing on a DLT will allow automation reconciliation of the accounts and instrument repricing.
      - This will add a strong level of operational resiliency to capital markets utilizing asset linking to other instruments.
    - Issuing FIGI codes (Financial Instrument Global Identifier) for assets and tying those to identities will create a forensic trail to help prevent the same asset from fraudulently used for multiple different instruments & business deals.
         Example: 2x, 3x, 4x... over collateralization of the same asset for multiple business deals.
    - A common data encapsulation around which:
      - Financial institutions can use to help settle transactions.
      - Common data structure for embedding of KYC/AML and other compliance information.
        - Financial Institutions are faced with much higher regulatory, compliance costs as well as strict restrictions around capital exposure. These institutions are looking for innovative ways to reduce future regulatory and compliance costs as well as optimally manage their existing capital to generate new revenue streams.
      - Data exchange across dissimilar non-interoperable technology.
      - Digitization of analog documentation.
  - Payments and Remittance
    - Transactions can occur directly between two parties on a frictionless P2P basis. The technology application for overseas transactions has the potential to reduce risk, transaction costs and to improve speed, efficiency and transparency.
      - By including identity (either tokenized or privacy protection layer) we can allow regulatory controls over the movement of the value.
  - Issuance, Ownership and Transfer of Financial Instruments
    - A DLT securities market allows traders to buy or sell stocks directly on exchanges or directly to other market participants in a P2P manner without the intermediation services provided by a broker or clearinghouse.
      - By including identity (either tokenized or privacy protection layer) we can allow regulatory controls over the movement of the value.
      - In financial services, chains of custody of a financial instrument is deeply regulated territory. This chain of custody is a very costly legacy process. The only way to speed this up is to securely & privately embed chains of identity/ownership into the very process.
      - Without proper Identity it will be possible for bad actors to continue to create the same chaos thats occurring today. You will need to be securely authenticated with the system and have the proper access controls to the information.
      - Massive privacy issues related to publicizing transaction information over a public network/ledger. As a result of this problem the majority of the capital market industry is focused on development of private/permissioned DLT that will never allow an Internet based browser access to these private networks. Access will likely occur via proprietary applications or proprietarty+embedded Webkit technology.
      - By linking credentials to individuals, individuals and assets to corporate entities we can create unique cryptographic identification tagging to tradable instruments. Wrapped within a permissioned based privacy friendly security layer it will allow association of people and assets within a hostile environment (such as a public Blockchain running on the internet). This will allow authorized parties to utilize mathematical forensics to trace the chains of ownership yet prevent regulatory snooping.
        NOTE: Some will argue that this is a only on-ledger work effort but even ledger work requires on-ramp, off-ramp, data updates, and linked data to off ledger sources.
  - Clearing and Settlement
    - On the distributed ledger technology (DLT), the entire lifecycle of a trade "including its execution, clearing and settlement" can occur at trade level, lowering post-trade latency and reducing counterparty exposures.
      - This can only occur if the transactions themselves are tied back to real world identities yet layered with security mechanisms that protect the privacy yet allow role based regulatory insight into the transactions themselves. Roles could be State Taxes, court auditors, FinCEN.
  - Servicing of Instruments
    - Through the utilization of smart contracts, financial instruments can be pre-programmed to carry out corporate actions, such as payment of bond coupons or dividends.
      - This is only possible by removing the 20 year old security technologies that current Blockchain was built on and layer on Identity with privacy protective mechanisms.
  - Reconciliation
    - Since DLT is replicated and synchronized database of transactions distributed across a network of users, manual reconciliation become redundant.
      - Identity and security layering will be required that trust (ie access to manipulate underlying assets), is granted only to bits of contacts/ledgers that need to interoperate
  - Know-your-client and Anti-money Laundering Registries
    - the perception of anonymity associated with permissionless DLT like Bitcoin challenges existing know-your-client (KYC) rules and protocols;
    - An individual, or an entity's identity can be stored in an Identity Provider and utilized on the blockchain, ensuring secure and rapid ID authentication without the warehousing of sensitive data at third-party repositories. This will allow KYC/AML information to be directly propagated via DLT yet still protect the privacy of the individual
  - Regulatory Reporting
    - The DLT is fundamentally a record of transaction history, delivering a fully transparent, accessible transactional database for governing bodies.
      - By combining Identity & secure privacy layering mechanisms you can grant access to governing bodies without allowing regulatory snooping.
  - Reputational Management System
    - Reputation systems are in dire need of connectivity to real & merit based identities. This will prevent merit based identities (Ebay profile) from being stolen and used by unauthorized users.
    - Dont marginalize or penalize anyone.
  - Fines
    - Since the 2008 financial crisis, twenty of the world's largest banks including JPMorgan, Citibank and HSBC have paid over US$235 billion in fines.
    - Interestingly, the majority of the fines derived from the banking system's inefficiency and failure to keep track of "verifiable assets". Example: sold mortgages, insurance products, collateralized assets, etc
    - A lower level standard that addresses verifiable assets, transference of assets, assets chained with other assets, assets with shared ownership, assets with "collateral burdens" will help facilitate creation of a document ledger of assets to reduce the regulatory arbitrage that Financial Services is experiencing.
  - Accounting Ledgers & audit chains
    - Reduce corporate fraud. Transaction and the record of the transaction are the same thing.
    - Trustless audit chains, property title chains, record keeping for sensitive personal, medical and corporate materials, and public accountability mechanisms.
    - Internet of things. A ledger of devices and the transactions that happen between them.
  - Licensing Ledger
    - Empower self-service licensing models like yearly subscriptions, ownership for life of device, ownership for life of the individual.
    - Soft linking the license of the content to the ledger. Current approaches are hard license approaches where the licensing is embedded in the content.
    - Relicensing of the content without having to reissue the content.
    - Direct tracking of licensed content for devices
    - Relicensing of 2nd party content to 3rd parties. Example: Electronic music, purchased by a conductor, for Concert and Quire
    - Tracking of & direct payment of commissions for 3rd party re-sellers.
    - Direct 1x1 coupon issuance to the individual without the need for a 3rd party.
    - Dynamic licensing between the electronic format and a license ledger provides us a lot more "self-service" licensing options
    - Creation of currently unheard of licensing models like licensing of all content from one particular artist or bulk licensing to a group of individuals.
    - Content licensed to a cryptographic biometric identifier
    - Usage based licensing like 5 prints of a 3D printing schematic, 3 plays of a movie, 1 free play of a song, 1 passthrough of a electronic sheet music.
    - Better persistence of indication of rights (e.g., what happens if company using live data goes out of business?). Ledger persists even after companies are gone.
    - Immutability and censorship-resistance are useful for governments in certain instances, such as conducting international trade in the face of sanctions.
  - Identity
    - In Capital Markets, Identity isn't just about "what you know" but also "when you knew it".
	- Selective disclosure: You can verify the age but not the individual, Verify first and last name.
    - Digital identities will get compromied. Digital Identity should be self-issued but verified attributes or "digital selfies" can be attached to that identity.
      - Digital identifier is the Christmas Tree, attributes are the ornaments
    - Identity assertions, once extracted out of the Blockchain must be invalid, considered compromised, or at-a-minimum a very short time-to-live. Some data values, such as proofs of a user's identity, must be considered fresh to have any value.
    - Identity isnt just about ontology (data structure of user verifiable attributes) but its also about how the environment influences that information. User privacy, court auditors, law enforcement, international laws all apply pressure on the environment and requirements for access to user verifiable attributes.
    - At its simplest form, Identity over a hostile environment like the Internet is about combining authentication and secrecy techniques to create a "Privacy Friendly Identity & Data Management".
    - Current trends is "Hardware as surrogate for the Identity". Ultimately the assurance of a user's identity will come down to the capabilities or limitations of the user's hardware device. Devices are registered with a ledger to create a trust mechanism.
    - Blockchain is certainly NOT the solution to Identity as its too far from the point of origin of the user. However Blockchain uniquely solves 1 problem that has been eluding Financial Services for many decades, non-repudiation. If you use the above W3C specs as a tunnel/entry-point to the Blockchain you can put user assertions & claims on a public ledger yet keep the access controls to that information "In the users pocket".
    - Privacy friendly Identity Management:
      - Usage of Identity in a hostile environment that is forensically trackable yet private at the same time. It needs to allow:
        - Friendly regulatory & legal tracking
        - Utilize anti-snooping measures to protect the privacy of the corporations & individual alike.
        - Extreme privacy for purchases of pharmaceuticals.
        - Empower Government use cases like:
        - Government programs like food stamps and Medicare where the government is providing the funding.
        - Grants. So how were those funds utilized?
      - Empower business use cases like:
        - Business processes for a shared role or delegable usage in instances of vacations,
        - Incase of death's, willable/transferable assets that were bound to the identity of the deceased.
      - Empower individual use cases like:
        - willable/transferable assets that were bound to the identity of the deceased.
        - Persona's and pure merit based identities and scoring mechanisms for online purchases. In many cases
  - Secure yet configurable access to varying levels of sensitive data.
    - Usage of secure objects:
      - Secure objects allow the access controls for its contents to be integrated with the object. Regardless of where the object is stored the data is secure
      - Secure objects have access control mechanisms where in roles can be granted to view various different levels of the objects contents.
    - Secure Objects permissioned by an organization chart and employee roles.
       - Objects are always secure. Even internal employees go through the same permissioning system as 2nd & 3rd parties.
    - There is no back door, only an algorithmic construction for keys to the front door.
      - The front door can be permissioned for roles like State Taxes, Auditors, Law Enforcement, various tiers of regulators, compliance officers, etc.
      - Algorithms construct dynamic Keys for access through the front door.
      - There is a different key for each object. Hacking 1 object only exposes the contents of that singular object:
        Example: Hacking the 1 object only exposes one transaction, not an series/history of transactions.
  - Voting
    - If you combine Identity with the Ledger this will prevent double voting and secure the data against unauthorized access by 3rd parties. You can anonymize various attributes of that data to allow useful statistics without disclosing privacy.
  - Regulatory Insight and Oversight
    - Regulation, in a nutshell, is about the movement of and insight into information. Regulation and Blockchain is about analytic's and intelligence of content before and after data is written to the ledger.
    - Insight: A public ledger, with the appropriate layering of privacy friendly mechanisms, can be used to also allow access to various anonymous statistics that governments uses to measure "economic health".
      Example: Demographics, housing, International movement of money, spending habits where consumers switch from 2% milk to powdered milk, etc.
    - Oversight: There exists many instances where Regulatory authorities have legal oversight of the movement of value. In these cases, allowing consensus algorithms with regulatory "veto" power over those transactions provides the regulators with the tools they need.
      Note: This is a concept I have been pushing to put the "regulations in the code". Regulations can be automated with far less cost and slower human involvement. This will directly reduce the amount of regulatory arbitrage & hand waving those authorities utilize.
    - Digital Forensics: If you combine a public ledger, access control on various information elements, you can unlock digital forensics yet prevent regulatory snooping.
      - Example: Price/amount+country+ZIPCODE is anonymized enough to allow public access for metrics purposes. Various algorithms can be used to determine business health, health signs, money flows, etc. IMO, cash flow is a much better business metric than the variety of accounting wizardry techniques that goes into profit statements.
   - Wallet
     - Current trend are toward physical wallets in the form of hardware (e.g. a dongle or mobile phone itself).
     - If you combine the hardware key management with a public ledger you can truly create a digital wallet since the contents of the wallet are secure regardless of the mechanics surrounding the wallet storage. Hardware will offer the privacy and access controls to a cloud or Blockchain based wallet.
  - Data protection:
    - Data is written to DLT. There is no confidentiality as everyone can see it. Even if you encrypt the private metadata how do you allow differential access to a pyramid of sensitive/private information.
    - Other data, such as HIPAA, has a 125 year storage requirement and existing data security mechanisms cant achieve this requirement since computer capabilities double every 2 years.
    - Data is exposed to a hostile environment (the internet). Any hacker can download the information and attack the data structures directly. This further challenges security measures around data confidentiality half-life. 5 half-lives is an industry acceptable mechanism to measure the time it takes for data, disclosed publically, to be out dated & useless.
    - Encrypting data breaks existing tools used to measure economic health & statistics. Example: International movement of money, trade flow, imports/exports, etc. Entire new data analysis tools will need to be developed
    - Cryptography, like any technology, gets better and changes over time. Existing Blockchain cryptography is directly soldered/fused into the Blockchain protocols. This will be very costly, require lots of maintenance and developer time.
      - Key Management agreements and their dynamic construction is the future most companies are working toward but Tecsec long ago developed.
    - Blockchain was built with US 'standard' data encryption but different curves. No foreign nation trusts the other nations encryption and certainly no one trusts encryption the NSA 'helped develop and recommends'. China, UK, Europe, Japan all have their own devastations of that math and refuse to trust other nations recommendations.
      - Because of this reason its impossible to get consensus on an international data security algorithm. You must use a 'standard' data security schema that allows choices of which algorithms to use. Call this an international schema that wraps local/domestic requirements. Standard good practice engineering approaches can allow interoperability even when absolute math doesnt.
      - This schema also allows new advancements in cryptography to be added to the schema, accounting for advancements in math & technology, without breaking data encrypted through older versions of the schema.
    - In essence, the current financial systems reach consensus by reconciliation. This requires a lot of data collection, recording, auditing, processing, and reconciling of vast amounts of information. This process is slow, expensive, and difficult to automate. Existing Blockchain (token based ledger business model) is not a ledger to store enormous amounts of sensitive information with varying privacy, reporting, regulation & access control requirements.
    - When it comes to data security and Blockchain .... Its not about what they are doing right, its about what they are doing wrong.
  - Love
    - Dont shoot the messenger but is "crypto-love" or "chain of love" really a use case?
      - http://motherboard.vice.com/read/blockchain-of-love-someone-proposed-using-bitcoin
      - https://youtu.be/0_9HdZwf60U
  - Inventory
    - Inventory management platform

### Blockchain projects: 7 mistakes to avoid
  - Misunderstanding or misusing blockchain
    - The majority of blockchain projects are used for recording data on blockchain platforms via decentralized ledger technology (DLT). While this is one function of the blockchain, it ignores its other critical features, including decentralized consensus, tokenization, and smart contracts.
    - DLT is a component of blockchain, not the whole blockchain. The fact that organizations are so infrequently using the complete set of blockchain features prompts the question of whether they even need blockchain
  - Assuming the technology is ready for production use
    - The emerging blockchain platform market is increasingly large and fragmented. Vendors focus on everything from confidentiality to tokenization to universal computing in an attempt to differentiate themselves to customers. However, most remain too immature for large-scale production work, the research found. CIOs must keep an eye on the market to monitor these platforms as they evolve in the coming years, and change their blockchain project timelines accordingly.
  - Confusing a protocol with a business solution
    - Blockchain is a foundation-level technology—while it can be used across industries for different situations, it is not a complete application, the research said. For example, it must also include features such as user interface, business logic, data persistence, and interoperability mechanisms.
    - When it comes to blockchain, there is the implicit assumption that the foundation-level technology is not far removed from a complete application solution. This is not the case. It helps to view blockchain as a protocol to perform a certain task within a full application. No one would assume a protocol can be the sole base for a whole e-commerce system or a social network.
  - Viewing blockchain purely as a database or storage mechanism
    - Blockchain technology is designed to provide an immutable, trusted record among a number of untrusted parties, not as a database manager. Currently, blockchain does not implement the "create, read update, delete" model used in conventional database managers—only "create" and "read" are supported. 
    - You should assess the data management requirement of a blockchain project. A conventional data management solution is likely the better option.
  - Assuming that interoperability standards exist
    - Because most blockchain platforms are still being developed, interoperability with other blockchains is not yet fully possible. You should approach vendors who discuss interoperability with caution at this point in time.
    - Never select a blockchain platform with the expectation that it will interoperate with next year's technology from a different vendor.
  - Assuming smart contract technology is a solved problem
    - Smart contracts are one of the most powerful features enabled by the blockchain. However, many challenges in terms of scalability and manageability of these contracts still exist. You should run small experiments with smart contract technology to start, as it will change significantly in the coming two to three years.
  - Ignoring governance issues
    - Public blockchains require governance from CIOs or trusted companies, while governance for private and permissioned blockchains is typically handled by the owner of the blockchain.
    - Governance in public blockchains such as Ethereum and Bitcoin is mostly aimed at technical issues. Human behaviors or motivation are rarely addressed. You must be aware of the risk that blockchain governance issues might pose for the success of their project. Especially larger organizations should think about joining or forming consortia to help define governance models for the public blockchain.


### WORDS OF WARNING:
  - 2015 saw a double increase in hacks targeting financial data
  - The very data structures of asset messaging will be targeted by hackers.
    - Its inevitable that financial asset information starts to move over the public internet
      - As asset information is exchanged it should not be possible to take the information about that asset out of the context for which that information was being exchanged.
  Example: I have a Bar of Gold with QR code xxx, verified/signed by Well Fargo as safely secure in their facility, being exchanged as an asset/collateral for a transaction. Assuming a hacker somehow became a man-in-the-middle of the message chorography and has access to the raw signed asset message, he should not be able to separate that signed asset for a different intent.
      - Verifiable asset exchange information must be 1x1 bound to the parties and inseparable from its original intent.
    - Blockchain is an hyped attempt at a technology leading business solutions. What problem are we trying to solve before we pick a technology.
    - Blockchain, as it stands today, is based on yet another procedural programming language with traditional data structures and algorithms.
      - Oracle, years ago, tried to codify interactive/behavior information systems into a database with PL/SQL and later followed by embedding Java. This didnt work out the way they intended. Irregardless of cryptography, Blockchain as a procedural database programming language is trying to repeat the history that Oracle went through.
      - Blockchain does have a role in financial services but Blockchain ISNT THE ROLE ITSELF. Blockchain role is non-repudiation via final storage of the inputs to a financial agreement, not the code that executes the agreements.
  - Blockchain, as a final resting place for the information, and a "dumb contract" who's intent is to help ensure the integrity of the information as its written to the ledger makes perfect sense. Codifying all information flows needed to construct financial agreements flowing to a public ledger? Now add in the integrity of the ledger is maintained by miners running computers in their basement?
    
