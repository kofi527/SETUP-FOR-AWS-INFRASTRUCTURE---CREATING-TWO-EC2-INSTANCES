# SETUP-FOR-AWS-INFRASTRUCTURE----CREATING-TWO-EC2-INSTANCES
 Instance setup for Aws infrastructure
 ![ec2 logo](https://github.com/user-attachments/assets/49ee67f3-b006-4bd5-bc9f-b3918950b432)



 ### PROJECT OUTLINE PHASE 1
CREATE TWO EC2 Instances to setup Jenkins and Tomcat on AWS
 virtual server provided by AWS. We will be using this EC2 to setup both Jenkins and Tomcat. Please follow the below steps to create an EC2 instance.

### STEPS TO PROJECT EXECUTION

1. we navigate to the ec2 instance within your aws console.

 ![2NAVIG~1](https://github.com/user-attachments/assets/183dd122-8079-4505-be47-5f5f70aac773)

2. created instances are named with their required intance attributes

![3GIVEA~1](https://github.com/user-attachments/assets/756c530c-794c-4f49-97c3-c1965ca5478f)

   
3. label the required instance that will be created

 ![3GIVEA~1](https://github.com/user-attachments/assets/f3f3a5d8-438e-4929-9cbc-60efeefa5a8d)

 4. choose the ubuntu free tier image for this project

![4  choose the ubuntu image select the seerver 24 04 free tier](https://github.com/user-attachments/assets/de005b4e-d37c-4464-ad63-c8ac87b9035a)


6.  click on create the key pair if you have not created one. This is very important as it will be very much needed during the connection of your instance
   
   ![5CLICK~1](https://github.com/user-attachments/assets/f07f82dc-2016-460d-b6af-088fd4d76280)

7. Under the network settings we edit our inbound and outbound rules

   ![7  under network settings click edit and lets do the following](https://github.com/user-attachments/assets/d9291786-cd86-4af1-8ab2-4060e2778772)

8. Add an additional security group to allow access to your application

   ![8SECUR~1](https://github.com/user-attachments/assets/be468402-f507-4bc8-99ec-e79fc62b50f8)

9. we add second security group and set our port range to 8080 which is a custom ip address

    ![9WEADD~1](https://github.com/user-attachments/assets/3c96e047-cc01-413f-95c4-9e4a207089f3)


