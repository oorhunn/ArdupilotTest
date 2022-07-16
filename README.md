# ArdupilotTest
* after cloning repo
    
        git submodule update –init --recursive 

* Install some required packages 

        Tools/environment_install/install-prereqs-ubuntu.sh -y 
* Cleaning  
        
		./waf distclean
		./waf clean
		./waf list_boards 
		./waf configure --board CUAV-X7  


* Building 

		./waf plane

* SITL
* * preconditions

		cd ~/ardupilot/ArduCopter	
		../Tools/autotest/sim_vehicle.py --map --console
		sim_vehicle.py --help
