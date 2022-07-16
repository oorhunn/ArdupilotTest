# ArdupilotTest
* after cloning repo
    
        git submodule update –init --recursive 

* Install some required packages 

        Tools/environment_install/install-prereqs-ubuntu.sh -y 
* Cleaning  
        
        ./waf clean
        ./waf list_boards 
        ./waf configure --board CUAV-X7  


* Building 

		./waf plane
