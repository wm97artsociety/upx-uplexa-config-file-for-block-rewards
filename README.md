# upx-uplexa-config-file-for-block-rewards
metadata processing for block reward ryzen 5 5000 series 2 hours mining process 7 block reward 

check read me in code mode for correct coding script 

hash rate 22414 hs power to 29639hs power 


 Current Hash Rate: 16.39 KH/sec
 Average 1 Hour Hash Rate: 24.03 KH/sec
 Average 6 Hour Hash Rate: 12.17 KH/sec
 Average 24 Hour Hash Rate: 5.02 KH/sec
 Shares: 3745 Valid Shares  0 Invalid Shares 
 Last Share Submitted: about a minute ago
 Total Hashes Submitted: 2845864210
 Block Found: 13 pool / 15 solo
  Payments
 Pending Balance: 1.82 UPX
 Unconfirmed Balance:  5664.53 UPX
 Total Paid: 33459.30 UPX
 Last 24 Hours Paid: 2825.16 UPX



new amounts 5 mintues later 


 Current Hash Rate: 23.92 KH/sec
 Average 1 Hour Hash Rate: 26.04 KH/sec
 Average 6 Hour Hash Rate: 12.34 KH/sec
 Average 24 Hour Hash Rate: 5.23 KH/sec
 Shares: 3751 Valid Shares  0 Invalid Shares 
 Last Share Submitted: about a minute ago
 Total Hashes Submitted: 2860215407
 Block Found: 13 polo / 16 solo
  Payments
 Pending Balance: 1.82 UPX
 Unconfirmed Balance:  7077.13 UPX
 Total Paid: 33459.30 UPX
 Last 24 Hours Paid: 2825.16 UPX


5 minutes later 12:25 pm 8/12/2025 1 block found 


 Current Hash Rate: 23.47 KH/sec
 Average 1 Hour Hash Rate: 20.7 KH/sec
 Average 6 Hour Hash Rate: 12.18 KH/sec
 Average 24 Hour Hash Rate: 5.35 KH/sec
 Shares: 3760 Valid Shares  0 Invalid Shares 
 Last Share Submitted: about a minute ago
 Total Hashes Submitted: 2874296074
 Block Found: 13  / 17 
  Payments
 Pending Balance: 1.82 UPX
 Unconfirmed Balance:  8489.57 UPX
 Total Paid: 33459.30 UPX
 Last 24 Hours Paid: 2825.16 UPX



had to make sure file was working way new to crypto bipolar is awesome :) i have a 28 day later rage disorder 

block meta data processing usage for threads and miner

meta data processes block height and info through meta data 

if a system has 12 threads

you would set 8 threads to mining which on upx gives 30k hs power for mining

and 2 threads for processing meta data blocks i removed the file due to bipolar and not knowing if the software was working properly 

test two has mined 6 blocks in 2 hours with meta data processing 

while you want to leave two threads for normal tasks like music and elements of processing with cpu temp cooling at 68 c start to 75 c stop 


add huge page for 5-15% boost in cpu power

add extra fan to cool system 


have fun getting blocks maybe one day the token will be worth alot 


{
    "algo": "cryptonight-upx/2",
    "api": {
        "port": 0,
        "access-token": null,
        "id": null,
        "worker-id": "Wm97#1",
        "ipv6": false,
        "restricted": true
    },
    "asm": true,
    "autosave": true,
    "background": false,
    "colors": true,
    "cpu-affinity": false,
    "cpu-priority": null,
    "donate-level": 1,
    "huge-pages": true,
    "hw-aes": null,
    "log-file": null,
    "max-cpu-usage": 100,
    "av": 1,

    "pools": [
        {
            "url": "upx.miningocean.org:4372",
            "user": "solo:UPX1jfkK8LrdewbhD9rYSEWXq2zoUDFpgZxxgAP52frG7K73pZzmgd7h2HpSjqMt4PLTWbBD7N1zjU63XwZX89D23X1j3VMJeo",
            "pass": "x",
            "rig-id": null,
            "nicehash": false,
            "keepalive": true,
            "variant": 1,
            "tls": false,
            "tls-fingerprint": null
        }
    ],

    "print-time": 60,
    "retries": 5,
    "retry-pause": 5,
    "safe": false,
    "user-agent": null,
    "watch": true,

"cpu": {
  "enabled": true,
  "huge-pages": true,
  "huge-pages-jit": true,
  "hw-aes": null,
  "priority": 2,
  "memory-pool": false,
  "yield": true,
  "asm": true,
  "threads": 8
},

    "randomx": {
        "init": -1,
        "init-avx2": -1,
        "mode": "fast",
        "1gb-pages": false,
        "rdmsr": true,
        "wrmsr": true,
        "cache_qos": false,
        "numa": true,
        "scratchpad_prefetch_mode": 1
    },

    "opencl": {
        "enabled": false,
        "cache": true,
        "platform": "AMD",
        "adl": true
    },

    "cuda": {
        "enabled": false,
        "nvml": true
    },

    "health-print-time": 60,
    "dmi": true,
    "syslog": false,

    "tls": {
        "enabled": false,
        "protocols": null,
        "cert": null,
        "cert_key": null,
        "ciphers": null,
        "ciphersuites": null,
        "dhparam": null
    },

    "dns": {
        "ip_version": 0,
        "ttl": 30
    },

    "verbose": 0,
    "pause-on-battery": false,
    "pause-on-active": false,
    "temperature-limit": 75,
    "temperature-start": 68,

    "_metadata": {
        "enabled": true,
        "threads": 2,
        "mode": "block-analysis",
        "source": "upx.miningocean.org:4372/json_rpc",
        "reward-calculation": {
            "method": "solo",
            "block_reward": "auto",
            "interval": 60
        }
    }
}



