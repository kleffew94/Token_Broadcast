---

TokenBroadcast
A marketplace-driven approach to ‘open advertising’ within the web3 ecosystem
For the June 2017 Token Hackathon, Brian Leffew and I elected to assemble a ‘bot’ on the Token Browser named “Token_Broadcast”. 
The bot implements an open-market bidding mechanism, allowing users to compete for the transmission of message onto an AdSpace. 
At the end of the time interval, the user with the highest bid wins, and gets their message pushed onto both the AdSpace and other bidders. Simultaneously, a smart-contract reimburses the non-winners with their original funds.
While the message could be easily redesigned to be pushed onto any external network, our proof-of-concept MVP uses a Twitter handle, @Token_Broadcast, to push the winning message onto the Twitterverse 
Scan this QR code to redirect you to TokenBroadcast (in app)The mechanics of the UX are rather simple:
First, the user initiates a conversation with Broadcast_Bot on Token, using any string to get the conversation rolling (i.e. “Hey”, “Shalom”, or “Whatsup”)


Broadcast_Bot follows up with an introduction, then uses SOFA UI elements to ask the user to either bid, donate, or display.
If the User decides to bid, she enters a value amount, which is listed in local currency and recorded in Ethereum.
If the bid is valid (i.e.- greater than the previous highest bid), the bot accepts it, asking the user “What is the message you’d like to Broadcast?”[insert UI Screenshot]
After the message submission is received, it is recorded and stored by the bot. If the bid associated with message remains the highest and the end of the time cycle — it is pushed through the Twitter API and tweeted out at the end of the time parameter.

In code, the UX looks like this:
[Picture]


---

Open-Source Mission
We are making it extremely easy for non-technical Adspace owners, advertisers, and developers to re-monetize and create their own open-market for advertising.
TokenBroadcast is fully open-source. 
This means that any other developer is free to fork the codebase and re-purpose it for their own Twitter handle or other specialized adspace.
The logic for the bot was written in JavaScript. The full code and documentation is available on Github (Link.)


Thumbs up for JavaScript! (Taken at TokenSummit, 2017)
With BroadcastToken, it doesn’t matter where you are located. We have enabled anyone to access and build free and open marketplaces for privately-owned, hyperlocalized Adspace.
Thus, whether you own a digital billboard in Japan or are the host of a popular livestream in Africa, you will be enabled to competitively monetize the attention drawn from your organically grown userbase.


---

Raising Funds for Charity and the Greater Good
The most important aspect of the BroadcastBot on Token is the way in which the revenue collected by the Bot is distributed.
We believe that certain high-profile advertising spaces could eventually become generators of revenue for the public good.
For example, consider a scenario where NYC decided to re-purpose funds raised by Times Square Advertisements for Charity or local revenue.
Imagine! An open, competitive market for Advertisements in Times SquareWhen the Token Browser moves off the Rosten-revival testnet and into its launch phase, we plan on implementing a smart-contract to repurpose all accumulated ETH revenue for a designated charitable foundation (i.e. Black Girls Code).


---

Real World Use Cases

The vision for Token_Broadcast is simply:
“To allow owners of AdSpaces to create engaging marketplaces where advertisers compete for the attention of users in a way which is transparent, non-discriminatory, and programmatically verifiable.” 
In order for the system to be economically effective, the message most be broadcasted within a space where attention is high and noise is low. 
Thus, the signal pushed by the TwitterBot onto the Twitterverse is in itself is of little value to advertisers (as users have no incentive to follow a bot which only posts ads).
However, when the Twitter handle is used as an middleware ‘messenger marketplace’ for high value AdSpace, the real value proposition begins to become realized.
Examples:
1. Targeting Hyperlocalized Ad Spaces 
(i.e. billboards)
Programmable, electronic billboards exist across the world. In the current system, the owners of these spaces form extensive paper contracts with 3rd parties and publishers who wish to utilize the space for ads. 
Through a pre-programmed smart-contract, TokenBroadcast brings in increased revenue for electronic billboard owners by (1) dis-intermediating unnecessary third parties; and (2) opening up the market to higher levels of price-competition due to the permission-less, global nature of the blockchain.
An example of monetizable billboard space (at Wake Forest Commencement, 2017)

2. Targeting Digital Spaces with High Visibility 
(i.e. Television Tickers, banner ads)
Another use case for TokenBroadcast would be to allow people to compete for adspace in the digital arena — which exists outside of the walled-garden of Twitter. 
Livestreams found on Television and on the Internet oftentimes allow users to interact directly with live-programming (as a means to incentivize community and engagement). On high trafficked streams–this space is highly visible and valuable. 
LiveStreams and Television networks could use  Twitter to monetize their audience!This use case, if implemented by a high-profile brand or organization, could lead to a viral growth component where the level of competition within the marketplace increases in-step with the pre-existing userbase.
Thus, LiveStreams (like Periscope, Youtube, etc) and Television Networks could utilize the TokenBroadcast bot+Twitter as a way to both monetize and engage their userbase and audiences!


---

Finally, after 48 hours of focus and dedication, we are happy to announce that the TokenBroadcast is up and running — and available for use in the Token Browser. To access the bot, use the QR code shown above or search “Token_Broadcast” under the ‘Browse’ tab from within the application.
Below is a picture of the Team, and the finished product.
