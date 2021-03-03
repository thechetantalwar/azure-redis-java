# redis-java-demo

### Setup Environment on Ubuntu & run demo Job
```
$ sudo apt-get update -y
$ sudo apt-get install -y maven
$ export REDISCACHEHOSTNAME=<YOUR_HOST_NAME>.redis.cache.windows.net
$ export REDISCACHEKEY=<YOUR_PRIMARY_ACCESS_KEY>
$ git clone https://github.com/kul-azure-demo/redis-java-demo.git
$ cd redis-java-demo
$ mvn clean compile
$ mvn exec:java -D exec.mainClass=thinknyx.demos.App
```
