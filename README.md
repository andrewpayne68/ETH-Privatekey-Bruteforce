# ETH-Privatekey-BruteForce
A simple python script that generates random privatekeys and checks if there is an ETH balance in the account.

### **Quick Start**
Ensure Python3 is installed, eg. `$ sudo apt install python3 python3-pip` for debian/ubuntu `$ sudo pacman -Sy python3-pip` for Arch
```
 $ git clone https://github.com/andrewpayne68/ETH-Privatekey-Bruteforce.git

 $ cd ETH-Batch-Import-Privatekey-Bruteforce

 $ pip install web3

 $ python3 main.py (on Linux)
```


Sign up for a free web3 infura account here: https://app.infura.io/dashboard
change infura api url in `main.py` with one from your account, and run it.


### **Please Note**
This is only intended for Educational purposes. According to Etherscan, there are 191,119,471 eth holders currently. 
Private key is a 64 bits hex number. That means there are 
`16 ** 64 = 115792089237316195423570985008687907852837564279074904382605163141518161494336 (1.157920892373162e+77)`
permutations, therefore you have a 
`191,119,471` / `1.157920892373162e+77` = `1.6505399657164846e-69`
chance to discover a valid private key for an account with ETH per attempt and could take centuries, or at least until quantum computing becomes mainstream.
