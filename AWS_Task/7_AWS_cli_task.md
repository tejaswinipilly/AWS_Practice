**Install and Setup AWS cli on Local machine**
**Config PA credentials**

  ***Steps to create vpc,subnets,Route table through AWS cli command line interface***
  
step 1
- Create VPC using cli

![vpc](../images/aws%20cli%201.png)
![vpc](../images/aws%202.png)

step 2
- create Pub and Pvt subnets
***Public subnet***

![vpc](../images/aws%203.png)
***Private subnet***

![vpc](../images/aws%204.png)

step 3
- create IGW

![vpc](../images/aws%205.png)

step 4
- Attach IGW to VPC

![vpc](../images/aws%206.png)

step 5

- Create Pub and PVT RT

***Public RT***

![vpc](../images/aws%207.png)

***Private RT***

![vpc](../images/aws%208.png)

step 6
- Attach Pub sub to Pub rt

![vpc](../images/aws%209.png)

step 7
- Attach Pvt Sub to Pvt rt

![vpc](../images/aws%2010.png)

step 8
- Attach IGW to Pub RT
![vpc](../images/aws%2011.png)

step 9
- Create Sg for ssh // http
![vpc](../images/aws%2013.png)

step 10
- Create a Ec2 in Pub Sub
![vpc](../images/aws%2014.png)

![vpc](../images/aws%2015.png

![vpc](../images/aws%2016.png))

step 11
- Create a Ec2 in Pvt Sub 
![vpc](../images/aws%2017.png)

![vpc](../images/aws%2018.png)

![vpc](../images/aws%2019.png)