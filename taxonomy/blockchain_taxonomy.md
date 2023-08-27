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
     -  This makes the network believe that the actual transaction was pre-prepared

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

  - *Wallet Theft*
    -   Wallet Theft happens when either the client based, or hardware based wallet is compormised. This can often be acomplished by stealing the private key of the user. But could also be acomplished by performing a a man in the middle attack. 
