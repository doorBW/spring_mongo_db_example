# Mongodb example in spring boot
## 1. Installing mongodb
1. https://www.mongodb.com/try/download/community
2. unzip file, mv directory
```shell
>> sudo mv mongodb-macos-x86_64-4.4.4-rc0 /usr/local/mongodb
>> sudo mkdir /usr/local/data/db
>> sudo chown user /usr/local/data/db
```
3. config mongodb path
```shell
>> vi ~/.zshrc
export MONGO_PATH=/usr/local/mongodb
export PATH=$PATH:$MONGO_PATH/bin
```
4. Check install
```shell
>> mongo --version
```
5. run mongodb server
```shell
>> mongod --dbpath /usr/local/data/db
```

## 2. Installing mongodb compass
https://www.mongodb.com/try/download/compass

## 3. Setting init project
https://start.spring.io/
- Gradle
- java 11

## References
- https://spring.io/guides/gs/accessing-data-mongodb/
