## Installation on AWS Elastic Beanstalk

### Requirement

* [The EB CLI](http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3.html)

### Install


```
eb init
eb create prod -i t2.small --elb-type network
eb open prod
```

Default loadbalancer is classic load balancer and it causes `websocket http 400 errors`.

Default protocol for classic and application load balancer are http protocol. 

Network load balancer's default protocol is tcp.

