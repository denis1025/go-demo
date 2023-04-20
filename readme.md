
1. cd 到此專案目錄下，建立docker image
```shell
docker build -t hello-world-golang .
```

2. 啟動container
```shell
docker run -p 8080:8080 hello-world-golang
```

3. 測試hello world, URI如下
```shell
http://localhost:8080/hello
```