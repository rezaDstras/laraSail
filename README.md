# laraSail
Docker with Laravel sail and phpmyadmin


- Access to phpmyadmin 
- localhost:8080

- Login in phpmyadmin
- user : sail
- password : password

- Build and Run :
- cd example-app
- ./vendor/bin/sail up

- Change title of ./vendor/bin/sail up (Create Alias for sail command) :
- In Command : nano ~/.bashrc
- End line insert : alias sail = 'bash vendor/bin/sail up'
- Save that


- Stop
- ./vendor/bin/sail down or sail down
