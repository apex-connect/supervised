# Apex Connect+ MCU (Supervised Install)
This is a builder for docker-compose to easily make and maintain Apex Connect+ MCU on the Raspberry Pi.


## Installation
1. On the (RPi) lite image you will need to install git first

```
sudo apt-get install git -y
```

2. Download the repository with:
```
git clone https://github.com/apex-connect/supervised.git ~/supervised
```

Due to some script restraints, this project needs to be stored in ~/supervised

3. To enter the directory and run menu for installation options:
```
cd ~/supervised && bash ./menu.sh
```

4. Install docker with the menu, restart your system.

5. Run menu again to select your build options, then start docker-compose with
```
docker-compose up -d
```
