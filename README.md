# ITCH-orderbook
This is a basic order book builder that takes the parsed file from the ITCH binary data feed and builds an orderbook out of it. This orderbook takes all add order and execute order messages from the data to update the order book in runtime.
In addition, traded messages can be used to keep track of the transaction prices whenever a transaction occurs. Also, it keeps track of best bid and best ask in the orderbook. This helps to keep track of the price for all the times when the transaction price is not available.
The midpoint price: (best bid + best ask)/2 is considered as an important measure of value of the security.
