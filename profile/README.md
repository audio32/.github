# Low-cost low-latency ethernet audio transmission for local high-channel count applications

This is the result of a master's thesis project building a scalable, DIY audio transmission for low-cost audio installations, ideal for high-channel count applications like Wave Field Synthesis (WFS).


The project uses off-the-shelf Nucleo-F767 boards. Each of which is capable of driving 32 individual audio channels. The Precision Time Protocol (PTP) ensures accurate playback timing to minimize audio unwanted interferences.


The project is split in three parts:
- [Audio32 Firmware](https://github.com/audio32/audio32-firmware): running on the STM32
- [Audio32 Server](https://github.com/audio32/audio32-server): running on the Linux system containing the audio source
- [Audio codec extension PCB](https://github.com/audio32/audio32-codec-pcb): facilitates connecting 32 audio codecs to a single STM32
