# DeFi Token Attack Taxonomy

> Taxonomy for specific attacks: exploit, hacks, and compromises, in the Decentralized Finance industry

-   **Types of DeFi attacks**

    -   *Rebase Error*
        - Rebase - The circulating supply of a token is automatically adjusted on a routine basis based on the price fluctuation of the token. The supply is not fixed and will return to it's pegged price dependent on the base level set by the protocol, else the circulating supply will be adjusted instead. 

        - Furthermore, a *rebase error* occurs when the protocol fails to adjust the token supply to the desired level after depegging from its base price. Rebase tokens are commonly known as ["elastic supply tokens"](https://academy.binance.com/en/articles/elastic-supply-tokens-explained) \[5\].
        - e.g. A [rebase bug](https://cryptopotato.com/yam-developers-reveal-bug-in-rebase-contract/) was found in YAM Finance's protocol by developers in 2020. An excess of YAM tokens were generated after a 10% sell slippage on YAM Finance's parent protocol, Uniswap.
        
    -   *DoS Attacks*
        - DoS Attack - The circulating supply of a token is automatically adjusted on a routine basis based on the price fluctuation of the token. The supply is not fixed and will return to it's pegged price dependent on the base level set by the protocol, else the circulating supply will be adjusted instead. 

        - Furthermore, a *rebase error* occurs when the protocol fails to adjust the token supply to the desired level after depegging from its base price. Rebase tokens are commonly known as ["elastic supply tokens"](https://academy.binance.com/en/articles/elastic-supply-tokens-explained) \[5\].
        - e.g. A [rebase bug](https://cryptopotato.com/yam-developers-reveal-bug-in-rebase-contract/) was found in YAM Finance's protocol by developers in 2020. An excess of YAM tokens were generated after a 10% sell slippage on YAM Finance's parent protocol, Uniswap.

    -   *Smart Contract Exploit*
        - Smart Contract - A digital contract that defines and autonomously implements standards, conditions, and terms of agreements stored on a blockchain. Unlike standard contracts, smart contracts do not require an intermediary such as a lawyer to enforce conditional agreements between parties. 
        - The conditions are enforced by cryptographic code that automatically infringes penalties on broken agreements.

        - *Smart contract exploits* occur when the contract fails to execute as intended leading to the loss of funds, and in some cases, very severe and unrecoverable losses. 
        
        - A *smart contract bug* is a vulnerability in a smart contract that causes malfunction in the way the smart contract executes.
        
        - According to Imperial College London researchers \[1\], smart contract vulnerabilities are the precursor to smart contract exploits. Smart contracts can only be exploited if the contracts are deemed to be vulnerable. Vulnerability must be acknowledged by an attacker prior to exploit execution.
                - Smart contract vulnerabilities include: re-entrancy, unhandled exceptions, locked ether, transaction order dependency, integer overflow, and unrestricted actions.

        - e.g. The [largest hack](https://twitter.com/polynetwork2/status/1425073987164381196?lang=en) in DeFi history was a sophisticated smart contract exploit on the [PolyNetwork](https://cointelegraph.com/news/poly-network-hacker-returns-less-than-1-of-the-600m-theft) blockchain \[4\], in August 2021. Hackers were able to compromise the PolyNetwork smart contract holding massive amounts of cryptocurrencies, seizing over $600 million USD worth of investor assets across three chains.

    -   *Flash Loan Attack* or *Oracle Manipulation*
         - Flash Loan - A decentralized, uncollateralized and unsecured loan typically Ethereum-based. The borrower needs little to no security to receive a flash loan making it highly susceptible for attacks. \[2\]
         - Oracle - An oracle is a third-party service that allows smart contracts within blockchains to receive external data.
         - Flash loan attacks occur when a hacker takes out the flash loan from a lending protocol to perform market manipulation; in this case an oracle is manipulated in order to derive money from the exploited smart contract(s).
         - e.g. Pancake Bunny, a Binance Smart Chain protocol, experienced a severe [flash loan attack](https://cointelegraph.com/news/pancakebunny-tanks-96-following-200m-flash-loan-exploit) \[3\], in May 2021, resulting in the token price crashing by > 95%.

    -   *Fraud Rug Pull*
         - Exit scams that specifically occur in the DeFi industry. The project makes unpromised claims and runs off with investor funds.
         - e.g. [Compounder Finance](https://www.coindesk.com/tech/2020/12/02/108m-stolen-developers-implicated-in-alleged-smart-contract-rug-pull/) \[6\], garnered over $10 million USD in investors funds in 2020. Project developers claimed the project to be a replica of Harvest and Yearn Finance farming protocols, but it ended up being a sham. 

    -   *Mint Exploit*
          - A malicious event where a smart contract is broken to mintexcess tokens leading to hacker seizure of tokens and rewards (% yield).
          - e.g. [New Balancer protocol](https://ciphertrace.com/infinite-minting-exploit-nets-attacker-4-4m/) \[7\], was exploited for $4.4 million USD in a mint exploit attack. The hacker exploited the chain by depositing, then withdrawing funds from the [smart contract](https://etherscan.io/tx/0xf81fb72ee096e0d7afe4b99a55b723110604fb26ec82846043cfc396e1fa79da) and continuously minting rewards.

    -   *Infinite Approval*
        - A smart contract implementation in which the smart contract requires authorization for wallet access to an unlimited number of tokens that are greater than the amount held in the user's wallet.
         - e.g. In 2020, Bancor discovered an [egregious vulnerability](https://cointelegraph.com/news/bancors-bug-exposes-dangerously-common-practice-in-ethereum-defi) \[8\], in the Bancor protocol in which an external hacker could possibly drain funds from user wallets using infinite approval, granting them access to user funds.


**Works Cited**

\[1\] D. Perez, B. Livshits, "Smart Contract Vulnerabilities: Vulnerable Does Not Imply Exploited", USENIX, Aug. 2021. [Online]. Available: https://www.usenix.org/system/files/sec21summer_perez.pdf

\[2\] W. Vermaak, "What Are Flash Loan Attacks?", CoinMarketCap, May 22, 2021. [Online]. Available: https://coinmarketcap.com/alexandria/article/what-are-flash-loan-attacks

\[3\] S. Haig, "PancakeBunny tanks 96% following $200M flash loan exploit", CoinTelegraph, May 20, 2021. [Online]. Available: https://cointelegraph.com/news/pancakebunny-tanks-96-following-200m-flash-loan-exploit

\[4\] O. Avan-Nomayo, "Poly Network hacker returns less than 1% of the $600M theft", CoinTelegraph, August 11, 2021. [Online]. Available: https://cointelegraph.com/news/poly-network-hacker-returns-less-than-1-of-the-600m-theft

\[5\] Binance Academy Writers, "Elastic Supply Tokens Explained", Binance Academy, December 6, 2020. Updated: June 25, 2021. [Online]. Available: https://academy.binance.com/en/articles/elastic-supply-tokens-explained

\[6\] W. Foxley, "$10.8M Stolen, Developers Implicated in Alleged Smart Contract 'Rug Pull'", CoinDesk, December 2, 2020. [Online]. Available: https://www.coindesk.com/tech/2020/12/02/108m-stolen-developers-implicated-in-alleged-smart-contract-rug-pull/

\[7\] [Jake](https://ciphertrace.com/author/jake/), "Infinite Minting Exploit Nets Attacker $4.4M", CipherTrace, December 30, 2020. [Online]. Available: https://ciphertrace.com/infinite-minting-exploit-nets-attacker-4-4m/

\[8\] A. Shevchenko, "Bancor’s Bug Exposes Dangerously Common Practice in Ethereum DeFi", CoinTelegraph, June 23, 2020. [Online]. Available: https://cointelegraph.com/news/bancors-bug-exposes-dangerously-common-practice-in-ethereum-defi
