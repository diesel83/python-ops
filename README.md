# python-ops

## Install Packages

sudo su -
yum update
yum groupinstall -y "development tools"
yum install -y \
 lsof \
 wget \
 vim-enhanced \
 words \
 which
exit

## Configure Git

git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"

## Custom bashrc

curl $RAW_GITHUB_BASH_URL -o ~/.bashrc

## Custom Vim

curl $RAW_GITHUB_VIM_URL -o ~/.vimrc