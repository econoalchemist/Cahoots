# Old Fashioned StoneWallx2
Sometimes it's easier to conceptualize with a visual example. In this clip, you are looking at a traditional Stonewallx2 transaction without Soroban. In this example, the collaborators must be doing the transaction in person so that they can swap a few QR codes with each other:

[![OG Stonewallx2 Video](/assets/OGstonewallx2Thumbnail.png)](https://bitcointv.com/w/iXmpseNwRBQCHscuMCSXR7 "OG StoneWallx2 Video")

Note that with StoneWallx2 transactions, the collaborating peer needs to have a bitcoin balance in their wallet greater than the amount you want to transact. The sender and the collaborator are splitting the miners fees. In the above example, I was using an instance of Samourai Wallet installed on another Android device for demonstration purposes, like this I was acting as sender with the primary device and both collaborator/receiver with the secondary device

If you want to explore the transaction from the video example above, you may find it on KYCP [here](https://www.kycp.org/#/a856b1adb750905b7e9a50f7fa2d9e66da253c0babd2a73560626ab4e3ae7efd). This is kind of a bad StoneWallx2 example because I combined 3 of the outputs right afterwards. You'll probably notice that I combined the spend, decoy, & a change output as inputs to a later transaction. That move obviously diminished the privacy benefits from doing a StoneWallx2 transaction. That type of behavior is discouraged. But this will give you an idea of how the details look on-chain.

![](/assets/2.png)

[Here](https://blockstream.info/tx/a856b1adb750905b7e9a50f7fa2d9e66da253c0babd2a73560626ab4e3ae7efd) is another way to look at the same transaction on Blockstream's explorer. You'll see the two inputs: one from the spender, one from the collaborator; and the four outputs: one spend (to the collaborator), one decoy and one change outputs (return to sender) and one change output (return to collaborator). 

![](/assets/3.png)

