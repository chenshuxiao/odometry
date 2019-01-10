# Odometry

## License
This repository is under the [MIT License](https://github.com/chenshuxiao/odometry/blob/master/LICENSE "MIT License used in this repository").

## Use
This repository is meant to be used as a way to evaluate the performance of the [ZED Mini](https://www.stereolabs.com/zed-mini/ "ZED Mini").
In order to do you, we conducted multiple experiments. First, we tried to limit the 6-DOF-system to only meassure the performance in a 1-DOF case. In this scenario the [ZED Mini](https://www.stereolabs.com/zed-mini/ "ZED Mini") was connected to a [AGX Xavier](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems-dev-kits-modules/ "AGX Xavier").
Secondly, we mounted the [ZED Mini](https://www.stereolabs.com/zed-mini/ "ZED Mini") onto a [DJI F330](https://www.dji.com/newsroom/news/dji-releases-flamewheel-f330-arf-kit "DJI F330")-Frame using an [Aerocore 2 for Jetson TX2](https://store.gumstix.com/development-boards/aerocore-2/aerocore2-for-nvidia-jetson.html "Aerocore 2") for intercommunication running [PX4](https://github.com/PX4/Firmware "PX4") v1.8.0 and a [Jetson TX2](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems-dev-kits-modules/ "Jetson TX2").

## Included data
* .bag-file(s) from the different experiments
* .csv-files with the topics of the bagfiles
* Jupyter Notebook with evaluation

## Further resources
Videos showcasting the experiments can be found [here](https://www.youtube.com/playlist?list=PLhWaDMVPx95YjtxWDsKGIb2X4LEdHBCGH "YouTube-Playlist with videos of the experiment").

## Support
No support will be provided.
