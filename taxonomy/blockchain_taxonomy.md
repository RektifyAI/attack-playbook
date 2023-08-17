## General Blockchain Taxonomy
>Attack Taxonomy for general blockchain vulnerabilities.

- **Types of Consensus Mechanism Attacks**

  - *51% Attack*
     - The 51%-Attack is an attack on the consensus algorithm of a blockchain application. The
        hacker attempts to take over the network by controlling most of the nodes in said network, or more than 50%
        of the total computation power in the network.
     - This can overthrow the main consensus algorithim and allow otherwise valid blocks from being added to the chain or add malicious ones.

   - *Finney Attack*
     - The Finney attack happens when an attacker uses funds in a transaction, but has a pre-prepared block with an identical transaction to one of multiple accounts.
     -  From there, the attacker will wait untill the shop releases a good or service and then invalidate the inital transaction by broadcasting his block.
     -  This makes the network believe that the actual transaction was pre-prepared

- **Types of Attacks on the Peer to Peer System**

  - *Eclipse Attack*
    - In an Eclipse Attack, the goal of the attacker is to isolate the victim from a trusted network by making them connect to nodes under the attackers control.
    - This will happen untill the victim reaches the max connection limit. Afterwards any other attack can now be performed by the victim.
  
