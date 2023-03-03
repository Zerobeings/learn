<p align="center" width="100%">
    <img width="80%" src="images/zerobeings_logo_m.png">
</p>

🚧 Under construction 🚧
## Market gm ☕️ - An NFT marketplace 

> 0.5% platform fee & [EIP-2981](https://eips.ethereum.org/EIPS/eip-2981) royalties honored, filetype flexibility, auto-generated IPFS site, and fully customizable.


1. **Overview:** A tour of the marketplace.
2. **Mobile Devices:** How to use Market gm as a progressive web application.
2. **Guide:** How to create & cancel listings, create & close auctions, create an offer and Buy.
3. **Proposed Metadata Structures:** Additional meta data feature for rendinging non-image filetypes.
4. **goerli-market**: Overview of the goerli-market.
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
    <img width="50%" src="images/privateparty.png">
</p>

To access Market gm ☕️ head over to [gm.zerobeings.xyz](https://gm.zerobeings.xyz) and login with your preferred wallet.

<p align="center" width="100%">
    <img width="33%" src="images/login.png">
</p>

After logging into Zerb gm ☕️, open the menu on the left.

<p align="center" width="100%">
    <img width="100%" src="images/menubutton.png">
</p>

Click on goerli-market or Market gm ☕️.

<p align="center" width="100%">
    <img width="100%" src="images/selectmarket.png">
</p>

goerli-market will load the goerli marketplace for testing collection launches and rendering various filetypes.

> Filetypes currently supported are as follows: .png, .svg, .jpg, .jpeg, .gif, .wav, .mp3, .ogg, .mp4, .webm, .doc, .docx, .pdf, and .txt.

After clicking on the preferred market (goerli or mainnet) the market view will display the following. The market is automatically rendered with the Zero Beings NFT collection.

> [factoria](https://docs.factoria.app/#/),  created by [skogard](https://twitter.com/skogard), is a simple cost effective tool to launch your NFT collection.

## Market gm view - mainnet

<p align="center" width="100%">
    <img width="100%" src="images/searchview.png">
</p>

Continue to scroll down the page and three panels will render: the collection info, any available listings for that specific collection, and the NFTs minted for the searched collection.

<p align="center" width="100%">
    <img width="100%" src="images/collectionview.png">
</p>

### Collection Info

The Collection Info panel contains a combination of imformation rendered from the NFT collection metadata, the collections opensea profile, and both opensea & looksrare floor prices if applicable. The roaltiy information is fetched from the smart contract with the rarible api.

<p align="center" width="100%">
    <img width="33%" src="images/collectioninfo.png">
</p>

### Available Listings

The Available Listings displays all direct and auction listings for the collection being viewed. The number of total listings is labeled on the right hand side of the panel.

If there are no listings the view will look like this:

<p align="center" width="100%">
    <img width="100%" src="images/nolistings.png">
</p>

If there are listings available the view will look like this:

<p align="center" width="100%">
    <img width="100%" src="images/listingsavailable.png">
</p>

If the NFT or the Buy/Offer button is clicked, a detailed view of the listing of interest will be displayed.

#### Market Listing Detail View

If the wallet connected holds the NFT listed, a list of the offers will be displayed. If the wallet is the owner of the NFT, the title of the section heading above the offers is "Offers".

<p align="center" width="100%">
    <img width="100%" src="images/marketlistingdetails.png">
</p>

If the wallet connected is not the owner, the title will be rendered as "i want that!" above the list of competing offers.

<p align="center" width="100%">
    <img width="100%" src="images/iwantthat.png">
</p>


### Collection View
When the cursor hovers over an NFT in the collection a grey box will outline the NFT of interest. Each individual NFT will display the following information: The name, token ID, collection address (link to etherscan), a link to the NFT on looksrare and opensea.

<p align="center" width="100%">
    <img width="33%" src="images/individualcollectionview.png">
</p>

#### Detailed NFT View
If the the NFT is clicked, a detailed view will be displayed for the NFT of interest. The detailed view contains the following information: name, image/file, and NFT attributes.

<p align="center" width="100%">
    <img width="100%" src="images/detailedview.png">
</p>

## My Listings

The My Listings page displays the following three panels: create listings, your listings, and your portfolio.

<p align="center" width="100%">
    <img width="100%" src="images/listingsoverview.png">
</p>

### Create Listing Panel

By clicking connect the wallet of choice will connect to the marketplace and will be ready to interact with the marketplace smart contract. The Create Listing will display two options: direct or auction.

<p align="center" width="100%">
    <img width="33%" src="images/createlistingoptions.png">
</p>

After selecting which listing option is preferred. The respective listing form will be displayed.

#### Create Direct Listing Form

<p align="center" width="100%">
    <img width="33%" src="images/createdirectlisting.png">
</p>

#### Create Auction Listing Form

<p align="center" width="100%">
    <img width="33%" src="images/createauctionlisting.png">
</p>

### My Listings Panel

The my listings panel contains a view of all the NFTs listed by the connected wallet.

<p align="center" width="100%">
    <img width="100%" src="images/mylistingspanel.png">
</p>

#### Individual Listings

Each individual listing displays the following: name, price & currency, a cancel listing button, a link to an auto-generated IPFS website, and the iframe embed code.

<p align="center" width="100%">
    <img width="60%" src="images/individualmylisting.png">
</p>

>   
> The auto-generated IPFS website is a feature of the [thirdweb](https://thirdweb.com/?utm_source=embed) prebuilt marketplace smart contract.
>   


If the globe is clicked, the user will be lead to the respective NFT listing website.

<p align="center" width="100%">
    <img width="33%" src="images/ipfswebsite.png">
</p>

If the embed icon is clicked, the iframe embed code will be copied to the users clipboard. below is an example of what the code will look like:

```html
<iframe src="https://gateway.ipfscdn.io/ipfs/Qmcine1gpZUbQ73nk7ZGCcjKBVFYXrEtqrhujXk3HDQ6Nn/marketplace.html?contract=<marketplacecontract>&amp;chainId=5&amp;listingId=21&amp;theme=dark&amp;primaryColor=blue&amp;secondaryColor=red" width="600px" height="600px" style="max-width:100%;" frameborder="0"></iframe>
```
### My Portfolio Panel

The my portfolio panel displays all the NFTs owned by the connected wallet. Each NFT will display the following information: name, image, token ID, collection address, link to looksrare & opensea, and list button. If the NFT is currently listed the list button will be deactivated, greyed out, and non-active.

<p align="center" width="100%">
    <img width="100%" src="images/myportfoliopanel.png">
</p>

If the NFT is clicked on a detailed view of the NFT will be displayed, similar to the detailed view from the Detailed NFT View.

# Mobile Devices

> Zerb gm ☕️ is set up to function as a progressive web application (A2HS). Zerb gm ☕️ is the gateway to Market gm ☕️. 

The manifest.webmanifest is deployed as shown below. Adjust these parameters when customizing the marketplace with your NFT collection branding and colorsheme. This configuration will allow the webapp to be full screen when launched from the phone icon link giving the user a phone app like experience.

```html
{
    "background_color": "black",
    "description": "Zerb gm ☕️",
    "display": "fullscreen",
    "icons": [
      {
        "src": "icon/zero-icon.png",
        "sizes": "192x192",
        "type": "image/png"
      }
    ],
    "name": "Zerb gm ☕️",
    "short_name": "Zerb gm ☕️",
    "start_url": "/login"
  }
```
## A2HS
To create the webapp link on phone's home screen go to [gm.zerobeings.xyz](https://gm.zerobeings.xyz) or your custom domain using the phone's native browser application.

<p align="center" width="100%">
    <img width="100%" src="images/pwaA2HS.png">
</p>

## User Experience
Now the webapp will have a link from the phone home screen. This gives a similar experience to a native application. Users can log in with there preferred mobile wallet.

<p align="center" width="100%">
    <img width="75%" src="images/afterA2HS.png">
</p>

# Guide
The guide will demonstrate all the functions utilized through the Market gm ☕️ user interface. There are additional functions that can be explored by reviewing the smart contract [0x0000](). In the case of creating a listing and submitting an offer multiple smart contract interactions will occur. These two scenarios require two transactions to complete the function. The details are outlined in their respective sections.

## Create Direct Listing
To create a listing two transactions must occur. The first transaction gives permission to the marketplace contract to transfer your NFT upon sale. The first transaction is an approval function on the collection smart contract. The second transaction approves creation of the listing on the marketplace contract at the listing price specified in the listing form. All direct listings are for a duration of 7 days.

> Connect, select "Direct", approve access to and transfer of your NFT to be listed, and approve listing of the NFT.

<p align="center" width="100%">
    <img width="80%" src="images/createlisting.gif">
</p>

## Cancel Direct Listing
To cancel a direct listing first a wallet must be connect and secondly a cancel transaction must be approved. Only listings created by the wallet address that owns the NFT will be displayed.

> Click "cancel" on the NFT listing you would like to cancel. Connect wallet & approve cancel transaction.

<p align="center" width="100%">
    <img width="80%" src="images/cancelisting.gif">
</p>

## Create Auction

## Close Auction

## Submit an Offer

## Buy at full price or buyout auction

