<p align="center" width="100%">
    <img width="80%" src="zerobeings_logo_m.png">
</p>

🚧 Under construction 🚧
## Market gm ☕️ - An NFT marketplace 

> 0.5% platform fee & [EIP-2981](https://eips.ethereum.org/EIPS/eip-2981) royalties honored, filetype flexibility, auto-generated IPFS site, and fully customizable.


1. **Overview:** A tour of the marketplace.
2. **Mobile Devices:** How to use Market gm as a progressive web application.
2. **Quickstart:** How to create & cancel listings, create & close auctions, create an offer.
3. **Proposed Metadata Structures:** Additional meta data feature for rendinging non-image filetypes.
4. **goerli-marketgm**: Overview of the goerli-marketgm.
5. **Maretplace Source Code:** Overview of the marketplace source code.
6. **More Info:** FAQs, APIs, and links.


# Overview

> 
> "Speak fren and enter." - Gandalf 🧙🏼‍♂️
>
> Mint a Zero Being here [mint.zerobeings.xyz](https://mint.zerobeings.xyz)
> 

Market gm is an NFT gated marketplace. The connecting wallet must have a balance of at least one Zero Being NFT.
Wallet authorization is accomplished with [PrivateParty](https://privateparty.dev).

> Private Party is a dead simple blockchain auth framework created by [skogard](https://twitter.com/skogard)

<p align="center" width="100%">
    <img width="50%" src="privateparty.png">
</p>

To access Market gm ☕️ head over to [gm.zerobeings.xyz](https://gm.zerobeings.xyz) and login.

<p align="center" width="100%">
    <img width="33%" src="login.png">
</p>

After logging into Zerb gm ☕️, open the menu on the left.

<p align="center" width="100%">
    <img width="100%" src="menubutton.png">
</p>

Click on goerli-market or Market gm ☕️.

<p align="center" width="100%">
    <img width="100%" src="selectmarket.png">
</p>

goerli-marketgm will load the goerli marketplace for testing collection launches and rendering various filetypes.

> Filetypes currently supported are as follows: .png, .svg, .jpg, .jpeg, .gif, .wav, .mp3, .ogg, .mp4, .webm, .doc, .docx, .pdf, and .txt.

After clicking on the preferred market (goerli or mainnet) the market view will display the following. The market is automatically rendered with the Zero Beings NFT collection.

> factoria is a simple cost effective tool to launch your NFT collection created by [skogard](https://twitter.com/skogard)

## Market gm view - mainnet

<p align="center" width="100%">
    <img width="100%" src="searchview.png">
</p>

Continue to scroll down the page and three panels will render: the collection info, any available listings for that specific collection, and the NFTs minted for the searched collection.

<p align="center" width="100%">
    <img width="100%" src="collectionview.png">
</p>

### Collection Info

The Collection Info panel contains a combination of imformation rendered from the NFT collection metadata, the collections opensea profile, and both opensea & looksrare floor prices if applicable. The roaltiy information is fetched from the smart contract with the rarible api.

<p align="center" width="100%">
    <img width="33%" src="collectioninfo.png">
</p>

### Available Listings

The Available Listings displays all direct and auction listings for the collection being viewed. The number of total listings is labeled on the right hand side of the panel.

If there are no listings the view will look like this:

<p align="center" width="100%">
    <img width="100%" src="nolistings.png">
</p>

If there are listings available the view will look like this:

<p align="center" width="100%">
    <img width="100%" src="listingsavailable.png">
</p>

If the NFT or the Buy/Offer button is clicked, a detailed view of the listing of interest will be displayed.

#### Market Listing Detail View

If the wallet address holds the NFT listed, a list of the offers will be displayed. If the wallet is the owner of the NFT, the title of the section heading above the offers is "Offers".

<p align="center" width="100%">
    <img width="100%" src="marketlistingdetails.png">
</p>

If the wallet connected is not the owner, the title will be rendered as "i want that!."

<p align="center" width="100%">
    <img width="100%" src="iwantthat.png">
</p>


### Collection View
When the cursor hovers over an NFT in the collection a grey box will outline the NFT of interest. Each in dividual NFT will display the following information: The name, token ID, collection address (link to etherscan), a link to the NFT on looksrare and opensea.

<p align="center" width="100%">
    <img width="33%" src="individualcollectionview.png">
</p>

#### Detailed NFT View
If the the NFT is clicked, a detailed view will be displayed for the NFT of interest. The detailed view contains the following information: name, image/file, and NFT attributes.

<p align="center" width="100%">
    <img width="100%" src="detailedview.png">
</p>