#Build envrironment

Prepare Ubuntu 18.04 desktop

#Prepare snapcraft

snap install --classic snapcraft

#Build

Cross on x86 systems
Just run snapcraft in the top of the gadget or kernel folder

sudo snapcraft --target-arch=armhf
