# DigiByte Support
Feel free to submit pull requests if you have any information you think would be helpful.

## Common Problems
- Wallet App not showing correct balance?
  * Try resyncing app, by going to menu, settings and then sync with blockchain.
- Old wallet app non functional? 
  * [DigiSweep](https://mctrivia.github.io/DigiSweep/) can move funds to a new wallet. 
- DigiByte Go not functioning properly.
  * If you have no funds in segwit addresses(Starting with 3 in DigiByte Go) then you can move all funds to a more stable wallet like Coinomi using [DigiSweep](https://mctrivia.github.io/DigiSweep/)
- Wallet keeps crashing?
  * Report the crash and wait for fix or use [DigiSweep](https://mctrivia.github.io/DigiSweep/) to send to new wallet.
- Wallet says syncing but never finishes
  * Try the following steps in order and stop when problem is fixed:
    1) Turn wifi off then try resyncing
    2) Reboot phone then try resyncing
    3) If those fail it may have connected to a bunch of bad nodes.  At this point you can try again in a few days or use DigiSweep to send funds to coinomi
- Core wallet taking for ever to sync
  * Add the following to your digibyte.conf file then restart the core wallet
```
addnode=seed1.digibyte.io
addnode=seed2.digibyte.io
addnode=seed3.digibyte.io
addnode=seed.digibyte.io
addnode=seed.digibyteprojects.com
addnode=digihash.co
addnode=digiexplorer.info
addnode=seed.digibyteguide.com
addnode=seed-1.us.digibyteservers.io
```
