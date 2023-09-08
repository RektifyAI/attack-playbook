## General Blockchain Taxonomy
>Attack Taxonomy for general blockchain vulnerabilities.

- **Types of Consensus Mechanism Attacks**

  - *51% Attack*
     - The 51%-Attack is an attack on the consensus algorithm of a blockchain application. The
        hacker attempts to take over the network by controlling most of the nodes in said network, or more than 50%
        of the total computation power in the network.
     - This can overthrow the main consensus algorithim and allow otherwise valid blocks from being added to the chain or add malicious ones.
     -  Example: The DAO created by the Ethereum Foundation was hacked by an attack for more than $50 million dollars. This catastrophe led the members of The DAO to deploy a 51% attack to salvage what value they could amid the reckoning.

   - *Finney Attack*
     - The Finney attack happens when an attacker uses funds in a transaction, but has a pre-prepared block with an identical transaction to one of multiple accounts.
     -  From there, the attacker will wait untill the shop releases a good or service and then invalidate the inital transaction by broadcasting his block.
     -  This makes the network believe that the actual transaction was pre-prepared.
     -  The attack is super rare in real world instances due to a lack of computational power. 

- **Types of Attacks on the Peer to Peer System**

  - *Eclipse Attack*
    - In an Eclipse Attack, the goal of the attacker is to isolate the victim from a trusted network by making them connect to nodes under the attackers control.
    - This will happen untill the victim reaches the max connection limit. Afterwards any other attack can now be performed by the victim.

   - *FAW Attack (Fork After Withholding Attack)*
     - In this attack, a miner that is a member of two existing blocks and mining pools can withold and prevent a valid POW (Proof of Work Block) untill both pools can propogate a block.
     - This will happen untill the victim will lose the block anyway because the attacker owns both pools.

  - *Sybil Attack*
    - The Sybil attack, much like the Eclipse attack, will rely upon the controlling of nodes in order to sufffocate the user within the attackers network. But the Sybil Attack will actually feed them false information.
    - This can be used to launch double spending attacks. As well as several other attacks.
    - Example: The 2017–2021 attack run by threat actor KAX17. This entity controlled over 900 malicious servers, primarily middle points, in an attempt to deanonymize Tor users.
    - **The attack is super rare in real world instances due to a lack of computational power. **

  - *Wallet Theft*
    -   Wallet Theft happens when either the client based, or hardware based wallet is compormised. This can often be acomplished by stealing the private key of the user. But could also be acomplished by performing a a man in the middle attack.
    -   Example: The wallet theft of a major crypto casino Stake.com happned because of a compromised wallet. 

  - *Selfish Mining*
    -  This happens when a miner finds an FPoW then instead of releasing it immediately they hold on to it privately and continue mining on top of it in an attempt to generate a longer chain of blocks.
    -  Selfish Mining, although it doesnt have real world examples to pull from, is a very real thing. 
