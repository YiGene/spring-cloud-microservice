# spring-cloud-microservice
spring cloud microservice demo
the code for  https://www.infoq.com/articles/Microservices-SpringBoot?utm_source=infoq&utm_medium=popular_widget&utm_campaign=popular_content_list&utm_content=homepage
#did small changes on it

1. you need to install consul
2. start it ( client ip: 192.168.18.5 )
  ./consul agent -dev -client 192.168.18.5 -http-port 8500
  you can access via http://192.168.18.5:8500/ui
3. run the code then you can see it's registered in consul 
