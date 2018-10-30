Bitsum Command Line Tools v0.1.0c
Contents:
komodod - SumCoin's enhanced Komodo daemon.
komodo-cli - SumCoin's enhanced Komodo command line utility.
bitsum - wrapper for komodo-cli that applies the command to the SUM coin
bitsumd - wrapper for komodod that sets the SumCoin parameters to defaults properly
fetch_params.sh - utility to download the zcash parameters needed to start the SumCoin command line tools and scripts
lib*.dylib - assorted dynamic libraries, dependencies needed by fetch-params.sh, komodod and/or komodo-cli

Command line tools are run from the terminal. You can launch the terminal on a Mac by using the Finder, selecting Applications and from that select Utilities, finally selecting Terminal from the Utilities folder.
You will need to switch to the directory you extracted the bitsum-cl into. If you extracted it in the Download folder then the change directory command is
cd ~/Downloads/bitsum-cli
The first time on a new system you will need to run ./fetch-params before using komodod or bitsumd.

Run ./bitsumd to launch komodod, and use bitsum to run commands such as:
./bitsum stop
Which signals komodod (if it is running) to stop running.
