# Bitfinex Arbitrage

The purpose of this arbitrage bot is to find arbitrage opportunity in between of pairs instead of exchanges.

Currently it can only tracks for arbitrage opportunity. Automated trading on arbitrage opportunity will be added soon.

## Disclaimer

This is just an experimental/POC arbitrage bot, please use it with your own risk.

### How to use

To start the program, execute run.py and pass in symbol paramenter. 

E.g. Symbol parameter as in IOT, OMG, etc.

```sh
$ python3 run.py omg 
```

### Installation

This arbitrage bot requires [python 3](https://www.python.org/downloads/) to run.

You need to install required modules, and a running [mongodb](https://docs.mongodb.com/manual/installation/).

```sh
$ cd bitfinex-arbitrage
$ virtualenv -p python3 venv
$ . venv/bin/activate
$ python3 -m pip install -r requirements.txt
$ cp config.py.sample config.py
$ vi config.py
```

### Todos
Auto trading is currenly under development, features to be implement as below:
  - Exit mechanism (WIP - current version is unstable, please avoid running with deep staked account)

License
----

This project is licensed under the MIT License - see the LICENSE.md file for details

