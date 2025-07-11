# ECS Multiple Container Deployment on AWS
Running Multi Container deployment on AWS ECS with Load balancers for stable domains. This is a production application where customer request are hitting the load balancer directly and then the AWS load balancer route request appropriately to the responsible service. Each service also leverage on the mongo DB cloud (atlas).
The application is running such that services are replaced when stopped due to any downtime, and this is done at health check which is done by the AWS managed service (Elastic Container Service)
