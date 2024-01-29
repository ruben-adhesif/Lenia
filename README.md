# Lenia

## Evolution of Game of Life

I saw on personal research that that is an evolution of the Game of Life. This representation of life is in discret space while Lenia is in continuous one. We can see on this version new interesting form of life.  

I extact the .\Python files from [the repos of Chakazul](https://github.com/Chakazul/Lenia.git)


## Setup environnement
I am on Ubuntu 20.04
```bash
wsl
virtualenv lenia_env
source lenia_env/bin/activate
pip install -r requirements.txt
```

## Use SSH Key
``` bash
$ eval `ssh-agent`
Agent pid 1761

$ ssh-add /home/ruben/.ssh/id_rsa
Identity added: /home/ruben/.ssh/id_rsa (ruben@adhesif)

-- Copier coller la clef PUBLIC dans github

$ git add .
$ git commit -m "modif"
$ git push git@github.com:ruben-adhesif/Lenia.git
/!\ Clef SSH differente que lien git
```