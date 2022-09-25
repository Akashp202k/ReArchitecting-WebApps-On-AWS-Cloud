# ReArchitecting-WebApps-On-AWS-Cloud

The project is about deploying Multi-tear webApplication named [vprofile] on aws cloud and configuration with PAAS and SAAS aws services intead of using only aws IAAS . This Architecture boost agility and helps in business continuity . its highly available as we configured it with aws cloud front (CDN) and higly scalable as we are using elastic beanstalk and internally it uses configuration like load balancer , auto scalling groups etc.

# Technology used 
aws cloud
mysql database
gitbash


Architecture

![image](https://user-images.githubusercontent.com/76225409/192162527-1b90891b-a861-4674-a4e5-5fe3313417c2.png)



ElasticBeanStack
![image](https://user-images.githubusercontent.com/76225409/192157090-8e310c13-3d97-444a-b941-46788fcbeae9.png)

![image](https://user-images.githubusercontent.com/76225409/192157118-df8a7436-c2d1-443e-8e6f-cada3b42af33.png)

![image](https://user-images.githubusercontent.com/76225409/192157190-2a767904-20d2-4acf-98a4-28b4bcd8f86a.png)

# RDS
database
![image](https://user-images.githubusercontent.com/76225409/192157245-7f20d82c-b948-48e9-9f2e-5b05efa8ffb6.png)

RDS database configuration
![image](https://user-images.githubusercontent.com/76225409/192157277-19cb18e6-9c37-40cc-9f88-272b0c8643cb.png)

Subnet group Configuration  For RDS Database
![image](https://user-images.githubusercontent.com/76225409/192157317-4ec4598c-9cdf-4aef-ac5b-a6d465554a1e.png)

AmazonMQ (RabbitMQ)
![image](https://user-images.githubusercontent.com/76225409/192157348-4bf0ee2e-db91-43d1-9df4-aad9e2b1779e.png)

#elastic cache (memcached)
![image](https://user-images.githubusercontent.com/76225409/192157411-3aee6424-14e8-4a31-927e-b57addb2a995.png)

#CloudFront
![image](https://user-images.githubusercontent.com/76225409/192157753-e80c14e8-0087-4eac-88e6-b492c43101c6.png)

# Final Hosted WebSite View

#login page
![image](https://user-images.githubusercontent.com/76225409/192158052-fea9e3c3-63eb-419a-884e-d47a830c8578.png)
#After login
![image](https://user-images.githubusercontent.com/76225409/192158089-1f6bd7da-78e5-44e0-ae64-1afd80c9f9b2.png)
#fetching users from aws RDS database 
![image](https://user-images.githubusercontent.com/76225409/192158131-f2dd6055-1181-403b-b522-19a4b6e95899.png)
#data insertion into cache initially
![image](https://user-images.githubusercontent.com/76225409/192158165-24453230-b868-42c2-a85f-a6f31bf5860a.png)
#data fetched from cache
![image](https://user-images.githubusercontent.com/76225409/192158187-b976232b-a69d-410b-954c-d5785c160d22.png)


# Finally webApp is Successfully Rearchitected On aws Cloud

