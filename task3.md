# Launch EC2 instance and attach to TG with LB

* Create Security Group
  *  open port 80
  *  And attach to EC2
*  Write a userdata to install webserver (nginx)
*  Attach security group to EC2
*  Create TG and added EC2 as targed 
*  Create Application loadbalancer and user TG
*  Attach security group to loadbalancer
