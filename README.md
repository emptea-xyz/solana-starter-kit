# Chapter 1
In this chapter you will set up your work environment to work with Solana.

### 1.1 Operating System
To develop Solana programs we recommend to use Ubuntu or MacOS. 
Anchor doesn't support Windows at the moment so you have to use a Linux Subsystem.
If you're running Windows and want to use Ubuntu , you have two options:
* use a Virtual Machine(VM)
* Install Ubuntu on your machine

#### Links
* [Ubuntu download (LTS)](https://ubuntu.com/download/desktop)
* [Create a Ubuntu-VM (VMWare)](https://data-flair.training/blogs/how-to-install-ubuntu-on-vmware-player/)
* [Create a Ubuntu-VM (VirtualBox)](https://ubuntu.com/tutorials/how-to-run-ubuntu-desktop-on-a-virtual-machine-using-virtualbox)
* [How to install Ubuntu on your machine](https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview)

### 1.2 Rust 
We use Rust to develop Solana programs. 

#### Install on Ubuntu 
1. `sudo apt install curl`- install cURL.
2. restart terminal
3. `curl --version`- check if it's installed correctly
4. `curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`- install rust
5. restart terminal
6. `rustc --version`- check if it's installed correctly
7. Let's go!
If Rust isn't working check your PATH-system variables by entering: `echo $PATH` 
and make sure Rust is in there. 
If it's still not working, get in the discord to ask for help.

#### Install on MacOS 
1. `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" < /dev/null 2> /dev/null`- install brew.
3. restart terminal
4. `brew install curl`-install cURL. 
5. restart terminal
6. `curl --version`- check if it's installed correctly
7. `curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`- install rust
8. restart terminal
9. `rustc --version`- check if it's installed correctly
10. Let's go!
If Rust isn't working check your PATH-system variables by entering: `echo $PATH` 
and make sure Rust is in there. 
If it's still not working, get in the discord to ask for help.

#### install on Windows

1. `curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh` - install Rust
2. `rustup --version` check if it's installed correctly.
