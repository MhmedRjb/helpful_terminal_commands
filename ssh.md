![image](https://github.com/MhmedRjb/helpful_terminal_commands/assets/72052305/ee540420-0787-4fe7-9f22-39da93d5fc26)

#### insatll openssh-server openssh-client
`sudo apt-get install openssh-server openssh-client`
#### Check for Existing SSH Keys
`ls -al ~/.ssh`
#### Generate SSH Key Pair
`ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`
#### Add SSH Key to SSH Agent
`eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa`
#### Copy Public Key to GitHub
`cat ~/.ssh/id_rsa.pub`
#### Test SSH Connection
`ssh -T git@github.com`
