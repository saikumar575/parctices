Tomcat started

[root@ip-172-31-2-20 bin]# 
    
    1  yum update
    2  sudo yum install java -y
    3  java --version
    4  cd /opt
    5  sudo wget https://dlcdn.apache.org/tomcat/tomcat-10/v10.1.55/bin/apache-tomcat-10.1.55.tar.gz
    6  ls
    7  sudo tar -xvzf apache-tomcat-10.1.55.tar.gz
    8  ls
    9  sudo mv apache-tomcat-10.1.55 tomcat
   10  ls
   11  cd /opt/tomcat/bin
   12  sudo chmod +x *.sh
   13  sudo ./startup.sh
   14  http://YOUR_PUBLIC_IP:8080

[root@ip-172-31-2-20 bin]# 
