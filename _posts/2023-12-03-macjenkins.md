---
title: Mac安装Jenkins
---

Mac安装Jenkins

1. 
```
brew install jenkins
```
2. 启动 `brew services start jenkins` 或者 `/usr/local/opt/jenkins/bin/jenkins --httpListenAddress\=127.0.0.1 --httpPort\=8080`
3. Jenkins 需要java 11以上， 如果java版本较低会无法启动，需要安装高版本。 `brew install openjdk@11`
4. 然后执行允许时的java版本 `export JAVA_HOME=/Library/Java/JavaVirtualMachines/openjdk-11.jdk/Contents/Home`
5. 重复步骤2
6. 访问Jenkins 本地服务 `http://127.0.0.1:8080/login`
7. 查看初始密码 `cat /Users/xxx/.jenkins/secrets/initialAdminPassword`， 登陆使用 `admin` 账号.
8. 登陆成功后，安装插件，设置管理员用户
