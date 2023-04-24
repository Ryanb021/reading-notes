# Read 16

## AWS Cloud Servers

## What is an EC2 Instance?

- An Amazon EC2 instance is a virtual server in Amazon's Elastic Compute Cloud (EC2) for running applications on the Amazon Web Services (AWS) infrastructure.

## Name 2 use cases for EC2.

- Hosting Environments
- Development and Tests Environments

## Provide 1 reason to use ECS instead of a service such as Heroku, Digital Ocean, or Render.com.

- The flexibility to change underlying EC2 instances. As the traffic or demand increases, we can easily change EC2 instances without any issues. Amazon ECS APIs are extremely robust and one can start and stop containers by firing one post request only compared to Heroku, Digital Ocean, or Render.com.

## Where can we find EC2 on the AWS Console?

- Open the Amazon EC2 console at https://console.aws.amazon.com/ec2/ .

## Explain the general difference between T2 Micro and XL.

- The “t” stands for tiny and the “m” stands for micro or medium. The t2 instances are burstable instance type, which means that you can use it to run your basic applications such as websites or also use it as a development environment.
- T2.xlarge at slight cost reduction, and higher burst performance.

## Explain a “Compute Cycle” to a non-technical friend.

- Compute cycle if I had to explain it to a non-technical friend, would be, like man hours required to complete bulding a small shed. If it takes 8 hours to buld the foundation of a small shed, that is like a compute cycle. If it takes 1 week to fully complete a small shed, that can be compared to a compute cycle.

## What is Elastic Beanstalk?

- Elastic Beanstalk is a platform within AWS that is used for deploying and scaling web applications. In simple terms this platform as a service (PaaS) takes your application code and deploys it while provisioning the supporting architecture and compute resources required for your code to run

## Describe the relationship between EC2 and Elastic Beanstalk.

- EC2 allows creating a server in the AWS cloud where the user has to pay on an hourly basis. Elastic Beanstalk provides an environment that contains an optional database and AWS components such as an Auto-Scaling Group, Elastic Load Balancer, Security Group.

## Name some benefits of using Elastic Beanstalk.

- Elastic Beanstalk's main benefits include timesaving server configuration, powerful customization, and a cost-effective price point. Elastic Beanstalk automates the setup, configuration, and provisioning of other AWS services like EC2, RDS, and Elastic Load Balancing to create a web service.
