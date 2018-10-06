# Private Keys

* Private Keys are an excellent way to back up certain addresses contained within a wallet
* Private Keys will give you the ability to recover any coins contained on a certain address 
* Never give your Private Keys to anyone as they can unlock the coins in your wallet from anywhere

## Dumping Private Keys From Wallet

* Copy public address containing your coins
* Navigate to Help/Debug Window/Console within your Linda wallet
* Type the following command dumpprivkey xxxxx  replace the xxxxx with your public address containing your coins and press enter
* The console will display a key underneath your command, this is your private key
* Save your private key somewhere very secure, write on a piece of paper and double check you have copied correctly
* Never store your private keys on your computer in a word document
* Repeat the dumpprivkey command above for all addresses containing coins on your wallet

## Importing Private Keys To Wallet

* Navigage to Help/Debug Window/Console within your Linda Wallet
* Type the following command importprivkey xxxxx NAMEOFWALLET true replace xxxxx with your private key and replace NAMEOFWALLET with whatever you want to call this wallet finish the command with true
* This command uses a lot of resources as it rescans the block chain for any transactions associated with your private key
* Even if the wallet seems frozen let the process run eventually you will get an > output in the console to confirm its done
* Your coins associated with this private key will be loaded to your wallet, it may take a restart of the wallet for the public address associated with the private key to appear in the recieve tab
* Repeat the importprivkey command above for all private keys you want to load to your wallet
