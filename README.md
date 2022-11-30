# <p align="center"> <img src="https://user-images.githubusercontent.com/69895353/200911653-203af161-a56b-42ca-b3f8-8d1d6ec62956.png" width="300px"/> </p>

# <p align="center"> Fast-Type 

### <p align="center"> A terminal-base Typing Game for UNIX users.</p>

<p align="center">
  <img src="https://img.shields.io/github/license/gambhirsharma/Fast-Type">
  <img src="https://img.shields.io/github/languages/top/gambhirsharma/Fast-Type">
  <img src="https://img.shields.io/github/languages/code-size/gambhirsharma/Fast-Type">
</p>

## 👇🏽 Prerequisites

Before installation, please make sure you have already installed the following tools:
* Git
* Linux system (If you are windows user use WSL)
* make


## 🛠️ Installation 

> **Note**: Fast-Type don't natively support in Windows system. Use WSL(Windows Subsystem for Linux) if you are Windows user.


### <a name="section-1"> Install from Source </a>
Open your terminal in your preferred directory and clone this repository:

```sh
git clone https://github.com/gambhirsharma/Fast-Type
```

Run the makefile

```sh
cd Fast-Type/Fast-type/
make
```

Run Fast-Type

```sh
./FastType
```

**Install**: After building the binary, you can choose to install FastType to your `usr/local/bin` directory by

```sh
[sudo] make install
```

Now you could run FastType from anywhere with

```sh
FastType
```

## Setup WLS (Windows Users)
* Download any WSL of you choice. I chose Ubuntu

<img src="https://user-images.githubusercontent.com/69895353/204749851-9cc25f82-bde2-4bcf-9407-a26e07cf2c12.png" width="400px"/>

* Go to Windows Features by typing ``Turn Windows features on or off`` in search bar. Then search for ``Windows Subsystem for linux`` and select it.

<img src="https://user-images.githubusercontent.com/69895353/204751029-531a8036-a24d-4747-ab4d-cdb6a73ff0ab.png" width="600px"/> <img src="https://user-images.githubusercontent.com/69895353/204751058-f7fa67ec-a0ae-4123-a2c2-314fdf0064fe.png" width="400px"/>

* Open WSL and install all dependencies
```
sudo apt install git make g++ libncurses5-dev libncursesw5-dev
```
<!-- if this not work
sudo apt-get install libncurses5-dev libncursesw5-dev 
-->

Now your windows system is redy for building the project. Follow the [Install from Source](section-1) to build project form source code.

**Enjoy typing**

## 🛡️ License

Fast-Type is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## 💪🏽 Thanks to all Contributors

Thanks a lot for spending your time helping Fast-Type grow. Thanks a lot! Keep rocking🍻

[![Contributors](https://contrib.rocks/image?repo=gambhirsharma/Fast-Type)](https://github.com/gambhirsharma/Fast-Type/graphs/contributors)
