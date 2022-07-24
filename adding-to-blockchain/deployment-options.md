# Deployment options

Once you've generated the preview images for your collection, and are happy you can proceed to add your NFT collection to the blockchain. This permenantly adds your NFT to the blockchain.



Press "Add to blockchain"

#### Name of your collection

The name of your colleciton is the name that will appear in marketplaces and on the minting website for your collection. This cannot be changed so make sure it is correct.

#### Symbol

The collection symbol is a short few characters which is sometimes used in some apps as a short hand name for your collection. Typically it would be 2-4 characters in length.

#### Delayed Reveal

If you choose "Delayed reveal" you must upload an image to be shown as a placeholder. Once people mint your NFT they will not see the NFT image right away. At a later point in time you can manually trigger a reveal.&#x20;

#### Mint Price

This is the price you want to charge people by default to mint your NFT. This value can be changed later. You are also able to override custom pricing for each minter using whitelists later.

#### Royalty

This is the ammount you will earn on all future transactions when the NFTs are traded on marketplaces like opensea and looksrare. You are not able to change this value, so make sure you set it correctly.

You may select a value from 0-10%



**Mint Allocation**

You can deploy contracts so that people can mint randomly. Or they can mint sequentially. There are a few key differences between these options.\
\
Random Mints:

* The NFT on mint is decided randomly
* Creators are able to airdrop specific NFTs
* Gas costs more to mint
* Minting more NFTs will cost more gas

Sequential Mints:

* Uses the new ERC721A contract
* All mints are in a fixed order (0,1,2,3,4... etc.)
* The gas price to mint multiple NFTs at once is the same as minting 1
* Much lower gas to mint
* You can reserve NFTs allowing you to mint in batches
* You are not able to airdrop a specific NFT (they in order)

#### Network

You may change the network you deploy too. Depending on the wallet you use, you may need to change this inside your wallet app. Please note, that in order to deploy to a specific network, you must have that network configured inside your crypto wallet. If you have trouble please join our discord or the support of your wallet provider.

