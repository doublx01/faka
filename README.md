# 安装命令
docker run --name faka -itd -p 8000:8000 doublx1/faka:latest
# 卸载命令
docker rm -f faka && docker rmi -f doublx1/faka:latest
