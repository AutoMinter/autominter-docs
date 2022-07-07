# Rarity + Metadata

You can adjust the rarity of each layer image. This affects how many of the layers will appear. The default values for rarity are based on fixed ratios. However you can manually enter a fixed number of times you would like a layer to appear in the collection.

![](<../.gitbook/assets/image (7).png>)

You have two options when selecting rarity:

### Use default rarities

Selecting "common", "uncommon", "rare", or "super rare" will result in fixed ratios of images within the same layer being generated. The ratios are based on the following:

* Common = 100
* Uncommon = 40
* Rare = 20
* Super rare = 1

For example if you for every 40 "uncommon" images within a layer, there would be 100 "common" generated.&#x20;

### Or generate specific quantities

For the most control you can enter a specific quantity for the rarity. This means, that this exact number of images will occur in the generated collection. Be careful though, as you must make sure the numbers add up to the total number of images being generated. Otherwise AutoMinter will increase or reduce the excess amount.

![](<../.gitbook/assets/image (4).png>)



{% hint style="info" %}
**Empty Layers**: If you would like an image to be optional, please upload an empty transparent PNG image
{% endhint %}

### Mixing ratios and specific quantities

Within the same layer you can have both preset ratios, and specific quantities. The specific quantities will take president.
