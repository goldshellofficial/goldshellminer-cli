# goldshellminer-cli
Introduction
It is a mining software to interact with goldshell home-mining device (HS1, HS1-Plus)

HS1: #

HS1-Plus: #

Mining Guide
Tested on Linux, Windows and Mac OS.

1.Install Node.js
v10.15.3 is recommended and tested

2.Clone code
$:git clone https://github.com/goldshellofficial/goldshellminer-cli.git

3.Install dependency
$:npm install

4.Config pool
Config ./config.json to set your pool.

DXPOOL for example

{
  "loglevel": -1,
  "miners": [
    {
      "cryptoname": "hns",
      "minername": ["Goldshell-HS1", "Goldshell-HS1-Plus"],
      "pool": {
        "host": "hns.ss.dxpool.com",
        "port": 3009,
        "user": "USERNAME.WORKERNAME",
        "pass": "x"
      }
    }
  ]
}

5.Start Mining
$:npm run dashboard

6.Stop Mining
(Ctrl+C, Q, or ESC to stop the dashboard miner)
