# Using a Whitelist

AutoMinter uses gasless whitelisting, so that you are able to manage whitelists without paying gas.

You are able to manage whitelists to determine who can mint. You are also able to set custom pricing per whitelisted wallet and custom limits for each to be able to mint

### Adding whitelist entries

* You can enter whitelist addresses manually by adding them one at a time
* You can upload a CSV file containing the list of addresses. You can download a sample csv file from the dashboard. You can create a csv file in any standard spreadsheet app (excel, google sheets, etc.)

### Custom price + limits per entry

You are able to customise the price which each person can mint at. Please add a "mintFee" colum in your csv file. If you don't provide a mintFee, then the default price on the collection will be charged.

You can also give each person a custom mint limit, which limits the number of NFTs they can mint. Add a "mintLimit" column to the csv file if you would like to do this.  If you don't provide a mint limit, then the limit will be the default limit that was set on the collection. If you did not provide a mint limit for the collection there will be no limit.

