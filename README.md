# Robotics_Project1
This is a demonstration of the creation of a Gazebo World and a plugin

To execute the Project:

1. Clone the Repository "Robotics_Project1" to your /home/<user> directory
	
        cd ~
        git clone https://github.com/andreslc47/Robotics_Project1.git
        cd ~/Robotics_Project1/
        
	
2. Create a "build" directory and compile the project
	
        mkdir build
        cd build/
        cmake ../
        make
 
	
3. Add the directory "build" to the GAZEBO_PLUGIN PATH environment variable
	
        export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:/home/<user>/Robotics_Project1/build
	

4. Launch Gazebo

        cd ~/Robotics_Project1/world
	gazebo UdacityOffice.world --verbose

5. 
	
6. To close everything:

        cd ~/Robotics_Project1/
        ./pkill_all
