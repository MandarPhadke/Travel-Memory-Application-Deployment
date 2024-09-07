# Travel-Memory-Application-Deployment
Graded Project on Travel Memory Application Deployment
1. Created EC2 instance on AWS, using t4gmicro and ubuntu os
2. opened two ports on security groups for inbound communication 3000 and 3001
3. Cloned the repo from given url for application.
4. installed nginx, npm.
5. added mongodb url in .env file and port 3001 in backend
6. executed npm install in backend folder.
7. executed command  node index.js in backend folder.
8. http://35.84.28.101:3001/hello url is working
9. ![2024-09-07_13-47](https://github.com/user-attachments/assets/df8bbcf1-c6ed-44eb-91b8-12fa80326161)
10. added url in src/url.js in frontend folder.
11. executed npm install in frontend folder.
  12. executed command npm start.
13. the url is working properly.
14. ![2024-09-07_15-54](https://github.com/user-attachments/assets/66be0532-713c-4326-a465-8ac2152d844c)
15. created Image of current EC2 instance. and created second instance using the image.
16. added both EC2 instances in a load balancer the curent url for load balancer is "http://mandarmern-137643548.us-west-2.elb.amazonaws.com"
17. installed the nginx on both EC2 instances and configures proxy servers to access MERN app.
18. now app is visible on browser with load balancer url.  
19. ![2024-09-07_15-54](https://github.com/user-attachments/assets/65d7b10f-5adb-4faa-a977-266941fcc1bd)
20. Creating Account on cloudflare  

