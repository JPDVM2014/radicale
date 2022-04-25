# docker-radicale

1. Install the docker-radicale template from Unraid Community Applications. 

2. Make sure to mount an appdata/config directory and a data directory.

3. Place the sample config file (https://github.com/JPDVM2014/radicale/blob/main/config) and sample users file (https://github.com/JPDVM2014/radicale/blob/main/users) into the config directory. (NOTE: The file names should be "config" and "users" without the quotation marks. No leading period or extension.)

4. The only required change to these files is to delete the admin user from "users" and replace with your own.
   4a. The format for users is "username:password"
   4b. The provided config uses bcrypt as the hashing algorithm. You can use https://bcrypt.online to create a hash. Set whichever cost factor you prefer. The default is 10.
   
5. Once the files are in place, you can start the container, and you should be able to access the WebUI.

This is a basic configuration to get up and running quickly. For more advanced configuration options, refer to the image creator's github at https://github.com/tomsquest/docker-radicale.




