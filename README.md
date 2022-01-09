# Anyconnect
This doc is a way to install anyconnect vpn installation on Linux.
First you have to download the shell executable files which are on the src folder to run on terminal.

## Install
First you have to enable a executable code to the install file named vpn_install.sh
`chmod a+x vpn_install.sh`

If you want to know more about the `chmod` run this script 
`chmod --help`
the result will be like this :
  `Usage: chmod [OPTION]... MODE[,MODE]... FILE...
  or:  chmod [OPTION]... OCTAL-MODE FILE...
  or:  chmod [OPTION]... --reference=RFILE FILE...
Change the mode of each FILE to MODE.
With --reference, change the mode of each FILE to that of RFILE.

  -c, --changes          like verbose but report only when a change is made
  -f, --silent, --quiet  suppress most error messages
  -v, --verbose          output a diagnostic for every file processed
      --no-preserve-root  do not treat '/' specially (the default)
      --preserve-root    fail to operate recursively on '/'
      --reference=RFILE  use RFILE's mode instead of MODE values
  -R, --recursive        change files and directories recursively
      --help     display this help and exit
      --version  output version information and exit

Each MODE is of the form '[ugoa]*([-+=]([rwxXst]*|[ugo]))+|[-+=][0-7]+'.

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/chmod>
or available locally via: info '(coreutils) chmod invocation'
`
The code above will set a executable bit to the file. Then we have to install that.
`sudo vpn_install.sh`
after that your anyconnect vpn has been installed.
## Uninstall
For uninstalling the anuconnect, you have to download vpn_unistall.sh first.
After that the same as above set e executable bit to the file :
`chmod a+x uninstall vpn_uninstall.sh`
Now is the time to run the following script :
`sudo vpn_uninstall.sh`

Thats that simple to install anyconnect but pay attention that :
 ### You have to use some servers and an account of some vpn productions to connect to the UDP servers


