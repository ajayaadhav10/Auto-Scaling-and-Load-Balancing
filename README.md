# Banking app with Auto-Scaling-and-Load-Balancing


There are millions of devices accessed by one single website or server which leads to necessity of auto 
scaling and load balancing to provide optimal performance for Customers/Users. The main advantage of 
ELB is automatically distributed our incoming banking application across multiple targets in one or more 
availability zones. The EC2 instances which we created are effectively communicate with our application 
load balancer using Target groups. Even if any of our instances failed to communicate with Banking 
application, the other instances will take over the routing and effectively balance the load until the failed 
instance gets fixed.Our Autoscaling feature helps in increasing and decreasing the no of available 
instances when the “Threshold” value is exceeded and remove the instance when they are not in use, as 
per out scaling policy mentioned in AWS console, to manage the instances both in peak and off peak 
hours to face the low down time for our Banking Application.
