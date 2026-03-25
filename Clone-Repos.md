Clone Repos

 - install git for windows, use the mingw64 tool
 - use bash to enter shell from terminal

 - eval 'ssh-agent -s'
 - ssh-keygen -t ed25519-sk -C "adam.eisert@pascaltags.com"
 - cd :\Program Files\Git\bin
 - exec ssh-agent bash
 - ssh-add c:/Users/Jimmy/.ssh/id_ed25519
 - add the key to github (settings > SSH/PGP Keys)
 - ssh -T git@github.com <- successful test

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent


 - git config --global user.email ""
 - git config --global user.name ""
 - ssh -T git@github.com
 - ssh -vT git@github.com

 - git clone :SSH stuff
