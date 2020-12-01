# spring boot 操作 mongodb

## 环境搭建

### docker 安装mongodb

```shell
docker run --name mongo -p 27017:27017 -d mongo
```

## 保存数据

http://localhost:8080/save?id=15

## 查询所有数据

http://localhost:8080/findAll

## 更具id查询数据

http://localhost:8080/find?id=1

## 根据id删除数据

http://localhost:8080/remove?id=12