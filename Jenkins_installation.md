# TASK 
## Install Jenkins on Linux or Ubuntu

### Step 1 install java on instance 
     - for ubuntu : apt install openjdk-8-jdk 
     - For Linux: yum install java

### Step 2 Install Jenkins on the instance
     - for ubuntu: apt install Jenkins
     - For Linux: yum install Jenkins

### Step 3 Start Jenkins service 
       - for ubuntu: sudo systemctl start Jenkins 
       - for Linux: sudo systemctl start Jenkins 

### Step 4: Opening the Firewall [If you are using ec2 instance add port no 8080 into security group]
      - for ubuntu: sudo ufw allow 8080           
       - for Linux: sudo firewall-cmd --add-port=8080/tcp
