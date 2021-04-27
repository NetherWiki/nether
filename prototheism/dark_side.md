Dark Side is [Nouveau](nouveau.md)'s [darknet marketplace](https://en.wikipedia.org/wiki/Darknet_market).
It is one of the largest distributors of psychedelic drugs on the internet.
As a [Prototheist](index.md) organization Nouveau sells their products at cost without any pretense of profit.
Aside from controlled substances Dark Side also sells various nootropic and biohacking components.

Peculiarly for a dark net marketplace, Dark Side doesn't allow third-party sellers.
All products on Dark Side are sourced directly from Nouveau.
Dark Side is not accessible through HTTP, the reason being that by default HTTP leaks possibly identifying information.
All transactions are made through an automated bot running on a [Matrix](https://en.wikipedia.org/wiki/Matrix_%28protocol%28) server through a [Tor](https://en.wikipedia.org/wiki/Tor_%28anonymity_network%28) [hidden service](https://2019.www.torproject.org/docs/onion-services).
Clients are identified only by their GPG keys and Nouveau claims that their servers are hosted without hard drives through anonymous [NODE](node.md) instances.

The mascot of Dark Side is Edis Krad, an anthropomorphic cat cub.
The original creator claims to have no association with Nouveau and objects to his art being misappropriated.
Edis Krad is Dark Side backwards.


# History
The existence of Dark Side was the first documented communication between Nouveau and the public.
Dark Side was not associated with Nouveau until the [Lambda Leaks](lambda_leaks.md).
There are no references to Nouveau on the platform itself and Dark Side was initially spread by word of mouth alone.

Dark Side quickly became popular among Prototheist groups.
Although the platform does not require invitation, the text-based nature of the Matrix bot and the fact that it cannot be accessed through Tor browser prevents all but the technically-inclined from accessing it.

An [I2P](https://en.wikipedia.org/wiki/I2P) mirror was briefly put online before being taken down again, likely due to perceived anonymity risks in the I2P protocol.

# Structure
Dark Side is a text-based chat server running on a non-standard Synapse implementation.
All communication occurs through a bot that sends a direct message to the user after they log in.
Users cannot communicate with one another and it is likely that a new NODE instance is spawned for each session.

All communication is rate-limited to prevent traffic correlation attacks.
The only images are stickers of Edis welcoming the user to the server and reacting to various bot commands.
Users are asked to confirm their delivery address and submit payment.
One of several cryptocurrencies are accepted.
The package is then mailed to the provided address using a unique form of camouflage that appears to be automatically generated using machine learning.

[todo]
Perhaps the bot talks through the perspective of Edis, for example: "Hi, I'm Edis, welcome to the server!" and "Okay, so you want 200 tabs of 100ug of LSD, is that correct?"
There are specific images for each reaction, and in case of errors.
We want to show examples of a full transaction (or possibly just an image gallery of every possible reaction) in the Element client.
[/todo]

# Contents
Dark Side deals in pharmaceuticals and other psychoactive compounds.
Not every item sold by Dark Side is illegal to posses, although most would be illegal to sell without FDA approval.
Psychoactive drugs include personal and bulk quantities of LSD, LSA, psilocybin, and amphetamine.

[todo]
We should have a price chart somewhere, comparing prices for what they sell (probably including full Prototheist stacks with brand names) and the best prices at competing deep web markets (plus current street price).
[/todo]

Aside from controlled substances Dark Side is currently the premier source for biohacking components.
Popular products include [Myostatin](https://en.wikipedia.org/wiki/Myostatin) knockouts and other genetic enhancements, packaged as ready to use [CRISPR-Cas9](https://en.wikipedia.org/wiki/CRISPR_gene_editing) viral vectors.
This has led to substantial controversy due to the danger of off-target effects.
See also: [Biohacking in Prototheism](biohacking.md).
