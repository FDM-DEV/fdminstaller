<h1>FDM masternode installer</h1>
***
<h1>Script for installation FDM Masternode on Linux VPS</h1>
<br>
your masternode requires a shipment of exactly 1000 FDM and 15 confirmations
<br>
Paste in vps console and enter
<br>
bash <(curl https://raw.githubusercontent.com/FDM-DEV/fdminstaller/master/fdm_installer.sh)
<br>
In your local wallet, in the console run the following commands:
<br>
masternode genkey
<br>
masternode outputs
<br>

paste into masternode genkey console vps when prompted
<br>
wait for it to synchronize
<br>

In your local wallet
<br>
open "master node configuration file" and complete the following line:
<br>
alias ip: port masternode genkey masternode ouputs
<br>
save and reset wallet
<br>
open console and run:
<br>
startmasternode alias 0 (alias)
<br>

