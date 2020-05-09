## IIEC DOCKER PROJECT 
 I have learnt the docker under the guidence of **MR.Vimal Daga sir** in campaign **IIEC-RISE 1.0** which is his intiative on youtube.
Summary:
i have created a docker project in which is using container technology <br />
as u all know if u want to make a website using wordpress u have start your os <br />
then you have to configure the wordpress to use it and the u also have to configure <br />
the database to use the wordpress <br />
and i may have take around half an hour <br />
and here i have made an project with the help of the container technology <br />
which will run your os then it will configure your wordpress and the it will setup <br />
your database within seconds you dont have to wait for hours and u dont have to work <br />
too hard to confugre the wordpress. 

here i have used volumes for mount the folder with container <br />
if we want the container to be accessed by public then we can use patting <br />
so anyone outside the world can access this container <br />
here i have use containers because this is very fast(it installs and start the os very fast) <br />
and i want to ready the setup very fast. <br />
here i have use the docker compose because i want to run multiple containers <br />
and this is not a good practice that i will go and run each and every container <br />
thats why i used docker compose so i can run multiple container <br />
for using docker compose we have to configure a yml file and then we have to just run it then it <br />
will run every thing whatever is present inside it <br />
 
# how to run it
* mkdir /mycompose
* cd /mycompose
*copy docker-compose.yml file and paste that file in mycompose directory
* use docker-compose up ( you can use this cmnd to run file detach mode)
* docker-compose up -d  ( to stop the sevices you can use)
* docker-compose stop   ( So once you stop everything you can start everything from following command)
* docker-compose start  ( You can stop or delete all the container made by docker-compose up)
* docker-compose down
* docker-compose down --volumes    ( delete all the volumes created by docker compose up you can use)

 
