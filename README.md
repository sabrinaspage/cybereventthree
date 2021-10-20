# Password Cracking

Today, we'll be **password cracking** on your favorite Linux interface.  The purpose of this assignment is so that you may familiarize yourself with offensive security and **red team principles**. Thus, by the means of hashing, you will learn what the best password principles are.

## Install Kali Linux

We'll be going with a beginner friendly tool - Kali Linux. It is the premier choice amongst pen testing tool; coming with a large community and advanced features.

You'll want to start off by downloading **[VirtualBox](https://www.virtualbox.org/)**. VirtualBox is a cross-platform virtualization software developed by Oracle Corporation that allows a user to run guest operating systems on their host operating system without the need for partitioning their hard drive or running another OS on dual boot. These guest OS include Microsoft Windows, Mac O X, Linux, and Oracle Solaris, amongst others.

You'll then want to follow the steps in [**this article**](https://phoenixnap.com/kb/how-to-install-kali-linux-on-virtualbox). This can be a tedious process, but do not be discouraged! It is normal for bugs in software or hardware to occur. This is where iteration and patience is key. You may come across a *‘fatal system kernel error’* message in the process - in that case, downgrade VirtualBox to a different version.

Once you have completed all steps, delete the `.iso` file. The virtual machine, which is an emulation of a computer system, will be installed already, so no need to consume disk space! It is there simply for installation purposes.

### Alternatives to Kali Linux

If you need a lightweight alternative, **[Parrot OS](https://parrotsec.org/docs/installation.html)** is your best friend. It has a similar toolset and is an equally viable option to Kali Linux.

You could also install **[Window Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install)** on your Windows system. This helps if you are running low on space, since it installs the Linux tools you need, rather than the OS itself.

## Getting Started

Once you have a Linux interface setup, you'll want to open up your terminal and install the following commands.

```
sudo apt-get update 
sudo apt-get upgrade
sudo apt-get dist-upgrade 
sudo apt install python3-pip 
sudo apt-get install python3 
python3 -m pip install pysha3 
sudo pip3 install bcrypt 
sudo pip3 install scrypt 
sudo pip3 install omnihash 
```

You may copy all these commands and paste them into your terminal, rather than going one by one. We'll be going over the usage of the packages installed shortly.

## Ophcrack - LanMan Rainbow Table

ndsjfk

## Hash Identifier Accuracy

sdufijnks

## HashCat

dsfnjs
