## devops_tools

#Installation of Jenkins inside CentOS server  
sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo  
sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key  
sudo yum upgrade  
sudo yum install jenkins java-1.8.0-openjdk-devel  
sudo systemctl daemon-reload  
