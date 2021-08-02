# Nvidia Fan Control

GUI fan controller for Nvidia GPU
<br>
With this app you can set your preferred fan speed for Nvidia GPU (on Linux systems) without to use command line tools.
<br>

<b>Note:</b> Tested on GTX 460

![GUI Main Image](https://github.com/tudo75/nvidia-fan-control/blob/5308b771412321387d9f219d7e88ba8e4457abef/gui.png)

## Credits
Based on the work of Sabin Dcoster [nvidia-fan-control-gui-linux](https://github.com/dcostersabin/nvidia-fan-control-gui-linux)

## Disclaimer
NVIDIA is a registered trademark of NVIDIA Corporation.

Developers and app are not related to NVIDIA.

## Installation
To install the app:

<code>pip install nvidia_fan_control</code>

## Usage

1. Open application through the created menu launcher or from terminal <code>nvidiafancontrol</code>
2. Click on: <i>"Initialize Nvidia Xconfig"</i>
3. If you receive a positive confirmation dialog then click on: <i>"Reboot"</i>
If you receive an error message, you should install the <b>nvidia-smi</b> package and retry
4. After Reboot reopen app and set desired speed


