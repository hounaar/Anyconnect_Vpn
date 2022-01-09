# Anyconnect
This doc is a way to install anyconnect vpn installation on Linux.
First you have to download the shell executable files which are on the src folder to run on terminal.

## Install
First you have to enable a executable code to the install file named vpn_install.sh

`chmod a+x vpn_install.sh`

If you want to know more about the `chmod` run this script 

`chmod --help`

the result will be like this :

 ![alt text](https://hounaar.com/github/anyconnect/main.png)
 
 
The code above will set a executable bit to the file. Then we have to install that.
`sudo vpn_install.sh`
after that your anyconnect vpn has been installed.
## Uninstall
For uninstalling the anuconnect, you have to download vpn_unistall.sh first.
After that the same as above set e executable bit to the file:

`chmod a+x uninstall vpn_uninstall.sh`

Now is the time to run the following script :

`sudo vpn_uninstall.sh`

Thats that simple to install anyconnect but pay attention that :
 ### You have to use some servers and an account of some vpn productions to connect to the UDP servers


