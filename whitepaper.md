# INTERPEER - The trust-less peer-to-peer resource marketplace.
26 September 2016 - draft 11 - [Rory Renton] (http://www.smellymoo.com)

## 0. Abstract
Interpeer is a complete peer-to-peer alternative for the world-wide-web; a system to distribute dynamic web-pages. It achieves this by being a trust-less marketplace to exchange processing, bandwidth and storage using a distributed network of peers.

## 1. Introduction
The original concept of the Internet as a free exchange of information has increasingly become threatened by state censorship and the commercial interests of multi-national corporations who 'guide you'. Interpeer would remove the vulnerabilities making the internet free again.

Interpeer would function as a anonymous peer-to-peer marketplace connecting people that want to get paid for their system resources with others that want to author censorship free websites, store large amounts of data or do massive computation tasks.

in essence Interpeer does for the world-wide-web what [bitTorrent](http://www.bittorrent.com) does for file-sharing; each interpeer-site is hosted by groups of peers, which makes it very difficult to destroy, also authors can upload sites anonymously to the network. But unlike bitTorrent, the site is not static data; so to continue the analogy; it would be equivalent of a torrent that users could edit. This makes it possible for interpeer-sites to have dynamic (web 2.0) content like [wikipedia.org](http://www.wikipedia.org).

Currently websites are hosted on a physical server that is located by its domain name. An interpeer-site is hosted by many peers which are paid for the service they provide via a virtual currency (InterCoin). In this model anyone can install the program and get paid without further understanding.

The advantage for website hosting is easy to see if you look at the disadvantages of the current Internet client-server model: the server is a single point of failure, low anonymity when creating a website, each visitor downloads from the server not other visitors which is duplicating requests and finally the central control over domain name lookup with ISPs controlling access which limits freedom of speech.

For any system like Interpeer to be successful I see the following requirements:
 - **dynamic:** the modern internet is web2.0, and no one is going to use a system that isn't. if [Wikipedia](http://www.wikipedia.org) doesn't work on the platform then the idea is basically useless.
 - **user migration:** people don't understand tech, combined with the network effect, so it must work seamlessly with the standard web.
 - **vote on updates:** most P2P suffers from a similar problem, centralised development. because often things start well (Google: "don't be evil") and end horribly.
 - **website migration:** a website must be easily transferred to the platform without too much hassle.

## 2. Key innovations
Interpeer introduces large innovations to peer-to-peer technology. The significant ones are:

### 2.1 useful processing
In [Bitcoin](http://www.bitcoin.org) a gargantuan amount of processing power is used on a useless proof-of-work to reach consensus thus securing the network, but Interpeer uses the processing power of the network to do useful functions (run the scripts).

Interpeer adds a new concept called a "job", which is explained later in depth. But to summarise it is the ability for a group of peers to work on one task together, This is possible because they must agree on the outcome of processing. The reason why this is so valuable is it allows the network to perform a huge variety of tasks in parallel.

A good way of imaging it is think of how [bitTorrent](http://www.bittorrent.com) shares files, each separate file is seeded by a group of peers on the network, not the whole network. The difference is Interpeer is running scripts on these peers rather than sharing static data.

### 2.2 web 2.0
All other attempts at a peer-to-peer world-wide-web don't allow users to interact with the site leaving changes, only the authors, so modern sites using web 2.0 like [facebook.com](http://www.facebook.com) or [wikipedia.org](http://www.wikipedia.org) can not be implemented.

### 2.3 user migration
Interpeer sites will be accessible by users using vanilla browsers and no knowledge of Interpeer, this is key to getting Interpeer widely adopted. 

This is achieved by using [interpeer.net](http://interpeer.net) to redirect requests to peers that are currently handling the site in question. During this insecure method a warning bar will appear asking users to install the browser plug-in to use interpeer directly.

### 2.4 processing backed currency
Because Interpeer is primarily a P2P cloud computing platform, the linked currency (InterCoin) would be backed by something with a known value; processing power and storage. This would give InterCoin great stability in comparison with Bitcoin, which can drop to any arbitrary value during times of market upheaval.

InterCoin has a real known value of a fixed amount of processing power and/or storage on a peers computer.

### 2.5 website migration
Because Interpeer uses a modified version of PHP to make interpeer-scripts, migrating from PHP websites to Interpeer would often be trivial.

But because the peers hosting the interpeer-site or storing related data would be able to read any data that is unencrypted some security features would need to be implemented in browser (e.g. using JavaScript). For example end-to-end encryption or hash generation.

## 3. Example uses
If [wikipedia.org](http://www.wikipedia.org) or [wikileaks.org](http://www.wikileaks.org) used Interpeer, they would see huge advantages:

- content is addressed individually, so anyone viewing a page could serve it to others wanting to view it (like [bitTorrent](http://www.bittorrent.com) or [IPFS](http://www.ipfs.com)). Meaning Wikipedia would not be serving much of the traffic.
- donations to keep it running would go directly to the hosting account. Meaning it could run autonomously via direct anonymous donations.
- If the original authors got “silenced” the interpeer-site would continue to exist and be user-editable for as long as it was funded.

A few other examples of uses for Interpeer:

- anonymous bullet-proof web-hosting.
- getting paid for your spare computer resources.
- immortal sites that continue from donations or payments without author involvement.
- visit Interpeer sites anonymously.
- web2.0 will function unlike all other P2P WWW alternatives.
- massive computation tasks.
- storage with distributed multiple redundant copies.
- onion routing proxy service similar to TOR.
- smart contracts.
- dead-man-switch scripts.

## 4. Background
The internet is more than 30 years old now; we have come a long way since it's inception:
> “I think there is a world market for maybe five computers.” - 1943 IBM president

So far improvements have been stacked upon the older technology, leaving the antiquated parts in place. Interpeer only uses UDP/IP, everything else is built on cutting edge ideas of trust-less distributed computing.

Generally inventions come from taking pre-existing technologies and combining / improving them. So the easiest way to explain Interpeer is by showing you what has been sourced and why.

##### File storage :- [bitTorrent](http://www.bittorrent.com) / [IPFS](http://www.ipfs.com) / Storq / Maidsafe:
Share files peer-to-peer creating one shared storage system with distributed redundancy. Which makes it very difficult to lose or destroy files. In some of these technologies clients pay peers to secure files. Giving an incentive to do it, at a lower price than commercial options.

##### Consensus :- [Bitcoin](http://www.bitcoin.org) / Etherium / Namecoin:
Trust-less currency and smart contracts using block-chain technology. Without having a way to remunerate peers for taking part Interpeer would not be viable, also Namecoin demonstrates that domain registration can be done without the need of a central authority.

##### Hosting :- Cloud hosting:
A server no longer is one fixed computer, but can share the job between many.

##### Massive computation :- [Boinc](http://boinc.berkeley.edu):
Distributed computation, using the spare resources of many computers and combing them.

## 5. Philosophy
Information is power. Since the dawn of civilisation power has been hierarchical; with only very few at the top and everyone else at the bottom. Even the first attempt at a world-wide-web; which was supposed to liberate information didn't really change that; with domain registration centralised, the index (search engines) centralised and moderated, DNS centralised, and the ISPs as the gate keepers.

When peer-to-peer technology was invented (like [bitTorrent](http://www.bittorrent.com) and [Bitcoin](http://www.bitcoin.org)) it changed everything, unlike all previous power structures (pyramid shaped) it was flat; fair; peer-to-peer; people share and are equal. Although the importance of this breakthrough has been missed by most, it's the most important historical event in our life times; finally we have solved the unsolvable; trust without hierarchy. There is no longer a need for a governing body; people can work together as equals only using clever maths to govern the exchanges.

But this is only the start; a test case, to fully appreciate the advantage of this we need a new model of the internet; a fair one, where information is safe from censorship and there are no single points of failure or gatekeepers. Interpeer is designed to give people freedom of speech, so we can finally let information be free in every sense of the word, uncontrollable and uncensored for all!

## 6. Design summary
> “Any sufficiently advanced technology is indistinguishable from magic.” - Arthur C Clarke

Interpeer has 3 types of users with different goals:

- uploader – pay to host websites / process large computations / store data.
- seeder – get paid to run the Interpeer client.
- visitor – use [interpeer.net](http://www.interpeer.net) or install a plug-in to their browser to visit .peer sites using Interpeer.

When an uploader submits to Interpeer they post a “bundle” which is distributed on the network in a similar way to [bitTorrent](http://www.bittorrent.com), but unlike it the bundle is dynamic; the scripts can change the data. The task is split into “jobs” of a fixed amount of time / processing cycles and peers works together to complete it.

Interpeer jobs are trust-less, because unlike [bitTorrent](http://www.bittorrent.com) peers can't choose what job they are doing. Each peer plays a lottery to get jobs, and if they turn down the assigned jobs to attempt to game the system they quickly lose their peer-rating and won't get allocated jobs.

### 6.1 upload bundle 
When an uploader submits to Interpeer they post a “bundle” which is then distributed.

containing:

- Unique job_ID.
- Public key of uploader.
- Interpeer virtual currency address.
- Configuration file - states how the script will run.
- Interpeer scripts
- mutable data
- static data

### 6.2 peer-groups
Peer-to-peer networks have a common problem; how do you trust peers to complete their task correctly?

In a peer-group all the peers must agree at key points the current results of the job, it is in their interest to agree to get paid and peers can't just copy the answer of another peer (to get paid without working) as they only share a hash of the result (with their userID as a salt). This proves it's their own solution and that they match.

Because of how peer-groups are selected it means that the chance of colluding peers abusing the system is **(colluding peers / total peers)^N**. If, for example 50% of the network colludes, and there are only 3 peers in a peer-group, then there is a 1/8 chance of it being completely compromised.

If there is an disagreement then ratings of peers are used as well as number of peers on each side of the disagreement to settle which side is correct.

#### 6.2.1 Inter-peer-group communication
Communication is for synchronization to achieve agreement, so each message is signed, and only hashes of the data are needed.

When a peer is leaving the peer-group then they will hand-over the job to another eligible peer.

##### 6.2.1.1 multi-casting
One peer is selected to collate the data and send it back to every peer in the group. This saves bandwidth.

For example a 17 member peer-group sending all peers a message with a reply:
- **direct:** 544 messages = (16×2)×17
- **multicast:** 32 messages = 16×2

The other point is with direct messages is that the other peers wouldn't know what each other said, so would need an extra step after.

##### 6.2.1.2 onion routing
Peers would not need to know the other peers true identity, only that they are eligible. So all traffic could be onion routed without much added complexity.

Because each packet would be encrypted and the number of hops could not be ascertained from the packet, it would also add "plausible deniability" even with 0 hops, as it couldn't be proven that the destination peer of a packet was the final destination.

This would protect important jobs that need security against DDoS attack and peers that want security. As either a job or the peer could specify they needed X hops.

### 6.3 Interpeer scripting
The bundles that uploaders add to the network contain scripts to be run by the seeders which is where all of the work is done to create resources such as Interpeer sites.

The Interpeer scripting language will be a fork of PHP, this is for a number of reasons:
- PHP is fairly secure and tested.
- Most of the time the scripts will be serving web pages.
- Only small modifications will be needed, e.g. to account for the difference in file storage.

### 6.4 jobs
Each time a bundle is uploaded onto Interpeer it has scripts to be run by seeders and an associated configuration file that specifies how long it will run on a peer-group before the job is complete. If it is a continuing operation peers will be swapped in one at a time.

An example of a common job would be hosting an interpeer-site; using 5 peers for example, with each peer running it for 30 minutes, then every 6 minutes one peer would leave (and another join) so all the peers would verify consensus at this point to get paid.

A job would be in essence renting out processing power, memory and storage.

All jobs are limited by the processing power and memory that can be used by one job slot. If the job exceeds this, it fails (in a way that the script can catch the error and deal with it). If a script needs more than the maximum, it uses more job slots.

#### 6.4.1 segmented jobs
some jobs have too much data, and it can be split into shards. For example the data listing all jobs or listing all peers. In these cases a job can be split into sub jobs, where the code is the same for all, but the data that it's referencing is segmented.

The only difference would be during synchronisation, peers would come to consensus within one segment.

#### 6.4.2 public jobs
Not all jobs will be paid. Some are needed for the network to function as a whole.

##### 6.4.2.1 global job - vote-chain and job allocation
Each peer keeps copy of the vote-chain. This is needed to validate state data.

With each cycle (defined by the vote-chain block rate) every peer uses the hash of the lasted signed block to determine if they are the "root peers" to sign the next block. But to stop them being selected to be DDoS attacked, they don't publicise this until they have generated and shared the next block.

As each peer is running the global job, they calculate which jobs they are doing, then request to join them (with proof that they are eligible).

This job will be paid by minting InterCoin. Which will also provide a consistent flow of InterCoins into the system and reward peers for taking part.

##### 6.4.2.2 unpaid jobs - DNS and IP-lookup
New seeders show commitment by doing unpaid work to get a peer-rating so they are more likely to win paid jobs.

Because a peer can prove their own identity using self-signing of their peer ID; no security is needed for translating a peer ID into an IP address. But it would be wasteful for all peers to keep a complete peer list up to date, so one peer-group is tasked with handling a list of peer IP addresses.

Because DNS is only turning a human-readable domain name into a set of IP addresses for hosts, this will be handled by this peer-group too.

Each member of the peer-group can answer DNS or IP-lookup requests without contacting the other peers in the group because each entry has a validity period and is signed by other peers that agree. Any peer can sign it, so when a peer asks for an IP-lookup, if it's valid it will reply with a signature to add.

#### 6.4.3 job scheduling
In each cycle a peer gets tickets for completing jobs successfully, they can only request that many paid jobs in the next cycle. If they want to increase the amount of jobs, say they have no tickets for example, they can do unpaid work (there is a limit to how much they can request based on how many tickets they have).

If peers try to turn down jobs by not responding, they receive a negative rating. This cancels a previous ticket.

All peers must have do things at exactly the same time, as many functions (like peer-group handshakes) need it. So when a peer first connects, it will negotiate an Interpeer global time. It will keep this as a delta of it's system clock and update it at each reconnect.

If a peer has bad timing it will fail the handshake to join a peer-group, then after a few bad ratings they will be unable to find work.

#### 6.4.4 job hand-over
With a continuing task (such as serving an interpeer-site) it is broken into jobs of a certain length for each peer; each peer finishes a job at a different time interval to stagger hand-over. at the end of each job the peer must transfer the job to the next peer to get rewarded.

Peers will join a peer-group by doing the necessary handshake ahead of time, so hand-over events happen exactly on schedule.

Because peer-groups are contacted ahead of time, and hand-overs are staggered, all that is normally needed is 1 old peer to transfer the memory of the task to 1 new peer.

### 6.5 initialising
When first connecting to the Interpeer network, a peer needs certain information (for example the IP address of other peers). A bootstrap request can be answered by any peer, and when no peers are known [interpeer.net](http://www.interpeer.net) can be used or the Interpeer IRC chat room for redundancy.

A bootstrap reply has this information:

- list of peers running the root job.
- Synchronise Interpeer time.
- vote-chain height.

#### 6.5.1 registering a peer
Many attacks on peer-to-peer networks involve creating many fake nodes, either to DDoS attack the system or game the rating system / selection process.

The root-peers record the number of jobs completed in total and in the last interval for each peer, which is used to prioritise mature peers when allocating jobs or during disagreements. This creates a "joining cost" as new peers won't be allocated paid / important jobs making it less worthwhile to create fake peers.

### 6.6 peer rating system
Every time a peer finishes a job in a peer-group, they review each others work. If the job is completed with no disagreement then they all claim a positive rating that they report themselves with proof.

If a peer “lies” about something it is provable, as each message is signed so it can be quoted later. For certain malicious actions, the peer account gets terminated, any accrued funds are lost, and they must go through the joining process again paying the “joining cost”.

The rating system records more than one metric, as otherwise malicious peers could earn ratings by one way to 'spend' them doing a malicious activity. So there are a few different rating types to guard against different attack types:

- Connection reliability – to protect against selecting jobs by dropping connection.
- Job finished in agreement – to protect against collusion and job poisoning.

Over time as peers take part in different peer-groups they might get marked by bad ratings as collateral damage, but if they are normally being honest, then their ratio of good ratings to bad will stay positive. But if they are a malicious peer, it will not take long to accrue enough negative ratings to fall bellow a threshold so they are not assigned jobs, meaning they must pay the “joining cost” again.

When a rating is first given, it is not final, later on (when the delta-block gets converted to a checkpoint-block) the rating is updated. This is because there are 2 stages of storing a rating, first with a “proof” then later only the value. So if disagree with a malicious peer, then later they get banned, the negativing review gets removed from your rating.

### 6.7 vote-chain
Most of the Interpeer network systems work more like [bitTorrent](http://www.bittorrent.com); that not all of the peers are doing the same thing, jobs are run on small groups of peers. But certain data needs to be agreed by the network as a whole which is where the vote-chain is used.

An interesting difference from [Bitcoin](http://www.bitcoin.org) is that all the data doesn't need to be stored on the block-chain directly, only a proof of the data accuracy.

Differences with Bitcoin block-chain:
- There will be no data stored on the vote-chain. Instead for each set of data it will have: a hash of the data, a hash of the list of peers and their signatures that verify it.
- the root-group will sign each new block and state the peers that are in the next root-group that can sign the next block.

Because no data is stored on the vote-chain, but instead is referenced, it is trivial to implement checkpoints and delta-blocks. Also the vote-chain would be at least 100 times smaller than Bitcoin. And because of checkpoints, new client software could start synchronising at an arbitrary hard-coded checkpoint instead of the genesis block.

Peers have the option to only download the 2 last checkpoint blocks and verify the hash against [interpeer.net](http://interpeer.net) during initialisation if they choose, this would be a serious advantage to seeders as they wouldn't need to download the whole vote-chain and verify it to start working. Not much trust is needed for seeders to use this method, as at this point they have not yet done any work.

The vote-chain will be used to reference and verify:

- InterCoin currency ledger.
- Interpeer configuration settings.
- Interpeer domain name data shards.
- Peer details (public key, ratings).
- Job allocations.

#### 6.7.1 InterCoin
a currency ledger will be referenced from the vote-chain and will be where payments for work are sent.

Some features of the network are done for the good of the network as a whole, and are not paid by uploaders. Although most of this is covered by unpaid jobs, a few examples can't be done this way ([interpeer.net](http://interpeer.net) hosting), so there will be a small tax on InterCoin transactions, this will also mitigate transaction spam.

Because Interpeer functions by having micro-transactions for each job, no tax will be applied to money earned from jobs.

##### 6.7.1.1 deposit
Because one of the possible malicious aims is to take money out when it hasn't been properly earned, all earned money will only retrievable after it has matured and the peer has sufficient rating.

So malicious peers would either be forced to do work correctly to get a sufficiently high rating or forgo any payment.

### 6.8 peer consensus
One huge problem with the Internet as it functions now, is that updating the protocol is nearly impossible, as all parties must change. This can been seen with how long it is taking to make a trivial change like IPv6. Interpeer fixes this problem.

All Interpeer settings are referenced on the vote-chain. A “change request” with a scheduled “valid from” time can be added detailing the changes to the settings and allowing peers with over a certain rating to vote against it, if a high enough percentage vote against the changes, they are not applied. But otherwise the change will become valid at the set time so they will be applied to every peer simultaneously.

This means updating or changing settings would be possible, and there is no trust given to the core developers, as Interpeer will be open source, so if people notice a problem with an nefarious update they can spread the information and all vote against it.

One setting is “minimum vote time-frame” which would mean that an update could not happen faster than that. This does sacrifice quick patching of problems in favour of peer consensus, as otherwise a nefarious developer could post a change request happening straight away without giving time to vote.

### 6.9 data storage
All data is handled similar to [IPFS](http://www.ipfs.com)'s content-addressed storage model, but adds mutable files. When a script has associated data, it stores the necessary content references (in the job memory). So when a associated content-block in storage gets changed, it has a new hash, so therefore new reference.

Each content-block must manage a list of scripts that reference it. If it is no longer referenced, then the peers will discard it. When a script changes a content-block, it sends the data to known peers storing that content-block.
Any orphaned content-blocks will be deleted from peers when it is necessary to gain more space.

## 7. Migration
With something as enormous and interconnected as the Internet any attempt to replace it has to fight the “network effect”. To mitigate this Interpeer will be backwards compatible and migration will be seamless. All Interpeer links will work transparently for vanilla browsers.

Due to the Interpeer design, any node that is currently hosting an interpeer-site will respond to normal HTTP requests on a certain port; the only problem is how do you discover which socket is hosting the interpeer-site you are looking for without being a member of Interpeer? This is solved in 2 ways.

### 7.1 redirection
[Interpeer.net](http://www.interpeer.net) will act as a redirection service for vanilla browsers so any interpeer-site can be linked to using the Interpeer domain name, for example the “wikipedia” Interpeer domain would be: <interpeer.net/wikipedia> - this link would redirect to the index page of the interpeer-site and the redirection would point to the socket that is currently hosting the content on Interpeer.

Also links could point to any other page of the interpeer-site, meaning search engines could index Interpeer as a normal website, transparently.

When someone views a interpeer-site this way, a warning bar would be visible asking them to install the Interpeer plug-in for their safety. This would probably be done using an iframe to do the redirection.

If a user stays on one interpeer-site longer than the peer they are using is tasked the job of hosting it, they would begin getting 404 pages. The fix could be java-script that detects the lack of a plug-in and handles page changes by asking [interpeer.net](http://interpeer.net).

### 7.2 plug-in
The plug-in will detect URL's in the formats: "interpeer.net/example" , "example.peer", "example.ipn" or "ipn://example" and then fetch the page via the Interpeer network.

Due to the way the privacy features of Interpeer work, a vanilla browser would be trusting that the peer sent valid data, which is rather dangerous. So a small plug-in for each browser would be essential.

The plug-in would handle DNS requests to the Interpeer network, download the page from multiple peers comparing the result, expiry time of DNS information, and reporting malicious peers.

## 8. Mitigate attacks
As with all systems, there will be people that try to damage or take advantage of it. So we must know and protect against possible attacks.

### 8.1 creating fake peers
An attacker would pretend to be many peers.
The cost for the attacker to create many peers would be the “joining cost” which would make it prohibitively 'expensive' to make large numbers of fake peers.

The advantage would only be significant if they could generate a very large amount, as the peer-group system would mean they would need 50% of the total number of peers on the network to get a 1/8 change of corrupting a low security (3 peer) group. And in most situations they would need to completely corrupt a peer-group to get any ability to subvert the functions of the Interpeer network or an individual script of Interpeer.

### 8.2 colluding peers
Peers work together to cheat the network.
These malicious peers could work normally except when they are in a peer-group with other colluding peers. But to completely corrupt a peer-group would be statistically almost impossible even if a majority of the network colluded.

Another option would be to get 2 peers colluding against the honest peers in a peer-group, which is easier to do. This would often stopped by the peer-rating and “joining cost”.

### 8.3 51% attack
This attack is only valid against the block-chain part of Interpeer. Interpeer has central development, so any 51% attack could just be rolled back by a new delta-block authored by the admin if it was needed. making the effect temporary, so therefore not worth doing as there is a delay before funds are allowed to be withdrawn.

To protect against malicious admin, Interpeer will be open source and all admin changes to the block-chain will not be instant; instead they will be scheduled and all peers have that time to decide to vote against it, if a pre-set percentage vote against it, the change will not be applied.

### 8.4 man-in-the-middle attack
The seeder is hosting the interpeer-site to the visitor, so in a way it's even better than MITM; the options for the attacker are stealing data or modifying the data.

The plug-in would verify that the data is accurate as all members of the peer-group must agree and if they used [interpeer.net](http://www.interpeer.net) as a proxy there would be a clear warning of the dangers of not using the plug-in.

The issue of stealing data is bigger, as the seeder is acting as your web-host, but they are just an anonymous peer. This issue is left to the seeders to deal with, the problem can be fixed in a number of ways; for example using Java-script to decrypt any sensitive data on the browser of the visitor, and then storing the data encrypted on Interpeer. This would make end-to-end encrypted, thus secure from the malicious seeders.

### 8.5 splitting the network
If you can stop a peer from connecting to other peers, thus segmenting the network, an attacker may be able to do “double spends”.

This is rather difficult to achieve as each peer is connecting to many other peers continuously, and as jobs get assigned to new peer-groups the connections change. If a peer couldn't connect to form a new peer-group it would detect a connection problem to the network.

### 8.6 malicious developer
Because development will be centralised, one attack vector would be to hide malicious code in an update. But as peers get to vote against an update and all the code is open source, it would be almost impossible to get an update approved with malicious intent.

### 8.7 off-line Byzantine general
Although the Byzantine generals problem can be solved by signing messages, the problem assumes all the generals will be accessible. As peers will sometimes lose connection and drop off-line, Interpeer must be able to deal with this. The problem comes with malicious peers not replying on purpose or not redirecting messages from certain target peers to accuse them of being off-line.

This problem is solved by contacting peers directly if a peer tasked with multi-casting is accusing a peer of being off-line, but then you still have the problem of the peer being on-line to one and not replying to the other peer.

### 8.8 DDoS attack
By flooding all peers that are working on a job, it would be possible to temporarily degrade the performance of that interpeer site.

When a job is added by an uploader they can choose how many peers are used, so for critical sites, more peers could be used to mitigate against this.

### 8.9 fake jobs
An attacker would create a job that is hard for a normal peer to solve, but precomputed for the attacker.

This would not gain any real advantage, as the attacker would rarely get their own job, also jobs run for set time-frames. So gaming the block voting system using this would be ineffective.

### 8.10 parrot peer
The malicious peer would during peer-group synchronisation wait for another peer to give their answer first, then agree with it. This would mean that they didn't have to do any work, but would get paid as if they had.

This is solved by all peers in a peer-group first needing to share a hash+salt of the answer, then after answer+salt. So that you can prove they formed their own answer.

## 9. Development plan
Once it is agreed that Interpeer will function, then the plan is to use Bitcoin's business model as a guide; if a technology is good enough, it practically makes itself, as other developers join and make a community.

Remuneration for the core developers is the same as Bitcoin too, if the idea works and is used, the early adopters will be highly rewarded. So like share holders, we do well if Interpeer does well.

## 10. Similar projects
Currently there is no system that can host dynamic web2.0 sites in a peer-to-peer way like Interpeer proposes. So these can not host [wikipedia.org](http://wikipedia.org) for example.

- [Zeronet](http://www.Zeronet.io)
- [Morphis](http://www.morph.is)
- [webTorrent](http://www.webtorrent.io)
- [Project maelstrom](http://www.project-maelstrom.bittorrent.com)
- [MegaNet](https://www.torrentfreak.com/kim-dotcoms-meganet-preps-jan-2016-crowdfunding-campaign-150610/)
- [IPFS](https://www.ipfs.io/)
- [Decent](http://www.decent.ch/)
- [Freenet](http://www.freenetproject.org/)

### 10.1 Alternatives
Instead of a P2P network to share the websites, these projects are conserned with hiding normal server-client style websites.

- [TOR](http://www.torproject.org) - hides normal websites
- [Riffle](https://people.csail.mit.edu/devadas/pubs/riffle.pdf)

## 11. Future research
There are a few parts that fall outside of the scope of this white paper, but could be added to Interpeer later. For example:

- peer-to-peer search using DHT.
- more efficient computation using compilation instead of interpreting for interpeer scripts that are computationally focused.
- Add-ons; 3rd party developed engine that Interpeer calls to handle scripts in certain formats. It would be added to Interpeer by a “change request” if there was demand.
- registering a TLD to redirect to Interpeer, for example: '.peer' or '.ipn'.

## 12. Acknowledgements
Without standing on the shoulders of giants it would not be possible to dare such ambitious goals; [Bitcoin](http://www.bitcoin.org) and [bitTorrent](http://www.bittorrent.com) opened the way for trust-less collaboration on big scales, thank you.

## 13. References

- [IPFS](http://www.ipfs.com) - interesting system to have content addressed peer-to-peer storage.
- [Bitcoin](http://www.bitcoin.org) - the block-chain technology is pivotal to the network working together.
