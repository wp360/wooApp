##  操作步骤：

## 【初始篇】
```javascript
说明：此处用的ionic为版本2
1.安装Install Ionic
参考：
http://ionicframework.com/getting-started/

npm install -g cordova ionic

2.新建一个空的项目
ionic start wooApp sidemenu --v2
[ionic start --v2 wooApp blank]
注：这里--v2是因为使用ionic2，如果最新3.0+版本 可以去掉。至于版本1，忽略。

3.运行App

cd wooApp
ionic serve

web模拟环境

ionic serve --l
自动生成 http://localhost:8100/ionic-lab
```

## 【模拟篇】
```javascript
Android模拟器生成，在Windows环境下，需要先安装Android Studio 2+ ( eg:2.3 )

>`ionic platform add android`

等模拟器启动后，输入：

>`ionic run android`

注：可能会报错，无法找到'ANDROID_HOME'环境变量。尝试手动设置之类的。
解决办法：1.手动配置。2.如果不会配置，直接打开Android Studio选择已有项目，就是ionic生成的项目Android文件夹下，然后会有弹框下载生成对应gradle。项目启动生成，点击run android （绿色箭头）按钮，选择对应模拟器，就OK了。

同样，mac环境下，需要安装对应ios模拟器

ionic platform add ios

等模拟器启动后，输入：

ionic run ios
```

## 【WooCommerce篇】
```javascript
1.在Windows环境下，需要先安装Wamp；Mac的话，安装Mamp。
2.安装后，启动。下载Wordpress、WooCommerce。本地运行localhost，安装Wordpress。
开启数据库，新建数据库，wordpress。否则无法连接。
Wordpress安装好后，在Wamp或MAMP/htdocs/wordpress/wp-content/plugins里解压WooCommerce
登录Wordpress，选择插件 》 已安装的插件 》启用WooCommerce
WooCommerce 设置 API 》Keys/Apps
Consumer key
ck_d2b0ed2de78b39df2251e5e0d2dd8fe8b0f78967
Consumer secret
cs_ebd4cb4f9208603b62f63ad370c0e11db6068649

Rest API文档
https://docs.woocommerce.com/document/woocommerce-rest-api/
http://woocommerce.github.io/woocommerce-rest-api-docs/
```
## 【开发篇】
```javascript
>`ionic g page Menu`
```

## 参考课程
[Ionic 3 Apps for WooCommerce: Build an eCommerce Mobile App](https://github.com/samarthagarwal/wooionic3)