# PHP-BingWallpaper
## 关于此项目
因为本人需要一个既能将Bing壁纸保存到本地，又能随机返回的API，找了一大圈之后发现没有我想要的，因此干脆自己写（改）了一个。

本项目参考网上的部分实现方式，但是由于这个东西是很久之前写（改）的，而且似乎相互抄袭比较严重，找不到原出处，故此部分暂不标明作者，如果这是您的代码，可与我联系标注。

## 主要特性
- 由最好的语言PHP编写
- 保存当天壁纸到本地
- 随机返回最近10天的壁纸
- 若壁纸不存在则返回当天壁纸
- 壁纸将保存在`/bing/`中，以`日期.jpg`命名

## 使用方法
1. 将`bing.php`放到任意位置
1. 访问`/bing.php`即可
1. 可以使用`<img src="/bing.php">`访问

## Demo
Demo:[https://bing.kakkk.cc/bing.php](https://bing.kakkk.cc/bing.php "https://bing.kakkk.cc/bing.php")

![Demo](https://bing.kakkk.cc/bing.php "Demo")
