* ## Some of things to do after installation:
    * [40 things do after installing Linux](https://linuxhint.com/40_things_after_installing_ubuntu/)


* ## Through Command Line:

    1. Terminator: Terminal with better UI

            sudo apt install terminator

    2. git: 

            sudo apt install git-all

    3. ROS Melodic:

            sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
            sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654
            sudo apt update
            sudo apt install ros-melodic-desktop-full
            echo "source /opt/ros/melodic/setup.bash" >> ~/.bashrc
            source ~/.bashrc
            sudo apt install python-rosdep python-rosinstall python-rosinstall-generator python-wstool build-essential
            sudo apt install python-rosdep
            sudo rosdep init
            rosdep update

    4. catkin workspace for ROS:
	
            mkdir -p ~/catkin_ws/src
	        cd ~/catkin_ws/
	        catkin_make

    5. Simple Screen Recorder:

	        sudo apt-get install simplescreenrecorder
    
    6. dconf-editor: [Camera movement in RoadRunner](https://de.mathworks.com/help/roadrunner/ug/camera-movement-in-linux-or-ubuntu.html)

	        sudo apt-get install dconf-editor




* ## Through Website/Git clones/Software packages:

    1. [Google Chrome](https://www.google.com/chrome/thank-you.html?statcb=0&installdataindex=empty&defaultbrowser=0)

    2. [Discord](https://discord.com/?utm_source=google&utm_medium=advertising&utm_campaign=2020-01_google-de-registrations-brand_exact&utm_term=ENG-Text-Chat-Desktop-NA-All-All-All&utm_content=--t%3Apa&gclid=CjwKCAiAsOmABhAwEiwAEBR0ZlWRy8I9sRJmHPuAYHo_OfW0CXVY7fPRQG70VDIMjNTQSu9n25ZwoRoCt1kQAvD_BwE)

    3. [CARLA](https://carla.readthedocs.io/en/latest/build_linux/)

    4. [VisualStudio Code](https://code.visualstudio.com/docs/?dv=linux64_deb)

    5. [MATLAB RoadRunner](https://de.mathworks.com/downloads/web_downloads/download_roadrunner)

    6. [Blender](https://vitux.com/how-to-install-blender-3d-on-ubuntu/) - Ubuntu Software/snap store

    7. [esmini](https://github.com/esmini/esmini)

    8. [Team Viewer](https://www.teamviewer.com/en/download/linux/)

* ## Through Command Line:

    1. Numpy

            pip3 install numpy

    2. pygame: 

            pip3 install pygame


