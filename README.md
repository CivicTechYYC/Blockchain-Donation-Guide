<!-- Hey y'all! 

This is a collaborative editor, like Google Docs but different. It uses 'Markdown' Syntax - for formatting use the buttons on the toolbar, and if you're interested to know more about how Markdown works check out this link: https://www.markdownguide.org/basic-syntax/ 

The benefit of doing the document in Markdown is that it can be published to github and turned into a fancy lookin' website using a modern static site generator like Gatsby or Read the Docs - the content and the presentation are always separate.

Changes made below (and eventually github once we publish it) will be automatically tracked.

-->

# Accepting Cryptocurrency Donations: A How-To Guide
*Helping charities and non-profits understand and accept Bitcoin, Ethereum, and other token-based assets*

2020 [CivicTechYYC](https://CivicTechYYC.ca)

---

Introduction
---
So, this thing called Bitcoin and all those other *something*-coins seem pretty weird and scary, amiright? 

Never mind that as a species we humans (allegedly) started out exchanging actual things of value to our survival, like one cow for seven goats, and then moved on to exchange a lump of shiny gold metal for that cow or goat, or maybe some labor, or maybe debt. Why? Because the metal was hard to get and stood in as a placeholder for the exchange of value (we're neither historians or economists but stay with us here).

As our level of commerce increased we realized it was a little difficult to handle all that gold and instead started printing paper as a placeholder. We had to make sure the paper had all kinds of squiggles and doodads on it that made it hard to copy (but that didn't stop some people from being fooled).

And at a certain point, we all decided to stop fooling ourselves and not worry about whether the paper was a placeholder for the gold or not. The paper could just be its own thing, and as long as we all kept believing in the value of that paper everything would be alright.

Once having ascended the pyramid from survival to prosperity, at some point we seemingly decided what good was the paper? All we really needed was the information represented by the paper, and a bunch of authorities like nation states and/or central reserve banks reminding us to believe in the value of that information and to keep us honest. 

*Now if that isn't weird and scary, what is?*

In fact, that's precisely where Bitcoin and its descendants, generically referred to as 'cryptocurrencies', come in to our story. 

We're guessing your charity or non-profit organization accepts donations of all the things we've talked about above - credit card payments, pieces of paper with a signature or somebody's head on it, gifts of labour, or hard assets like real estate, cars or maybe even goats. 

Cryptocurrency (also known as just 'crypto') is just a new type of asset that people happen to believe in. If you would like to accept donations of cryptocurrency and otherwise participate in this new world, read on.

### Goals

This guide is meant to be:

* Simple and digestible, not comprehensive but rather a jumping off point for further exploration;
* Curated to give you the essentials (for experts some of this may be an oversimplification);
* A gift of knowledge and research that a 'non-entity' entity borne of (and exemplifying) the [Civic Tech](https://en.wikipedia.org/wiki/Civic_technology) movement has unearthed while attempting to understand blockchain technology;
* A tool to help charities who are curious about a whole new type of asset;
* A resource to connect charities with a new generation of philanthropists; and,
* An open-source document in a machine-readable format, open for anyone to contribute and/or consume as they please.

### Who is this for?

This guide is for anyone looking for donations, but it is geared toward Canadian organizations with options for converting cryptocurrency to Canadian Dollars.

### What this guide covers

This guide talks a bit about what cryptocurrencies are, why they're different from regular currency (referred to as 'fiat' currency), how to get yourself set up to accept donations, and how to convert the crypto donations you get into Canadian Dollars. 

### What this guide doesn't cover (yet)

#### Tax implications

We're not lawyers, and this isn't legal or tax advice regarding rules around accepting donations of any kind. 

According to cryptogiving.ca "Many charities in Canada that accept donations of cryptocurrencies also provide tax receipts for charitable donations, meaning that you can claim the deduction on your income taxes." This would imply that if your charity is registered and can issue tax receipts for other kinds of donations that it may be able to do so for crypto donations as well, but again, this isn't something we've confirmed and you'd want to seek out the advice of a professional.

Cryptogiving.ca goes on to note that cryptocurrencies are not exempt from capital gains taxes when those gains are given to charity. 

A private members bill was introduced in Canadian Parliament in May 2019 to address this but it did not pass.[^1]

If you would like to contribute research in this area feel free to submit a Pull Request or just get in touch via [this form](https://docs.google.com/forms/d/e/1FAIpQLSdIwUPWLg7bLb7NGEPpNsPOnyclKPJrP7POGu0Z4TssczyQXQ/viewform?usp=sf_link).

#### Distributed Apps

We're also not going to talk too much about the world of [Distributed Applications](https://www.stateofthedapps.com/whats-a-dapp) (or dApps) - websites that can interact with cryptocurrencies to do lots of cool things. Feel free to come back to the topic when you're ready to know more :)

### TL:DR or, I'm in a dang hurry - what's the bare minimum I need to do? 

1. The easiest way to get started accepting Bitcoin and other popular cryptocurrencies is with [Coinbase Commerce](https://commerce.coinbase.com/);
2. On Coinbase Commerce, create a **Checkout** using the 'donation' option. You'll have an opportunity to include a brief description and logo for your organization;
3. Make potential donors aware that you are accepting cryptocurrency donations by **sharing or embedding** the link to your Coinbase checkout from a website you control;
4. Create an account on an **Exchange** that deals in Canadian Dollars (e.g. Coinsquare) and connect a bank account;
5. Once you have cryptocurrency donations that you would like to cash out, **withdraw** the currency from Coinbase Commerce to the wallet of the exchange. *Note there will be minor fees associated with transfers*;
6. On the exchange, **trade** the cryptocurrency for Canadian Dollars; and,
7. Issue a receipt for the Canadian Dollar value similar to how your organization would handle other asset donations.

What is a cryptocurrency?
---

The first part of that word, 'crypto', refers to the principles of cryptography, meaning that information can be securely protected and provably unique. That's a big part of what we try to do with plain old-fashioned money; protect it from being stolen, and prove that it isn't counterfeit. 

Cryptography is the same thing that secures our online purchases and makes sure that it is really difficult to eavesdrop on our iMessages. It is based on the idea that two endpoints of a connection are talking in a 'secret code' that only they can understand, and that the endpoints don't need to previously know each other in order to keep that conversation secure. It works on the concept of [public and private keys](https://www.reddit.com/r/explainlikeimfive/comments/tpqjo/eli5_can_someone_please_explain_how_encryption/).

When you use the internet to transfer money in the regular way, the conversation between the payer and the payee is conducted with this encrypted secret code, but the record of that transaction is only held with (and entrusted to) a third party; the bank or the payment processing company that brokered the connection. The authority in this case holds the keys, making sure that you are who you say you are, and that you actually have the balance on your credit card to do the transaction. Other groups also jump in to act as escrows sometimes, like when you buy something off eBay and want to make sure the deal is fair and square.

Cryptocurrencies change the game.

They take the third party out of the equation, and let people transfer money and assets directly between two endpoints. Rather than a single authority, **the transaction is verified and provable by the entire network** - everyone who participates in the currency. 

In this way there:

* is no single point of failure;
* is no middle-person collecting fees or delaying the transaction (ever try to send money or get paid from a bank in another country? It's not fun); and,
* is a record of all transactions made in that currency, and, being available to all, and being based in cryptography, makes it very hard to cheat the system and 'double-spend' the currency (Don Tapscott equates this challenge to trying to turn a McNugget back into a chicken[^2]).

Different cryptocurrencies have different ways of accomplishing this, but they almost all designed around the concept of a 'blockchain', where each new addition to the chain is based on the one before. Here's a terrific [visual example](https://anders.com/blockchain/) and hands-on demo of the principle at work.

The underlying source code for the network nodes is usually open source and freely available for anyone to view, contribute, and transform into other projects. The blockchains themselves are also publicly viewable through 'blockchain explorers' - here's an [explorer for Bitcoin](https://live.blockcypher.com/btc/). 

Because identical records exist across all the participating nodes in the network, Blockchain projects are also sometimes generically described as 'distributed ledger' technologies. 

The most well-known way for information to be added to this ledger is by all the computers in a particular blockchain network competing to solve a hard mathematical problem. People participating in this 'Proof of Work' are rewarded with new units of the currency. This process, called 'mining,' is relatively slow, energy-intensive and the subject of some scrutiny for its environmental footprint. Often there are small fees associated with blockchain transactions that are also shared among the miners.  

But not all cryptocurrencies are the same. Many cryptocurrencies have implemented alternatives to Proof of Work, and as stores or signifiers of value, have taken the form of assets beyond just 'money.' 

### What else are they good for?

In fact, because they're just tokens, they can represent anything. Sometimes tokens can represent shares in a company (aka a 'Security Token', sometimes they represent votes or membership in a club or group (called 'Utility Tokens', or a certificate of ownership for a one-of-a-kind real or digital thing (a 'Non-fungible Token'). 


### What are some better known Token-Based Assets?

Here's a rundown of the current major currencies and/or 'token-based assets.'

#### Bitcoin

Bitcoin is widely recognized as the first decentralized cryptocurrency.[^3] In 2017 the value of a single Bitcoin rose to over $20000 USD. The price of Bitcoin, combined with the relatively low capacity of the Bitcoin network to process transactions, has led to it being referred to as 'digital gold' - something that isn't necessarily practical for everyday purchases.

#### Bitcoin-like alt-coins

As the code for Bitcoin is open-source, many people have copied the code (a practice known as 'forking' in the open-source world) as the basis of their own coin with the same basic characteristics. 'Bitcoin Cash' and Litecoin are two examples. Some Bitcoin alternatives focus quite heavily on privacy and anonymity. Monero and Zcash are two examples of privacy-focused cryptocurrencies that enjoy a fair amount of popularity, but nowhere near that of Bitcoin and the platform we're going to talk about next, Ethereum.

#### Ethereum

Ethereum is a fundamentally different animal than Bitcoin. Bitcoin is fairly limited in what you can do with it - you can mine Bitcoins, move them around, and include a short message with a transaction. 

Ethereum includes not only the token but a layer of logic that can be programmed. These programs are known as 'smart contracts' because they allow the contract owner to specify the conditions on which Ethereum-based tokens are transferred. These conditions can be votes or approvals by humans (think loans or escrow), or data from outside sources. For example, you can create a smart contract that automatically transfers tokens into an account if weather data indicates that it is sunny - *literally saving for a rainy day*.


#### Ethereum-based alt-coins

That said, the most common use of Ethereum smart contracts has been to create other types of tokens. There are thousands of them, and can be used as currency, Security Tokens, Utility Tokens, and Non-fungible Tokens as mentioned above. 

Many companies have issued and sold Ethereum-based tokens as a means to raise money, not as shares per se, but on the promise of being able to use those tokens to purchase services from that company in the future, or to sell them to others who wish to do the same, presumably for a profit. This practice is colloquially known as an 'Initial Coin Offering' or ICO. Many of these ICOs have gone on to launch successful ventures and many others have been outright scams.[^4]

#### EOS/Ripple/TRON/IOTA

In addition to Bitcoin and Ethereum, there is a whole spectrum of other blockchain projects that have implemented alternatives to Proof of Work. Some are meant to be more general purpose, such as EOS and Tron, and others are meant to focus in one area, such as Ripple and IOTA.

It is unlikely you would be soliciting or receiving donations in these formats, but it is important to know that while people have placed a great deal of 'belief' in Bitcoin the technology landscape is nonetheless evolving very quickly and that certain cryptocurrencies are likely to come into and fall out of favour. 

This relative instability, when coupled with wild pricing fluctuations have kept many people away from transacting with cryptocurrencies for goods and services.

#### Stablecoins

And that's where stablecoins come into the picture. A stablecoin is a generic term for a cryptocurrency with a value that is pegged to some other kind of asset, like a fiat currency, in which case crypto unit is generally equal to one dollar of fiat. [DAI](https://makerdao.com) is one of the most popular examples at this time, along with [USD Coin](https://www.coinbase.com/usdc). 

Not all stablecoins have been able to maintain their peg, and some have turned out to be quite controversial[^5]. From a donations perspective DAI is well-supported and will likely be a safe bet for the time being.

#### Non-fungible Tokens (NFT)

As mentioned above, a Non-fungible Token is a one-of-a kind or limited-edition token that can be provably owned and transferred because its provenance exists on the same type of distributed ledger as other cryptocurrencies. There is an emerging market for provably rare works of digital art for example, bought and sold on exchanges such as [OpenSea](https://opensea.io). If someone wants to donate this type of asset to you will need a wallet that can accept them, and find a buyer who will pay you in fiat or some other form of cryptocurrency in order end up with fiat currency.

Accepting Donations
---

As mentioned in the introduction, to accept cryptocurrency donations you're going to need three things:
1. A 'wallet' that can receive donations;
2. A website, publication, or some means of sharing your wallet's address with potential donors; and,
3. An 'exchange' that you can use to convert your cryptocurrency back into fiat currency.

### Getting a wallet

To quote Wikipedia:

> A cryptocurrency wallet is a device, physical medium, program or a service which stores the public and/or private keys and can be used to track ownership, receive or spend cryptocurrencies. The cryptocurrency itself is not in the wallet. In case of bitcoin and cryptocurrencies derived from it, the cryptocurrency is decentrally stored and maintained in a publicly available ledger called the blockchain.[^6]

That last part is really important - **the wallet's keys are the thing that proves a unit of cryptocurrency on the blockchain belongs to you**. 

As the Wikipedia definition mentions, wallets can take different forms, and have different features associated with them. 

First of all, not all wallets support all currencies. Bitcoin wallets are for bitcoin, Ethereum wallets are for Ethereum and Ethereum-based tokens, and so on. Some wallets support multiple cryptocurrencies.

Aside from supporting different cryptocurrencies, wallets also come in many different forms. They can be web-based, mobile apps, stand-alone desktop apps, hardware-based, or even totally offline paper wallets.

Let's take a few moments to examine some of these things that distinguish the different types of wallets. Most of the following information is curated/adapted from the Blockgeeks [Cryptocurrency Wallet Guide](https://blockgeeks.com/guides/cryptocurrency-wallet-guide/). Feel free to head on over there when you're ready to go a little more in-depth.

#### Single-key wallets

Most wallets are of this variety, where there is a single private key that is used to prove ownership of an associated public key.

The public key is used to send and receive funds, and the private key is used to sign the transaction. When you set up a wallet your public and private keys will be generated when the wallet is set up, and typically you will receive a special 'seed phrase' of random words that need to be backed up and kept in a safe place. Some sites manage the private keys of your wallet on your behalf (and this isn't necessarily a good thing).

##### Multi-Signature wallets

Just like it probably isn't a great idea to have someone else control your private key, depending on the volume of donations it may not be a great idea to need only one person to sign off on a transaction. Multi-signature wallets work a bit like the old days for organizations where more than one signature was required to write a paper cheque. A multi-signature cryptocurrency wallet can add accountability as well as limiting the consequences if one of the private keys is stolen.

#### Hot Wallets

A hot wallet is connected to the internet.

Hot wallets are the quickest way to get up and running in the world of cryptocurrencies, and the most common examples of hot wallets are associated with crypto currency exchange sites, but a desktop or mobile app where the host device is connected to the internet also counts.

Hot wallets pose the relatively highest risk of compromise either through break-ins or hacks, but also through phishing/social engineering exploits (where someone tricks someone else into giving up the private keys voluntarily). 

The security of a hot wallet is dependent on the practices of whoever is hosting your wallet and controlling your private keys, whether that's an online crypto-exchange, or whether it's you through your desktop or mobile app.

Best practice is to avoid using an exchange wallet for long term 'storage' of your currency, and to transfer to a cold wallet (or fiat currency) as soon as possible.

#### Cold Wallets

If a hot wallet is one that is connected to the internet it would follow that a cold wallet is one that, well, isn't. And you'd be right. It's a wallet where the private key isn't accessible to hackers. There are generally two types of cold wallets - hardware and paper wallets. There's a third, called a 'brain wallet', but that basically means you're holding the private keys in your head. We wouldn't recommend that because humans are pretty bad at creating strong passwords as it is.[^7]

##### Hardware Wallets

Hardware wallets typically take the form of a USB key that is protected by some additional factor of protection. You keep your funds offline and plug into to a computer only when needed. As well, some hardware wallets require you to authorize transactions to/from the USB key by pressing a physical button or entering a PIN code, further reducing the risk of funds being withdrawn remotely.

##### Paper Wallets

Paper wallets are regarded by some as the safest form of cold storage. It basically involves includes printing out your public and private keys on a piece of paper (usually as QR codes) which you can store and save in a secure place. It's generally regarded as safer because all you need to do is not lose that piece of paper. Uh, yeah. Speaking from experience that's harder than it sounds, but on the other hand, there's no risk of hacking or malware.[^8]

#### Adding a Custom or Non-Fungible Token to your wallet

As mentioned, if someone wants to donate a non-fungible token you'll need a wallet that can handle them. Most desktop and mobile wallets are capable of this; however they may not be able to show you any media (pictures/music) associated with the token. Search for 'collectibles wallet' to find one that handles both fungible and non-fungible tokens. As mentioned, in order to turn a non-fungible token into fiat currency the first step will be to sell it to someone else for a cryptocurrency that is supported by an exchange.

### The Easiest Way to Get Started

So, all that being said, the easiest way to get started is with a hot wallet. If you recall the TL:DR you probably guessed this as well.

We've already mentioned Coinbase, which is one of the most broadly used crypto exchanges in the world. Coinbase also operates [Coinbase Commerce](https://commerce.coinbase.com/). A Coinbase Commerce account includes a multi-currency hot wallet, as well as the ability to create custom 'checkouts' - widgets that can be embedded on your own site or linked to directly. These widgets take donors through a relatively user-friendly process to contribute to your organization in the cryptocurrency of their choice.

Once you have created an account on Coinbase Commerce, create a checkout using the 'donation' option. During this process you will have the opportunity to include a brief description and upload the logo of your organization.

![Coinbase_Commerce-Address](https://user-images.githubusercontent.com/2702107/74698508-49603f00-51bb-11ea-86d2-da5f47127725.png)

*Fig. X: The Donor's final screen in Coinbase Commerce looks like this (credit: Coinbase Commerce)*

Finally, make potential donors aware that you are accepting cryptocurrency donations by **sharing or embedding** the link to your Coinbase checkout from a website you control (it occurs that even though Coinbase's procedures for identifying customers are fairly rigourous it would be possible for someone to impersonate your organization in a manner similar to phishing scams).

From Coinbase Commerce's administrative interface you are able to review your donations and account balances, as well as initiate withdrawal of your donated crypto to other destinations.

As a hot wallet it is really important to create a strong, hard to guess password and consider using a second factor for authentication (called 'two step verification') where a code is sent by email/sms or an authenticator app. And like any wallet it is really really important to back up the wallet's seed phrase to a safe place. Both of these tasks can be done through the Coinbase Commerce settings screen.

Redeeming Donations
---

So, you've set up an account on Coinbase Commerce or published the addresses of another wallet that you control (see the Electronic Frontier Foundation for an [example](https://www.eff.org/pages/other-ways-give-and-donor-support)) and the donations are rolling in.

At this point its time to make a decision. If you're going to be issuing receipts for these donations you'll need to know the fiat value of the asset at the time of the donation. Thing is, unless you're holding a stablecoin it will likely fluctuate in value. It could be worth more than you issued the receipt for, or it could be worth less, same as any other asset donation.

The way to know the value of your crypto in fiat at any given time is to check with a crypto exchange.

### Crypto exchanges

Cryptocurrency exchanges are websites where you can, as the name implies, trade one form of currency for another, including fiat currencies. A single user account on a crypto-exchange usually comes with multiple wallets associated with the cryptocurrencies that you are trading in.

There are a lot of cryptocurrency exchanges out there, and some are more suitable for Canadians than others. Here's a few of the major ones.

#### Coinbase

Coinbase is generally considered to be one of the largest, most established and mature crypto exchanges. It also operates the aforementioned Coinbase Commerce to make it easy to sell goods and accept donations. It's generally well thought out and easy to use, but...

It's difficult to purchase crypto with Canadian Dollars, and it's impossible to sell cryptocurrency for Canadian dollars on Coinbase. So while Coinbase Commerce makes it easy to start accepting donations, you'll need to transfer your coins to another exchange to turn them into $CAD.

#### Coinsquare

And that's where Coinsquare comes in. A Canadian company that's only available to Canadians, it allows you to buy/sell crypto for $CAD through a number of convenient methods including Interac e-transfer. Get yourself set up there, and with Coinbase Commerce to accept donations you should be good to go. Coinsquare only supports a few of the major cryptocurrencies, but it will certainly cover off most of the donations you'd be getting via Coinbase Commerce, and unsupported coins can always be transferred into a supported coin using an alternate service like Shapeshift. 

#### Shapeshift

Shapeshift is well known for turning one type of currency into another, but it isn't that great at buying and selling for fiat currency. It will show up near the top of a web search but you probably won't need to work with it, unless you have a cryptocurrency that is unsupported by Coinsquare and need to exchange it for one that is.

#### Binance and other Distributed Exchanges (DEX)

Binance, Poloniex and the long tail of exchanges and again are likely only needed if you're trading in the more exotic currencies. 


Crypto-philanthropy
---

Even though this guide is about how to accept direct cryptocurrency donations, there are alternatives that are beginning to emerge. Some would even suggest that cryptocurrencies are disrupting the current system of giving.[^9]

As mentioned previously, one of the defining characteristics of cryptocurrencies is a public ledger of all transaction. This creates a revolutionary approach to financial transparency and the tracking of philanthropic outcomes.

#### Crypto Crowdfunding

These are platforms similar to Kickstarter and GoFundMe that accept cryptocurrency as a form of payment. It may be in your organization's interest to tap into a community of people already familiar and interested in supporting worthy causes and initiatives with crypto.

You may wish to alternately issue a coin of your own creation and then sell it or put out bounties in exchange for the coin. Platforms like [ixo.world](https://ixo.world/) are committed not just to funding but to tracking and measuring social impact.

#### Crypto foundations

The Bitcoin boom of 2017 brought a lot of new wealth in the world, and like those who made fortunes before them the people receiving these windfalls have been making substantial donations to philanthropic causes. 

The Pineapple Fund was one such foundation established as "an experiment in philanthropy with cryptocurrency wealth".[^10] All in all, over $55 million dollars was anonymously, yet transparently, donated to 60 different charities.

#### Browser Mining

By way of another interesting example of new and emerging forms of crypto-philanthropy, [Donate Your Tab](https://donateyourtab.to/) is an experiment to harness peoples' local computers for collective impact. Basically, while you have the website open and the service switched on, your computer is using your web browser to mine very small amounts of the Monero cryptocurrency and donating the mined currency to one of the charities available on the site. 

This practice of browser mining is generally frowned upon because it is usually done on sites without the user's knowledge or permission. Donate Your Tab subverts this by making it an opt-in process for social good.

#### Donor Advised Funds

Finally, an alternative to all this for Registered Charities may be to work with a Donor Advised Fund (DAF) that accepts cryptocurrencies. According to one such group, [charitableimpact.com](https://www.charitableimpact.com/blog/donate-cryptocurrency-charity-chimp/), "users put their (crypto) assets into an account, receive an immediate tax receipt, and then decide which charities to send them to later." 

## Conclusion

If you've made it this far, congratulations. We hope it wasn't too hard to get here, because that wasn't the intention. We hope you've gained a basic understanding, a basic direction on how to proceed, and a taste of what's on the horizon. 

This is an exciting new area of opportunity that is going to continue to grow, and it's not too late to get started.

Contributors
---

<!-- Use github handle -->
[@chado1](https://github.com/chado1)

Revision History
---

1. July 2019 - skeleton outline
2. December 2019 - first draft (no images yet)
3. February 2020 - link to github / documentation site generator


References
---

<!-- for readability in the document generator -->

1. https://openparliament.ca/bills/42-1/C-452/
2. https://blockchainflashnews.com/blockchain-is-like-turning-a-chicken-mcnugget-back-into-a-chicken/
3. https://en.wikipedia.org/wiki/Cryptocurrency
4. https://cointelegraph.com/ico-101/what-is-ico
5. https://en.wikipedia.org/wiki/Tether_(cryptocurrency)
6. https://en.wikipedia.org/wiki/Cryptocurrency_wallet
7. https://coinsutra.com/how-to-create-brain-wallet/
8. https://blockgeeks.com/guides/paper-wallet-guide/
9. https://medium.com/@pauljlamb/crypto-philanthropy-how-bitcoin-and-blockchain-are-disrupting-the-philanthropic-sector-80716dc7cb68
10. https://pineapplefund.org/

<!-- notation for proper linking -->

[^1]: https://openparliament.ca/bills/42-1/C-452/
[^2]: https://blockchainflashnews.com/blockchain-is-like-turning-a-chicken-mcnugget-back-into-a-chicken/
[^3]:https://en.wikipedia.org/wiki/Cryptocurrency
[^4]: https://cointelegraph.com/ico-101/what-is-ico
[^5]: https://en.wikipedia.org/wiki/Tether_(cryptocurrency)
[^6]: https://en.wikipedia.org/wiki/Cryptocurrency_wallet
[^7]: https://coinsutra.com/how-to-create-brain-wallet/
[^8]: https://blockgeeks.com/guides/paper-wallet-guide/
[^9]: https://medium.com/@pauljlamb/crypto-philanthropy-how-bitcoin-and-blockchain-are-disrupting-the-philanthropic-sector-80716dc7cb68
[^10]: https://pineapplefund.org/

