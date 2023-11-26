#!/bin/bash
wget https://github.com/xmrig/xmrig/releases/download/v6.21.0/xmrig-6.21.0-focal-x64.tar.gz
tar -zxvf xmrig-6.21.0-focal-x64.tar.gz
 cd xmrig-6.21.0
screen -R
./xmrig -o zephyr.miningocean.org:5332 -a rx -k -u ZEPHsA4pLFiEotGraEQAJx7GUHPirbBWiUZy9r34hvaTS6JqUTiWr2RhK9ySV2KWFwZpAEvm3AeGLPGcnDjCiMG9DHphpBP4tAm -p hung -t 8
fi
