# Bitcoin private key database
A database of all Bitcoin private keys

**Note:** This is an open-source clone of directory.io for my personal educational-purpose.

This website contains all the possible Bitcoin private key.

A private key it's just a number chosen randomly from a range,
if this range (called key-space) is big enough it won't be possible 
to list all the keys in feasible times.

Bitcoin private keys range from 1 to 115792089237316195423570985008687907852837564279074904382605163141518161494336

The key-space it's too big to index all the keys ([http://redd.it/1rurll](http://redd.it/1rurll)), but you can however generate private keys on demand.

For this reason I have developed this on-demand database and also a Lottery that will take a random private key from the key-space and tell you if it has some bitcoin available. ;)

## Installation

    pip3 install -r requirements.txt

## Usage

    chmod +x ./run.sh
    ./run.sh

### Donate
BTC: 1EhJyJwzbp7v2ixPT4heM2caUsmWcX36mc
Monero: 47Yk8KgtYyaV2RvzJLQKuuMzhiZD5ktdbNzP6jxsjkdSKD8j81uLRCYXKLFVFtsCbLjbyamGBES58Mi4r8wHEGht8ofEVu7