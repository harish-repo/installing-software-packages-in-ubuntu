## installing-software-packages-in-ubuntu
#### Resynchronize the package index files from their sources via the Internet
```sh
$ sudo apt-get update
```

#### Install the newest versions of all packages currently installed system
```sh
$ sudo apt-get upgrade
```

#### Install a desired package. If package is already installed it will try to update to latest version.

```sh
$ sudo apt-get install package-name
```

#### Uninstall a package
```sh
$ sudo apt remove package-name
```
#### Installing vim
```sh
$ sudo apt-get install vim
```

#### Installing git

```sh
$ sudo apt-get install git -y
```
#### Installing visual studio code

```sh
$ curl https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > microsoft.gpg

$ sudo mv microsoft.gpg /etc/apt/trusted.gpg.d/microsoft.gpg

$ sudo sh -c 'echo "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main" > /etc/apt/sources.list.d/vscode.list'

$ sudo apt-get install code
```
#### Installing nodejs

```sh
$ curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -

$ sudo apt-get install -y nodejs

$ sudo npm install npm --global
```

#### Installing express

```sh
$ sudo npm install express
```
#### Installing mysql

```sh
$ sudo apt-get install mysql-server
```
#### Installing angular-cli

```sh
$ sudo npm install -g @angular/cli
```
#### Installing virtual box

```sh
$ sudo apt-get install virtualbox
```
#### Installing vagrant

```sh
$ sudo apt-get install vagrant
```

