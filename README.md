ROS interface to Usarsim simulator based on UDK (Unreal Development Kit)


### Installation

- Install Git
```
sudo apt-get install git #deb based
brew install git	# on mac using homebrew
```
- Clone the repo using 
```
git clone git://github.com/makokal/usarsim-ros.git
cd usarsim-ros
```
- Set up ROS env 
```
export ROS_PACKAGE_PATH=$ROS_PACKAGE_PATH:`pwd`
rosmake
```

- Run the application
``` 
rosrun executive_usarsim usarsim_manager.py 
```


### TODO
* Catkinize
