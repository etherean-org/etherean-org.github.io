---
layout:   post
title:    "Autonocrats and Anthropocrats"
subtitle: "The most important political debate of our generation has nothing to do with Democrats or Republicans. It’s just heating up."
image:    /assets/andy-kelly-0E_vhMVqL9g-unsplash.jpg
author:   Lane Rettig
date:     2020-03-04 11:00:00 -0500
categories: [blockchain, community, governance]
---

![Image of young girl and robot](/assets/andy-kelly-0E_vhMVqL9g-unsplash.jpg)

<p style="text-align: center"><sub>May our children grow up in a world full of peaceful robots and algorithms. Photo by <a href="https://unsplash.com/@askkell?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Andy Kelly</a> on <a href="https://unsplash.com/s/photos/child-and-robot?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>.</sub></p>


> “We shape our technologies at the moment of conception, but from that point forward they shape us… While this axiom may be true for technologies from the pencil to the birth control pill, AIs add another twist: after we launch them, they not only shape us but they also begin to shape themselves... The long-term danger is not that we will lose our jobs to robots… the real threat is that we’ll lose our humanity to the value system we embed in our robots, and that they in turn impose on us." - Douglas Rushkoff, _Team Human_ (ch. 55)


## Autonomous software

A large part of the appeal of blockchain platforms such as Bitcoin and Ethereum comes from the fact that the code underlying the platforms themselves, as well as the applications deployed on them, are autonomous, in the sense that they are partially or fully beyond the control of one person (or any one group of people). Applications on these blockchain platforms are “unstoppable” by design, and are able to function without ongoing human intervention. Once deployed, they are governed by their own code, rather than by people. This allows them to make reliable [commitments](https://cdixon.org/2020/01/26/computers-that-can-make-commitments).

Blockchain developers don’t often talk directly about autonomous software, preferring instead to discuss properties such as permissionlessness, trustlessness, and censorship resistance. However, all of these properties have one thing in common: it’s the autonomous nature of the underlying software that enables them.

Unlike the corporations, governments, and other legacy institutions that, voluntarily or involuntarily, we interact and transact with on a daily basis, blockchains and other autonomous software agents by design limit the scope of human judgement and bias. They limit the ability of human actors to decide who does and does not have access, or what content is permissible and what should be censored.

In an age when enormous financial and technology companies are to a great extent unaccountable to their users or to society at large, and are increasingly engaging in arbitrary censorship and [deplatforming](https://en.wikipedia.org/wiki/Deplatforming), there is clear value in systems that treat all users equally and fairly. To a blockchain—indeed, to any computer algorithm—you are no more and no less than the data that represent you.

Just how desirable a property this is, and whether it’s a bug or a feature, is a contentious question, and is the focus of this article.


### Software eating software

Autonomous software has permeated more aspects of everyday life than you are probably aware, and the trend will of course only continue. Marc Andreesen famously said in 2011 that “software is eating the world,” but the trend today is that software is beginning to [eat other software](https://www.technologyreview.com/s/607831/nvidia-ceo-software-is-eating-the-world-but-ai-is-going-to-eat-software/). And this is especially true for autonomous software such as AI, machine learning algorithms, and blockchain, which have begun to replace their earlier, less sophisticated forebears.

We’ve relied on software to help make life-or-death decisions for quite some time now. AI [helps doctors decide on treatments](https://www.wired.com/2014/06/ai-healthcare/). Software makes and executes billions of trading decisions every day, which in some cases can result in [increased volatility and unexplainable phenomena](https://en.wikipedia.org/wiki/2010_flash_crash). Demonstrating the [prescience of science fiction](https://en.wikipedia.org/wiki/The_Minority_Report), police use it to [help forecast crimes](https://www.nytimes.com/2015/09/25/us/police-program-aims-to-pinpoint-those-most-likely-to-commit-crimes.html?_r=0). Autonomous systems are playing an increasing, and troubling, role [in warfare](https://www.economist.com/briefing/2019/01/19/autonomous-weapons-and-the-new-laws-of-war), possibly auguring a future where we give such systems even greater autonomy to make life and death decisions without human oversight.

In the context of blockchain, autonomous software has found a niche in smart contracts, self-executing code snippets that bear some resemblance to their offline counterparts. They partially or, in some cases, fully obviate the need for human involvement or judgement once deployed to a blockchain like Ethereum. In order to understand the pros and cons of this technology, we first need to understand the value proposition of blockchain in the first place.


<a name="social"/>
## Blockchains and social scalability


### Scaling trust

In essence, a blockchain is an engine for scaling trust. According to Nick Szabo, a computer scientist and legal scholar who laid the intellectual groundwork for much of the field of cryptocurrency and smart contracts, the way to do that is by _minimizing trust._ This means minimizing the cognitive burden upon the participants in any given transaction by reducing the number of systems they need to understand and trust in order to transact. Szabo calls this concept [social scalability](http://unenumerated.blogspot.com/2017/02/money-blockchains-and-social-scalability.html).


If Alice in Adelaide and Bob in Berlin want to exchange funds with one another using the legacy financial system, there are a lot of moving parts that both need to understand and put faith in. This includes the respective currencies and financial systems of their two territories (the Euro and the Australian Dollar), the private companies involved in the funds transfer (e.g., PayPal, Western Union), the laws governing movement of funds, associated taxes, etc. in both of their jurisdictions, _as well as_ in the jurisdictions of these third party companies. (This is a partial list; I leave it as an exercise to the reader to come up with more!) This “institutional stack” has enabled the dynamism of modern business, but it requires putting quite a bit of trust in a lot of places.

To list just a few of the questions inevitably on Alice’s mind as party to the transaction: How does Alice know with certainty that the funds she received from Bob are final and that the transaction is irreversible? How and when does she feel comfortable sending him a product or service in exchange for those funds? How does she know that one of the many parties to the transaction won’t unilaterally decide to censor or reverse the transaction?

This question may seem relatively unimportant and low-stakes, especially for a low-value transaction, and to those of us with access to a reliable, modern banking system. In practice, however, many transactions [simply don’t happen](https://twitter.com/brian_armstrong/status/1225554351466467330?s=20) today because of these costs and inconveniences, and others are much more expensive than they need to be. As one example, [5-8% of retailer revenue is lost to credit card chargebacks](https://midigator.com/the-year-in-chargebacks-report-2019/) alone. This raises prices for credit card transactions and means that low-margin sales aren’t even possible in the first place.


### Role of blockchain

Trustless systems have an important role to play in reducing these transaction costs. If, instead of using the legacy financial system to transact, Alice and Bob have access to Bitcoin, there’s far less that each of them needs to understand and trust in order to transact. They both need reliable access to the Internet and electricity, of course. They need Bitcoin wallet software and at least one of them needs to have some bitcoin to send the other. They need to trust the software and the Bitcoin network and protocol (all of which is open source). This is still much cheaper, easier, and faster than, say, opening bank accounts and trusting multiple private companies, subject to multiple sets of regulation, to execute their transaction as intended. For one thing, in Bitcoin there is by design no such thing as a chargeback.

Building on this simple example, a smart contract platform such as Ethereum allows far more complex transactions to be structured in the same “trust-minimized” fashion. The only additional thing both parties need is the ability to understand the computer code underlying the smart contract—or, failing that, they can hire someone who does. They can also reuse the same code for many transactions. This is much cheaper than hiring lawyers and negotiating a new paper contract for every transaction!

The technology is still immature and is nowhere near ready to replace more complex types of contracts and transactions such as those that underpin corporations, but what’s abundantly clear today is that the ability to transact in such a cheap, reliable, trust-minimized fashion will have an enormous impact. Not just on business, but on society as a whole. One need only look to the transformative power of previous social scalability technologies—such as fungible currency, common language, the telephone, or indeed the very contract law that smart contracts might augment or partially replace—and the degree to which each has reduced transaction costs.

Despite the fact that the technology is only a few years old, smart contracts already secure billions of dollars’ worth of value. This technology has enabled exciting applications but it is not without risks. One small bug in such code, as we’ve seen [time](https://en.wikipedia.org/wiki/The_DAO_(organization)) and [time](http://hackingdistributed.com/2017/07/22/deep-dive-parity-bug/) [again](https://www.parity.io/security-alert-2/), can cause this value to evaporate or be stolen faster than you can say “Solidity.” There have already been several high profile failures, leading to the loss or theft of hundreds of millions of dollars’ worth of digital assets.

In the face of these challenges, and of the promise and risks of autonomous software more generally, the blockchain community is divided into two camps.


## Two camps


> “Where there is no law, there is no freedom.” - John Locke, _Two Treatises on Government_

While most of the world’s political attention is riveted by the American presidential election and by the question of Democrats versus Republicans, big government vs. small government, liberals vs. conservatives, and populist demagogues vs. elitist technocrats, an entirely new political debate is brewing in Silicon Valley and in academic circles. It’s not on the radar of most political pundits yet, and most are familiar with the question only in the broadest strokes; the clickbait sci-fi version, rather than the the one based in reality: “AI will destroy all jobs,” or “attack of the AI.”

It’s the question not of what type of human ruler we want to be ruled by, but rather the more fundamental question of whether, and to what extent, we want to be ruled by humans in the first place. As autonomous software matures and gains more abilities—blockchain, for instance, has for the first time allowed software to autonomously hold and control the movement of value—we can hand increasingly broad swathes of responsibility to software, in theory increasing social scalability by freeing limited human cognitive capacity to focus on higher value tasks.

While lots of [people are talking about human leaders](https://www.economist.com/graphic-detail/2019/12/21/americas-president-dominated-readers-attention-in-2019), what almost no one is talking about is the fact that this autonomous technology exists today, [it’s here to stay](https://cointelegraph.com/news/andreas-antonopoulos-blockchain-tech-cannot-be-uninvented-or-stopped), and it’s time we had an informed debate about the opportunities and threats it presents, and how to respond to them.

On the face of it, the question may seem moot since, after all, how much agency do algorithms have in the first place? They’re responsible for sorting our Twitter feed, recommending videos to watch, and, someday maybe, preparing our [morning coffee](https://youtu.be/J4dyrZnV-98) and driving us to work. We’re not exactly on the verge of handing our criminal justice system over to AIs, let alone electing an AI president (as much of an improvement as that might be over the status quo).

Nevertheless, as technology based on autonomous algorithms, including blockchain and smart contracts, play a bigger and bigger political, economic, and social role in the coming decades, this question will become increasingly relevant and critical. The time to have an informed debate is now, while this technology is still in the earliest phases of development and deployment.

Let’s explore both sides of the debate.


### Anthropocrats

The first camp, which I call the _anthropocrats,_ are those who desire and expect humans to remain firmly at the helm of government, society, the economy, and our other collective institutions for the foreseeable future. Anthropocrats feel that our shared humanity and human systems are too special and too fragile to attempt to capture them in unthinking, unfeeling algorithms. They feel that to hand too much agency to such algorithms is hubristic, dangerous, and certain to backfire.

To offer a slightly more technical definition, anthropocrats _desire to minimize the degree of agency put into the hands of AIs, machine learning algorithms, blockchains, and other autonomous software._ This is to ensure that, for the important things at least, humans remain in the loop and make the final call. This camp believes that, fallible as we may be, and toxic as our politics may sometimes become, _rule by other humans is always, necessarily preferable to rule by algorithm._ The logic supporting such a stance should be self-evident: feel free to refresh your memory by watching the [Terminator series](https://en.wikipedia.org/wiki/Skynet_(Terminator)), the [Matrix series](https://en.wikipedia.org/wiki/The_Matrix_(franchise)#Setting), [Black Mirror](https://en.wikipedia.org/wiki/Hated_in_the_Nation), or reviewing any of a hundred other dystopian cyberpunk novels and films depicting [AI takeover](https://en.wikipedia.org/wiki/AI_takeover). These fears are at least [a hundred years old](https://en.wikipedia.org/wiki/R.U.R.), and maybe much older still: [Frankenstein](https://en.wikipedia.org/wiki/Frankenstein) was published in 1818, and stories of the [Golem](https://en.wikipedia.org/wiki/Golem#Hubris_theme) have existed since biblical times.

Anthropocrats may be proponents of blockchain technology, including distributed ledgers and smart contracts, feeling that it has great potential to automate some social functions, improve institutions, and scale trust. What distinguishes them from other proponents is their insistence that blockchain technology and the communities that build and support it should engage with existing social systems and institutions and should seek to design mechanisms with _people_ at the center. They feel that we should not rely on the allure of autonomy and immutability, which, in a vacuum and without connection to existing human systems, cannot solve anything on its own. Rather, they expect such systems to augment processes that still incorporate human oversight.


### Autonocrats

The opposite camp, which I’ve dubbed _autonocrats,_ takes a different stance. Autonocrats feel that we should _maximize the degree of agency that we vest in autonomous systems and algorithms._ Since agency is zero sum, this by definition means minimizing the degree of agency in the hands of humans, which in practice means minimizing or, in the extreme case, eliminating human governance entirely.

In the context of blockchain, autonocrats feel strongly that the only way that blockchain or smart contracts can fulfill their potential value to humanity is to remain as simple, neutral, and immutable as possible. This means little to no governance, no reversions of transactions, and no recourse. Autonocrats believe that adding governance would [alienate certain stakeholders](https://twitter.com/NickSzabo4/status/1068960876416258049?s=20) and cause blockchain to become far less trustworthy and less useful. As if that’s not already bad enough, explicit governance also opens the governors up to possible [legal liability](https://ethereum-magicians.org/t/when-does-contentious-review-happen-in-core-eips/2974/19?u=lrettig) without the usual protections afforded to both political and corporate leaders, and in theory makes the blockchain itself something that you can negotiate with, and coerce.

The perspective of the autonocrats can be summed up in a single principle, called Szabo’s Law, which Ethereum researcher Vlad Zamfir lays out in his diatribe [Against Szabo’s Law, For A New Crypto Legal System](https://medium.com/cryptolawreview/against-szabos-law-for-a-new-crypto-legal-system-d00d0f3d3827). Zamfir, who named the principle in honor of Nick Szabo (although the articulation is Zamfir’s), defines Szabo’s Law as:


> Do not implement changes to the blockchain protocol unless the changes are required for the purpose of technical maintenance.

Because this camp is newer, smaller, less well-understood, and its arguments are somewhat less intuitive, it’s worth taking some time to explore the position in greater detail.


### A note on agency

The above definitions both use the word “agency” several times. Since this idea is a bit nuanced and difficult to understand, I’ll try to define it here. To me, agency simply means the ability of an actor to exert its will and effect some change on the world.

An autonomous actor has no agency because it has no will. However, a human actor can _delegate_ its agency to an autonomous actor, temporarily or permanently. To give the simplest possible example, if I point a gun at someone and then pull the trigger, I’ve effectively, permanently, and completely delegated my agency (with respect to this particular act) to the bullet now in motion, since I cannot stop it. If I instead deploy a smart contract that incentivizes (i.e., [incites](https://en.wikipedia.org/wiki/Incitement)) a crime to be committed, I have delegated my agency (with respect to this crime) to the smart contract and to the blockchain. In both cases, the ultimate culpability for the crime still rests with me, the _first mover_ actor: the autonomous nature of the _eventual actor_ does not absolve me of responsibility.

Note that _culpability_ is not the same thing as _accountability._ As discussed below, the _first mover_ actor, however culpable, may choose to act through an autonomous agent in such a way that their accountability is limited, making it much harder to identify them and bring them to justice.

This is a fascinating topic in its own right, and I defer to philosophers and social scientists for more informed discussion and analysis.


## The appeal of “rule by algorithm”


> “...to the end that it may be a government of laws and not of men.” - Massachusetts Constitution of 1780, I, XXX, Declaration of Rights ([John Adams](https://www.bartleby.com/73/991.html))


### Fairness


> “Humans still like to compete. We don’t have to be absolutely generous all the time. There’s a place for aggression and entrepreneurialism, winners and losers. It just has to happen, like sports, with rules and transparency.” - Douglas Rushkoff, _Team Human_ (ch. 96)

The first argument made by autonocrats in favor of rule by algorithms is that algorithms are by design fairer than their human counterparts. To an algorithm, each case is absolutely identical: just some input data that’s subject to precisely the same logic as all other inputs. Algorithms don’t care about race, creed, origin, gender, height, looks, wealth, fame, or any of the other factors that bias human judgement (except insofar as those same factors are encapsulated in the algorithm itself, more on which in a moment). You cannot coerce, threaten, or bargain with an algorithm. Perhaps even more importantly, they never get tired, hungry, or frustrated, and are no more or less likely to be [lenient early in the day or just after a lunch break](https://www.pnas.org/content/108/17/6889.short). In this respect, at least, it’s tempting to think of an algorithm as the perfect judge (and, perhaps, jury and executioner as well).


> “*Anonymous* telecommunications has the potential to be the greatest equalizer in history. Bringing this power to as many as possible will forever change the discourse of power in this country (and the world).” - Matthew J Miszewski, [ACT NOW!](http://cypherpunks.venona.com/archive/1993/03/msg00232.html), sent to [cypherpunks@toad.com](mailto:cypherpunks@toad.com), 1993-03-06

It is difficult to overestimate the degree to which this property of autonomous algorithms, which is manifest today in the form of smart contracts, appeals to many vanguards of blockchain technology. We must always remember that Bitcoin and the technologies that followed it emerged in a particular place and time, in response to a particular set of social, political, and economic circumstances. Bitcoin was created in response to the perception of unfairness in the global economy due to things like bank bailouts and mismanagement of monetary policy by central banks.

Satoshi Nakamoto “wanted to create a currency that was impervious to unpredictable monetary policies as well as to the predations of bankers and politicians,” [wrote The New Yorker](https://www.newyorker.com/magazine/2011/10/10/the-crypto-currency) in 2011. Its design was [heavily influenced](https://www.nytimes.com/2013/11/27/opinion/much-ado-about-bitcoin.html) by the cypherpunk and crypto-anarchist movements, which emphasize libertarianism and a level playing field. In the view of these movements, big government tends to favor an entrenched elite. The solution in their view is to keep government small, and the laws it enforces should be few in number, simple to understand, and accessible to average citizens. There should be one set of rules, known to all, and everyone should play by those selfsame rules. No exceptions, no preference, no privilege.

These values are manifest in blockchain technology like Bitcoin, in properties such as permissionlessness, censorship resistance, and trustlessness. Permissionlessness means that there is no gatekeeper—no one with the authority to admit or deny access to the network. I don’t need anyone’s permission to transact on the network, deploy an application, etc. Censorship resistance means that, by the same token, no one has the power, explicit or implicit, to block my transactions or data from propagating throughout the network. Trustlessness means that, when transacting on the network, I need not fear that some arbitrary, complex, biased social process may interfere with my transaction.

Bitcoin, and cryptocurrency and blockchain more generally, were created partly as a response to a system perceived to be broken beyond repair, one that puts the interests of certain groups—well-connected, wealthy, influential insiders—above the interests of the public at large. For many visionaries designing and building blockchain technology, the allure of a fairer system, and a more level playing field, is great indeed. Hence the allure of autonomous algorithms, which underpin this fairness.

For more on this topic, see [Credible Neutrality As A Guiding Principle](https://nakamoto.com/credible-neutrality/).


### Efficiency

One of the sublest but most important aspects of smart contracts is that they have the potential to drastically lower transaction costs for all parties. In order to be party to a traditional legal agreement, all parties need legal representation, or at least to have a strong grasp of the underlying legal systems and principles at play. By contrast, as described in [Blockchains and social scalability](#social) above, the only burden on participants of a smart contract transaction is that they have access to electricity, the Internet, and the blockchain, and that they understand the computer code that underlies the contract (or can rely on someone who does).

Furthermore, the code underlying a smart contract can be forked, modified, and redeployed at near-zero cost. Good luck doing that with a legal contract! In other words, blockchain and smart contracts disintermediate lawyers and the legal profession in general, at least for certain types of transactions.

If this sounds a lot like how the printing press disintermediated the power of the church and the monarchy over knowledge, and how the Internet further reduced the cost of publishing and disintermediated the power of publishers, it should! Bitcoin and smart contract platforms like Ethereum reduce the state’s monopoly on money and law.

This property of autonomous algorithms is highly appealing to both cypherpunks and entrepreneurs, although for different reasons. Cypherpunks like the idea of not being forced to rely upon the legal regime of an arbitrary jurisdiction (or set of jurisdictions), while entrepreneurs should delight in how significantly cheaper transaction costs make some new types of innovations viable for the first time, such as micro-payments or costless international payments.


### Robustness

A third common argument made in support of autonomous algorithms is their robustness: once deployed they can, in theory, function with no ongoing intervention on the part of their creators. Simple automated weapons like landmines and [loitering munitions](https://en.wikipedia.org/wiki/Loitering_munition) have existed for decades. Unmanned combat drones can stay aloft for days and can travel thousands of kilometers. We’re not quite at the point where “killer robots” make the decision to utilize lethal force in a fully autonomous fashion, but [that day is probably not far away](https://www.vox.com/2019/6/21/18691459/killer-robots-lethal-autonomous-weapons-ai-war).

In the context of blockchain, smart contracts deployed on immutable ledgers such as Ethereum live forever, at least in theory. As long as there is some set of computers running unmodified blockchain software, and as long as the asset underlying the blockchain still has some market value (so that economic guarantees are maintained), a smart contract may remain viable indefinitely, lying dormant and waiting patiently for more incoming transactions_—_even if long abandoned by its creator.

This property of autonomous algorithms makes them especially robust against legal threats. There is no authority on earth that has jurisdiction over a global, decentralized network such as Bitcoin or Ethereum. Legal action against any single actor, or against any group of actors, or even an outright ban in one or more jurisdiction, cannot and will not cause the network to stop running, nor can it prevent the execution of even one lowly smart contract. This is in sharp contrast to traditional, centralized organizations such as corporations, which are subject to legal and economic sanctions, with public actors behind them that are vulnerable to state-sanctioned violence.

Robustness also enables censorship resistance, as in, “The Bitcoin network and protocol are so robust that not even a state actor can censor Bitcoin transactions. It has sovereign-grade censorship resistance.” The idea of a group of individuals, an organization, perhaps even a digitally-native society acting in a self-sovereign capacity, immune to the sovereignty of any particular existing nation state or jurisdiction, protected from physical coercion, has been a holy grail for technologists since at least the early days of the web (as articulated by visionaries such as [John Perry Barlow](https://vimeo.com/111576518)). Fully realizing such a society has been the motivating force for the development of much blockchain technology, and we would do well to remember that.


## New technology, old fears

![Luddites](/assets/luddites-2800x1440.jpg)

<p style="text-align: center"><sub>It's not technology we're afraid of, it's the power it grants to the people behind it. <a href="https://www.historic-uk.com/HistoryUK/HistoryofBritain/The-Luddites/">Source</a></sub></p>


> “Code enforces rules without bias (unless, of course, you happen to be the coder). It’s a blockchain reality, where machines execute the letter of the law without any sense of the spirit.” - Douglas Rushkoff, _Team Human_ (ch. 71)

While arguments for fairness, efficiency, and robustness are not without merit, there are equally strong counterarguments that emphasize the risks and weaknesses of autonomous algorithms. Do the risks outweigh the potential benefits?

To be clear, we’re far from the first group of people to consider this question. In a broader context, techno-utopianism—the belief that technology holds the solutions to some of humanity’s hardest problems—and the concomitant backlash against technology have both existed for [hundreds of years](https://en.wikipedia.org/wiki/Luddite).

Previous bouts of anti-tech hysteria tended to be fueled by exaggerated (but nevertheless understandable) fears of technology giving enormous power to one group of people at the expense of another, e.g., factory owners replacing human workers with more efficient machines. The technology in question doesn’t have to be especially high tech to raise suspicions: Facebook gives Mark Zuckerburg unparalleled power to affect the tone of public discourse and sway the course of elections in the world’s biggest democracies. However, bleeding-edge technologies including blockchain, self-driving cars, and autonomous drones are here today and are increasingly viable. They could lead to unprecedented power imbalances, lending urgency to these important questions.

In an effort to present both sides of the argument, let’s consider some counterarguments next.


### Fragile values, ruthless efficiency, perverse incentives


> “Achieving a higher human value such as universal justice is not a question of engineering. Blockchains and robots don’t address the fundamental problem of humanity’s widespread refusal to value one another and the world we share. Rather than trying to locate our values in better computer code, we should be turning to the parts of ourselves that can’t be understood in those terms: our abilities as humans to engage with ambiguity” - Douglas Rushkoff, _Team Human_ (ch. 94)

The canonical example in the blockchain world of a terrifyingly dystopian algorithm is the [assassination market](https://en.wikipedia.org/wiki/Assassination_market): were such a market to exist, and meaningful funding to flow into it, it could become ruthlessly efficient and do a great deal of harm: imagine Internet trolls having an “enforcement agency.” However, an algorithm that seemed much more benign could still do harm through perverse incentives. For instance, an algorithm that incentivized people to collect trash could, in theory, also incentivize the creation of more trash (more trash means more rewards to be had for collecting it). A blockchain that granted access to an account or its funds solely on the basis of biometrics could incentivize a market for stolen body parts.

Even the most well-designed, well-intending algorithm optimizing for something that sounds completely innocuous could, in the extreme, still do a lot of harm, as the [paperclip maximizer](https://wiki.lesswrong.com/wiki/Paperclip_maximizer) thought experiment demonstrates. If the system running the algorithm were to become extremely intelligent and powerful, it could theoretically do a great deal of harm on a very large scale very quickly.

The underlying point here is that it’s impossible to programmatically capture all of the things that humans care about, and capturing only a subset of them (as any algorithm must inevitably do) may very well lead to an outcome that most of us would consider unacceptable. As the AI research community has written about extensively (and as Vitalik Buterin has kindly [introduced us to](https://blog.ethereum.org/2016/06/19/thinking-smart-contract-security/)), this concept has a name: _fragility of value._


> Fragility of value is the thesis that losing even a small part of the rules that make up our values could lead to results that most of us would now consider as unacceptable (just like dialing nine out of ten phone digits correctly does not connect you to a person 90% similar to your friend). For example, all of our values except novelty might yield a future full of individuals replaying only one optimal experience through all eternity. (From [Complexity of value](https://wiki.lesswrong.com/wiki/Complexity_of_value))

Because no algorithm can possibly capture everything that matters to humans—our _complexity of value_—by extension, no algorithm can ever determine what’s “right” or “wrong” in any meaningful, human sense of these terms.


### Bias


> “That’s why the original commands we give them are so important. Whatever values we embed—efficiency, growth, security, compliance—will be the values AIs achieve, by whatever means happen to work. AIs will be using techniques that no one—not even they—understand.” - Douglas Rushkoff, _Team Human_ (ch. 55)

While algorithms themselves may be indiscriminate by definition and thus, in a sense, fairer than human judgement, they’re only as good as the data they’re trained on. We must therefore be extraordinarily careful when designing such algorithms, ensuring that the underlying data and designs contain as little bias as possible (while being honest about the fact that no data set and [no design is totally free from bias](https://www.theguardian.com/lifeandstyle/2019/feb/23/truth-world-built-for-men-car-crashes)). There have already been several high-profile cases of well-intentioned applications of AI agents [reflecting severe biases](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing) present in the data sets used to train those algorithms, as well as AI agents released “into the wild” aping biased, discriminatory, even hostile behavior [learned from humans they interacted with](https://www.theguardian.com/technology/2016/mar/24/tay-microsofts-ai-chatbot-gets-a-crash-course-in-racism-from-twitter).

Social systems and protocols, more even than “pure” technological protocols, present a real risk of systematizing and institutionalizing bias. Systems designed by a small, like-minded group of people with certain inherent biases don’t necessarily work well for people at large. Blockchains are money and [money is inherently social](https://socialistrevolution.org/what-is-money-part-two-value-and-social-relations/). As blockchain technology becomes the backbone for ever larger and more important social systems and institutions, and as we vest ever greater agency into such systems, we would do well to take this risk seriously. Otherwise we may end up with a new world order that works well for educated, English-speaking, financially and tech-literate, libertarian men, and not so well for everyone else.


### Interoperability


> “All governmental power in constitutional democracies must be legally authorised and limited by law. AI systems should serve to maintain and foster democratic processes and respect the plurality of values and life choices of individuals. AI systems must not undermine democratic processes, human deliberation or democratic voting systems. AI systems must also embed a commitment to ensure that they do not operate in ways that undermine the foundational commitments upon which the rule of law is founded, mandatory laws and regulation, and to ensure due process and equality before the law.” - [Ethics guidelines for trustworthy AI](https://ec.europa.eu/digital-single-market/en/news/ethics-guidelines-trustworthy-ai), European Commission (pg. 11)

There is a tendency, both in Silicon Valley tech culture and in blockchain culture, to give up on existing systems, write them off as hopelessly outmoded and incapable of being improved or reformed, and to put faith into brand new systems instead. I call this a “blank slate” mindset, and it’s visible in the way many in Silicon Valley feel about the government: that it cannot be relied upon, and that as a result [it’s up to the titans of tech](https://www.newyorker.com/magazine/2013/05/27/change-the-world) to move human society forward. Similarly, many proponents of blockchain technology feel that existing institutions such as retail banks, central banks, and even the judicial system, are beyond saving. People with this mindset feel that it’s incumbent upon the technologists to build something better and fairer, and the mindset is often manifest in [misguided phrases such as “bank the unbanked”](https://www.aier.org/article/dont-say-unbanked-say-differently-banked/).

This mindset is flawed for two reasons: because there is in fact a lot we can learn from existing systems, and because it fails to factor in the cost of switching to an ostensibly better system.

On the first point, flawed as they may be, existing systems are often the product of centuries of wisdom accumulated through trial and error. How many blockchain thought leaders can explain how the Federal Reserve actually operates? How is money created and distributed throughout the financial system, and _why_ do things work this way today? How are rates set? What other systems have been tried, and what became of them?

Before seeking to replace existing systems, at the very least we should seek to understand why they are the way they are—and we should make a point of learning as much from them as possible. As one positive example, the EU published [ethics guidelines for AI technology](https://ec.europa.eu/digital-single-market/en/news/ethics-guidelines-trustworthy-ai) that are well-written, sensible, and draw heavily from existing scholarship in jurisprudence and political philosophy. Despite the fact that this work is a product of the “legacy” governmental and legal order, there is a great deal we can learn from it and incorporate into new legal, political, and philosophical systems that emphasize the challenges and opportunities presented by autonomous algorithms. \


In particular, existing systems embed a great deal of _cultural_ and _contextual_ wisdom and understanding. Designing a theoretically better system _in a vacuum_ does not mean that the system will work _in practice, in situ,_ once all the social complexities are factored in. We tend to use systems that are consistent with our cultural values, and systems that fail to account for these values are unlikely to be adopted by the masses. As one example, [Google Glass](https://en.wikipedia.org/wiki/Google_Glass), introduced in 2013, failed to make a splash largely due to concerns over privacy and etiquette.

On the second point, the “blank slate” mindset is flawed because it fails to take account of switching costs. It may very well be true that an existing system is deeply flawed, unfair, and suboptimal, and that many potentially better designs exist. It may also be true that the costs of actually realigning to such a new system would simply be too great, and in fact would outweigh any benefits the new system might provide. For this reason, when evaluating the utility of a new system, it’s important to account not only for the absolute difference between the two systems, but for the switching costs as well, something that even clever, well-intentioned intellectuals often fail to do.

If we want blockchain (or, for that matter, any new technology) to have a chance of succeeding and touching the lives of billions of people as it is no doubt capable of doing, we must better understand how it can interface with existing institutions. At the very least, we must study those institutions closely and understand where and how we can improve things meaningfully without throwing the baby out with the bathwater. By the same token, we should seriously consider the costs were existing institutions—financial, legal, governance, communications, etc.—to adopt blockchain technology in earnest, how those costs might offset some of the benefits to be gained by switching (especially in the short term), and how we might make those costs worthwhile.


> “So strange that we act as if blockchains are all about math or science when they are really just about people deciding to work together, how they get along, and whether they can protect themselves from people who disagree with them or want their stuff.” - [Angela Walch](https://twitter.com/angela_walch/status/1083069503335002112)

In his [diatribe](https://medium.com/cryptolawreview/against-szabos-law-for-a-new-crypto-legal-system-d00d0f3d3827) against novel legal systems based on Szabo’s Law, Zamfir argues that, quite in opposition to their professed aim of social scalability, such systems are in fact “insecure and antisocial” in that they bluntly refuse and do not even attempt to engage with existing political and legal processes, abandoning such social processes entirely in favor of immutability (“code is law”). I'd add that they’re also [“libertarian, crypto-anarchic, and extra-legal”](https://medium.com/cryptolawreview/crypto-scaling-is-a-legal-problem-b2074367eedb) and as a result, rather naive.

Rather than taking a naive stance with respect to existing legal, political, and other social systems, in order to build actual systems that deliver actual value to actual humans around the world now and in the future, we need to be willing and indeed excited to engage with existing systems and to design mechanisms that work well for real people, rather than rely on the allure of immutability to magically solve all of our problems.


### What’s the algorithm for mercy?


> “The problem is not that we aren’t investing enough in scientific research or technological answers to our problems, but that we’re looking to science for answers that ultimately require human moral intervention.” - Douglas Rushkoff, _Team Human_ (ch. 78)

Say what you will about the fairness, efficiency, and robustness of autonomous algorithms: an algorithm cannot and probably never will be able to encode a concept as fuzzy and downright _human_ as mercy. Algorithms necessarily reduce the wonderful, complex, multi-dimensionality of the world around us down to cold, hard, inflexible ones and zeroes. In so doing, much that makes the analog world a wonderful place is lost.

Mercy is just one example, but there are many other desirable, [fundamental human values](https://psynso.com/rokeach-value-survey/) that have no bitwise equivalents: justice, fairness, dignity, truth, beauty, compassion, and forgiveness come to mind. I for one would not want to live in a world devoid of these values, no matter how efficient. If you give me the choice, I would rather face a human jury and be sentenced by a human judge—any human judge—than by the fairest, most efficient, most robust digital court imaginable.

As they say of Nazi Germany, the trains ran very, very efficiently, and [efficiently delivered millions to the death camps](https://en.wikipedia.org/wiki/Holocaust_trains#The_role_of_railways_in_the_Final_Solution), right on time.


### Lack of transparency, accountability, auditability


> “If we don’t truly know what something is programmed to do, chances are it is programming us. Once that happens, we may as well be machines ourselves.” - Douglas Rushkoff, _Team Human_ (ch. 29)

Autonomous algorithms tend to make things like transparency, accountability, and auditability hard. We can cause an algorithm to log every decision made, every action taken, etc., but in many cases it may be difficult or impossible for an algorithm to “explain” the rationale behind such a decision: the answer may have high complexity and therefore not be reducible to anything less than all of the code of the algorithm itself, and all its input data (which, for various reasons, might not be made public). As a result, in many cases we may [not actually know why](https://journals.sagepub.com/doi/full/10.1177/1461444816676645) an algorithm made the decision that it did.

This is especially problematic in the context of bias, as described above. We risk ending up with systems that we do not understand and cannot easily improve, much less alter to counteract bias, since we may not understand or be aware of the source of bias.

I don’t know about you, but I tend not to trust a system that isn’t transparent, accountable, and auditable. After all, what other guarantees do I have that a system is doing what its creators say it does, what it’s intended to do?

This is one of the main problems blockchains are designed to solve. Indeed, platforms like Bitcoin and Ethereum are fully transparent and auditable. (At least at layer one; the applications running on them may not be.) However, the same cannot be said of systems designed for privacy. Privacy is incredibly important and valuable, but we must understand that it comes with tradeoffs.

Due to the fact that the details of a private ledger (transaction senders and recipients, amounts, etc.) are intentionally obfuscated by technologies such as zero-knowledge proofs, these systems are much harder to audit. As one concrete example, Zcash discovered, fixed, and eventually disclosed a [severe bug](https://electriccoin.co/blog/zcash-counterfeiting-vulnerability-successfully-remediated/) that could have allowed token counterfeiting for a period of months. While the Zcash team believes that no counterfeiting occurred, due to the private nature of the ledger, [they cannot be sure of this](https://news.bitcoin.com/zcash-bug-demonstrates-the-difficulty-of-auditing-complex-cryptocurrencies/), and we need to take their word for it that the bug wasn’t exploited by the core developers who discovered it. (For avoidance of doubt, I’m not suggesting that it was, but it is at least theoretically possible and, for now, impossible to prove otherwise.)

There will doubtless be many future examples of autonomous systems that no one but the system’s creators fully understand. This has the frightening potential to create a tiny, privileged elite who understand and can possibly even exploit such systems to their own advantage. For this reason it’s absolutely essential that autonomous systems be made as simple as possible, that they be based on common design patterns as much as possible, and that their full specifications, codebases, and documentation be made available for public scrutiny.


### Legality


> “Human dignity shall be inviolable. To respect and protect it shall be the duty of all state authority.” - Article 1, [Basic Law for the Federal Republic of Germany](https://www.bundesregierung.de/breg-en/chancellor/basic-law-470510)

One of the most interesting questions regarding autonomous algorithms, and indeed one of the most controversial questions in blockchain, surrounds the question of legality. Are autonomous algorithms legal? Legal with respect to what system of law? Do they need to be? What happens when they’re not?

When a human actor breaks the law, there are ramifications such as fines, imprisonment, reputational harm, etc.. When an organization such as a corporation breaks the law, there are ramifications, both for the organization itself and, potentially, for the persons of record accountable for that organization. But what happens if an autonomous actor—a drone, an AI agent, or a blockchain—breaks the law? The answer to this question is still very unclear.

Even if it were possible to impose order on blockchain, it’s unclear _which_ body of law would apply. As Balaji Srinivasan helpfully explained in [Bitcoin becomes the Flag of Technology](https://nakamoto.com/bitcoin-becomes-the-flag-of-technology/), Bitcoin and networks like it are _inherently digital and international,_ i.e., not tied to any particular jurisdiction. This is, of course, in theory true of the Internet itself, a point emphasized by Internet pioneers including John Perry Barlow:


> Governments of the Industrial World, you weary giants of flesh and steel, I come from Cyberspace, the new home of Mind. On behalf of the future, I ask you of the past to leave us alone. You are not welcome among us. You have no sovereignty where we gather...

> Your legal concepts of property, expression, identity, movement, and context do not apply to us. They are all based on matter, and there is no matter here.

> Our identities have no bodies, so, unlike you, we cannot obtain order by physical coercion...

> We must declare our virtual selves immune to your sovereignty, even as we continue to consent to your rule over our bodies. We will spread ourselves across the Planet so that no one can arrest our thoughts.

>  [A Declaration of the Independence of Cyberspace](https://www.eff.org/cyberspace-independence) by John Perry Barlow 

In practice, however, as we’ve seen over the past few decades, even on the Internet anonymity is hard. The actors _behind_ the Internet, humans and corporations, are mostly well-known and subject to real-world consequences. As a result, the laws of a small number of countries, such as China, the EU, and the USA, circumscribe much of our online experience today.

Blockchain, however, is different—at least for now. As in the early days of the Internet, it has no robust identity layer as yet, and it’s commonplace to transact using only a pseudonym (or wallet address). This lends itself to an air of impunity with respect to existing, jurisdictional law, one reason Bitcoin is popularly used to buy drugs and launder money.

One naive possibility for ensuring legal compliance is to hold the designers, creators, builders, deployers, and/or maintainers of an autonomous digital system legally liable in case something goes wrong with that system. On the face of it, this doesn’t seem unreasonable. If I design and build and deploy an autonomous agent that breaks the law, then it seems to make sense to hold me accountable for that behavior.

However, this approach has several practical, ethical, and legal challenges. For one thing, the real-world identities of these human actors may not be known (e.g., the human actors behind a smart contract on a platform like Ethereum may be identifiable only by a pseudonym or cryptographic wallet address). For another, this approach may severely discourage innovation and risk-taking, since some well-intentioned systems will malfunction and break the law unintentionally.

It would be best to have an explicit legal framework, so that innovators can understand and forecast the risks and continue to innovate in spite of them. A good starting point for such a framework might be the sort of legal personhood granted to a corporation. An autonomous actor might be granted certain legal protections in exchange for its being registered, with one or more accountable “persons of record” behind it. This establishes a basis for legal liability in case something goes wrong.

However, this approach still fails to completely address the pseudonymity and anonymity questions, since the anonymous actors behind an autonomous application may simply choose not to register it. To be clear, these questions are no longer merely hypothetical. It’s possible today to deploy a smart contract onto a censorship-resistant platform such as Ethereum in a pseudonymous fashion. That smart contract may break one or more laws, in one or more jurisdictions, in sundry ways. It might contain repugnant, illegal data such as child pornography—or, more realistically, an [illegal number](https://en.wikipedia.org/wiki/Illegal_number). It may be something like an [assassination market](https://en.wikipedia.org/wiki/Assassination_market) that, while not perpetrating violence directly, is nevertheless guilty of [incitement](https://en.wikipedia.org/wiki/Incitement).

What happens in cases such as these? Remember, in a decentralized network like Ethereum, every single full node (Ethereum has [thousands](https://etherscan.io/nodetracker)) contains a full copy of all of the data, legal or illegal, that’s ever been written on the blockchain. And those data are, in theory, immutable. Does the entire blockchain thus become illegal? Does it become illegal to run a node?

In his articulation of Szabo’s Law, Zamfir argues that if we decide that blockchains are immutable and ungovernable (by any ordinary interpretation of the word “govern”), then by definition that puts them into conflict with established law in most or all jurisdictions and blockchains themselves will likely be deemed illegal as a result.

What can and should blockchains and their constituent communities do to remain legal, at least in reasonable jurisdictions? If they’re not able to gain widespread recognition as being legal, what chance do they stand of going mainstream? If they go mainstream in spite of never achieving legal status or recognition, what does that mean for existing legal systems? Should natively autonomous, digital, international communities such as blockchains seek to establish new legal systems?

Another approach, in contrast to the permissionless approach taken by platforms such as Bitcoin and Ethereum, is the permissioned blockchain: rather than allowing anyone to mine, transact, etc., these platforms only allow known actors, who prove their identity via some off-chain method (and therefore usually have a reputation at stake), to participate. While permissioned platforms are often regarded by blockchain purists as little more than centralized databases, they do offer an interesting compromise. They can potentially provide an interface between social laws and blockchain mechanisms, with an explicit recognition of the fact that blockchain actors are humans (and not anonymous, unaccountable automata). The blockchain is as much a community of human actors as it is a network of nodes.

This is a fascinating topic, and the question of legality represents one of the biggest challenges for blockchains, smart contracts, and other autonomous algorithms. At present, there are more questions than answers. Deeper analysis is beyond the scope of this article, but for those who are interested in the question of legality of blockchain, initiatives such as [COALA](https://coala.global/) and the [Wharton Cryptogovernance Workshop](https://cryptogov.net/) are doing important work on it.


### The Upgradability Paradox

[All software has bugs](https://softwareengineering.stackexchange.com/questions/195571/is-it-possible-to-reach-absolute-zero-bug-state-for-large-scale-software). This is simply a rule of software engineering. Even a hypothetical, bug-free piece of software still has to be upgraded for reasons of maintenance, optimization, and ongoing development. What’s more, this upgrade process must by definition be initiated _from outside._

For this reason, every software-based system must have some mechanism for fixing or upgrading the system—effectively, an emergency “stop” button or an escape hatch that allows the system to be shut down, at least temporarily, in case of malfunction or need of upgrade. And any autonomous algorithm lacking such a feature would in practice be abandoned the first time it malfunctioned or became out of date.

But if this is the case, then by definition there is some person or set of people who have “god-mode” control over the system—who, _acting from outside the system,_ can exercise unilateral authority over the system. Can such a system ever truly be called autonomous? (To put the question another way: if some alien had the power to press a button and “pause” or “reboot” or unilaterally alter the governance of the United States, is the United States still a sovereign nation?)

Herein lies one of the most important differences between humans and machines: human judgement, however fallible, _does not need to be upgraded._ This is because it’s not a formal system, doesn’t rely on formal logic, and doesn’t by necessity reduce all data and all decisions to ones and zeroes. Human judgement is malleable, and that malleability is one of its greatest strengths. (Incidentally, this is also why I think humans need not fear AI takeover, but that’s a topic for another article.)

Since all such “autonomous” actors are in fact subservient to some social, human upgrade mechanism, it’s disingenuous and in fact hypocritical to speak of such systems as autonomous, or as above/outside/beyond the loop of social or human or meatspace actors, i.e., politics. Such systems are _not_ a law unto themselves (autonomous literally means “own law”); they are in fact subject to the same social laws as all existing human systems, indirectly if not directly.

In the case of blockchain, in addition to the core developers who upgrade and maintain the protocol, there are also human node operators who play a crucial role in network operations. They choose whether, and when, to upgrade their node software, and by extension which upgrades or changes to accept. They could, in theory, be subject to legal liability for approving, propagating, or storing certain transactions, and may therefore decide to censor or even roll back certain transactions. Calling a blockchain “autonomous” ignores the role of these human actors.


## Conclusion


> “Artificial intelligence, cloning, genetic engineering, virtual reality, robots, nanotechnology, bio-hacking, space colonization, and autonomous machines are all likely coming, one way or another. But we must take a stand and insist that human values are folded into the development of each and every one of them.” - Douglas Rushkoff, _Team Human_ (ch. 92)

Without a doubt, autonomous algorithms have the potential to generate enormous value. Technologies such as smart contracts significantly reduce transaction costs and enable entirely new sorts of transactions, among parties who might not otherwise transact. In this way, they will enable ideas, products, and services that we cannot even imagine today. Of course, they also have the potential to do enormous harm, as discussed above.

The question we should be asking ourselves is not whether or not such technologies are _good,_ nor even whether or not we should pursue them. All technology can be used for good or for evil. Regardless of what we may think of autonomous software or its associated risks, it already exists and cannot be uninvented. Indeed, regardless of a technology’s potential use or misuse, _someone somewhere_ will build it. This is true of _any_ technology, doubly so for software that can be deployed anonymously and that can be used to make (or mint) money.

Instead, the question we should be asking ourselves is, how do we prepare for a future where autonomous systems are prevalent to the point of invading every aspect of our lives, _eating the world,_ like (mostly non-autonomous) software has already done today? How do we ensure that such systems are as robust as possible? That they factor in the values, needs, and preferences of as many humans as possible? And, just as importantly, that they continue to do so long after they have been deployed to production. How do we minimize bias in such algorithms, and make sure that they continue to mature and improve over time?

In response, both the autonocrats and the anthropocrats make valuable points. On the one hand, autonocrats argue that Bitcoin has proven Szabo’s Law viable in practice for at least some subset of blockchain communities; without it, blockchain will inevitably enfranchise certain groups of stakeholders at the expense of others, run the risk of being captured by companies, states, or other powerful actors (just like all social systems), and fail to deliver on its maximum potential for social scalability (in the [Szabo sense of the word](http://unenumerated.blogspot.com/2017/02/money-blockchains-and-social-scalability.html)).

On the other hand, anthropocrats make the case that a total inability to engage with existing social systems or debate social questions severely limits the appeal of blockchain, makes it difficult for existing institutions to engage with blockchain or take it seriously, and alienates certain groups of stakeholders. It also means that blockchain risks falling victim to the [tyranny of structurelessness](https://en.wikipedia.org/wiki/The_Tyranny_of_Structurelessness), or capture from within by an unaccountable set of elites.


### More experimentation

The most important thing we can do today is recognize both the incredible potential before us, as well as the limitations of our current systems, and _keep experimenting._ We should not be fearful, but we must also not get ahead of ourselves and act hubristically. We must have an honest dialog about both the risks and the opportunities before us. We simply won’t know what does and does not work—what enables the most innovation, the most promising applications, the most economic growth and efficiency—without a lot more experimentation. Therefore, our priority today should be to shun tribalism, zealotry, purity, and fearmongering in favor of a bold, pioneering spirit that presses forward.

In the interest of experimentation, we should let a thousand flowers bloom. Different blockchain communities should reflect different [sets of values](https://www.etherean.org/blockchain/community/governance/2019/11/18/key-ingredients-better-blockchain-part-iv-constitution.html), different [governance strategies](https://www.etherean.org/blockchain/governance/2020/01/06/key-ingredients-better-blockchain-part-v-governance.html), and different solutions to the challenges facing this emerging technology. Indeed, Ethereum already experienced one chain split along these lines when the community now known as Ethereum Classic refused to participate in the network upgrade hard fork to mitigate The DAO attacks, valuing immutability and Szabo’s Law over redress and social cohesion. We should recognize that these divisions are inevitable and encourage communities to form around different sets of values, while also promoting cross-community and cross-chain dialog and collaboration.

Most likely, there is no single optimum, but rather multiple equilibria representing different, valid points on the solution space. Over time, we’ll discover which of these points represent value for the most people, and which ones succeed organically.

And who knows? Maybe in the 2100 presidential election we’ll see an AI-backed candidate representing the autonocrat party run against an old-fashioned human candidate representing the anthropocrats—or an interesting hybrid somewhere in between!

Special thanks to Brian Behlendorf, Matan Field, Jack du Rose, André Geest, Yael Hoffman, Boris Mann, Jude Nelson, Kevin Owocki, Ryan Selkis, Nathalia Scherer, Gustav Simonsson, Ameen Soleimani, and Vlad Zamfir for invaluable pre-publication ideas and feedback.

