# DownUtil
下载框架
在你的build.gradle文件中导入以下代码

allprojects {
repositories{
    maven { url 'https://jitpack.io' }
            }
       }

然后在dependencies项中写以下代码即可使用

compile 'com.github.xiongyeping:DownUtil:1.0.0'
