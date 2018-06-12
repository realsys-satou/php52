# command

## powershell

`mkdir php52`

`cd php52`

`vagrant init bento/centos-6.8`

- Vagrantfileの"private_network"行のコメント解除

`vagrant up`

## ssh

`sudo yum -y update`

`sudo yum -y install git`

`git clone https://github.com/gijutsubusoku/php52.git`

`cd php52`

`./run.sh`

`exec $SHELL -l`
