# DevSettings

## Ubuntu Terminal

[Tmux Plugin](./.tmux.conf)

## Init Github repository & Connect to Local

[github] Create Repository @ github page
  
[local]
```
  echo "# cs231n_study" >> README.md
  git init
  git add README.md
  git commit -m "first commit"
  git remote add origin <link>
  git push origin master
```
## Installing Python3.7 in Ubuntu
### setting
```
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update
sudo apt install python3.7
```
### alias
File /home/dongmin/.bashrc
```
alias python=python3.7
alias pip=pip3
```
