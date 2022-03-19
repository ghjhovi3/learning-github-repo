# Learning Github Day 01
- Created README.md
- Updated README.md
- Downloaded a clone of this repo locally.
- Added index.html locally.
- Learned new git commands
  - git clone https://github.com/ghjhovi3/learning-github-repo.git
  - git add . , this will follow what files that are being updated so that it would be ready for commiting changes
  - git commmit -m, -m is for adding message to the commit that you will be making, and git commit will update your repo locally
- Learned how to connect local machine to my github account
    - create SSH keys, ssh-keygen -t rsa -b 4096 -C "your@email.com" make sure to this command on users directory not on your git clone directory
    - after doing this command you can change the name for the keys and create a phrase for it
    - after filling up the phrase and the name of the keys there will be two files that will be generated one will be just the keyname you setup and the other one will be keyname.pub, copy the text content in keyname.pub
    - Next go to your github account
    - Next go to your settings
    - Under settings look for deploy keys, wherein you will be prompted to enter the keyname and the ssh key that you generated
    - After submitting it github will ask your password, just enter your password then submit

