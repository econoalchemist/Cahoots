# Old Fashioned Stowaway
Here is a video example of a Stowaway transaction before Soroban. It looks very similar to the way collaborating peers would build a StoneWallx2 transaction, they need to swap a few QR codes. But the way the transaction is being built makes it so that the details left on the blockchain obfuscate the amounts being transacted instead of using decoys to confuse the common-ownership-heuristics. 

*In this example video, I mistakenly took the added and unnecessary step of first scanning a deposit address. There is no need to do this as Stowaway will generate the deposit address automatically. 

![OG Stowaway Video](/assets/OGstowaway-thumbnail.png)](https://bitcointv.com/w/9v5ogN42n25Bd9uNHKRXPW "OG Stowaway Video")

Note that with Stowaway transactions the collaborator needs to be the receiver. If you are interested in exploring this transaction on KYCP, it can be found [here](https://www.kycp.org/#/0514f44addd72809b8eb1b8dc462db2ce97077c9d86e6cd834616aa9395ee9a9). You may recognize some of the inputs of this transaction from the outputs of the other transaction I showed you earlier. 

![](/assets/5.png)

[Here](https://blockstream.info/tx/0514f44addd72809b8eb1b8dc462db2ce97077c9d86e6cd834616aa9395ee9a9) is another way to look at this transaction with Blockstream's explorer. There are multiple inputs and multiple outputs. None of the input or output amounts match the amount that was sent (0.00802 BTC). Since we have prior knowledge and know that the collaborator contributed 0.00848346 BTC, we can see that the 0.01650346 BTC output is the return of the collaborator's funds plus the 0.00802 that the sender was spending. But if I wasn't explaining this with prior knowledge, there would not be anyway to know that the values in this transaction were not valid at face value and that some other, hidden, amount was being spent. 

![](/assets/6.png)
