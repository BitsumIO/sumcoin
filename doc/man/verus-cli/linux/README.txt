Bitsum Command Line Tools v0.1.0c

Contents:
komodod - SumCoin's enhanced Komodo daemon
komodo-cli - SumCoin's Komodo command line utility
bitsum - wrapper for komodo-cli that applies the command to the VRSC coin
bitsumd - wrapper for komodod that sets the SumCoin parameters to defaults properly

The first time on a new system you will need to run ./fetch-params before using komodod or bitsumd.

Run ./bitsumd to launch komodod, and use bitsum to run commands such as:
./bitsum stop
Which signals komodod (if it is running) to stop running.
