# Putting the Who? in Cahoots.
An article on the privacy enhancing StoneWallx2 & Stowaway transactions and the recently deployed Soroban improvements from Samourai Wallet.
![](/assets/01.jpg)

With the release of Samourai Wallet version 0.99.96, users gained tremendous UX improvements on collaborative (cahoots) transactions with Soroban, among other features like increased load times and increased Tor stability. Click [here](https://medium.com/samourai-wallet/wallet-update-0-99-96-introducing-soroban-adc9a36a7ddb) for Samourai Wallet's official announcement. 

StoneWallx2 and Stowaway are privacy enhancing transaction tools that can be used to break the assumption that all inputs to a transaction were owned by the same entity. This assumption is called the common-input-ownership-heuristic and is a common tactic used by chain analysis firms to track users' activity throughout the Bitcoin network. 

Over the past several months, if not years, the Samourai Wallet team has been hard at work developing methods and tools that any Bitcoin user can employ to mitigate the invasive surveillance tactics developed by chain analysis firms. 

  - StoneWallx2 introduces reasonable doubt as to who owned which input by using multiple inputs and always 4 outputs; 1 is the spend, 1 is a decoy, and 2 are change outputs. A StoneWallx2 can be used when doing a self-transfer, sending to the collaborator, or even sending to a third party not participating in the collaboration. 

  - Stowaway on the other hand, also uses multiple inputs but the amounts being transacted are obfuscated. These transactions can be used with another Samourai Wallet user and the collaborator must also be the recipient of the spend.    


The StoneWallx2 and Stowaway tools have been available to the public for some time. Being the collaborative transactions that they are, these tools required that participating users exchange information between each other by sharing a few QR codes to build the transaction. Until recently, sharing these QR codes required that the collaborators were doing the transaction in person. However, Soroban introduces the ability to build these transactions using an app agnostic comms layer over Tor. Translation: Now you can build StoneWallx2 and Stowaway transactions across vast geographic distances, privately and instantly over Tor, and this technology can be implemented by other wallet developers.
