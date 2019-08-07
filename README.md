# blog_in_docker



### 构成

1. Image: mysql
2. Image: wordpress+apache
3. image: nginx 
4. docker stack

### 安装步骤

1. 替换`etc/nginx`中的 `crt`和`key`文件
2. `wordpress`中安装插件`Really Simple SSL`插件实现全站`https`。
3. 启动命令 `docker stack deploy -c stack.yml wp`。
4. 添加cnzz流量统计。
5. dnsPod添加dns配置。



