[PRE-WHITEPAPER NOTES]

IDCoin
======

Identity and Reputation Cryptocurrency Coinbase Supporting a Web of Trust

This is an exploratory project for a Bitcoin-like system based in part on ideas found in GPG/PGP with a Degrees of Separation Web of Trust as well as reputation based on txfee's to be paid to miners.

Gathering feedback right now at https://startjoin.com/IDCoin

Bitcointalk Forum: https://bitcointalk.org/index.php?topic=711305.0

Twitter: https://twitter.com/IDCoins

Facebook: https://facebook.com/IDCoins

Freenode: #idcoins

Skype: The_Little_Duke

* 2014-10-12 *

Research continues!  The current thought is to have IDENTITY SERVERS accept PGP keys and send an ecrypted email to the individual to decrypt and click on a link inside to confirm receipt an in return will receive an IDCOIN to their wallet/key ring.

From here, the invididual we be permitted to STAKE additional coins that are meant to be used for REPUTATIONAL EVENTS, which can include signing other peoples keys.

The more coins you accrue in your primary IDCOIN account, the more coins you are permitted to stake.   This is a means of testing/showing MOJO.

A normalized VOTE on a reputation event could be represented by .00000001 - .99999999 as a TXFEE 

To encourage transactions the coins could have a DECAY built such the holders would have to "STAKE OR DIE" so that the new coins being generated would eventually replace those coins that are expiring.

Very simply the IDENTITY SERVER could periodically perform a "PROOF OF IDENTITY" test by sending a new encrypted email to the KEY HOLDER and then reward for ACKNOWLEDGEMENT.

This means that even if an individual let their initial IDCOIN expire and had not staked new coins, the system could replenish the holder at the next POI interval.


*UPDATED*

Our current plan is to use part of crowdsourced funds to pay a BOUNTYSOURCE to the OpenGPG developers to add in support for the Bitcoin like ECC keys called out RFC 6637 - Elliptic Curve Cryptogrpahy in PGP

http://tools.ietf.org/html/rfc6637

Provisionally enabled in:  https://code.google.com/p/gnupg-ecc/

This would provide an instant world wide system to support email encryption using little more than your Bitcoin payment addresses!

Our plan is to spin up a TESTNET implementation within six-months and launch a year from now at a World Wide IDCoins conference where we would create the actual genesis block from all the attendees public keys and have a good old fashioned key-signing party to begin our distributed Web of Trust!

Doing a simultaneous key signing party around the world is VERY possible if out of the TESTNET experience we get a solid base of vetted public keys that we can put into the genesis block.  We have been talking about ways to do that remotely.   There is a level above a Notary Public available in the US & Canada known as a “Medallion Stamp” available at financial institutions that is used as a stronger identity vetting mechanism.  Not that we would require it of course, just looking at ways of doing a higher level of vetting for accepting keys.

We think that by leveraging a membership structure in the Strength in Numbers Foundation we could offer an equivalent of a Digital Notary service whereby the foundation would accept keys at varying levels of trust and in turn could certify individuals that meet various levels of proof of identity status for a Digital Notary Public designation within our Web of Trust

*A Coinbase for Identity and Reputation*

IDCOIN will be designed to be an 80/20 Proof of Stake / Proof of Work based blockchain that will establish both Identity as well as Reputation in a public ledger.

The generation and addition of a GPG/PGP key will suffice as the "proof of work" as well as the "key signing" of other members keys. The system will be designed to award coins based on addition of validated keys, the signing of additional keys to build out the Web of Trust.  By using encrpyted email you set a very high bar when combined with a CAPTCHA like challenge/response system to slow down potential Sybil attacks.

We are essentially creating a new system of record for VERIFIED ECC based GPG & PGP keys.

Reputation will be leveraged through transactions, whereby Transaction Fee's will be used to "vote with your coins."

Feedback can easily be calibrated based on the identity of the individual leaving it -- we can work to make a "neutral" rating safe again as compared to the "grade inflation" we see in markets like Ebay where everyone is essentially shamed into providing only positive feedback.

You would be able to determine with a high degree of confidence WHO the identity of an individual (or autonomous computer system) is -- you could also see what kind of reputation they had. What do people think about them based on their transactional history. If you are a counter-party to a transaction you should have the right to express your sentiment without fear of censure. Think about every time you go through a drive-thru to get food or coffee. Is every experience really a five-star? With IDCoin you could simply acknowledge that you had an experience that was neither positive nor negative.

With IDCoin you could instantly determine if someone's +5 rating actually meant anything especially if they gave everyone +5. You could instantly baseline the feedback.

With a Web of Trust model you could choose to transact with people and business that are say only within 3 or 4 degree's of separation. In this way you could completely detect and ignore any "astro-turfing."

IDcoin is different than http://identifi.org in that it will be based on PGP/GPG and will work to leverage existing plugins to support email clients. In this way you could generate coins just by sending an encrypted email.

IDcoin will also differentiate itself from Namecoin (NMC) though we would absolutely look at ways to potentially leverage it as well. The general problem with block-chain based approaches is the current need to have clients download and maintain their own copy. This should absolutely be an OPTION but not a hard REQUIREMENT -- we conceive of a model through the Web of Trust that you could elect to essentially ATTACH to any public node that has a sufficient level of TRUST associated with it based on your own own level of confidence within whatever degrees of separation you're willing to permit. In this way the system supports a variant of check-pointing.

In fact our current design allows you the ability to link a TXID from any other blockchain into the web-of-trust -- so if you spend Bitcoins with a vendor you can link that TXID AND your feedback into the chain.

In our IDCoin model Web of Trust, you could leverage Notary Publics who have been DEPUTIZED by institutions you find credible to perform key-signing services. For example, we conceive of a system that would support say Rotary International to use our system as a public ledger for their membership roster. In fact with our IDCoin ANYONE could obtain and demonstrate AFFINITY with any organization they so choose to. It can act as a TRANSCRIPT or a RESUME/CV -- your company could digitally acknowledge that you are an employee from some period of time. Your performance could be logged if you so choose to use it that way.

IDCoin could be used to take credit for ANY transaction in any other blockchain. Our current designs include the ability to insert FOREIGN_TX into the chain that would include CHAIN and TXID. From there you could find the ADDRESSES and AMOUNT. Of course you would have to take credit for an address first -- this OPT-IN method completely de-anonymizes the crypto-currency transaction which may be required in the future by some financial institutions.

Most of the Identity and web-of-trust ideas come from the PGP/GPG world...

But what we're hoping to do is:

1. Incentivize people to create keys and use them!
2. Make the web-of-trust easier to navigate (and display!) using social-graph techniques
3. Make key-signing easier AND 
4. Create an intersection with existing identity verification services such as Notary Publics (in the US for example)

Skew is definitely a concern. We have been talking about a couple of different approaches to launching including doing a BIG BANG BLOCK at one of the bigger Bitcoin conferences when a lot of people and organizations will be present for a classic KEY SIGNING PARTY. Another approach is to simply let it grow organically even though most of the early participants will have very low affinity, that might be okay. The PGP keys themselves should in fact be long lived and widely distributed. One of the bootstrap prototypes we are considering would have a simple KEYSERVER accept a key only after a user has responded to an encrypted email from that key. The keyserver itself could essentially offer a low-level of confidence in the form of confirming that the key works to a then valid email address. In fact it could simply offer a first NEUTRAL rating as well to get the REPUTATION score started.

PGP/GPG Key-signing SHOULD be, generally speaking, a BI-DIRECTIONAL event.

What do we care if random bots or spammers sign our key? We do not have to acknowledge the relationship unless we counter-sign their key. The Web of Trust would easily expose a nexus of single-linked relationships or a self-contained loop.

To keep SPAM out of the chain as well as minimize AFFINITY seeking agents our current thoughts on the design would use a two-phase commit system before accepting certain transactions into the blockchain.

For example, both parties to a transaction could digitally sign the TXID from their private keys (since the transaction is publicly disclosed and the public addresses are known) -- you could instantly confirm whether the transaction was mutually beneficial -- versus having someone try and spam by sending small amounts to a known identity (known as DUSTING) -- once the transaction was ACKNOWLEDGED then both parties would be free to provide REPUTATION tokens to that event without fear of censure.  This means that you could leave positive or negative or even neutral feedback without fear of reprise.  And since the feedback can be amended, it gives both parties an opportunity to CURE any dissatisfaction over time.

IDCoins could also be used in a two-factor authentication system, potentially in concert with OpenID providers.  We conceive of a model where fractions of IDCoin could be transacted between known addresses instead of using a password.  Essentially using the wallet as a one-time password vault.

The IDCoin blockchain would essentially be currency and transaction AGNOSTIC.

This means that individuals using something like KIVA.org could take credit for repaying their micro loans back!

What this means is that we could create an open/public ledger that could render credit reporting bureaus largely irrelevant.

Who's opinion would you trust?  A friend of a friend or some greedy for-profit corporation?

By leveraging some of the ideas implemented in Namecoin that feedback and reputation could be amended over time -- this means that you could essentially agree to show payment schedule performance until the loan was satisfied or discharged and then simply indicate an overall status after some period of time.

IDCOINS SHOW PROVENANCE

Since the inputs and outputs can be easily traced back to the origin you could in theory discover ASTROTURFING whereby one individual distributes coins that are in turn spent back to increase positive feedback on a self-serving transaction.

IDCOINS AS A PREDICTION MARKET DRIVEN DNS REPLACEMENT

Here's a radical idea in DNS service that even #Namecoin doesn't support: you allow any and everyone to register ANY name they want and then you just surf based on your Web of Trust recommendations.

It eliminates the incentive of cyber-squatters and decimates the intellectual property fights over domain names -- it means everyone could have a "disney dot com" if they wanted to but the system would react based on reputation feedback where the source of truth was within whatever degrees of separation you elected.

We contemplate an OpenID based provider service that would allow sites to embed universal "like/dislike" buttons within their content that would permit people easy/authenticated access to spend coins on validating content.

Feedback comments could be stored in local "wallets" or in a P2P environment with designated trust third-parties (simple replication) -- the content author could elect to amend or delete their content as they see fit -- the main chain could use a UUID as the reference to ask the network to fetch the content from an authoritative source.

IDCOINS AS AN ANTI-SPAM PLUGIN

Given the proposed generic namespace, IDCoins could be used as a SENDMAIL plugin to determine IP address reputation

IDCOINS AS LICENSE PLATE REPUTATION

A generic reputation namespace could be used to provide feedback for drivers or people who park like jerks ;-)

Imagine an ap that you could snap a picture, OCR the license plate number and then vote to feedback that identity.
