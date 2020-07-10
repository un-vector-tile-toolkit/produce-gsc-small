# produce-gsc-small
small scale tile production


# How to use
vi config/default.hjson  
mkdir /data/small-zxy  

npm install  
node index.js

If you are running this at windows environment, please use docker (for tippecanoe).  

Need to have gdal greater than 2.4.0  
If not,     
sudo apt update  
sudo apt install software-properties-common  
sudo apt-get install python3.6-dev  
sudo add-apt-repository ppa:ubuntugis/ppa  
sudo apt-get install gdal-bin  
