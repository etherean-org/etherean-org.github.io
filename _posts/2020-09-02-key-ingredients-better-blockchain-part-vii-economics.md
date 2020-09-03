---
layout:   post
title:    "The key ingredients to a better blockchain, Part VII: Economics"
subtitle: "Our understanding of what makes a blockchain successful is becoming clear. What will it take to succeed?"
image:    /assets/jude-beck-41uCnC2RDck-unsplash.jpg
author:   Lane Rettig
date:     2020-09-02 09:20:00 -0400
categories: [blockchain, economics]
---
![Ceramic Piggy Bank]({{page.image}})

<p style="text-align: center"><sub>Blockchain is to economics what virtualization is to computing: it allows us to run more economic experiments at a much faster pace. It remains to be seen where this experimentation will lead. Photo by <a href="https://unsplash.com/@judebeck?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Jude Beck</a> on Unsplash.</sub></p>

{%- include blockchain-nav-top.html -%}

* Table of contents
{:toc}

## Introduction

### Economic virtualization

One of the most important lenses we can use to understand blockchain is economics. A blockchain is, among other things, an “economy in a box.” In this way, blockchain is to economics as virtualization is to computer science.

[Virtualization](https://en.wikipedia.org/wiki/Virtualization), i.e., running multiple logical servers (usually called VMs, or virtual machines) cheaply on a single physical system, has vastly reduced infrastructure costs. Hosting websites and applications used to be beyond the reach of all but the most professional, well-funded startups. Today, anyone casually building something at a hackathon can have a backend up and running on a VM in seconds very cheaply or for free.

In like fashion, blockchain enables _economic virtualization._ Just as the virtualization of computing led to an explosion of innovative apps and services that directly enabled the modern digital economy, virtualization of economics is leading to a Cambrian explosion of new economic ideas, applications, and protocols that, in time, will change the world.

Until recently, if you wanted to run a large-scale macroeconomic experiment, you needed a country, a currency, and an economic ministry. This is no longer the case. Anyone with a little know-how can create their own cryptographic token, or even their own fully-fledged blockchain, with whatever set of economic incentives they want.[^1]

What’s more, the near-total [lack of privacy](/blockchain/privacy/2020/03/26/key-ingredients-better-blockchain-part-vi-privacy.html) among existing blockchains is a boon to economists since it lets them study these micro-economies in high fidelity and in real time. By working with core teams to design and implement better economic policies, economists can test their theories _in situ_ in a live economy, something that was impossible before blockchain. Since the stakes are so much lower—there aren’t yet trillions of dollars of existing business, livelihoods, and institutions relying upon blockchains—it’s possible to run much more radical experiments.[^2]


### Good economic governance

While blockchain is capable of enabling a wide range of exciting economic experimentation, in order for these experiments to thrive and yield meaningful results, it’s important that the base layer be well-governed and maintain sound economic policy. This requires asking difficult, contentious questions such as, What are cryptographic tokens, fundamentally?[^3] Who should hold them? How should they be distributed? Where and how is value captured and distributed? How should we think about common goods funding?

The rest of this article focuses on these important questions. As with so many of the other topics covered in this series, it’s important to note that _failing to make a decision is, in effect, making a decision._ If you don’t think about the economics of your blockchain, it doesn’t mean these economic questions magically go away—and you’ll very likely end up somewhere other than where you want to be! So it’s worth taking them seriously.


### Secret power

The economic secret power of blockchain is the fact that its economic policy can be entirely autonomous and sovereign, not subject to the policies or constraints of any existing currency, commodity, or economy. Issuance can be capped or uncapped. A native token can float freely or be indexed against a more stable asset. It can be convertible to other assets or entirely independent. The set of possibilities is enormous, and is at least as great as that of countries and territories with sovereign currencies—in fact, probably greater, since blockchains have fewer constraints than countries.[^4]

In the past, if you wanted to start a venture, you had to follow a set of existing economic rules and work within the bounds of extrinsic constraints. This is because any venture, whether for profit or nonprofit, involves some exchange of value. To exchange value meant choosing an existing set of payment rails and conforming to its requirements.

Blockchain has fundamentally changed this, for better or for worse. In a sense, blockchain lets you defy economic gravity. As many blockchain projects have by now proven, you no longer need to raise fiat money from traditional investors to bootstrap a project. You need not subject yourself to someone else’s economics. You can mint money—in the form of digitally scarce cryptographic tokens—out of thin air, so to speak. You can subsequently give them, or sell them, to investors and other project stakeholders, thus bootstrapping an autonomous micro-economy.

In a sense, this is no different than what companies have been doing for centuries with stock. However, there are two important differences between tokens and equity. For one thing, company equity is highly regulated, which in practice severely limits what companies can do with it: how much they can issue, who they can give it to, whether the holders can trade or sell it, etc.. For another, the purely digital nature of cryptographic tokens vastly increases the scope for creativity in their design. Novel cryptoeconomic mechanisms (on which more [below](#whats-the-purpose-of-the-token)) allow these tokens to be issued, bought, sold, burned, and traded in ways that corporate CFOs can only dream of.

Enough with the introduction, let’s get to the questions!


## Does the project need a token in the first place?

The first and arguably the most important question you should ask yourself as a founder is, does your project need its own token? For the vast majority of projects, the answer should be a resounding “No.” There are already thousands of networks and tokens, and many are part of open, permissionless protocols, networks, and ecosystems that encourage innovation. You’ll need a very compelling reason to overcome skepticism on the part of investors and ecosystem participants, in addition to convincing the market that the world needs yet another “shitcoin.” Successful projects such as Uniswap show what’s possible without issuing a token.[^5]

Frustratingly, most projects that issue tokens do so primarily in order to raise money. Most don’t have a compelling story to tell about why their token has value or why anyone should buy or hold it. This strategy worked in 2017 but, fortunately, the market has matured quite a bit since then.

There are two legitimate reasons to issue tokens, one good, one sort-of-good.

The good reason is monetary policy. This is the one thing that you absolutely cannot do if your project uses another token since it involves issuing tokens. Most applications probably do not need to worry about monetary policy and would be better off focusing on things like product design and user experience. However, layer one protocols probably do need some form of monetary policy since, as discussed above, they’re effectively micro-economies.[^6]<sup>,</sup>[^7]

The sort-of-good reason is governance. [Good governance](/blockchain/governance/2020/01/06/key-ingredients-better-blockchain-part-v-governance.html) means clearly delineating who does and does not have voice or power, the way a nation state does with the notion of citizenship. Due to [Sybil attacks](https://en.wikipedia.org/wiki/Sybil_attack) and the limitations of identity in purely digital jurisdictions, scarce cryptoeconomic tokens are one way of enforcing this delineation. It’s by definition plutocratic, which isn’t necessarily a bad thing: modern firms operate as plutocracies because it’s straightforward and efficient. There are other forms of cryptoeconomic governance, but those other ways are mostly harder and are only just starting to be developed, while several fairly standard token-based governance models have already emerged.

If you’ve decided that your project doesn’t need a token, congratulations! You can skip the next section. If you still think you need a token, the next most important question is: what’s it for?


## What’s the purpose of the token?

The most common classes of tokens are work tokens, utility tokens, security tokens, and governance tokens. This list is not intended to be exhaustive, and novel token designs are rapidly emerging, but most designs more or less fit into one or multiple of these categories.[^8] You should have a pretty good reason if you intend to deviate from this list.


### Work tokens

Work tokens are commonly compared to a taxi medallion: a service provider must obtain and subsequently stake the token before they can begin providing services to the network. Typically, service providers receive more of the same token in exchange for providing work, and if they misbehave by, e.g., breaking the rules of the protocol, they can be punished by having their stake “slashed” (i.e., reduced, or burnt).

The work that service providers perform could be objectively or subjectively useful. Running a validator node in a proof of stake network is an example of objectively useful work, since it involves confirming transactions and contributing to network security. Rewarding objectively useful work with tokens has the nice property that it’s [credibly neutral](https://nakamoto.com/credible-neutrality/) and thus tends not to be contentious.

By contrast, [SourceCred](https://sourcecred.io/) is an example of a system and a project where tokens are assigned on the basis of subjectively useful work that’s recognized by one’s peers. This work could include writing code, being active in chat groups and forums, or hosting events.


### Utility tokens

You can think of a utility token like a ride ticket at a carnival. The network offers some service, and in order to meter access to the service a limited number of utility tokens are minted and sold. The tokens can be exchanged for access to the service. The price of the service, i.e., the number of tokens required to purchase one unit of the service may be constant or it may vary depending on supply and demand.

Bitcoin is a utility token because it can be redeemed for block space in future Bitcoin blocks. In Ethereum, ether can be used in the same way: to pay for gas for future transactions. This _redeemability_ is one way to reason about the intrinsic value of utility tokens: to the extent that Bitcoin block space, and compute time and storage in the Ethereum “world computer” continue to have value, and that both remain scarce, these tokens will continue to have intrinsic value.


### Security tokens

A security token is, simply, an analogue to a financial security. By purchasing a security token, you are investing in the company, project, network, or community that issued the token. Unlike financial securities, the idea of a security token is rather ill-defined and many tokens marketed explicitly or implicitly as security tokens offer few or none of the protections and advantages that traditional securities offer investors. In fact, in the blockchain community, the idea of a security token has become something of a bête noire and is usually considered an antipattern. Many project teams try to ensure that their token design does not pass the infamous [Howey test](https://en.wikipedia.org/wiki/SEC_v._W._J._Howey_Co.), will not be classified as a security, and thus will avoid the outcome of ill-fated projects such as [TON](https://telegra.ph/What-Was-TON-And-Why-It-Is-Over-05-12).

Just as traditional financial securities like stocks and bonds have a source of intrinsic value such as a stream of future dividends or coupon payments, a security token should, in theory, also include a future cashflow in order to have value. Well-designed security tokens work this way: for instance, in a proof of stake network, tokenholders can stake or bond their tokens to receive a portion of future inflation and transaction fees.


### Governance tokens

A governance token gives a project stakeholder a voice in project governance. The simplest example is an [on-chain governance](https://messari.io/article/on-chain-governance) system where one token equals one vote (and those without tokens cannot vote). In more complex systems, one may be able to [cast multiple votes](https://en.wikipedia.org/wiki/Quadratic_voting) in favor of a particular issue, or stake or lock a governance token for some period of time to [amplify their vote](https://polkadot.network/a-walkthrough-of-polkadots-governance/).

Such a token may have value simply because it provides a voice in the governance of a valuable system. However, there are also more sophisticated governance token designs that provide explicit incentives for good governance. An early example is the MKR token in Maker.

MKR tokens have value because they give the holder power in [the governance of the Maker system](https://community-development.makerdao.com/makerdao-mcd-faqs/faqs/mkr-token). MKR tokenholders vote to govern certain aspects of the system such as fees and the minimum required collateralization ratio. Similar to work tokens, if the system functions well, MKR tokenholders should see the value of their holdings increase. This is because MKR tokens are burnt in the process of normal usage, and this deflationary pressure exerts upward pressure on the price of the token over time. If MKR tokenholders are negligent in their governance duties or make bad economic decisions, the system can become undercollateralized. In this scenario, the system automatically mints and sells new MKR tokens, diluting the same tokenholders. Incentives are thus aligned on both the upside and the downside.[^9]


### Hybrid tokens

It’s important to note that in practice many or perhaps even most tokens exhibit characteristics of multiple of these classes. ETH, for instance, can be earned, like a work token, in exchange for providing useful work to the network—namely, mining. It also requires staking, whether directly, as in the case of PoS (under Ethereum 2), or via a proxy such as electricity as in the case of PoW. And like a utility token, users who wish to utilize the services of the network need to acquire ETH and exchange it for access to the network’s services (i.e., to pay gas to have transactions mined). In networks with on-chain governance, the native token can also act like a governance token.


## Why does the token have value?

It’s not essential that a token have a market-based value. Other forms of value may be just as or even more important. For instance, a small group of collaborators may decide to create a DAO and give each of its members a token that allows them to vote. This has intangible and practical value but little to no economic value. Collectibles such as [POAP tokens](https://www.poap.xyz/) allow community members to assert that they attended past events, but the value of these tokens is sentimental, not economic. Very few people would pay money for a token from an event that they did not actually attend, few enough that there will never be a market for such tokens. In fact, when a token that’s not intended to be a security does develop economic value that’s recognized by the market, it can [detract from the experience](/blockchain/economics/experience/2020/05/24/cult-of-ownership.html) of using a platform or service by making it harder or more expensive to access.

For some types of token, however, value is an important part of the design. If a work token had no value, then anyone could acquire the tokens, offer low-quality or unreliable service to the network, and abscond at no cost to themselves (this is known in blockchain as a [griefing attack](https://vitalik.ca/general/2017/07/16/triangle_of_harm.html)). For this reason, work tokens are useless if they have no value and no market.

It’s naive to believe that a token will have value simply because it’s required to access a service, especially if the value of the service itself is unclear and if the token doesn’t have some form of intrinsic value. Without a strong case for the intrinsic value of a new token, it’s better to rely on an existing token with value rather than trying to create a new one.


## Do you need a stable token?

Stable tokens, a.k.a. stablecoins, are designed to overcome the challenges associated with the high volatility of many crypto assets. Indeed, users will be reluctant to hold a token for any length of time, or to transact with it, if it increases or decreases in value by [as much as 10% in a single day](https://www.tradingview.com/symbols/BVOL24H/)!

Stability is generally accomplished by making the price of the token track that of one or more underlying assets that are more stable, such as USD, or a basket of currencies or more stable tokens. This makes stable tokens a better form of money than other crypto assets: they’re more useful as a unit of account, medium of exchange, and store of value.

While the idea is simple, designing a working stable token is in fact a complex feat of financial engineering. The details are beyond the scope of this article, but some of the more robust existing designs speak to the expressive power of token design and the importance of factoring in many of the economic challenges discussed in this article. 

There are [three prevailing models](https://www.cbinsights.com/research/report/what-are-stablecoins/#types) of stablecoins: centralized asset backed (a.k.a. fiat or commodity-backed, e.g., Tether), decentralized asset backed (a.k.a. crypto-backed, e.g., Maker DAI), and seigniorage (e.g., Celo). The details are beyond the scope of this article, but each model has advantages and disadvantages. Think carefully about which most closely aligns with your project’s goals and values.


## One token or multiple tokens?

A system with a single token is simpler to design, understand, and reason about. However, some economic designs aren’t possible with a single token, and some require multiple tokens that act in a complementary fashion. A good example is the model which pairs a governance token with a stable token, adopted by projects such as Maker and [Celo](https://celo.org/papers).

The complexity of an economic system increases exponentially in the number of tokens that it employs, as do the number of things that can go wrong. For this reason, other things being equal, fewer tokens make for better designs. I have yet to see a well-designed, working system that uses more than two tokens, but some [interesting](https://www.basis.io/basis_whitepaper_en.pdf) [proposals](https://www.placeholder.vc/blog/2020/3/6/aragon-ant-economics) exist and I’m excited to see how they play out in the coming months and years.


## How are contributors rewarded?


### What is a blockchain?

One of the things that makes blockchain economics difficult and contentious is the fact that blockchain is novel and defies simplistic classification. A blockchain is kind of like a startup in that, typically, a small team raises money from investors (who expect a return on their investment) and use it to pay for the costs associated with designing, building, launching, and operating the platform.

Even small, highly centralized companies inevitably face the challenge of how to fairly compensate contributors. How should a firm balance compensating the earliest stakeholders, such as the investors and the founding team, for the risk that they took in launching the project, while also retaining enough dry powder (in the form of unissued equity) to attract and retain talented contributors throughout the firm’s lifecycle?

However, if a blockchain were just a startup, it wouldn’t be very interesting because a private company raising money to build a database is nothing new. Indeed, a blockchain is _unlike_ a startup in that the project is open and permissionless. Anyone, anywhere can use the final product—the platform—to transact or, indeed, to build applications, services, and businesses. In this respect, blockchain is less like a startup and more like a political entity such as a city or a nation state: its governance and economics are to some degree decentralized and beyond the control of any one organization or group of people. The micro-economies of the largest blockchain platforms contain thousands of applications, business, and services, and millions of users.

The challenge becomes greater as the number of contributors grows, especially once control over economic policy is decentralized. If you consider all the ways the economy of a nation state may reward industry and distribute wealth, and all of the ways in which it may fail to do so, you’ll see why this question is so complex and multifaceted. Nevertheless, decisions made early in the life of a project, and the [culture and values](/blockchain/community/governance/2019/11/18/key-ingredients-better-blockchain-part-iv-constitution.html) installed by the project’s founders, will continue to have outsized impact for a very long time. That’s why it’s important to consider questions such as [wealth distribution](/blockchain/economics/society/2020/05/02/to-share-or-not-to-share.html), and to get these things right in the beginning.


### Three variables

One way to think about an economy is as a machine for distributing wealth and other scarce resources. How that distribution occurs matters a great deal. This is of course a very old human problem, as contentious today as ever, and it has no definitive answer. I won’t attempt to answer it here, but I will explore some of the levers that blockchain platforms and communities can manipulate as they search for an optimal configuration that works for them. For our purposes, we’ll focus on three such variables: initial configuration (endowment), ongoing distribution (inflation), and distribution function (who gets what, and on what basis).

Before attempting to derive a model for fair ongoing compensation for blockchain, let’s start with a simpler case: a firm. We can look at how actual firms think about rewarding contributions over time as a starting point. We'll use Apple stock as an example. For sake of argument let’s assume that a company’s public offering is a bit like a blockchain launching its mainnet. The set of Apple shares outstanding as of its IPO was the system’s initial configuration. The number of shares that were subsequently authorized and issued served as its inflation. Finally, the way in which those newly-issued shares were distributed was its distribution function.[^10]


### Apple

On the day of its IPO, December 12, 1980, Apple had around 50M [shares outstanding](https://www.quora.com/How-much-equity-did-Steve-Jobs-have-during-Apples-IPO-Did-he-really-have-double-the-equity-of-Woz), 32M of which were held by its officers and directors (including Venrock, the fund which led its first venture round). Over the following decades the firm regularly issued new shares, and the number of shares outstanding peaked at 6.631B in 2012, or around 132x the number of shares outstanding as of the IPO.[^11] In other words, between 1980 and 2012, Apple issued on average around 16.5% new shares every year. Some of those shares were sold to new investors to raise additional capital, and some were awarded to employees as part of equity-based compensation.


### Ethereum

To introduce a comparison from the perspective of blockchain, Ethereum issued around 72M ether as part of its presale and premine in 2015 (initial configuration). A lot of that ether ended up in the hands of the Ethereum Foundation, ConsenSys, and a small number of other investors and early team members. Ongoing work on the Ethereum platform has mostly been paid for out of these funds in the form of grants and payments to employees and contractors. At the same time, since launch Ethereum has had a compound annual growth rate of about 9% (inflation), all of which has gone to miners, so that the [supply outstanding today](https://etherscan.io/chart/ethersupplygrowth) is around 112M ether. Ethereum’s distribution function is thus bimodal: it has handed ether both to miners out of ongoing issuance, and to those working on the platform out of the premine.

Unlike Apple, however, Ethereum’s inflation rate has been reduced several times, further reductions are planned, and the community may eventually decide to permanently [cap supply](https://www.investopedia.com/news/why-ethereum-cofounder-proposing-hard-cap/). There is not much appetite in the Ethereum community for issuance to remain high indefinitely. This raises the question, how will ongoing contribution, especially to common goods, be funded if issuance decreases?


### Other models

There are other models. Bitcoin, for instance, has managed to fund ongoing work for over a decade while issuance continues to decrease (on which more [below](#how-is-the-common-good-funded)). Private companies and individuals that have profited from and continue to rely upon the network can and often do fund such work in both Ethereum and Bitcoin, affectionately referred to as the “benevolent billionaire” model. It’s unclear how sustainable this model is over the long term, however, since premine funds won’t last forever, and most of the charitable individuals and organizations have no ongoing source of revenue. They tend not to be profitable, or are non-profit foundations. The model is also subject to a [great deal of bias](/blockchain/economics/2020/05/10/the-problem-with-grants.html) and has the downside of not being permissionless and [credibly neutral](https://nakamoto.com/credible-neutrality/) the way, e.g., mining and the mature, liquid market are.


### Wealth distribution is hard

As the blockchain space continues to become more competitive, it’s in the interest of every project team to consider how to distribute the wealth generated by the community in the fairest way possible. Different teams will of course choose different paths, informed by the [values and principles](/blockchain/community/governance/2019/11/18/key-ingredients-better-blockchain-part-iv-constitution.html) of each community. It can help to ask some straightforward questions: Are the people adding real value to the project receiving compensation that’s similar to what they’d receive for doing similar work for another similar project, or at a company of a similar stage? Is their compensation sufficient so that they can focus all of their effort and attention on the platform? Do they have adequate benefits? How much of the overall value of a network or platform was accrued at the instant of its creation, on the part of its founders, relative to the value accrued by ongoing, long-term development work on the part of a much larger set of stakeholders and contributors? I explore these questions further in [To Share or Not to Share?](/blockchain/economics/society/2020/05/02/to-share-or-not-to-share.html).

One final point: while wealth distribution may at first glance appear to be zero-sum, in point of fact it is not. More talented people working to create more value will grow the overall size of the pie. We should be focused on growing the pie and on sharing the fruits of this shared exercise in value creation more widely. Otherwise, what’s the point of blockchain and how is it any different than that which came before?[^12]

Wealth distribution is, of course, more an art than it is a science. Whatever path you choose, enacting it will require designing and installing good economic policies, the topic of the next section.


## What are the economic policies?

One big difference between a blockchain and a city or a country is that, in a blockchain, management of the economy can be either active or passive. The best example of passive economic policy is Bitcoin: its issuance, i.e., its monetary policy, was fixed at genesis and (aside from a small number of critical bugfixes) it has not changed since then, and it may never change again. Bitcoin issuance halves roughly every four years and will eventually taper off to zero in [a little over 100 years](https://en.bitcoin.it/wiki/Controlled_supply), after which point no new bitcoin will ever be issued. That is the entirety of Bitcoin’s economic policy.[^13] It has no fiscal policy because it has no government, nor any form of active governance to speak of, and all spending occurs on the part of private actors acting in their own interest.

By contrast, Ethereum has far more active economic management, in the form of both monetary and fiscal policy. Ethereum’s issuance schedule has been changed several times by its core developers, typically for technical reasons. There is no official party line on its monetary policy, other than to pay as little as possible for a “sufficient” degree of security.[^14] Unlike Bitcoin, Ethereum has no concrete plans to reduce block rewards to zero, but the expectation is that rewards, and thus inflation, will be [significantly reduced](https://blockonomi.com/ethereum-2-eth-inflation/) after the eventual transition to Ethereum 2 and proof of stake. Ethereum’s fiscal policy comes in the form of spending on the part of the Ethereum Foundation as well as of private organizations such as ConsenSys, both of which fund the common good in Ethereum: ongoing R&D work on core infrastructure. The “revenue” for both of these organizations was paid by all network participants, past, present, and future, out of the initial premine and crowdsale (funds that were used to establish both organizations, and continue to fund the bulk of their operations to date).

Bitcoin and Ethereum thus represent two opposite poles, from passive to active economic policy. There are many points in between. Zcash offers another interesting example. Its community recently [decided to reauthorize](https://news.bitcoin.com/zcash-to-distribute-20-of-mining-rewards/) an existing ecosystem fund, in the form of a 20% tax paid out of ongoing issuance, to fund common goods work including the work of the Zcash Foundation and the Electric Coin Company.

There are many other possible configurations of both monetary and fiscal policy. In addition to premine (genesis token distribution), taxation, and ongoing issuance (block rewards), one may also consider how transaction fees are set and paid (e.g., whether they may be paid in multiple tokens); whether fees are burnt or “recycled” (and a portion paid to, e.g., miners or core developers); curation; reputation; identity; and all of the other fantastic cryptoeconomic and [token engineering primitives](https://blog.oceanprotocol.com/towards-a-practice-of-token-engineering-b02feeeff7ca). The design space is vast and practice is still emerging so there’s scope for innovative and fascinating economic experimentation. Watch this space.


## How is the economy managed?

Once you’ve chosen a set of economic policies, the next question is, how should this policy be managed and enforced? In other words, how should the system be governed? This design space is also vast. Economics and governance are of course not new fields and there’s a body of theory and practice going back millennia that we can draw from. A good starting point is Part V of this series, on [Governance](/blockchain/governance/2020/01/06/key-ingredients-better-blockchain-part-v-governance.html).

The most interesting and most unique aspect of blockchain governance is its decentralized nature. This is both a challenge and an opportunity. It’s simpler and easier to manage economic policy in a highly centralized fashion. But it’s also less interesting because it’s not novel: governance of almost every private company is highly centralized. The interesting and challenging thing to do is to take advantage of the [superpower of blockchain](/blockchain/2019/09/15/key-ingredients-better-blockchain-part-ii-decentralization.html) and decentralize management of the economy.

As discussed above, one idea that’s been reasonably well tested is the [governance token](#governance-tokens). Holders of such a token have the collective power to adjust economic parameters, within the bounds of a protocol. In a well-designed system, they are also incentivized to govern the system well, participating in some economic upside if the system is well-governed, and paying an economic price if it is not.

I see two challenges with this model. The first is that it’s inherently plutocratic. It costs money to buy a governance token and thus to have a voice in governance, meaning that wealthier actors will always have more influence. This is okay for some systems, especially simple systems that are designed for a limited set of participants, but it will fail to account for the needs of a large, diverse set of stakeholders (if that’s your goal). While a more inclusive form of governance such as democracy is desirable for systems with many and diverse stakeholders, we have yet to figure out how to govern blockchains in this fashion due to challenges involving identity, Sybil resistance, and defining the set of stakeholders.

The second challenge is the “meta” challenge: to the extent that you’ve picked the right set of parameters and set the right ranges and thresholds, a system may be governable in a decentralized fashion. But what happens if the parameters themselves aren’t chosen correctly? What happens when something needs to be changed _outside of these bounds?_ Upgradability, which is really a question of meta-governance—how to change and upgrade the governance mechanism itself—is a serious challenge in decentralized systems.

For this reason, rather than trying to decentralize everything at once, it probably makes more sense to start with centralized governance over most aspects of the system. Isolate one or a small set of parameters and allow them to be governed in a more participatory, decentralized fashion. You can always “throw away the keys” and fully decentralize the system later. This strategy is known as progressive decentralization.


## How is the common good funded?

Another way in which a blockchain resembles an economy is in the question of common goods funding. In economic terms, a common good is both rivalrous (i.e., my consumption prevents your consumption) and non-excludable (no one can be prevented from consuming it). Because of these properties, common goods are subject to [tragedy of the commons](https://en.wikipedia.org/wiki/Tragedy_of_the_commons): everyone enjoys the resource but no one feels obligated to pay for it or maintain it. Common goods include things like clean air and water (if someone pollutes the air or water, everyone suffers as a result), and physical infrastructure such as roads, bridges, and tunnels (which are subject to traffic).

Does your community recognize the notion of a common good? In the context of blockchain, this includes things like core infrastructure and development that supports the network. The blockchain itself is rivalrous because the network only supports a fixed amount of block space and a fixed number of transactions per second, and access to an open network is by definition non-excludable. The common good also includes things like leadership and coordination, events and other forms of marketing, education, etc. that are widely beneficial to the community and ecosystem.

In communities such as Bitcoin that eschew the notion of common goods, this is a gray area. Common goods, such as core infrastructure and development, clearly do exist even in Bitcoin, but they’re funded by private actors out of self-interest. This model can work once an ecosystem matures and there are robust and diverse sources of private funding. Early in the lifecycle of a project, it can be very helpful to have a governance mechanism to bootstrap this virtuous cycle. A good example is the Zcash community, which has explicitly chosen to maintain a fund for the common good.

Indeed, funding common goods is one of the key roles of governance. Sustainable common goods funding can come from either monetary policy (inflation) or fiscal policy (taxation). This revenue can be collected either upfront, in the form of a premine, or on an ongoing basis.

There are other hard questions: what, exactly, is considered a common good? Who makes this decision? How are the funds managed and distributed? One common distribution model is a grants program, which can certainly help, but grants are centralized, are not permissionless, tend to be biased, and are often not transparent (for more on this topic, see [The Problem With Grants](/blockchain/economics/2020/05/10/the-problem-with-grants.html)).

Ultimately, the way each community agrees to define and support common goods depends on the community’s values. To the extent that a community places emphasis upon values such as inclusivity, permissionless contribution, and sustainability, a source of common goods funding may be required to put these values into practice. By contrast, communities with more libertarian values may find the idea of common goods funding distasteful.


## How do you get tokens into as many hands as possible?

Cryptographic tokens are a powerful, novel tool. Never before has it been possible to grant a meaningful stake in the ownership, governance, and economic upside of a potentially lucrative platform, project, or product to a large, financially unsophisticated, geographically diverse group of people. Blockchain takes novels ideas such as crowdfunding and [exit to community](https://www.colorado.edu/lab/medlab/exit-to-community) to the logical extreme, allowing a community of passionate supporters to bypass the rarified world of VCs and IPOs entirely and bootstrap a large-scale infrastructure project on their own. This is an underappreciated, under-researched, and poorly understood factor behind the most successful blockchain projects. It is also one of the reasons that the communities backing such projects are highly international.

In theory, everything that a cryptographic token enables was possible before, but it came at a high cost. The idea of selling a stake of ownership, governance, and economic upside in a highly bespoke fashion to individuals in dozens of jurisdictions was unthinkable before, and the legal fees alone would have made it impractical. Cryptographic tokens have reduced the transaction costs associated with this process by orders of magnitude.

Getting even a nominal number of tokens into the hands of a prospective community member can have a powerful, captivating effect. I still remember the feeling of buying my first bitcoin. It was a watershed moment. I had bought stocks and bonds before, but bitcoin felt remarkably different. Here was something I actually cared about, actually understood—a project where I was a peer, rather than a second- or third-class citizen.[^15] Even more importantly, it was a project that aligned with my values, and one that I could contribute meaningfully to. And, unlike a traditional crowdfunding campaign hosted on a platform like Kickstarter, I could even participate in the economic upside of the project. It seemed too good to be true.

The importance of having a broad set of community members who own network tokens cannot be overstated. Getting this right is not trivial, and it is one of the very most important things a project founder can do. Ultimately, you have to ask yourself: who is your project for? Who are its stakeholders, both present and potential?

If the project has a relatively narrow vision and is intended to benefit a small group of stakeholders, you may have no trouble identifying those people and ensuring they have tokens. However, many blockchain projects claim to be building a platform for the whole world, and for people everywhere. This is another matter entirely! In this case you need a credible plan for getting tokens into the hands of as many people in as many places as possible. This is not something that can be done in a totally centralized way, but nor is it something you can just “let the market sort out”—because the market is not good at reaching the 99.9% of people who have never traded cryptographic tokens.

It’s easy to give tokens to cofounders, investors, friends, and [people who happen to be in the room](/blockchain/economics/society/2020/05/02/to-share-or-not-to-share.html). Going beyond this group is surprisingly difficult. It requires care, thought, and careful planning and attention.

One option is the RegA+ regulated crowdsale that Blockstack performed.[^16] While this allows you to go beyond accredited investors and it’s one of the only ways to legally distribute tokens in the United States, even this will probably only allow you to reach a relatively wealthy, sophisticated few. Reaching a broader audience may require an unregistered token offering, and/or doing something more creative such as an [airdrop](https://github.com/handshake-org/hs-airdrop).[^17]

Distributing tokens is more of an art than a science, and it’s definitely not one-size-fits-all. Having said that, as a rule of thumb, I think you could do worse than the following breakdown. Use this as a starting point and adapt it to the needs and circumstances of your project and community.

Around 10% of the tokens should be reserved for the core team. Another 10% should be used to compensate early investors. All of the rest should be reserved for the community. Some significant chunk of these should probably be used to pay for ongoing security—perhaps half of the remaining tokens, or 40% of the total. And the remaining 40% should be distributed over a reasonably long period of time, perhaps five or ten years, to community members that create value in other ways: by organizing events (great for increasing geographic diversity), by contributing code, design work, or other “building,” by helping spread the word about the project, by writing documentation, etc. As a rule of thumb, you should endeavor to _sell_ as few tokens as possible—ideally, none!—and instead make folks earn them through one form or another of “proof of work.”

Also, make sure you use vesting. With the possible exception of something like a bounty, where a “mercenary” contractor is hired to deliver some straightforward deliverable, _everyone_ that receives tokens should be subject to a vesting period of at least three or four years. Founders should set an example by subjecting their own tokens to such a vesting schedule. Projects that chose not to impose vesting saw most core contributors abandon the project shortly after launch, which was demoralizing to the rest of the community.


## Are you reinventing the wheel?

A little bit of game theory can go a long way. The field of cryptoeconomics didn’t exist until a few years ago, but it has matured quite a bit recently. On top of existing economic theory, especially game theory and mechanism design, cryptoeconomics introduces certain “primitives” such as bonding and staking, slashing, and fraud proofs that can be used to build robust incentive models.

These primitives can be used to design robust economic incentives. Your goal should be incentive compatibility, which is just a fancy way of saying that all network participants are incentivized to do what is best for the network. In other words, an individual’s incentives should align as closely as possible with the network’s incentives.[^18]

Other things being equal, your economic model should be as simple as possible. There are some fairly well-understood cryptoeconomic primitives that can be used to achieve incentive alignment. There’s no need to reinvent the wheel. If one rule of blockchain is “don’t roll your own crypto,” another should be, “don’t roll your own cryptoeconomic primitives”!

It’s hard to say anything more specific since each project and its incentive structure will be different, but the cryptoeconomic building blocks described here can get you pretty far. If a universal model exists for designing, reasoning about, and testing cryptoeconomic systems, it’s probably [agent-based modeling](https://en.wikipedia.org/wiki/Agent-based_model). This involves listing each class of actor in your system, and the system’s overall constraints, and making sure that the system design—constraints, as well as rewards and punishments—achieve the desired outcome, such that rational actors play “by the rules.” There are powerful tools such as [cadCAD](https://cadcad.org/) that can help with this.


## Conclusion

As with so many of the other topics covered in this series, token economics and engineering are vastly complex and nuanced, and one article cannot possibly do these topics justice. By laying out some of the most difficult and important questions related to blockchain economics, hopefully your curiosity has been piqued and you appreciate both how important and how difficult these questions are. As you can see, there are no simple answers to the these thorny questions and challenges. Designing and governing the micro-economy of a blockchain requires careful thought and planning. While pondering these questions, as a next step, I encourage you look into the work being done by groups such as [Token Engineering](https://tokenengineeringcommunity.github.io/website/), [Block Science](https://block.science/), and the [Commons Stack](https://commonsstack.org/).

Because these fields are so new and best practice is just emerging, there’s a huge opportunity today to make an outsized contribution. The world needs more people who understand the importance, nuance, and challenge of token economics and engineering, and of blockchain economics and cryptoeconomics more generally. At the same time, as with all new fields, these fields build on top of decades of work in related progenitor fields such as game theory, mechanism design, engineering (especially software engineering), public policy design, optimization design, etc. The blockchain space sorely needs input from more experts with a background in these and other diverse fields.

Just as virtualization in computing enabled a Cambrian explosion of innovation in tech and business, the economic virtualization enabled by blockchain will lead to an explosion of new economic models, ideas, and opportunities. Allowing ordinary community members around the world to have a stake in the ownership and economic upside of a project, as well as a voice in its governance, is a truly novel idea and we don’t yet know what it will enable. It has the potential to redefine the relationship among people, communities, and the tools, projects, and platforms that they rely on. It’s essential that we keep innovating, experimenting, and iterating upon these economic models and ideas in order to learn just how powerful they are and just what they can enable.

[^1]: Indeed, I would describe an open, general-purpose, programmable blockchain like Ethereum as, fundamentally, a platform for precisely this sort of experimentation.

[^2]: Some examples of radical economic experiments happening on blockchain today are [CLR matching](https://gitcoin.co/blog/gitcoin-grants-clr-matching/) on Gitcoin and [CLR fund](https://clr.fund/), the burgeoning #DeFi ecosystem on Ethereum, and the experiments [Zcash](https://zips.z.cash/zip-1014) and [Decred](https://www.coindesk.com/decred-is-turning-its-entire-21-million-crypto-treasury-over-to-investors) are running with common goods funding.

[^3]: A convention has arisen whereby “coin” typically refers to something issued by a base-layer network (i.e., layer one), such as BTC, while “token” refers to something issued _on top of_ an existing network (i.e., at layer two), such as ERC-20 tokens on Ethereum. This distinction is unimportant for the purposes of this article, and I will use the word “token” to refer to either interchangeably.

[^4]: For example, a blockchain doesn’t need a defense ministry, an interior ministry, or a foreign ministry. It doesn't need to trade with other sovereign actors. It doesn’t have a sovereign debt rating. Over time, some of these will probably change as blockchains and other sovereign, digital communities increasingly resemble nation states.

[^5]: Uniswap has never had its own token. It raised money by [selling equity](https://www.bamsec.com/filing/177518020000001?cik=1775180) to VCs. Each token pair traded on the platform causes a new token to be minted to represent the liquidity pool associated with that pair, but there is no Uniswap token.

[^6]: It’s also possible for a layer one protocol to anchor in the security and monetary policy of an existing blockchain. As one such example, Blockstack had no token for the first two years of its existence, opting instead for [a protocol based on burning Bitcoin](https://blog.blockstack.org/video-reusing-bitcoins-hashpower-to-launch-the-stacks-blockchain/). It did later issue its own token and is in the process of transitioning to [a new protocol](https://uploads-ssl.webflow.com/5e7b1a27d160ce49af1c24e1/5f1596b12bcc0800f3dcadcd_pox.pdf) based on it, although the network’s security will continue to be anchored in Bitcoin.

[^7]: A good real world analogue is a country that doesn’t have its own currency. While many countries are printing money to finance Covid19 relief, Ecuador, which completely converted its economy to use the US dollar in 2000, is [unable to do so](https://www.economist.com/the-americas/2020/07/04/ecuador-is-in-intensive-care-and-a-straitjacket).

[^8]: Another token model that I find particularly interesting is the [personal token](https://www.forbes.com/sites/colinharper/2020/05/06/people-are-tokenizing-themselves-on-ethereum-why-personal-tokens-raise-red-flags/#4900df7b6680), but I don’t mention it above because it’s not really relevant for blockchain networks and communities. Or is it? 🤔

[^9]: One potential issue with economically incentivizing holders of a governance token is that it makes it more likely that the token will be bought and held by speculators, i.e., those more interested in financial gain than in governance. This is likely one cause of extremely low rates of voter participation in projects like [Maker](https://forum.makerdao.com/t/anon-poll-why-havent-you-voted/3687).

[^10]: The comparison isn’t perfect for a number of reasons. Equity and cryptographic tokens aren’t exactly alike. And blockchains aren’t run the same way as firms (although, arguably, some would be better run if they were!). The main difference is decentralization and permissionlessness. Firms make no pretense of awarding equity in an objectively fair way, and there’s no equivalent of permissionless “mining” in a firm (although, arguably, firms would be better if there were!).

[^11]: Since then, Apple has engaged in an [aggressive share repurchase program](https://s2.q4cdn.com/470004039/files/doc_financials/2019/q4/Apple-Return-of-Capital-and-Net-Cash-Position-Q4-19.pdf?mod=article_inline) to return cash to shareholders, so net shares outstanding has fallen to about 4.5B. For purposes of this simplistic analysis, I only consider the period before these buybacks began.

[^12]: The non zero-sum mindset is referred to by Simon Sinek as an “infinite” as opposed to a “finite” mindset. For much more on this topic, I highly recommend reading [The Infinite Game](https://simonsinek.com/product/the-infinite-game/). I wrote more about how this applies specifically to blockchain projects and communities in [Crypto Has a Purpose Problem](/blockchain/culture/values/2020/08/09/crypto-has-a-purpose-problem.html).

[^13]: It’s important to note that, while Bitcoin has the most stable and conservative monetary policy of any blockchain, even this is not set in stone because it’s enforced at the social layer. In particular, it’s unclear what will happen when issuance falls too low for block rewards alone to cover the cost of mining, i.e., network security. The original plan was for fees to make up for the difference, but it’s unclear at this point whether there will be enough demand. Over the past few months, fees collected per day have averaged 2% to about 10% of the total block reward generated per day. If fees don’t increase enough over the next few years, and the [next few halvings](https://en.bitcoin.it/wiki/Controlled_supply#Projected_Bitcoins_Long_Term), to cover the amount paid out in rewards today (i.e., there isn’t enough demand for Bitcoin block space), then economics dictates that either network security must decrease substantially (i.e., mining would become much cheaper) or issuance needs to increase. Another alternative would be to replace proof of work with an alternative such as proof of stake that has lower operational costs. Any of these changes would be hugely controversial in the Bitcoin community. For a more thorough analysis, see [2020 could be the year Bitcoin’s fee market is put to the test](https://elidourado.com/blog/bitcoin-fee-market/).

[^14]: Ethereum’s monetary policy is complicated by something called the Difficulty Bomb, also referred to as “Ice Age.” Originally intended to force the hand of potentially recalcitrant proof of work miners, who would have to upgrade to Ethereum 2.0 (with proof of stake) or else see the current network grind to a halt, the Difficulty Bomb has already been extended several times as Ethereum 2 has taken much longer to develop than originally planned. It works by gradually increasing difficulty and thus block times: gradually at first, then exponentially, over the course of a few months, until the network becomes unusable. The effects of the bomb are quite visible on [historical block times](https://etherscan.io/chart/blocktime): the “bomb” moniker comes from the way it “ticks” difficulty upward every few days. The economic complexity comes from the fact that issuance falls proportionally as block times increase. Thus, every time the bomb is delayed, Ethereum’s total issuance schedule can be said to increase substantially. In response to this, when the bomb was pushed back, the size of the block reward was also decreased (visible as the inflection points in the [growth in the supply of ether](https://etherscan.io/chart/ethersupplygrowth)). No one really knows how much the network should be paying for security. The [analyses](https://medium.com/@eric.conner/a-case-for-ethereum-block-reward-reduction-in-constantinople-eip-1234-25732431fc77) done at the time of the adjustments, and the [debate preceding them](https://github.com/ethereum/pm/issues/55), are not terribly thorough, relatively unprofessional, and do not typically involve input from economists.

[^15]: I mean this concretely, not in an abstract sense. If you hold common stock in a modern corporation, there are likely several classes of stakeholders who sit above you in the firm’s [capital structure](https://en.wikipedia.org/wiki/Capital_structure). You are actually a fourth- or fifth-class “citizen” of the firm. This means that, in case of financial distress, other investors may walk away with some value but your stock is [very likely worthless](https://www.fool.com/knowledge-center/what-happens-to-stock-prices-after-exiting-bankrup.aspx).

[^16]: All of Blockstack’s SEC filings are [publicly available](https://sec.report/CIK/0001693656), including [annual reports](https://www.sec.gov/Archives/edgar/data/1693656/000119312520124379/d918967dpartii.htm) and information on [token offerings](https://www.sec.gov/Archives/edgar/data/1693656/000110465919039908/a18-15736_1253g2.htm). These filings contain a wealth of information and should be of interest to any company considering taking a similar path.

[^17]: Blockchain projects aren’t the only ones who struggle to distribute ownership. Companies in the United States are forbidden from offering shares to anyone who isn’t an employee or investor. This has been a problem for some sharing economy firms, such as Airbnb, which [petitioned the SEC](https://www.documentcloud.org/documents/4917050-Airbnb-Letter-to-the-SEC-09-21-2018.html) to allow it to give company shares to its hosts. (It hasn't yet.)

[^18]: Even popular protocols such as Bitcoin are not perfectly incentive compatible due to issues such as [selfish mining](https://www.cs.cornell.edu/~ie53/publications/btcProcFC.pdf).

{%- include blockchain-nav-bottom.html -%}

Special thanks to Yael Hoffman for invaluable pre-publication feedback and corrections.
