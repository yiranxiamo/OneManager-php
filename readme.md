 ## 概要

 * 一款不错的Onedrive目录索引和管理器。可以部署到 Heroku/Glitch/Vercel/Replit/SCF/FG/FC/CFC/PHP 以及VPS。
 * 支持阿里云盘，谷歌Drive，微软OneDrive以及sharepoint
 * 实例Demo: https://upload.pan.mediy.cn/
 
## 说明
原程序[OneManager-php-3.5](https://github.com/qkqpttgf/OneManager-php)

因兴趣使然而修改的如下几处地方用于自用。
 * 修改默认主题为逸笙nchyn_grey.html；
 * 修改游客上传文件名称为：文件名+MD5值；
 * 修复该主题文件点击登录为="?login=admin"，使其可以正常跳转登录；
 * 删除Timestamp not Number提示；
## 安装
* php: 7.4+
* 设定网站根目录：/OneManager-php-3.5
* 设置伪静态：rewrite ^/(.*) /index.php?/$1 last;
## 下载
  [OneManager-php-3.5-Mediy](https://github.com/yiranxiamo/OneManager-php/releases/tag/v3.5)
 ## 示例图
![图示3](https://mediy.oss-cn-beijing.aliyuncs.com/github%E5%B1%95%E7%A4%BA%E5%9B%BE/2.png)
![图示1](https://mediy.oss-cn-beijing.aliyuncs.com/github%E5%B1%95%E7%A4%BA%E5%9B%BE/1.png)
![图示2](https://mediy.oss-cn-beijing.aliyuncs.com/github%E5%B1%95%E7%A4%BA%E5%9B%BE/3.png)
#
