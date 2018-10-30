Bisum Command Line Tools v0.1.0c
Contents:
komodod.exe - SumCoin's enhanced Komodo daemon
komodo-cli.exe - SumCoin's Komodo command line utility
bitsum.bat - wrapper for komodo-cli that applies the command to the VRSC coin
bitsumd.bat - wrapper for komodod that sets the SumCoin parameters to defaults properly

You need to run a command prompt, for example hit <Ctrl><Esc> and type cmd<Enter>
From the command prompt change to the directory where you installed bitsum-cli. If you downloaded the file to your Downloads directory and extracted it there then the change directory command is
cd \Users\MyName\Downloads\bitsum-cli
From this directory you can run the Bitsum command line utilities.
The first time on a new system you will need to run fetch-params before using komodod.exe or bitsumd.
Many anti-virus products interfere with the SumCoin tool's ability to open ports and will need to be configured to allow what the scanner says is unsafe behavior.
Extreme cases can result in the virus scanner deleting Agama.exe or moving it to "protect" the system. You will to add the executables to a whitelist and re-extract the bitsum-cli-windows.zip file if that happens.
Run bitsumd.bat to launch komodod, and use bitsum.bat to run commands such as:
bitsum.bat stop
Which signals komodod.exe (if it is running) to stop running.

Note that if you pass in command line options to bitsum.bat or bitsumd.bat that include an = like -ac_bitsumpos=50 you must surround it with double quotes like this:
bitsumd.bat "-ac_sumpos=50"
Otherwise Windows will drop the = and pass the two values in as separate command line options.
