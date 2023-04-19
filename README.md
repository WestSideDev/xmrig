## ⛏️XMRIG⛏️
**Clone this repository and run the install file to build and install in your termux, the build can be fast or slow, it just depends on your device**

**Example:**
+ ``git clone https://github.com/WestSideDev/xmrig-android``
+ ``cd xmrig-android && chmod +x *``
+ ``./install``

## Usage
**In this example I will use the pool from [Unmineable](https://www.unmineable.com/)**

**Example:**
```
  -a, --algo=ALGO          cryptonight (default) or cryptonight-lite
  -o, --url=URL            URL of mining server
  -O, --userpass=U:P       username:password pair for mining server
  -u, --user=USERNAME      username for mining server
  -p, --pass=PASSWORD      password for mining server
  -t, --threads=N          number of miner threads
  -v, --av=N               algorithm variation, 0 auto select
  -k, --keepalive          send keepalived for prevent timeout (need pool support)
  -r, --retries=N          number of times to retry before switch to backup server (default: 5)
  -R, --retry-pause=N      time to pause between retries (default: 5)
      --cpu-affinity       set process affinity to CPU core(s), mask 0x3 for cores 0 and 1
      --cpu-priority       set process priority (0 idle, 2 normal to 5 highest)
      --no-huge-pages      disable huge pages support
      --no-color           disable colored output
      --variant            algorithm PoW variant
      --user-agent         set custom user-agent string for pool
  -B, --background         run the miner in the background
  -c, --config=FILE        load a JSON-format configuration file
  -l, --log-file=FILE      log all output to a file
  -S, --syslog             use system log for output messages
      --max-cpu-usage=N    maximum CPU usage for automatic threads mode (default 75)
      --safe               safe adjust threads and av settings for current CPU
      --nicehash           enable nicehash/xmrig-proxy support
      --print-time=N       print hashrate report every N seconds
      --api-port=N         port for the miner API
      --api-access-token=T access token for API
      --api-worker-id=ID   custom worker-id for API
  -h, --help               display this help and exit
  -V, --version            output version information and exit
      --percent            set single cpu max percent
      --simpleSpeed        simple show speed
```

``./xmrig -o yourpool:port -u Token:Your_wallet_address.name_for_your_miner -p x -k -a rx/0``

``./xmrig -o rx.unmineable.com:3333 -u BTC:bc1q2pu0jpl9f5xv9ltsx8cu0l6h00tghmw63849ms.WestSideDev01 -p x -k -a rx/0``

## Doubts ⁉️
**You can consult the original [repository](https://github.com/xmrig/xmrig) of this project, there you will have more information on how to configure it**

## `⚠️` Warning `⚠️`
**Maybe it's not worth it if your device is average, mining requires a lot of computational power and it's no different on a cell phone, you can get good results using several cell phones and even better if you have a snap 845+**
