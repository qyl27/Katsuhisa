# 安装Java

## Java 是什么？

一种编程语言，也可以指这个编程语言的运行环境，没了这个运行环境，用 Java 语言编写的程序就没办法工作。

Minecraft 是用 Java 编程语言写就的，所以我们也需要 Java 运行环境来运行它。

### 什么？我玩 Minecraft 都没听说过这个啊。

你可能是傻瓜式操作的受害者（笑）。市面上的大部分启动器（包括官方启动器、HMCL、中国版等）都内置了下载和安装 Java 的功能，所以没有手动下载和安装过 Java 也是正常的。

## 安装 Java

### 我如何确定自己装没装 Java ？

1. 按下 `Win + R` 键打开一个标题为**运行**的窗口（通常在屏幕左下角。
2. 在其中的输入框中输入 `cmd` ，之后会看见一个黑框框。
3. 在看见的黑框框里面输入 `java -version` 。

- 如果结果和下面类似（这里以 Adoptium OpenJDK 17 为例，后续其他页面也是），则你已经成功安装了 Java 运行环境，可以回到上个页面了：
```text
openjdk version "17" 2021-09-14
OpenJDK Runtime Environment Temurin-17+35 (build 17+35)
OpenJDK 64-Bit Server VM Temurin-17+35 (build 17+35, mixed mode, sharing)
```

- 如果结果和下面类似，还没有正确安装 Java 运行环境：
```text
'java' 不是内部或外部命令，也不是可运行的程序
或批处理文件。
```

### 我没装 Java 怎么办？

下面列出了几个由不同提供商发行的 Java 运行环境，选择并下载其中一个就够。

 1. [🔗 Oracle JRE](https://www.oracle.com/java/technologies/downloads) （需要注册并登录账号，比较麻烦。）
 2. [🔗 Adoptium](https://adoptium.net/) （它的服务器在中国大陆以外的地区，下载较慢，最好正确访问国际互联网。）

然后找到有 **17**、**windows**、**x64** 类似字样的下载链接，并下载。

如果这样描述的话还不知道下载哪一种，那没办法了，用它吧[🔗 Java运行环境（64位）](https://github.com/adoptium/temurin17-binaries/releases/download/jdk-17.0.2%2B8/OpenJDK17U-jdk_x64_windows_hotspot_17.0.2_8.msi)。

解压，打开安装包，一路同意并点击Next按钮就可以安装。

之后重复检查自己的 Java 运行环境。