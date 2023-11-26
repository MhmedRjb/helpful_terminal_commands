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




