SmartMinerPRO (SMP/SMP+) - multi crypto mining panel
=================================

SMP + is a software product developed by SmartMiner.PRO with a simple and convenient GUI. This version of SMP + was created to work with each cryptocurrency based on these algorithms, including Bitcoin. Ethereum, Ethereum Classic, Sumocoin, Grin, Monero, Ravencoin and many others. This version of SMP + runs on Windows with AMD CPUs and GPUs or Nvidia and ASIC / FPGA.


Key Features SMP:
=================================

      • 💎 Built-in miners: XMR-STAK & XMRIG, GMINER. T-REX, TeamRedMiner, CGMiner, T-Rex, NBMiner, Nanominer, PhoenixMiner, CCMiner, miniz, cpu miner, cpuminer-opt, Kadena Miner, Kawpowminer and many others.
      • 🖥 Works on all versions of Windows (7, 8, 10)
      • Over 50 of the best mining puols
      • ℹ️ Complete information about each currency with links
      • 🔸 Easy to use
      • 📈 CoinGecko price and coin statistics
      • 📊 Coin mining statistics from Cryptunit
      • ♻️ CPU & GPU Mining
      • Easy installation of other miners and .bat configuration files.
      • To start mining using SMP +, just enter your wallet in the .bat file of the selected miner
      • SMP + has demonstrated high performance when working with Bitcoin, Ethereum, Ethereum Classic, Monero, Raven and other currencies, stands out for its high stability and easy setup.

DOWNLOAD LINKS SMP/SMP+:
=================================

SMP (SmartMinerPRO) - version without pre-installed miners and batch files
- SMP.rar (50.1 MB): https://mega.nz/file/VA1G1KgK#i8fZbwm_YK80kem4dHZL8x1KVET-p_-DYIgs6ZPd1f0
SMP+ (SmartMinerPRO) - version with a full package of pre-installed miners and batch files + instructions
- SMP+.rar (533.4 MB): https://mega.nz/file/tA0mgY5Q#RHwInzyqGMd5iOY4eMEBVNKl6l6kvI2FizOeFN7Dnx0
Miners Package - This is a complete package of all miners that support SMP +
- Miners Package [password:SMP+] (483.4 MB): https://mega.nz/file/tItj1YiJ#k-ky9tvyKA-8i1qhvwRdn21iZzVQvm_M7QTA45UDoE0

Release Note:
-------------

SMP + v1.0.1 is a smart multi-currency cryptocurrency miner for CPU / GPU / ASIC / FPGA. Which itself finds the available equipment and selects the optimal settings. SMP + allows you to connect / disconnect / stop / start one or more farms in one click. During the initial start-up, in the “Quick Start” step, you can select a separate algorithm for each farm. OS Support: Windows (64 bit).

How to start
=================================

1. Download SmartMinerPRO+
2. Unpack the archive
3. Run SMP.exe/SMP+.exe

IMPORTANT! For your mining equipment, you must install the necessary dependencies. Since each miner program has its own requirements for work. For reference, you can refer to the root directory in the miner’s folder.

System requirements
=================================

+ WINDOWS XP, 7,8,10 or later (x64) 
+ CPU (x64/x86/ARM)
+ OpenCL for AMD GPUs.
+ CUDA for NVIDIA GPUs

How to use
================================

1. At the first launch of SMP, select the coin to be mined
    • Optionally, you can choose what equipment will be used, according to the standard, all available CPU / GPUs are used.
2. Click "Start mining", in the mining parameters window, select the miner and the finished .bat file (coins \ pool)
    • By default, safe recommended settings for increased profitability of mining are used.
3. You can edit the .bat file to replace the wallet and pool values with your own by pressing the "EDIT" button.
    • If desired, you can replace the parameters of the request, for this we recommend that you refer to the practical guide in the root folders of the miners.
4. After replacing the values of the wallet and pool with yours, click "RUN"
5. Then begins the extraction of coins

Screenshots SMP+:
===============================

<img src="SMP + v1.0.PNG" />

<img src="SMP+ miners.PNG" />

Command line options
=====================

Network:
--------
    
    --no-cpu                  disable CPU mining backend
    -o, --url=URL                 URL of mining server
    -a, --algo=ALGO               mining algorithm 
      --coin=COIN               specify coin instead of algorithm
      -u, --user=USERNAME           username for mining server
      -p, --pass=PASSWORD           password for mining server
      -O, --userpass=U:P            username:password pair for mining server
      -x, --proxy=HOST:PORT         connect through a SOCKS5 proxy
      -k, --keepalive               send keepalive packet for prevent timeout (needs pool support)
      --nicehash                enable nicehash.com support
      --rig-id=ID               rig identifier for pool-side statistics (needs pool support)
      --tls                     enable SSL/TLS support (needs pool support)
      --tls-fingerprint=HEX     pool TLS certificate fingerprint for strict certificate pinning
      --daemon                  use daemon RPC instead of pool for solo mining
      --daemon-poll-interval=N  daemon poll interval in milliseconds (default: 1000)
      -r, --retries=N               number of times to retry before switch to backup server (default: 5)
      -R, --retry-pause=N           time to pause between retries (default: 5)
      --user-agent              set custom user-agent string for pool
      --donate-level=N          donate level, default %% (5 minutes in 100 minutes)
      --donate-over-proxy=N     control donate over xmrig-proxy feature
      
CPU backend:
------------

      --no-cpu                  disable CPU mining backend
      -t, --threads=N               number of CPU threads
      -v, --av=N                    algorithm variation, 0 auto select
      --cpu-affinity            set process affinity to CPU core(s), mask 0x3 for cores 0 and 1
      --cpu-priority            set process priority (0 idle, 2 normal to 5 highest)
      --cpu-max-threads-hint=N  maximum CPU threads count (in percentage) hint for autoconfig
      --cpu-memory-pool=N       number of 2 MB pages for persistent memory pool, -1 (auto), 0 (disable)
      --cpu-no-yield            prefer maximum hashrate rather than system response/stability
      --no-huge-pages           disable huge pages support
      --asm=ASM                 ASM optimizations, possible values: auto, none, intel, ryzen, bulldozer
      --randomx-init=N          thread count to initialize RandomX dataset
      --randomx-no-numa         disable NUMA support for RandomX
      --randomx-mode=MODE       RandomX mode: auto, fast, light
      --randomx-1gb-pages       use 1GB hugepages for dataset (Linux only)
      --randomx-wrmsr=N         write custom value (0-15) to Intel MSR register 0x1a4 or disable MSR mod (-1)
      --randomx-no-rdmsr        disable reverting initial MSR values on exit
      --astrobwt-max-size=N     skip hashes with large stage 2 size, default: 550, min: 400, max: 1200
      --astrobwt-avx2           enable AVX2 optimizations for AstroBWT algorithm

API:
------------

      --api-worker-id=ID        custom worker-id for API
      --api-id=ID               custom instance ID for API
      --http-host=HOST          bind host for HTTP API (default: 127.0.0.1)
      --http-port=N             bind port for HTTP API
      --http-access-token=T     access token for HTTP API
      --http-no-restricted      enable full remote access to HTTP API (only if access token set)

OpenCL backend:
---------------

      --opencl                  enable OpenCL mining backend
      --opencl-devices=N        comma separated list of OpenCL devices to use
      --opencl-platform=N       OpenCL platform index or name
      --opencl-loader=PATH      path to OpenCL-ICD-Loader (OpenCL.dll or libOpenCL.so)
      --opencl-no-cache         disable OpenCL cache
      --print-platforms         print available OpenCL platforms and exit

CUDA backend:
-------------

      --cuda                    enable CUDA mining backend
      --cuda-loader=PATH        path to CUDA plugin (xmrig-cuda.dll or libxmrig-cuda.so)
      --cuda-devices=N          comma separated list of CUDA devices to use
      --cuda-bfactor-hint=N     bfactor hint for autoconfig (0-12)
      --cuda-bsleep-hint=N      bsleep hint for autoconfig
      --no-nvml                 disable NVML (NVIDIA Management Library) support

TLS:
-----

      --tls-gen=HOSTNAME        generate TLS certificate for specific hostname
      --tls-cert=FILE           load TLS certificate chain from a file in the PEM format
      --tls-cert-key=FILE       load TLS certificate private key from a file in the PEM format
      --tls-dhparam=FILE        load DH parameters for DHE ciphers from a file in the PEM format
      --tls-protocols=N         enable specified TLS protocols, example: "TLSv1 TLSv1.1 TLSv1.2 TLSv1.3"
      --tls-ciphers=S           set list of available ciphers (TLSv1.2 and below)
      --tls-ciphersuites=S      set list of available TLSv1.3 ciphersuites

Logging:
---------

    -S, --syslog                  use system log for output messages
    -l, --log-file=FILE           log all output to a file
      --print-time=N            print hashrate report every N seconds
      --health-print-time=N     print health report every N seconds
      --no-color                disable colored output
      --verbose                 verbose output

Misc:
--------

    -c, --config=FILE             load a JSON-format configuration file
    -B, --background              run the miner in the background
    -V, --version                 output version information and exit
    -h, --help                    display this help and exit
      --dry-run                 test configuration and exit
      --export-topology         export hwloc topology to a XML file and exit
      --title                   set custom console window title
      --no-title                disable setting console window title      

