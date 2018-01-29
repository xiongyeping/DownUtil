# DownUtil
下载框架
本util由可能是深圳最厉害的Android程序员，就算不是，也可能是深圳最厉害的java程序员猴哥所写
不要问我猴哥是谁~~
在你的build.gradle文件中导入以下代码
allprojects {
repositories {
    maven { url 'https://jitpack.io' }
            }
       }

然后在dependencies项中写以下代码即可使用

compile 'com.github.xiongyeping:DownUtil:1.0.0'
