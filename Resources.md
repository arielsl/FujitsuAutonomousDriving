#Resources

####This page includes all links to necessary assets to our projects, as well as links to tutorials and credit to works referenced.

##Project Requirements:
The main three parts for this project are:
- The [OpenDaVinci simulator](https://github.com/davjs/AutodriveSim) suited to run the driving scenarios
- A [toy car](http://makezine.com/projects/build-android-powered-autonomous-rc-car/) modified with sensors and capable to be mounted with sensors
- The [Android Carduino](https://github.com/Petroula/Android-Car-duino) application to communicate with the toy car

##Running the simulator
In order for the simulator to run, a few things must be prepared before:
- Access to Ubuntu [12.04](http://releases.ubuntu.com/12.04/) or [14.04](http://releases.ubuntu.com/14.04/). A copy of a VirtualBox is provided later.
- The [OpenDaVinci simulator](https://github.com/davjs/AutodriveSim) suited to run the driving scenarios
- Knowledge of the [Linux enviroment](http://ryanstutorials.net/linuxtutorial/)

To run the simulator two main commands are needed: `./build.sh` and `./autodrive.sh` inside the `AutodriveSim` directory:

1. Everytime a change is made to the simulator or ran for the first time, it needs to be build again.
2. The autodrive file runs the simulator and opens it in another window.
3. To edit the driving logic, the files on the `include` directory must be changed.
4. To change the driving scenarios the `configuration` file on `/opt/odv/bin/configuration` must be edited
5. To edit the scenarios, [ScUI](http://opendavinci.cse.chalmers.se/www/products/ScUI/index.html) must be opened in the environment. Needs the [Docker Engine](https://docs.docker.com/engine/installation/linux/ubuntu/) to be installed in the machine.

####Pre made VirtualBoxes
- A virtual [image of Ubuntu 12.04]() with the simulator already running
- A virtual [image of Ubuntu 14.04]() with the simulator and ScUI running


##Credits
- The basis of the project goes to Dimitris Patris' [Build Your Own Android-Powered Self Driving R/C Car](Build Your Own Android-Powered Self Driving R/C Car)
- The instructions for installing OpenDaVinci provided by [davjs](https://github.com/davjs/)
- Android Carduino by [Petroula](https://github.com/Petroula/)
- [OpenDaVinci website](http://opendavinci.cse.chalmers.se/www/)
- All other open source assets used are owned by their respective creators.
