# 基于`IntoYun第三方设备SDK`开发的实例工程

通过该项目，我们将介绍如何使用`IntoYun第三方设备SDK`开发第三方设备。

该项目工程使用intoyuniot开发工具开发。


## 目录和文件组成

```
+-- lib                       : 库目录
+-- src                       : 源文件目录
    +-- intoyun-iotkit-sdk    : 第三方设备SDK
    +-- user                  : 用户应用代码
+-- intoyuniot.ini            : intoyuniot配置文件
+-- README.md                 : 项目说明文件

```

## 下载工程

```
git clone --recursive https://github.com/IntoYun/intoyun-iotkit-demo.git
```

## 项目实例开发

- [Linux硬件平台](#Linux硬件平台)
- [MacOS硬件平台](#MacOS硬件平台)
- [Windows硬件平台](#Windows硬件平台)
- [esp8266硬件平台](#esp8266硬件平台)
- [esp32硬件平台](#esp32硬件平台)

### Linux硬件平台

#### 代码编写

用户可以把示例代码复制到工程中，具体如下：

复制`src/intoyun-iotkit-sdk/examples/smartLight-destop/`到`src/user/`中。

#### 程序编译

```
intoyuniot run -t clean              # 清除临时文件

intoyuniot run -e linux_x86_64       # 编译64位程序
或
intoyuniot run -e linux_i686         # 编译32位程序

```

#### 程序运行

```
./.intoiotenvs/linux_x86_64/program
或
./.intoiotenvs/linux_i686/program
```

### MacOS硬件平台

#### 代码编写

用户可以把示例代码复制到工程中，具体如下：

复制`src/intoyun-iotkit-sdk/examples/smartLight-destop/`到`src/user/`中。

#### 程序编译

```
intoyuniot run -t clean              # 清除临时文件
intoyuniot run -e native             # 编译程序
```

#### 程序运行

```
./.intoiotenvs/native/program
```

### Windows硬件平台

#### 代码编写

用户可以把示例代码复制到工程中，具体如下：

复制`src/intoyun-iotkit-sdk/examples/smartLight-destop/`到`src/user/`中。

#### 程序编译

```
intoyuniot run -t clean              # 清除临时文件
intoyuniot run -e windows_x86        # 编译程序
```

#### 程序运行

```
./.intoiotenvs/windows_x86/program
```

### esp8266硬件平台

#### 代码编写

用户可以把示例代码复制到工程中，具体如下：

复制`src/intoyun-iotkit-sdk/examples/smartLight-esp8266/`到`src/user/`中。

#### 程序编译

```
intoyuniot run -t clean              # 清除临时文件
intoyuniot run -e esp8266 -t upload  # 编译和下载
```

#### 程序运行

```
./.intoiotenvs/esp8266/program
```

### esp32硬件平台

#### 代码编写

用户可以把示例代码复制到工程中，具体如下：

复制`src/intoyun-iotkit-sdk/examples/smartLight-esp32/`到`src/user/`中。

#### 程序编译

```
intoyuniot run -t clean              # 清除临时文件
intoyuniot run -e esp32 -t upload    # 编译和下载
```

#### 程序运行

```
./.intoiotenvs/esp32/program
```

