# 下载必要文件

### 1.https://github.com/protocolbuffers/protobuf/releases
放在A目录下，并将`A/bin`加入环境变量
### 2.git clone https://github.com/dart-lang/protobuf.git（下方名为protobuf）
放在B目录下

先进入`B/protoc_plugin`执行`pub install`（没有pub请自己将dart根目录加入环境变量）

将`B/protoc_plugin/bin`加入环境变量

# 注意
直接把pb文件全部放在./pb目录下即可，其他不用管

# 执行`一定要再本目录执行，不是根目录是本目录`
```cmd
sh run.sh //mac
run.bat //window
```

