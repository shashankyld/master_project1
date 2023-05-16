# master_project1


## Uninstall Existing CUDA  - NOT 100% Reliable (From a youtube video)
### 1. Removing existing CUDA
```
sudo apt --purge remove "cublas*" "cuda*"
sudo apt --purge remove "nvidia*"
rm -rf /usr/local/cuda*
sudo apt-get autoremove && sudo apt-get autoclean
```
### Now you need to reboot
### reboot

### 2. Downloading specific CUDA version
### Install build essentials

```sudo apt-get install g++ freeglut3-dev build-essential libx11-dev libxmu-dev libxi-dev libglu1-mesa libglu1-mesa-dev
```
