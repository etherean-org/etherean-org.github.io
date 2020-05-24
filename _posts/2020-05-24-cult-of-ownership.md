---
layout:   post
title:    The Cult of Ownership
subtitle: The advent of immersive digital worlds give us an unprecedented opportunity to rethink the relationship between people and property. Let’s take advantage of it before it’s too late.
image:    /assets/tierra-mallorca-rgJ1J8SDEAY-unsplash.jpg
author:   Lane Rettig
date:     2020-05-24 11:05:00 -0400
categories: [blockchain, economics, experience]
---
![A tiny house and a big set of keys]({{page.image}})

<p style="text-align: center"><sub>Home ownership hasn't worked out so well for most humans. Would that we do better in the digital world to come. Photo by <a href="https://unsplash.com/@tierramallorca?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Tierra Mallorca</a> on Unsplash</sub></p>

# Ownership

We rarely, if ever, pause to think about concepts as abstract as ownership. Indeed, the idea of ownership is woven into the very fabric of modern society thanks to capitalism. When you actually reflect on it, however, you realize that ownership is a pretty strange notion.

It’s one that I’ve been thinking about a lot recently. Ownership makes intuitive sense to me in the physical, offline world. If there’s one bowl of single serving pea soup between us, then either you have it, and can enjoy it, or else I do, and can—but not both. Of course it’s even more germane for truly scarce commodities like land: we can always grow more peas and make more pea soup, but we cannot really grow more land (reclaimed land aside).

In the digital realm, Bitcoin also makes intuitive sense. There is clearly some value in the idea of digital gold, even if its scarcity is artificial and socially enforced. Why? Because currency is useful, and in order for currency to have value, it has to be scarce. Bitcoin is pretty close to a platonic actualization of decentralized, digital currency.

What _doesn’t_ make intuitive sense to me is ownership of other types of digital assets, in particular things like digital art and “land” in virtual worlds. In order to understand why I feel this way, I’ve been pondering the basic question: What does it really mean to own something?

We’re used to the way ownership works in the pre-blockchain world. To own a piece of land, for instance, means to have a publicly recognized, verifiable title to it, entitling its owner to use, profit from, or dispose of it however they please, within legal bounds.

On the surface, blockchain-based ownership actually isn’t that different. What it literally means to own some bitcoin is to possess a few bytes of data, a cryptographic “key” that can be used to “unlock” a transaction stored in the Bitcoin distributed ledger.[^1] This is not unlike holding a title to land, with the caveat that a bitcoin private key is a [bearer instrument](https://en.wikipedia.org/wiki/Bearer_instrument) in the sense that he who holds the key holds the bitcoin that it controls. In the case of Bitcoin, possession really is 99% of the law.[^2]

In both cases, ownership is publicly verifiable and enforceable. Indeed, without these properties, the whole idea of ownership is pretty meaningless. The main difference is that enforcement of the first is primarily legal, whereas for blockchain-based assets like bitcoin, it’s primarily cryptographic and computational in nature.

# Ownership is social

In fact, ownership of both land and bitcoin is a socially enforced construct.

Land, of course, has intrinsic value: it’s practically useful for renting, growing, building, or storing things. It’s therefore tempting to think that the value of land derives entirely from its intrinsic value, but in fact, its value is highly social. This should be evident when you consider two otherwise identical plots of land in two different social settings: one in the middle of a highly desirable city, the other thousands of miles away from the nearest town. Moreover, to own land is to rely on a public, verifiable land registry, title to the land, and various institutions and mechanisms of the state to enforce that ownership, such as evicting a delinquent tenant or calling the police if someone trespasses.[^3]

Ownership of bitcoin, too, may not seem inherently social at first glance due to the cryptographic nature of its enforceability. However, if you peer a little deeper, the social layer becomes visible. The private key and the ledger entry corresponding to your bitcoin holdings have value only because other people believe they have value. In other words, just like fiat currency, bitcoin has no intrinsic value. Another reason bitcoin has value is the fact that a group of people has agreed to run software that conforms to the Bitcoin protocol, not to debase bitcoin by issuing too much of it, etc..

# Presentation

But there’s an important way in which these two types of asset differ. Tangible artifacts such as land need no _presentation layer._ Digital assets, on the other hand, are meaningless and, indeed, invisible without a presentation layer. You can only claim, and see, and spend the bitcoin you own because you have a wallet application that talks to the Bitcoin network on your behalf, interpreting things like cryptographic keys and presenting them to you as legible things like transactions and balances.

The idea of a presentation layer is a very old concept in the digital world. Think of reading your email on your laptop versus reading it on your phone. You’re using two very different applications to access and interact with the same data: this is the presentation layer. The possibilities for how to present even the most mundane data creatively are endless.[^4]

# Fungible and nonfungible assets

The concepts of ownership and presentation get very interesting in the world of digital assets. The first and most common form of digital asset is the fungible asset, which includes bitcoin: like a dollar, every bitcoin is the same as every other bitcoin, so they are totally [fungible](https://en.wikipedia.org/wiki/Fungibility).[^5]

By contrast, an asset like land, or a piece of art, is not fungible. Each one is unique and special. Nonfungible assets can be traded, but the correspondence is never precisely one to one: even two plots of land of identical size that are near each other will almost certainly have characteristics which mean their values will differ!

While the concept of a nonfungible asset makes intuitive sense in the tangible world, in the digital realm it’s a bit murkier. It’s easy to value bitcoin because of its fungibility. What makes an asset like land or art nonfungible is that it has a lot more variables. Land, for instance, is valued not only on the basis of its area, but also its shape, location, drainage, elevation, history, improvement/development status, neighbors, etc..[^6]

A digital nonfungible asset, however, has none of these intrinsic properties. Like bitcoin, under the hood it’s really just a series of bytes on a ledger. Everything else—including all of the properties that actually matter—lives in the presentation layer, and is therefore subjective.

On the one hand, this disconnect between the ownership layer and the presentation layer is wonderful because it allows for a lot of creativity in how digital assets are composed and presented. Witness one of the oldest, and most well-known, nonfungible digital assets: [CryptoKitties](https://www.cryptokitties.co/). One could build a different presentation layer that presents the same underlying [genetic data](https://guide.cryptokitties.co/guide/cat-features/genes) that gives a kitty its fur color and eye shape as, say, a [robot](https://etherbots.io/), or a pair of [shoes](https://thenextweb.com/hardfork/2019/12/10/nike-blockchain-sneakers-cryptokick-patent/). One can also compose multiple nonfungible digital assets: giving a crypto kitty [a unique hat](https://kittyhats.co/#/), for instance.

On the other hand, however, there’s something odd and a little troubling about the way that all of the variables and properties that matter in a nonfungible asset are open for interpretation in the presentation layer. This calls into question even very basic concepts such as value and ownership. Do you really “own” a CryptoKitty in any meaningful sense if under the hood what you possess is really a series of bytes that have no intrinsic value and are meaningless without interpretation? What about a piece of virtual art—say, a digital image—when, in practice, you really only control an arbitrary series of bytes on some ledger that are at best a hash of the contents of the art, and at worst are totally arbitrary? Given that the art is digital, it’s trivial to copy, and many people may choose to enjoy or even display it simultaneously, “ownership” or no.

Assets can have value for intrinsic or extrinsic reasons. Intrinsic reasons tend to be less subjective and to require less interpretation, whereas extrinsic reasons tend to be highly subjective and to rely on a socially-constructed interpretation. You can acquire an oil painting, hang it in your house, and admire it. No one else in the world can possess and admire precisely the same piece of art in the same way at the same time. This uniqueness is an intrinsic source of value for traditional forms of art. Digital, nonfungible assets do not have this same property. Their value is almost entirely extrinsic and subjective. 

To be clear, I am not suggesting that digital art, land, collectibles, or nonfungible assets in general have no value. My point is that, to the extent that we as a society collectively choose to attach value to them, that value will necessarily be fundamentally different in nature from the value of traditional assets such as land and art. We’ve barely begun the process of understanding these assets and the ways in which they may possess value in the eyes of society.

As fascinating as digital assets are, there’s an aspect of the way they’re being marketed today that worries me.

# Reimagining

What attracted me to blockchain was the once-in-a-century opportunity that it presents to reimagine so many aspects of our society: how we communicate and collaborate, how we relate to one another, how we form institutions and bonds of trust, etc.. In the same way, blockchain presents us with an equally rare opportunity to totally reimagine basic social concepts like art, community—and, yes, ownership. It is of course natural that we should start by attempting to import already-familiar ideas and analogues. Some of them may even stick! Decades later, we still have a “recycle bin” sitting on our “desktop”: great, useful examples of [skeuomorphism](https://en.wikipedia.org/wiki/Skeuomorph). Some less useful analogues, however, should be jettisoned while we still have the chance.

Rather than attempting to recreate the world of scarcity, of “this is mine, not yours,” why blithely bring these offline constraints with us into the digital realm? The entire point of the digital world is that, free from the constraints of the physical world, _digital assets need only be precisely as scarce as we want them to be!_ Digital assets need not be [rivalrous nor exclusive](https://livingeconomics.org/article.asp?docId=239): we can both enjoy a digital bowl of pea soup, and my enjoyment doesn’t detract one whit from yours.

As we collectively undergo a once-in-humanity phase shift from an offline, agricultural and industrial world, a world of scarcity and need, to a more digital, online world based on data and information, we have a unique opportunity to rethink fundamental concepts such as wealth and ownership. We have a rare opportunity to transition from a scarcity mindset into one of abundance. The next hundred years of human society will be less about which scarce assets we own and exclusively control, and more about which networks we are a part of—and, thus, which connections and information we have access to.

What sort of novel experiences could we conceive of if we relax the constraints of the offline, tangible world? It’s probably too soon to tell, since we’re still quite early in the development of virtual worlds and experiences, but the platforms that exist today do offer a glimpse. One good example is the avatar: platforms like [Decentraland](https://decentraland.org/), [Mozilla Hubs](https://hubs.mozilla.com/#/), [AltspaceVR](https://altvr.com/), and [VRchat](https://vrchat.com/), not to mention [Fortnite](https://www.epicgames.com/fortnite/en-US/home), offer users a fantastic array of ways to express themselves in the form—literally—of avatars of all shapes, sizes, colors, species, and [agility](https://www.youtube.com/watch?v=9wMI5R4beE0). Some platforms do allow users to buy or pay to upgrade their avatar, and maybe that’s okay, but I suspect the dominant model will let the user express themselves creatively at no or very low cost.

![Avatars having a chat in VR](/assets/avatars.jpg)

<p style="text-align: center"><sub>Just an ordinary day in the crypto VR meetup scene: lower fidelity than an in-person event, perhaps, but lots more latitude for creative expression. A panel chat, part of Consensus Distributed, held in VRChat.</sub></p>

# It’s about the experience, dummy

The point is that we should be innovating on the _experience,_ and that means innovating on the presentation layer, not on the ownership of arbitrary blobs of cryptographic data. The average person cares a lot more about experience and self-expression than they do about some abstract notion of self-sovereign ownership. There’s a reason that well-designed, centralized games like Fortnite have [hundreds of millions](https://en.wikipedia.org/wiki/List_of_video_games_by_monthly_active_player_count) of active players while the most popular dapps have many orders of magnitude less.

Ownership is not, in and of itself, an experience. If you ask me it’s not something that 99% of humanity cares about or is looking for in the digital world. As one example, young people everywhere are frustrated by high levels of debt, and property that feels totally out of reach (a situation that’s quickly [getting worse](https://www.nytimes.com/2020/05/19/business/economy/coronavirus-young-old.html)). I suspect they’d sooner keep living in the offline world than subscribe to a digital world that _also_ forever relegates them to second-tier, rentier status.

There is probably some value in moving existing traditional assets, such as stocks, bonds, and derivatives, onto blockchains. And the idea of fractionalizing ownership of traditional assets such as art or real estate is genuinely interesting. Indeed, work on all of this is proceeding apace in the #DeFi space.

But let’s not seek to commoditize _all_ the things. Once we figure out the _experience,_ there will be ample time to figure out the economics. By leading with economics, the same old economics we’ve been stuck with for generations, we’ll never win the hearts and minds of the 99% of people who feel less than enfranchised by the current system.

My greatest fear is that, in conceiving of and building a new, digital world for humans, we manage only to recreate and indeed to exacerbate existing socioeconomic divisions that have sown strife and discord in the offline world for millennia—in other words, a Black Mirror-esque dystopia.

The types of people that have been the most active thus far in conceiving of, and building, digital worlds, and blockchains, have by and large been beneficiaries of the current system. It’s therefore unsurprising that we should have recreated aspects of the system, such as scarce assets and old-fashioned property rights, on chain.

But it’s time we recognize this opportunity for what it is—an epoch-making opportunity to rethink every human social system—and boldly envision and build a better future together. In particular let’s be careful not to enshrine ownership and property rights as primal, at the expense of intangible but essential things like experience, identity, and self-expression.

[Special thanks to James Prestwich for invaluable pre-publication input.]

[^1]: This, of course, assumes you hold the keys and custody the bitcoin yourself, which you really should do. [Not your keys, not your coins](https://cointelegraph.com/news/antonopoulos-your-keys-your-bitcoin-not-your-keys-not-your-bitcoin). If you don’t, holding bitcoin is really not very different from holding fiat money in an [ordinary bank account](https://www.applescotch.com/finance/cryptocurrency/sovereignty/2020/04/19/scalpels-and-sledgehammers.html).

[^2]: Whether or not the legal system of this or that jurisdiction might provide some protection if this key is stolen is a thorny question and will differ from place to place and case to case. This is what makes up the last 1%.

[^3]: This works well enough where property rights are clearly delineated, and enforced, and where one can rely on the rule of law. It doesn’t work so well where these things are not the case. Witness jurisdictions where people hold land [without explicit title](https://www.thenewhumanitarian.org/report/97654/analysis-cambodian-land-rights-focus), or where [all land is owned by the state](https://www.nytimes.com/2016/06/01/business/international/in-china-homeowners-find-themselves-in-a-land-of-doubt.html) and can be requisitioned for state purposes at any time. The concept of ownership is much fuzzier in such situations.

[^4]: One of my favorite examples of creative presentation of everyday data is the [Foursquare Time Machine](https://www.youtube.com/watch?v=rFrcN5EE18Y).

[^5]: This is an oversimplification and isn’t completely true in practice for digital assets like bitcoin—read more about crypto’s “[fungibility problem](https://bravenewcoin.com/insights/cryptos-fungibility-problem).” Fungibility and privacy go hand in hand, and true fungibility is a goal of privacy-preserving platforms like Zcash.

[^6]: To be fair, in addition to these intrinsic properties, land does have a set of extrinsic properties that are the product of a social presentation layer, so to speak: things like zoning, taxation, air rights, etc.. Here, the presentation layer is the set of formal and informal laws and norms that apply to the land’s ownership, use, and disposition.
