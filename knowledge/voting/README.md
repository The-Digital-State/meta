Digital voting is one of the most complicated topics which require compromises and correct implementation. When implemented incorrectly, it has the negative effect. The fundamental problem with voting is that most people will form their opinion about "electronic voting" based on media and influencers, rather - having no capacity to valiate solution themselves.

We have collected some knowledge and expertise around voting fundamentals and are offering information on how modern technologies such as SSI, Digital Identity, Blockchains and decentralisation can help.

Depending on how much control and political will exist, there are different ways to apply voting techniques. This document will describe ideal techniques and then offer some semi-functional solution that can be used as a "warm-up" for your electric voting. Also - check out other files that would have information about other contries who have successfully conducted electring voting and what kinds of systems they have used.

## Three parts to successful digital elections

### Full end-to-end general voting

The ideal scenario in a digital state is to have fully autonomous voting system, which is not controlled by anyone but only people. A blockchain-based solution (like bitcoin, but with a custom blockchain) uncontrolable by the government may be used to initiate elections, conduct them and then implement the results by empowering individual who won the election. Such a system can be built and tested on a smaller schale than promoted, but could meet incredible amount of resistance from existing and even opposition parties, who all fight for power and would not want to participate in a system unless it's a de-facto system established by the community.

1. Through Digital Identity a certain certificate can be issued by a custom blockchain protocol to the winner of the a general vote. Such a system can be configured to elect agreed amount of candidates as per the current constitution. (Etherium 2.0 uses votes through ETH staking and similar voting system is implemented in EOS)
2. Cryptocurrency blockchain voting methods determine weights by the amount of staked currency. In general election each citizen must have one vote, so a concept of Census (people eligible to vote) is important. Making sure that census consists only of real people who have sole control of the vote and their voting power cannot be compromised is crucial to avoid electorial fraud.
3. Census must be converted to blank ballots - system, upon receiving a proof of uniquiness would respond with an emty ballot. This part of system is really difficult to make transparent as it is designed to disconnect identities from ballots. A concepts of open-source and decentralisation can make it very difficult to accuratelly influence the system.
4. Repeated votes is required by community - to allow citizens to re-vote, however this mechanism is known to be compromised in 2021 election in Russia (see file)
5. Proof of vote accountability - is ability for a voter to hold a private token which they can track to a resulting pool of votes and make sure that their vote has been properly accounted to the right candidate.
6. Voting beginning and ending - quite difficult if the country is located in multiple timezones and voting must finish at different times.
7. Opening up the envelopes - technically this can be done by publishing a secret "seed" used for a pseudo-number generation of unlock keys for the votes. Once published - this would allow results to be observed.
8. Hashing of voters - distributing citizens as per some hashing algorithm to a "digital polling districts" - can be used to decentralise process of vote collection and counting. With 5-10 districts maintained by different political backers it would make it really difficult to compromise all of them to affect results. 
9. Invalidation of fraudulent patterns - techniques how voting system on its own can spot and mark entire election as "corrupted"
10. Granting certificate to the winners - assuming that election was carried out successfully and the amount of "fraud" did not generate enough sway to change the outcome, the system may even announce winners automatically and on-schedule. (digital mandates)

Those are the theoretical points for a fully automated general election however a more selective solution can also be used.

### Helping with the off-line vote

When off-line voting takes place, the results are conducted and controled on a regional level. Being able to create transparent system for collecting regional information and transferring it into a global results can reduce a single-point-of-failure which is commonly used to produce fake election results.

1. District elections are carried normally - booths and ballot counting.
2. All observers are granted special certificate through digital identity, which allows them to interract with a public blockchain system
3. Observers may register offense along with the proof (video, picture, etc) through public blockchain while uploading evidence files to IPFS
4. Official results from regional centers are also recorded in a blockchain by observers along with the confidence level as per their observation (counted correctly or inaccurate counting)
5. Blockchain application can use this inputs to come up with realtime results, which can then be compared with official results

This solution is significantly more simple and will produce unskewed results, which can then be used in PR. Due to the use of blockchain system and digital identity, the system would be very difficult to compromise and it should be very well received internationally. It also wouldn't be owned by anyone and would be difficult to block due to the "blockchain-based" implementation.

### Regional voting

The third possible application of voting can be used by groups or organisations. For example - give ability for a neighbourhoods to decide on which utility/construction compnay to hire or to coordinate other local efforts.

In this scenario, having a decentralised solution may not be that important - instead a hosted solution can be used for voting. The application would require some degree of transparency:

1. Allow organisers to create a census registry, which can be rievewed by all voters (to make sure no fake accounts are used)
2. Everyone from the census would receive one voting token through their email. With that token they can cast one or multiple votes, but only the last vote would count.
3. During every vote person would receive "vote-id", something they can write down in their notes for future veification
4. Once results are announced, voters will be able to find their vote-id in the list to make sure that their voice was counted and also confirm with the others that resulting spreadsheet is same for everyone.

 - ALBO - regional voting application.


### Other voting software and techniques

- Vocdoni
- 