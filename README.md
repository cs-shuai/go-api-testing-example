# go-api-testing-example

## 创建新项目
1. 获取测试框架包
```
go get github.com/cs-shuai/go-api-testing
```
2. 创建 conf/config.toml
```
Host = "https://XXXXXXXXXXX/"
TOKEN_KEY = "XXXXXX"
JSON_PATH = "json/"
JSON_ROUTE_PATH = "route/"
JSON_GROUP_ROUTE_PATH = "group_route/"
SQLCONN = "user:pass@tcp(127.0.0.1:3306)/database"
```
3. 创建route文件夹和json文件
4. 创建group_route文件夹和json文件
