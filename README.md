![BUCK](https://i.imgur.com/RXp7QTz.png)

# Buck - The Future of Cryptocurrency

**Keep running wallet to strengthen the Buck network. Backup your wallet in many locations & keep your coins wallet offline.**

BUCK

Project site: https://Buck.red 

Block Explorer: https://Explorer.Buck.red 

- Type: Cryptocurrency
- Ticker: BUCK
- Algo: Equihash
- Max supply: 1 Billion coins 
- Target block creation rate: 1000 coins every 2.5 minutes
- Current block size is similar to BCC/BCH (BUCK = 2MB every 2.5 mins ~ BCC/BCH = 8MB every 10 min)
- Technology: ZeroCoin / Zcash

## Buck Principles: 
- Anonymous:
It is recommended to use an anonymous zaddr for all transactions. Public taddrs transactions are also allowed.
- All contributors are welcome

As a miner you should not use the biggest pools to follow main principles.
- Easy to mine:
Equihash algorithm.
You can use your Desktop PC to mine Buck. Most profitable is GPU mining.

### Ports:
- RPC port: 5739
- P2P port: 5749

Install
-----------------
### Mac
Get dependencies
```{r, engine='bash'}
#install xcode
xcode-select --install

/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install cmake autoconf libtool automake coreutils pkgconfig gmp wget

brew install gcc5 --without-multilib
```

Install
```{r, engine='bash'}
# Build
./zcutil/build-mac.sh --disable-rust
# fetch key
./zcutil/fetch-params.sh
# Run
./src/zcashd
```


Security Warnings
-----------------

**Buck is experimental and a work-in-progress.** Use at your own risk.
