# ECS-Mult-Cont-Dep
Running Multi Container deployment on AWS ECS with Load balancers for stable domains. This is a production application where customer request are hitting the load balancer directly and then the AWS load balancer route request appropriately to the responsible service. Each service also leverage on the mongo DB cloud (atlas).
