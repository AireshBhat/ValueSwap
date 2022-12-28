# Still under construction... 👷
Check out my [blog](https://mirror.xyz/0x493EDA97486EC88C9C79404476B3dB71699a4040)

# Executive Summary:

* [v 0.0.1](https://github.com/AireshBhat/TransferOfValue/blob/main/Versions/v0.0.1.md)
* [v 0.0.2](https://github.com/AireshBhat/TransferOfValue/blob/main/Versions/v0.0.2.md)
* [v 0.0.3](https://github.com/AireshBhat/TransferOfValue/blob/main/Versions/v0.0.3.md)
* [v 0.0.4](https://github.com/AireshBhat/TransferOfValue/blob/main/Versions/v0.0.4.md)

![](https://badgen.net/badge/Version/v0.0.4/green)

From the oldest civilization of humanity till date, we humans have used various technologies to exchange value.

The following diagram shows us the evolution of money as a technology.
![Evolution of the technology of money](./assets/Money_Tech.png)

What are Alice and Bob trying to do here?
Bob wants some "value" Alice can provide. For this value, Alice is given a token to keep track that she provided value. This token is supposed to be a proof of value transfer. It's also something that Alice should be able to use tomorrow for obtaining "value" provided by others.

In today's crypto world, we are building blockchains to track these tokens. We are building systems to track which token is under whose address. Using these tokens as incentives, we also stamp other proofs which led to NFTs, DIDs, ENS domains and so many more unique web3 projects. When we however track an individuals value using only one token, we end up centralising around that token. The end goal of humans will then be to get as much of that token as possible which is no different to what dollar is in todays world.

Today, the more of a token a person has, the more value that person has. 
 We can't use one token only to define a user's worth. That would be nothing different from dollar or fiat currency.

What's the next step? How do we fix this problem?

# Transfer of Value protocol
The protocol keeps track of a very simple value exchange. It incentivises users to keep track of the value they provide. In turn the protocol will keep track of the value a user provided. Whenever a users token is minted, 1 CHET token is added to the users wallet.

In the example above, the protocol incentivizes Alice to record the transaction by sending her 1 CHET token when her token is minted.

![Bob minting Alice's token](./assets/Minting_Token.png)

At the end of the exchange, Bob's wallet will have 1 "Alice" token and Alice will have 1 CHET token.

The transaction will record the proof of value exchange. It can be anything from a DID, transaction, URL, IPFS link, NFT, anything. It can also be a signed agreement between the two parties.

## Rules and the beliefs behind the protocol
1. A users value is calculated as the total number of tokens(which have crossed the nakamoto coefficient threshold). If a token crosses the nakamoto coefficient, it means that the user behind the token has provided some sort of value to majority of the wallet holders.
2. A token crosses the nakamoto coefficient threshold when it is collected by x% of the wallets being used. For starting off we can keep a threshold of 90%. Moving forward we can have many more thresholds.
3. A token can be collected as many times. However its entire value in a wallet is only 1.
4. Each user is incentivised to operate only one wallet. In the beginning, until each wallet is backed by biometric verification, it is not possible to merge the value one wallet has collected with another.
5. A user cannot send their own token to any other wallet. Only an external address can mint a token.