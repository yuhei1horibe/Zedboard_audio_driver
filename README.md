# Zedboard_audio_driver
Zedboard audio device driver (combination of Xilinx I2S transmitter, I2S receiver and ADAU1761 CODEC).

Detail is explained in this article.
https://medium.com/@yuhei1.horibe/linux-device-driver-for-zedboard-audio-2-2-376888ffb64c

This driver is supposed to be used with Xilinx Linux repository below.
https://github.com/Xilinx/linux-xlnx

At the time of writing, this kernel version is 5.4. This driver DOES NOT work with PetaLinux tools since the kernel version for PetaLinux tools (at the time of writing) is 4.19.
