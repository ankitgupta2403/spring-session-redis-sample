# spring-session-redis-sample
In order to follow cloud native 12 factor principles, application should be stateless.

Since http session are managed by Tomcat or any other servlet container by default, we need use the feature of 
Spring Session to make our application completely stateless.

Redis is the best candidate to manage sessions across multiple microservices.

As the application grows or in case of autoscaling(upscaling or downscaling), there is no issue is managing session.
