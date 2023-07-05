### 蜜蜜妈妈服务端

### php版本
v 8.2

### docker部署

###  运行制作镜像（镜像名称按 开发者/应用:版本）：
docker build --rm -t zhonghaibin/mm_serve:1.0 .

### 使用镜像创建容器：
docker run -d --name=mm_serve -p 8787:8787  zhonghaibin/mm_serve:1.0