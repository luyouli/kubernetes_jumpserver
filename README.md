# kubernetes_jumpserver

mysql和redis都部署在kubernetes，这里就不过多赘述了



在服务器上生成SECRET_KEY和BOOTSTRAP_TOKEN并写入配置文件

$ SECRET_KEY=`cat /dev/urandom | tr -dc A-Za-z0-9 | head -c 50` 

$ echo "SECRET_KEY=$SECRET_KEY" >> ~/.bashrc

$ BOOTSTRAP_TOKEN=`cat /dev/urandom | tr -dc A-Za-z0-9 | head -c 16` 

$ echo "BOOTSTRAP_TOKEN=$BOOTSTRAP_TOKEN" >> ~/.bashrc



录像路径：/home/server/data/jumpserver-media

