# BitSurv

 A Survey Engine for developers, by developers

# Installation

 First, get git if you don't got it.
 
 Clone this repo and enter it:
 
     git clone --recursive https://github.com/agroff/bitsurv.git
     cd bitsurv
 
 Get composer if you don't have it.
     
     curl -sS https://getcomposer.org/installer | sudo php -- --install-dir=/usr/local/bin --filename=composer
     
 Install Dependencies:
 
      composer install
 
 Create your config file and edit it
 
      cp config.sample.php config.php
      nano config.sample.php #only if you need to change something in here
 
 