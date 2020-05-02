# docker-project
Very delighted to complete my docker project after completion of free docker training under the Linux world informatics ltd initiative IIEC-RISE under the world record holder Mr Vimal Daga sir.

ABOUT THE PROJECT :-
I had created a multi-tier Architecture to cope up with the real world problems that we face,
the infrastructure consists use of Docker container which are so faster that it can install and give an interacting interface to user just in a second and thereby saving our time so in this project i created a webapp of my own 'collection of wallpapers'using the open source content management tool Joomla 3.9.16 ,linked mysql:5.7 as a database server and by using docker-compose made a multitier infrastructure 
as a code like PLUG AND PLAY as manually doing it couild have taken lots of time but by using docker-compose we can do it very fast.

Following are the steps required to get the complete setup ready:-
step 1:
I used basically two docker containers so we need to pull these images: 
1.)mysql:5.7 and 
2.)joomla:3.9.16-php7.3-apache 
these images can be pull using the command ->docker pull mysql:5.7
and ->docker pull joomla:3.9.16-php7.3-apache

step 2:
Then we need to download docker-compose as it doesn't comes with linux by default.it can be downloaded from going to the website
https://docs.docker.com/compose/install and following the required instructions.

After installing we need to create a file named docker-compose.yml which is a yaml code file consisting the codes to launch our complete infrastructure using docker-compose.
Note-(always use file name as docker-compose)
Docker-compose consists of many steps as we need to setup the a)volumes b)services c)environments d)restart and at last we need to specify the version of docker-compose we are using.  
I have attached this yml file in my repository for the reference.

step 3:

Now we need to start our infrastructure and so we need to launch the docker-compose which can be done by initiating the following commands:
1.docker-compose up
This single command does all the work on behalf of us and thereby creates the multi-tier infrastructure and by checking the IP address of our system by using the command>>ipconfig enp0s3 ,we can get the required IP and use that with the port number 
used during compose to browse our webapp which in my case opens a joomla platform which we can use according to our own choice and create our own website.


                                                            THANK YOU




