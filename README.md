# Revive Adserver Installed
#### 该项目适用于容器集群部署，通过修改 var/[域名].confi.ph文件中的数据库连接内容以及域名内容即可访问，无需进入初始化安装界面。
### 如何配置Revive
通过环境变量来生成docker container
REVIVE_DB_HOST:  数据库host
REVIVE_DB_USER:  数据库user
REVIVE_DB_PASSWORD：数据库密码
REVIVE_DB_NAME：数据库名称
REVIVE_WEB_DOMAIN：网站域名，例如 127.0.0.1:8000

