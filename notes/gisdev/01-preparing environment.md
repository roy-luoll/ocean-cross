1. Install Ubuntu 16.0 on virtual-box machine
2. install add-ons
3. Adjust alias to use Python 3:
   edit /etc/bash.bashrc to append following two lines:
   alias python='python3'
   alias pip='pip3'
   
4. Install PostgreSQL database system:
    $sudo apt-get install postgresql
    
5. change user password of postgres
  $sudo passwd postgres
  
6. install gdal
   http://trac.osgeo.org/ubuntugis/wiki/UbuntuGISRepository
   update achive repostitory
   $ sudo add-apt-repository ppa:ubuntugis/ppa
   $ sudo apt-get update
   (TBD)
   
