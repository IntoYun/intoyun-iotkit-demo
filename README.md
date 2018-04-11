# IntoYun 第三方设备接入示例程序


## 3. 编译与调试

lorawan_gateway 采取intoyuniot编译，具体如下：

```
intoyuniot run -t clean   # 清除临时文件


intoyuniot run -e native             # 编译和下载 GL1000

intoyuniot run -e linux_x86_64       # 编译和下载 GL1000

intoyuniot run -e linux_i686         # 编译和下载 GL1000

intoyuniot run -e windows_x86        # 编译和下载 GL1000

intoyuniot run -e esp8266 -t upload  # 编译和下载 GL2000

intoyuniot run -e esp32 -t upload    # 编译和下载 GL2100

```


