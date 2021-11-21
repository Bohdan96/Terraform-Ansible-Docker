Via terrraform setup 2 servers on AWS, run ansible that up docker with nginx image.

To run this project you needs:
 
1. In AWS create user with full acces, then export his credentials on local server:

# export AWS_ACCESS_KEY_ID="xxxxxxxxxx" 
# export AWS_SECRET_ACCESS_KEY="xxxxxxxxxx" 

2. In folder with project run:
# terraform init

# terraform apply

After all actions, you get 2 ip's:

![2021-11-21_18-31](https://user-images.githubusercontent.com/64528224/142770599-b625038a-a2dd-4349-af70-14fa3a4e47a6.png)


Then, you can go on page with defaults wellcome message from nginx:

![2021-11-21_18-19](https://user-images.githubusercontent.com/64528224/142770638-e2a3d104-541e-4fca-8ab7-6d920a3b1874.png)

![2021-11-21_18-20](https://user-images.githubusercontent.com/64528224/142770648-08d6cde8-b4f0-4e6a-a9d0-e4db0b1624e8.png)







