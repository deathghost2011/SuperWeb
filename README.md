## FNSuperWeb 超级浏览器

#### 基于腾讯X5内核

#### 目前已有功能：

* 1、文件浏览（支持pdf/ppt/doc/excel/txt）
* 2、文件上传（JS）
* 3、文件下载

#### 计划迭代功能：

* 1、JS通信封装
* 2、自定义进度条封装
* 3、视频播放封装
* 4、敬请期待。。。

#### 1、添加依赖和配置
* 根目录build.gradle文件添加如下配置：

>>```
allprojects {
    repositories {
        maven { url "https://source.enncloud.cn/FNAndroidTeam/FNSuperWeb/raw/master/superweb" }
    }
}
```

* APP目录build.gradle文件添加如下配置：

>>```
dependencies {
    implementation 'com.fanneng.android:superweb:1.0.0@aar'
}
```

* 申请权限：

>>```
    <uses-permission android:name="android.permission.INTERNET" />
    <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
    <uses-permission android:name="android.permission.ACCESS_WIFI_STATE" />
    <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
    <uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />
    <uses-permission android:name="android.permission.READ_PHONE_STATE" />
    <uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
    <uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />
    <uses-permission android:name="android.permission.CAMERA" />
```



#### 2、基本功能
* 文件浏览（支持pdf/ppt/doc/excel/txt）

![点我查看效果图](https://source.enncloud.cn/FNAndroidTeam/FNSuperWeb/raw/master/file_open.gif)

* 文件上传（Android与JS通信）

![点我查看效果图](https://source.enncloud.cn/FNAndroidTeam/FNSuperWeb/raw/master/file_upload.gif)

* 文件下载

![点我查看效果图](https://source.enncloud.cn/FNAndroidTeam/FNSuperWeb/raw/master/file_download.gif)

* 未完待续。。。
* 未完待续。。。
* 未完待续。。。


#### 3、 作者
* 鲁宇峰   邮箱：466708987@qq.com
