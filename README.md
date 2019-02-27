# registrationsystem
A registration system that sends confirmation email after new user is registered.

INTRO:
With less no. of microservices, (3 to 4) , changing the config file , for ip addresses will work , but as microservcies grow in number as 100+, it's difficult to manage the system with just config file updation, there comes the thing service registry ,which helps to store network locations of service instances.Netflix Eureka is used as a registry in this project.
Good thing about Eureka is , it pings each registered services every 30 sec, if they are up and running.

