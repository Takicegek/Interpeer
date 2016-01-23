# INTERPEER - Trust-less peer-to-peer resource marketplace.
Jan 2016 - draft 8 - Rory Renton (<smellymoo@gmail.com>)

## 0. Abstract
I propose Interpeer as a complete replacement for the world-wide-web; a system to distribute dynamic web-pages. Also as a trust-less marketplace to exchange resources such as processing and storage.

Interpeer is a peer-to-peer distributed network where people are incentivised to share unused system resources via a virtual currency; these system resources would be computational power, storage and bandwidth; which are then combined in a trust-less peer-to-peer way to make all the systems needed to make a functional replacement for the world-wide-web.

## 1. Introduction
in essence Interpeer does for the world-wide-web what [bitTorrent](www.bittorrent.com) does for file-sharing; each interpeer-site is hosted by other peers, which makes it very difficult to destroy, also authors can upload sites anonymously to the network. But unlike bitTorrent, the site is not static data; so to continue the analogy, it would be equivalent of a torrent that other users could edit, making it possible for interpeer-sites to have dynamic content like [wikipedia.org](www.wikipedia.org) with only very slight changes from the standard website design method.

Interpeer would function as a anonymous peer-to-peer marketplace by connecting people that want to get paid for the unused system resources of their computer with people that want to author censorship free websites, store large amounts of data or do massive computation tasks.

Currently websites are hosted on a physical server that is located by its domain name. An interpeer-site is hosted by many peers which are paid for the service they provide via a virtual currency. In this model any user can install the program and get paid without doing anything.

The advantage for website hosting is easy to see if you look at the disadvantages of the current internet client-server model: the server is a single point of failure, low anonymity when creating a website, each visitor downloads from the server not other visitors which is wasteful and finally there is central control over domain name lookup and ISPs control access which limits freedom of speech.

## 2. Interpeer key innovations
Interpeer introduces large innovations to peer-to-peer technology. The main ones are:

### 2.1 vote consensus
In [Bitcoin](www.bitcoin.org) a gargantuan amount of processing power is used on a useless proof-of-work to reach consensus thus securing the network, but Interpeer uses a voting system to achieve the same security.

Each time a peer completes a job, they get one token to vote on the next block. Because peers can't choose jobs, it is nearly impossible to game the system.

### 2.2 web 2.0
All other attempts at a peer-to-peer world-wide-web don't allow users to change the site, only the authors, so modern sites using web 2.0 like [facebook.com](www.facebook.com) or [wikipedia.org](www.wikipedia.org) can not be implemented natively.

### 2.3 jobs
Interpeer adds a new concept called "jobs", which is explained later in depth. But to summarise it is the ability for a small group of peers to work on one task for a set time period then hand it over to another group of peers to continue.

The reason why this is so valuable, is it allows the network to perform a huge variety of tasks in parallel.

A good way of imaging it is think of how [bitTorrent](www.bittorrent.com) shares files, each separate file is seeded by a group of peers on the network, not the whole network. The difference is Interpeer is running scripts on these peers rather than sharing static data.

### 2.4 user migration
Interpeer sites will be accessible by users using vanilla browsers, this is key to getting Interpeer widely adopted. This is acheived by using [interpeer.net](interpeer.net) to redirect requests to peers that are currently handling the site in question.

### 2.5 website migration
Because Interpeer uses a modified version of PHP to make interpeer-scripts, migrating from PHP websites to Interpeer would often be trivial.

But because the peers hosting the interpeer-site or storing related data would be able to read any data that is unencrypted some security features would need to be implemented in browser (eg: JavaScript). For example end-to-end encryption or hash generation.

## 3. Example uses
If [wikipedia.org](www.wikipedia.org) or [wikileaks.org](www.wikileaks.org) used Interpeer, they would see huge advantages:

- content is addressed individually, so anyone viewing a page could serve it to others wanting to view it (like [bitTorrent](www.bittorrent.com) or [IPFS](ipfs.com)). Meaning Wikipedia would not be paying for much of the traffic and users that are close would get a speed advantage.
- donations to keep it running would go directly to the hosting account. Meaning it could run autonomously. And donations would be anonymous.
- If the original authors got “silenced” the interpeer-site would continue to exist and be user-editable for as it was funded.

A few other examples of uses for Interpeer:

- anonymous bullet-proof web-hosting.
- getting paid for your spare computer resources.
- immortal sites that continue from donations or payments without author involvement.
- visit Interpeer sites anonymously.
- web2.0 will function unlike all other p2p alternatives.
- massive computation tasks.
- storage with distributed multiple redundant copies.
- onion routing proxy service similar to TOR.
- smart contracts.
- dead-man-switch scripts.

## 4. Background
The internet is more than 30 years old now; we have come a long way since it's inception:
> “I think there is a world market for maybe five computers.” - 1943 IBM president

So far improvements have been stacked upon the older technology, leaving the antiquated parts in place. Interpeer only uses UDP/IP, everything else is built on cutting edge ideas of trust-less distributed computing.

New inventions come mainly from taking pre-existing technologies and combining them. So the easiest way to explain Interpeer is by showing you what has been sourced and why.

##### File storage :- [bitTorrent](www.bittorrent.com) / [IPFS](www.ipfs.com) / Storq / Maidsafe:
Share files peer-to-peer creating one shared storage system with distributed redundancy. Which makes it very difficult to lose or destroy files. In some of these technologies clients pay peers to secure files. Giving an incentive to do it, at a lower price than commercial options.

##### Consensus :- [Bitcoin](www.bitcoin.org) / Etherium / Namecoin:
Trust-less currency and smart contracts using blockchain. Without having a way to remunerate peers for taking part Interpeer would not be possible, also Namecoin demonstrates that domain registration can be done without the need of a central authority.

##### Hosting :- Cloud hosting:
A server no longer is one fixed computer, but can  share the job between many.

##### Massive computation :- [Boinc](boinc.berkeley.edu):
Distributed computation, using the spare resources of many computers and combing them.

### 4.1 flat power structure
Information is power. Since the dawn of humanity power has been hierarchical; with only very few at the top and everyone else at the bottom. Even the first attempt at a world-wide-web; which was supposed to liberate information didn't really change that; with domain registration centralised, the index (search engines) centralised and moderated, DNS centralised, and the ISPs as the gate keepers.

When peer-to-peer technology was invented (like [bitTorrent](www.bittorrent.com) and [Bitcoin](www.bitcoin.org)) it changed everything, unlike all previous power structures (pyramid shaped) it was flat; fair; peer-to-peer; people share and are equal. Although the importance of this breakthrough has been missed by most, it's the most important historical event in our life times; finally we have solved the unsolvable; trust without hierarchy. There is no longer a need for a governing body; people can work together as equals only using clever math to govern the exchanges.

But this is only the start; a test case, to fully appreciate the advantage of this we need a new model of the internet; a fair one, where information is safe from censorship and there are no single points of failure or gatekeepers. Interpeer is designed to give people freedom of speech, so we can finally let information be free in every sense of the word, uncontrollable and uncensored for all!

## 5. Design
> “Any sufficiently advanced technology is indistinguishable from magic.” - Arthur C Clarke

Interpeer has 3 types of users with different goals:

- uploader – pay to host websites / process large computations / store data.
- seeder – get paid to run the Interpeer client.
- visitor – use [interpeer.net](www.interpeer.net) or install a plug-in to their browser to visit .peer sites on Interpeer.

When an uploader submits anything to Interpeer they post a “bundle” which is distributed on the network in a similar way to [bitTorrent](www.bittorrent.com), but unlike it the bundle is dynamic; the scripts can change the data. Peers works together by splitting a task into “jobs” of a fixed amount of time / processing cycles.

A bundle is group of the following:

- Unique job_ID.
- Public key of uploader.
- Interpeer virtual currency address.
- Configuration file - states how the script will run.
- Interpeer scripts and mutable data.

Interpeer jobs are trust-less, unlike [bitTorrent](www.bittorrent.com) because peers can't choose what job they are doing. Each peer sets how many jobs they can do concurrently then is only eligible to do a sudo-random selection of jobs of that amount. They also can't turn down a job without quickly loosing their rating and being blocked.

### 5.1 peer-groups
Interpeer has many different functions, but all of them have a common problem, how do you trust peers to complete a job correctly?

In a peer-group all the peers must agree on the results of a function to proceed, it is in their interest to agree as they get paid, also if they don't agree the malicious peers get negative rating which leads to them getting banned, this is explained later.

Because of how peer-group are selected it means that the chance of colluding peers abusing the system is **(colluding peers / total peers)^N**. If, for example 50% of the network colludes, and there are only 3 peers in a peer-group, then there is a 1/8 chance of it being completely compromised.

If there is an disagreement and the peers in the minority agree, then it's detected as an tie meaning an attack is happening. To decide the outcome of an attack, ratings of peers are used as well as number of peers on each side of the disagreement. If no resolution is reached, the handshake / job fails.

### 5.1.1 handshake process
The initial handshake process is used to share contact information of other peers in the group and decide if backup peers are needed.

1. peer_1 sends an IP-lookup for all possible peers of the peer-group.
  - If any peers are behind a firewall they hole-punch to peer_1.
2. peer_1 multi-casts the IP-lookup (to all of the peer-group).
  - if peer_1 is off-line peer_2 does this instead, etc.
3. all peers send a job-confirmation to peer_1.
4. peer_1 multi-casts the job-confirmation (to all of the peer-group).
5. any peers missing information they contact the peers directly for it.
6. the job has started. (backup peers decide for themselves if they are needed).

### 5.1.2 Inter-peer-group communication
Communication is for synchronization to achieve agreement, so each message is signed, and only hashes of the data are needed, also one peer is selected to collate the data and send it back to every peer in the group.

<TODO: insert diagram peer-group communication to agree>

When a peer is leaving the peer-group then they will hand-over the job to another eligible peer.

<TODO: insert diagram job hand-over>

### 5.2 DNS and IP-lookup
Because a peer can prove their own identity using self-signing of their peer ID; no security is needed for translating a peer ID into an IP address. But it would be wasteful for all peers to keep a complete peer list up to date, so one peer-group is tasked with handling a list of peer IP addresses.

Because DNS is only turning a human-readable domain name into a set of IP addresses for hosts, this will be handled by this peer-group too. The domain name records are stored on the block-chain, so everyone has a copy.

This task will actually be a normal Interpeer script, but will just be paid with the communal account. To deal with the volume of requests and security needed, the job will have a long job interval and large peer-group.

Each member of the peer-group can answer DNS or IP-lookup requests without contacting the other peers in the group because each entry has a validity period and is then signed by other peers that agree. Any peer can sign it, so when a peer asks for an IP-lookup, if it's valid it will reply with a signature to add. If it is invalid the peer will get a bounty for reporting it.

### 5.3 Interpeer scripting
The bundles that uploaders add to the network contain scripts to be run by the seeders which is where all of the work is done to create resources such as Interpeer sites.

The Interpeer scripting language will be a fork of PHP, this is for a number of reasons:
PHP is already fairly secure and tested.
Most of the time the scripts will be serving web pages.
Only small modifications will be needed, eg to account for the difference in file storage.

### 5.4 jobs
Each time an uploader adds a script to be run by seeders, it has an associated configuration file that specifies how long it will run on a peer-group before the job is complete. If it is a continuing operation peers will be swapped in one at a time.

An example of a common job would be hosting a interpeer-site; using 3 peers, each peer running it for 30 minutes, and every 10 minutes one peer would leave and another join. So every 10 minutes all the peers would verify consensus then get paid.

All jobs are limited by the global maximum of processing power and memory that can be used by one job slot. If a the job exceeds this, it fails. If a interpeer script needs more than the maximum, it uses more job slots.

### 5.4.1 job scheduling
Jobs aren't assigned by a 3rd party on Interpeer, each peer can calculate when it is their turn to do a job. Each peer specifies how many jobs they can do concurrently, then requests that many “job slots” which are globally agreed and maintained by the IP-lookup peer-group.

The “job slots” are like raffle tickets; each time a peer in a peer-group must relinquish it's job, the new peer is defined by which job slot has a hash of [job_id + hand-over time] that matches the job slot id.

If peers try to turn down jobs by not responding, they will get banned once they have enough negative ratings. Also a peer can only increase how many job slots they are requesting by 1 each interval (to stop peers claiming more than they can process to disrupt the network).

### 5.4.2 job hand-over
With a continuing task (such as serving an interpeer-site) it is broken into jobs of a certain length for each peer; each peer finishes a job at a different time interval to stagger hand-over. at the end of each job the peer must contact the replacement peer to get rewarded (with virtual currency and positive ratings).

A peer has meta-data on all existing jobs which is stored on the blockchain, and each job has an ID and scheduling information. So peers can calculate when a job is scheduled for them and prepare a peer-group by doing the necessary handshake ahead of time.

Because job assignment is publicly calculable and peer-groups are prepared ahead of time, it is trivial for the peer-group that has finished it's job to contact the replacement peer-group, then all that is needed is the memory of the task to be transferred.

### 5.5 initial boot-strapping
When first connecting to the Interpeer network, a peer needs certain information (for example the IP address of other peers). A bootstrap request can be answered by any peer, and when no peers are known [interpeer.net](www.interpeer.net) can be used or the Interpeer IRC chat room for redundancy.

A bootstrap reply has this information:

- list of some other peers.
- Synchronise Interpeer time.
- blockchain height.

### 5.6 registering a peer
Many attacks on peer-to-peer networks involve creating many fake nodes, either to dos attack the system or game the rating system / selection process. In Interpeer, when you first join you will need to do a proof of work later refereed to as the “joining cost” which makes it less worthwhile to create fake peers.

Also during the “joining period” the abilities of your computer will be measured by the client software to get metrics of: bandwidth, processing power and memory available.

### 5.7 peer rating system
Every time a peer finishes a job with other peers in a peer-group, they review each others work. If the job is completed with no disagreement then they all claim a positive rating that they report themselves with proof. A review is weighted by which peer gives it, a peer with a high rating is more valuable.

If a peer “lies” about something it is provable, as each message is signed so it can be quoted later, so if a peer colludes with another, then other peers gets rewarded for leaving a negative rating with proof. For certain malicious actions, the peer account gets terminated, any accrued funds are lost, and they must go through the joining process again paying the “joining cost”.

The rating system records more than one metric, as otherwise malicious peers could earn ratings by one way to 'spend' them doing a malicious activity. So there are a few different rating types to guard against different attack types:

- Connection reliability – to protect against selecting jobs by dropping connection.
- Job finished in agreement – to protect against collusion and job poisoning.

Over time as peers take part in different peer-groups they might get marked by bad ratings as collateral damage, but if they are normally being honest, then their ratio of good ratings to bad will stay positive. But if they are a malicious peer, it will not take long to accrue enough negative ratings to fall bellow a threshold and be blocked, meaning they must pay the “joining cost” again.

When a rating is first given, it is not final, later on (when the delta-block gets converted to a checkpoint-block) the rating is updated. This is because there are 2 stages of storing a rating, first with a “proof” then later only the value. So if disagree with a malicious peer, then later they get banned, the negativing review gets removed from your rating.

### 5.8 tax
Some features of the network are done for the good of the network as a whole, and are not paid by uploaders, these jobs will be paid by the public account. To raise money for that account a small tax is applied to all payments from uploaders.

Not all network jobs will be paid by tax, some will mint the currency, like Bitcoin “mining”. Because Interpeer functions by having micro-transactions for each job, transaction fees for miners will also be minted for jobs. But normal users pay transaction fees to stop transaction spam.

### 5.9 vote block-chain
Most of the Interpeer network systems work more like [bitTorrent](www.bittorrent.com); that not all of the peers are doing the same thing, jobs are run on small groups of peers. But certain data needs to be agreed by the network as a whole which is where the blockchain is used.

Taking the Bitcoin blockchain idea as a way to have trust-less shared ledger is a good solution, but there will be a few big differences:
- Permanent storage of all data is not needed, it will be using checkpoints that collate all the still required data.
- proof-of-work is not needed, instead each job a completed in the previous interval gives peers a vote to which block is valid.

An example: each time a user gets a rating, at first it must be proven, so it shows a message they sent that disagrees with a peer-group consensus for example. But once it has been accepted by the network and added to a block which is buried under other blocks, so is verified, the proof of the rating no longer matters so is cropped.

So every N blocks will be a checkpoint-block and in-between them are delta-blocks. Each checkpoint-block is chained to all previous ones. When a client joins they only need to download and verify all the checkpoints-blocks up until the last one, and only need to store the last checkpoint-block.

Peers have the option to only download the 2 last checkpoint blocks and verify the hash against [interpeer.net](www.interpeer.net) during initialisation if they choose, this would be a serious advantage to seeders as they wouldn't need to download the whole blockchain and verify it to start working. Not much trust is needed for seeders to use this method, as at this point they have not done any work yet.

The blockchain will be used to store:

- the currency ledger.
- Interpeer configuration settings.
- multi-hashes of Interpeer domain name data.
- peer details (public key, 'joining cost' proof-of-work, ratings).

Another interesting difference from [Bitcoin](www.bitcoin.org) is that all the data doesn't need to be stored on the blockchain directly, only a proof of the data accuracy. So a multi-hash of distributed data would suffice, meaning the data would be split into shards, each getting a hash, then all the hashes are stored on the blockchain for peers to verify. One example of this is storing the Interpeer domain names, only certain peers would be tasked with storing the shards of the domain name data and serving the information to visitors.

### 5.10 peer consensus
One huge problem with the world-wide-web as it functions now, is that updating the protocol is nearly impossible, as all parties must change. This can been seen with how long it is taking to make a trivial change like IP6. Interpeer fixes this problem.

All Interpeer settings are contained on the blockchain. A “change request” with a scheduled “valid from” time can be added to the blockchain detailing the changes to the settings and allowing peers with over a certain rating to vote against it, if a high enough percentage vote against the changes, they are not applied. But otherwise the change will become valid at the set time so they will be applied to every peer simultaneously.

This means updating or changing settings would be possible, and there is no trust given to the core developers, as Interpeer will be open source, so if people notice a problem with an nefarious update they can spread the information and all vote against it.

One setting is “minimum vote time-frame” which would mean that an update could not happen faster than that. This does sacrifice quick patching of problems in favor of peer consensus, as otherwise a nefarious developer could post a change request happening straight away without giving time vote.

### 5.11 data storage
All data is handled similar to [IPFS](ipfs.com)'s content-addressed storage model, but adds mutable files. When a script has associated data, it stores the necessary content references (in the job memory). So when a associated content-block in storage gets changed, it has a new hash, so therefore new reference.

Each content-block must manage a list of scripts that reference it. If it is no longer referenced, then the peers will discard it. When a script changes a content-block, it sends the data to known peers storing that content-block.
Any orphaned content-blocks will be deleted from peers when it is necessary to gain more space.

### 5.12 synchronisation
All peers must have do things at exactly the same time, as many functions (like peer-group handshakes) need it. So when a peer first connects, it will negotiate an Interpeer global time. It will keep this as a delta of it's system clock and update it at each reconnect.

Jobs are not assigned, but are claimed. A peer “knows” when it's their turn to do a job by using it's peer id and a algorithm. So if a peer has bad timing it will fail the handshake to join a peer-group, then after a few bad ratings it will be banned.

### 5.13 deposit
Because one of the possible malicious aims is to take money out when it hasn't been properly earned, all earned money will only retrievable after a certain peer rating threshold.

So malicious peers would either be forced to do work correctly to get a sufficiently high rating or forgo any payment.

## 6. Migration
With something as enormous and interconnected as the Internet any attempt to replace it has to fight the “network effect”. To mitigate this Interpeer will be backwards compatible and migration will be seamless. All Interpeer links will work transparently for vanilla browsers.

Due to the Interpeer design, any node that is currently hosting an interpeer-site will respond to normal HTTP requests on a certain port; the only problem is how do you discover which socket is hosting the interpeer-site you are looking for without being a member of Interpeer? This is solved in 2 ways.

### 6.1 redirection
[Interpeer.net](www.interpeer.net) will act as a redirection service for vanilla browsers so any interpeer-site can be linked to using the Interpeer domain name, for example the “wikipedia” Interpeer domain would be: <interpeer.net/wikipedia> - this link would redirect to the index page of the interpeer-site and the redirection would point to the socket that is currently hosting the content on Interpeer.

Also links could point to any other page of the interpeer-site, meaning search engines could index Interpeer as a normal website, transparently.

When someone views a interpeer-site this way, a warning bar would be visible asking them to install the Interpeer plugin for their safety. This would probably be done using an iframe to do the redirection.

If a user stays on one interpeer-site longer than the peer they are using is tasked the job of hosting it, they would begin getting 404 pages. The fix could be java-script that detects the lack of a plug-in and handles page changes by asking [interpeer.net](interpeer.net).

### 6.2 plug-in
The plug-in will detect URL's in the formats: "interpeer.net/example" , "example.peer", "example.ipn" or "ipn://example" and then fetch the page via the Interpeer network.

Due to the way the privacy features of Interpeer work, a vanilla browser would be trusting that the peer sent valid data, which is rather dangerous. So a small plug-in for each browser would be essential.

The plug-in would handle DNS requests to the Interpeer network, download the page from multiple peers comparing the result, expiry time of DNS information, and reporting malicious peers.

## 7. Mitigate attacks
As with all systems, there will be people that try to damage or take advantage of it. So we must know and protect against possible attacks.

### 7.1 creating fake peers
An attacker would pretend to be many peers.
The cost for the attacker to create many peers would be the “joining cost” which would make it prohibitively 'expensive' to make large numbers of fake peers.

The advantage would only be significant if they could generate a very large amount, as the peer-group system would mean they would need 50% of the total number of peers on the network to get a 1/8 change of corrupting a low security (3 peer) group. And in most situations they would need to completely corrupt a peer-group to get any ability to subvert the functions of the Interpeer network or an individual script of Interpeer.

### 7.2 colluding peers
Peers work together to cheat the network.
These malicious peers could work normally except when they are in a peer-group with other colluding peers. But to completely corrupt a peer-group would be statistically almost impossible even if a majority of the network colluded.

Another option would be to get 2 peers colluding against the honest peers in a peer-group, which is easier to do. This would often stopped by the peer-rating and “joining cost”.

### 7.3 51% attack
This attack is only valid against the blockchain part of Interpeer. Interpeer has central development, so any 51% attack could just be rolled back by a new delta-block authored by the admin if it was needed. making the effect temporary, so therefore not worth doing as there is a delay before funds are allowed to be withdrawn.

To protect against malicious admin, Interpeer will be open source and all admin changes to the blockchain will not be instant; instead they will be scheduled and all peers have that time to decide to vote against it, if a pre-set percentage vote against it, the change will not be applied.

### 7.4 man-in-the-midle attack
The seeder is hosting the interpeer-site to the visitor, so in a way it's even better than MITM; the options for the attacker are stealing data or modifying the data.

The plug-in would verify that the data is accurate as all members of the peer-group must agree and if they used [interpeer.net](www.interpeer.net) as a proxy there would be a clear warning of the dangers of not using the plug-in.

The issue of stealing data is bigger, as the seeder is acting as your web-host, but they are just an anonymous peer. This issue is left to the seeders to deal with, the problem can be fixed in a number of ways; for example using Java-script to decrypt any sensitive data on the browser of the visitor, and then storing the data encrypted on Interpeer. This would make end-to-end encrypted, thus secure from the malicious seeders.

### 7.5 splitting the network
If you can stop a peer from connecting to other peers, thus segmenting the network, an attacker may be able to do “double spends”.

This is rather difficult to achieve as each peer is connecting to many other peers continuously, and as jobs get assigned to new peer-groups the connections change. If a peer couldn't connect to form a new peer-group it would detect a connection problem to the network.

### 7.6 malicious developer
Because development will be centralised, one attack vector would be to hide malicious code in an update. But as peers get to vote against an update and all the code is open source, it would be almost impossible to get an update approved with malicious intent.

### 7.7 off-line Byzantine general
Although the Byzantine generals problem can be solved by signing messages, the problem assumes all the generals will be accessible. As peers will sometimes lose connection and drop off-line, Interpeer must be able to deal with this. The problem comes with malicious peers not replying on purpose or not redirecting messages from certain target peers to accuse them of being off-line.

This problem is solved by contacting peers directly if a peer tasked with multi-casting is accusing a peer of being off-line, but then you still have the problem of the peer being on-line to one and not replying to the other peer.

### 7.8 DOS attack
By flooding all peers that are hosting a site, it would be possible to temporarily degrade the performance of that interpeer site.

When a job is added by an uploader they can choose how many peers are used, so for critical sites, more peers could be used to mitigate against this.

### 7.9 fake jobs
An attacker would create a job that is hard for a normal peer to solve, but precomputed for the attacker.

This would not gain any real advantage, as the attacker would rarely get their own job, also jobs run for set time-frames. So gaming the block voting system using this would be ineffective.

## 8. Development plan
Once it is agreed that Interpeer will function, then the plan is to use Bitcoin's business model as a guide; if a technology is good enough, it practically makes itself, as other developers join and make a community.

Remuneration for the core developers is the same as Bitcoin too, if the idea works and is used, the early adopters will be highly rewarded. And the idea is the core developers will the only ones with access until it is released to the general public, so we can 'mine' the early Interpeer blocks. So like share holders, we do well if Interpeer does well, but unlike shareholders, we don't pay any money for shares instead we must make the system work.

## 9. Alternatives
Currently there is no system that can host dynamic web2.0 sites in a peer-to-peer way.

Here are other similar projects:

- [webTorrent](webtorrent.io) - only hosts static html using [bitTorrent](www.bittorrent.com).
- [Project maelstrom](project-maelstrom.bittorrent.com) - custom browser needed and static sites.
- [Zeronet](Zeronet.io) - sites are only multiple author editable not web2.0.
- [Morphis](morph.is) - static.
- [TOR](www.torproject.org) - only anonymises normal hosts.

So these can not host for example: [wikipedia.org](wikipedia.org) or [facebook.com](facebook.com) because the visitors don't change the data stored.

## 10. Future research
There are a few parts that fall outside of the scope of this white paper, but could be added to Interpeer later. For example:

- peer-to-peer search using DHT.
- Add-ons. One example would be more efficient computation. An add-on would be a program developed by 3rd party developers that Interpeer calls to handle scripts in certain formats. It would be added to Interpeer by a “change request” if there was demand.
- registering a TLD to redirect to Interpeer, for example: '.peer' or '.ipn'.

## 11. Acknowledgements
Without standing on the shoulders of giants it would not be possible to dare such ambitious goals; [Bitcoin](www.bitcoin.org) and [bitTorrent](www.bittorrent.com) opened the way for trust-less collaboration on big scales, thank you.

## 12. References

- [IPFS](ipfs.com) - interesting system to have content addressed peer-to-peer storage.
- [Bitcoin](bitcoin.org) - the blockchain technology is pivotal to the network working together.
