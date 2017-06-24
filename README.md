# IEEE_RasberryPi_Socket_Pokemon

The 2016 IEEE Fall Mini-Project Repo. All information is broken into 3 main folders with details below. Any questions please contact Spencer at sjfricke.at.wisc.edu

# Folder Breakdown

- **MainServer** all the backend server code and front end graphic code
- **Pi** all the Raspberry Pi socket server code
- **docs** guides used for teaching and setting up

# Things that are set and DO NOT CHANGE
Please, feel free to mess with the code and make your changes, but here are the things TO NOT alter unless full changes are made

- Port the Pi and Main server run on
  - I have the code hardcoded to look for port 5000 on the Pi and port 8000 on the Main server
- Database scheme
  - the names are uses as is so its easier to just add a new field instead of deleting one
- URL paths for HTTP request
  - The server expects the PI to have certain URL routes avaiable and same for the Main server
