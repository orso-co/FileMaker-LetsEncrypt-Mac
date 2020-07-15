# FileMaker-LetsEncrypt-Mac
A bash script for fetching and renewing Let's Encrypt SSL certificates for FileMaker Server running on Mac.

How to use it (should work, without guarantee):

1. install [homebrew](https://brew.sh/) if it is not installed already
2. install certbot: `brew install certbot`
3. download the git repo
4. change the directory to the downloaded folder
5. find out what shell you use: `echo $SHELL`
6. the file you'll need is either "GetSSH.zsh" if your are using the zsh shell or propably "GetSSH.sh" for bash or sh
7. edit the file and change the domain name on line 13
8. run the script: either `sudo ./GetSSH.zsh` or  `sudo GetSSH.sh` depending on your shell
9. good luck!


The original instructions and an example video can be found at https://bluefeathergroup.com/blog/lets-encrypt-ssl-certificates-for-filemaker-server-for-mac/
