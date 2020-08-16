# Emission

Grin's emission schedule is completely linear; New grins are created at a constant rate of 60 grins per block, meaning *1 grin/s*, forever. Such linear increase in supply results in a decreasing inflation rate, or disinflationary emission.

![emission chart](../assets/images/emission_chart.png){ width=650 }


This simple design serves to ensure the long term security and stability of the chain, as well as provide a fair process of distribution. We'll set to explore those topics more thoroughly.

!!! note "Compare to Bitcoin"
    The first four years of Bitcoin emission rate are identical to the first four of Grin. Bitcoin had a full reward for 4 years, followed by half that for the following 4 years. So compared to a constant supply, after 8 years, the total amount of coins emitted is only 33% less.

## Security

The more resources being spent on mining a proof-of-work chain, the less it's suceptible to various mining attacks, most prominently 51% attacks. The financial resources deployed, or the overall mining revenue, are often referred to as *security spend*, which is solely determined by the incentives provided as block rewards. This reward is composed both of transactions fees, and of the block subsidy, i.e. newly generated coins.

### Block Subsidy

Grin introduces a constant block subsidy in order to remain sufficiently secure over the coming years and decades. Block reward is then *guaranteed*, regardless of how full the blocks are, or how much users are willing to pay in fees for faster confirmation.

Furthermore, This type of emission provides a lot of certainty, and avoids the shortcomings of the standard decreasing emission which has yet to be proven stable and effective on a longer time horizon. The uncertainty in emission changes is eliminated both for users, who never know how the chain's security might be affected, and for miners who wish to plan their operations far into the future.

### Fees

All other proof-of-work chains are designed to generate and distribute most of the supply early on, to the benefit of a few, and then increasingly rely on *transaction fees* to incentivize mining.

An apparent issue with this approach is that overall security spend is likely to decrease as time passes, making the chain fundamentally less secure in the face of mining attacks, whether by selfish attackers or state actors. This results in a "tragedy of the commons", as individual users strive to pay a minimum amount of fees, while also depending on the security that their fees are paying for[^1].

Although not as obvious, even a chain with extremely high transaction fees is uniquely prone to selfish mining attacks and undercutting[^2], potentially making a 51% attack possible with much less than the majority mining power. This causes inherent instability which would have otherwise been avoided, given a chain with similar mining revenues earned only through block subsidy.

## Distribution

How the coin gets distributed carries significant importance. Grin was not created to quickly enrich a few people, but for providing private digital cash to all.

### Fairness

The constant issuance establishes a fair coin distribution[^3], where equal opportunity is given to everyone, in any point in time. New users should not feel discouraged or disadvantaged when adopting a new form money.

In constrast, a currency distributing early a large portion of the coins largely benefits it's first users but presents an unwelcoming narrative to new ones, since it assigns them with a substabially smaller portion of the network's value. This in turn affects the currency's long-lasting story of distribution[^4].


### Wide Distribution

As it stands today, the ownership of bitcoins is very centralized and will likely remain so. The situation is far worse in most other cryptocurrencies.

The likely result is that a narrow group emerges, consisting of individuals and organizations who may have an exorbitant amount of control over the market price. More importantly, they have the the power to influence the project and its ecosystem more than any others, since early, unpropotional hoarding carries a good deal of centralization pressure.

A constant emission aims to support Grin's intent of being at the hands of many people and being used to transact freely, as a privacy-perserving medium of exchange.

## More

Additional properties of constant emission that are worthy to consider:

* Early users do not profit exponentially due to a decreasing supply, but purely through increasing demand for the coin.
* 1 grin/s is very intuitive to understand[^5]. Such clear emission rule is more likely to be enforced by community concensus, unlike a blurred, complex model.
* One of the pitfalls of monetary inflation in fiat currencies is governments can inflate the monetary supply on a whim. This has been used to disastrous effect throughout history. A consensus based currency solves this issue by making the emission policy well known ahead of time, and makes it difficult if not impossible to change. Removing central authorities with arbitrary control is much more what makes Bitcoin important than the arbitrary amount of its capped supply. By this definition, Grin is just as much "sound money".
* When ownership is more evenly distributed, it likely means that more participants are holding a sizable portion of the network, and thus more users are meaningfully incentivized to advance its growth & improve it.


[^1]: [Bitcoin's Security Trilemma](https://youtu.be/zPYkL6L3VGw?t=988)
[^2]: [On the Instability of Bitcoin Without the Block Reward](https://www.cs.princeton.edu/~arvindn/publications/mining_CCS.pdf)
[^3]: [Grin and the Mythical Fair Launch](https://medium.com/@arjunblj/grin-and-the-mythical-fair-launch-395ca87a5e73)
[^4]: [The Story of Distribution](https://github.com/mimblewimble/docs/wiki/The-Story-of-Distribution)
[^5]: [Nick Szabo on Supply Predictabilty](https://twitter.com/NickSzabo4/status/1077317105148547072)