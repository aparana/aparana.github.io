Hi there 👋🏽

If you’re on Twitter, you would have come across this -

![image](https://user-images.githubusercontent.com/10815402/139591681-9412fd44-3975-44e1-9352-89057ddf1342.png)\
[Source](https://www.christies.com/presscenter/pdf/9971/Joint%20Press%20Release%20-%20Metapurse%20__%20Christies%20(2)_9971_1.pdf)

Or this -
> The Twitter CEO shared a link Friday afternoon to a platform called “Valuables,” where his March 21, 2006 tweet “just setting up my twttr” was up for bidding. The highest offer is from Sina Estavi, CEO of Bridge Oracle, for $2.5 million as of Saturday afternoon, according to the website.
> 
![image](https://user-images.githubusercontent.com/10815402/139591699-c209f0b3-136d-4215-aed0-67aa5648e982.png)\
[Source](https://v.cent.co/tweet/20)

So what is it? Grab a cup of your favorite beverage and let’s get reading!

---

NFT stands for Non-Fungible Token.

> Non-fungible tokens (NFTs) are unique, digital items with blockchain-managed ownership. Examples include collectibles, game items, digital art, event tickets, domain names, and even ownership records for physical assets. A NFT (non-fungible token) is a special cryptographically-generated token that uses blockchain technology to link with a unique digital asset that cannot be replicated.

Fungible means which can be replaced by another identical item, for example, the laptop, chair, clothes, etc. (and currency - you can replace a 5 rupees note with another 5 rupees note.)

So non-fungible digital items would include domain names, Instagram handles, etc.

Now let’s say you own one of these items and want to sell it - sounds difficult right (how is the ownership going to be transferred, etc.) - This is where blockchains come in!

## Blockchain
I’m going to paste the key takeaways from this Investopedia article -

![image](https://user-images.githubusercontent.com/10815402/139591732-559d2b8f-0a33-4408-a141-64d9d98a5e72.png)
[Source](https://www.investopedia.com/terms/b/blockchain.asp)

## Tokens
> A “token” represents a utility or asset and is typically issued on an existing blockchain. In contrast, a “coin” is a crypto asset that is native to its own blockchain and is primarily used as a currency.

> For example, Musicoin is a token that allows users to access different features of the Musicoin platform. This could be watching a music video or streaming a song.Some tokens are created for a whole different kind of purpose: to represent a physical thing. Let’s say you wanted to sell your house using a smart contract. You can’t physically put your house into the smart contract, can you? No.
So, instead, you can use a token that represents your house.

Ethereum is an open software platform built on blockchain technology that enables developers to build and deploy decentralized applications. Ethereum introduced a new, more user-friendly way to create tokens. Using a simple smart contract, Ethereum made it easy for anyone to launch their own token for just about anything.

> Since the developer of a dApp and token doesn’t have to create their own blockchain, it saves them time and resources. They can use the features of cryptocurrency with their application while benefiting from the security of the native blockchain.

## Standards
The explosion of tokens made standardization increasingly important, to ensure that the tokens could be exchanged for each other. Now just like we have image standards in terms of JPG, PNG, etc. - NFT has its own standard interfaces!

> It provides functionalities like transferring tokens from one account to another, getting the current token balance of an account, getting the owner of a specific token, and also the total supply of the token available on the network.

ERC-20 are identical tokens like currency, ERC-721 are unique tokens to represent NFTs and ERC1411 are the security tokens that include assets that require compliance with financial law.

All NFTs have a uint256 variable called tokenId, so for any ERC-721 Contract, the pair contract address, uint256 tokenId must be globally unique. '

Token Contract Address refers to the address location of the actual token contract that manages the logic for the tokens. It does not refer to the address that holds your own personal tokens!

## How to get started?
Well, this is going to be a short part -
1. Creating your contract
2. Minting your tokens - Mint new assets to our newly-deployed ERC721 contracts
3. Add metadata: Each token identifier in your ERC721 contract will have corresponding metadata URI that returns additional important information about the item, such as the item's name, image, description, etc. The metadata can be stored on-chain or off-chain, on-chain meaning that it resides with the token and off-chain means somewhere else like AWS, etc.
4. View your items, create a storefront, and auction!

## Future of NFTs
The market for non-fungible tokens is still quite small, though growing rapidly.

![image](https://user-images.githubusercontent.com/10815402/139591799-0d7c829e-3a74-4286-a9dd-cc79c621d4be.png)

[Source](https://blockonomi.com/nft-market-cap-315-million/)

Given the early market, another interesting metric to look at is the ERC721 contracts.
![image](https://user-images.githubusercontent.com/10815402/139591816-8258f058-86f5-4bbf-9314-4da37e35c342.png)

> Since January 1st, the number of deployed ERC-721 contracts has grown by almost 350%, compared to about 39% and 36% for ERC-21 contracts and non-token contracts, respectively.

**I think, in India, the craze of NFTs will start once BCCI starts rolling out cricket-based NFTs!**

That’s it for today!


