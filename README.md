# AWS_Terraform_Final_Task
 
 ![environment](https://user-images.githubusercontent.com/73169815/208947870-acef2865-9ef6-4efc-8491-6a0f04aa7826.png)

**It includes:
**
2 Load Balancers - Internet Facing and Internal 
4 Web Servers
4 Application Servers
1 RDS with two nodes (MySQL)
1 S3 Bucket

------------


#### Implementation :
**1. Init terraform enivroment:
**
 
```bash
terraform init
```
<img width="493" alt="צילום מסך 2022-12-21 171705" src="https://user-images.githubusercontent.com/73169815/208950016-58ae2f9b-dff6-40cd-90b6-1dfae5733de0.png">


**2. Deploying your configuration
**

```bash
terraform plan
```
<img width="397" alt="צילום מסך 2022-12-21 171754" src="https://user-images.githubusercontent.com/73169815/208950132-01f3219b-05b9-48ee-ad5f-c4b3aac6d5a3.png">


**3. deploy the configuration by executing the plan with the command below.**
```bash
terraform apply
```


**4. To destroy the resources created by Terraform run**
```bash
terraform destroy

```



