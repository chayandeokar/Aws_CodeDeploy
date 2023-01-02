# Aws_CodeDeploy

Download CodeAgent to connect from Ec2 install for CI and CD


##It Will Update our Yum
Sudo yum update -y


sudo yum install -y ruby wget
wget https://git-codecommit.ap-south-1.amazonaws.com/v1/repos/webrepo2022
chmod +x ./install
sudo ./install auto 
service codedeploy_agent status
