# btcrelay-fetchd

[![Join the chat at https://gitter.im/ConsenSys/btcrelay-fetchd](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/ConsenSys/btcrelay-fetchd?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This will periodically scan for Bitcoin blockheaders and store missing ones in btcrelay.

1. `git clone https://github.com/ConsenSys/btcrelay-fetchd.git && cd btcrelay-fetchd`

1. `pip install -r requirements.txt`

1. `python fetchd.py -s <YourUnlockedEthereumAccount> -r 0x2fd4f3ae10608cd6192339e72d4f6a0c182dee22 -n btc --rpcPort 8545 --fetch -d --gasPrice 500000000000`  use YourUnlockedEthereumAccount
