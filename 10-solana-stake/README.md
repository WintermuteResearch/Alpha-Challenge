# Solana-Stake - Tier 3
The Solana Foundation [recently announced](https://www.theblock.co/post/299244/solana-foundation-removes-certain-operators-from-delegation-program-over-malicious-sandwich-attacks) their plan to remove stake from their delegation program if participating validators produce blocks including sandwich attacks.

Here is a [useful thread](https://x.com/0xMert_/status/1799955514786234751) for extra context, also you can view the announcement on the foundation’s Discord.


- a) You are aware of Jito's modified Solana client to improve the efficiency of MEV extraction. Describe how unaligned validators can run their own private mempool to facilitate sandwich attacks.
- b) Identify the validators that had their stake removed, and determine the total amount removed.
- c) Write code that, given a Solana block, outputs whether a sandwich attack was included.
