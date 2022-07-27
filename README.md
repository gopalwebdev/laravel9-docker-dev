app: http://localhost
phpmyadmin: http://localhost:8001/
username (phpmyadmin): sail
password (phpmyadmin): password

If any permission issue is there:
sudo chmod o+w ./storage/ -R

To run:
./vendor/bin/sail up
