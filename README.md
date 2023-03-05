# AWS
My notes of learning path  
[My notes](https://docs.google.com/document/d/19NS8rZcNoGq488RCOC3BJlGA6Ve4c5gJpj0Tklm-D5A/edit?usp=sharing "Title")  
[Learning site as reference](https://www.youtube.com/watch?v=_xXw2JBVXWg "Title")  



## IT Certification
![](https://i.imgur.com/ef1QpYa.png)
![](https://i.imgur.com/D4vl1zf.png)
![](https://i.imgur.com/3B0HoRP.png)
## AWS Network
![](https://i.imgur.com/kCS1HFN.png)

We could see that deploying subnets in different AZ within same VPC in my AWS environment below.
I 
![](https://i.imgur.com/PKIXvnm.png)

### Subnets communication
![](https://i.imgur.com/5ImTlD4.png)
Different subnets in same VPC can communicate via "Local"
![](https://i.imgur.com/xaowCYh.png)

### Subnet via IGW to Internet
![](https://i.imgur.com/WcpbCmd.png)
Set default route to IGW at route table of the subnet
![](https://i.imgur.com/4kG96Bh.png)

### Subnet via NAT and IGW to Internet
- ***NAT GW*** should associate with ***Elastic IP***, not lab yet.
![](https://i.imgur.com/0vvhZT3.png)

## Security Group and NACL
- ***NACL*** : Stateless and default allow all for both inbound and outbound.
- ***SecurityGroup*** : Stateful and sticky to ***ENI***.
![](https://i.imgur.com/N1qgkqm.png)

## [EC2](https://ithelp.ithome.com.tw/articles/10263305)
![](https://i.imgur.com/TA1wjM9.png)

## Relation between EC2 and EBS
- EC2 Instance 與 EBS Volume 會在同一個 AZ 之中
![](https://i.imgur.com/yDxsd2J.png)
- EBS Snapshot 會與 EC2 Instance 在同一個 Region 中
![](https://i.imgur.com/nQT3eLF.png)
- Instance storage vs EBS
![](https://i.imgur.com/pB0cOlj.png)
## EBS type
![](https://i.imgur.com/9OKnM0U.png)
## [S3 vs EBS](https://ithelp.ithome.com.tw/articles/10267413)
- Article comparison description is very nice, can check again if forgot
![](https://i.imgur.com/cQMVxop.png)
## [Bucket in S3](https://ithelp.ithome.com.tw/articles/10268155)
- Property : ***Versioning***
![](https://i.imgur.com/DYKApyI.png)
## 5 storage class types of S3
- Feature : Lifecycle management
![](https://i.imgur.com/ftwUnYa.png)
## [Lab of S3](https://ithelp.ithome.com.tw/articles/10269526)
Not lab yet
## [EC2&DB&EBS vs RDS](https://ithelp.ithome.com.tw/articles/10270473)
![](https://i.imgur.com/OSVXqfE.png)
## [RDS Structure](https://ithelp.ithome.com.tw/articles/10271693)
![](https://i.imgur.com/Cc3WNGO.png)



## Reference 
https://ithelp.ithome.com.tw/users/20100951/ironman/4671
https://venturebeat.com/security/15-top-paying-it-certifications-for-2022/
https://holori.com/cloud-market-2022/

Long IMG file testing
![](https://i.imgur.com/pkNY0EE.jpg)