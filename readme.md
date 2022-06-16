 ## 概要

 * 一款不错的Onedrive目录索引和管理器。可以部署到 Heroku/Glitch/Vercel/Replit/SCF/FG/FC/CFC/PHP 以及VPS。
 * 支持阿里云盘，谷歌Drive，微软OneDrive以及sharepoint
 * 实例Demo: https://upload.pan.mediy.cn/
 
## 说明
原程序[OneManager-php-3.5](https://github.com/qkqpttgf/OneManager-php)

因兴趣使然而修改的如下几处地方用于自用。
 * 修改默认主题为逸笙nchyn_grey.html；
 * 修改上传文件名称为：文件名+MD5值；
 * 修复该主题文件点击登录为="?login=admin"，使其可以正常跳转登录；
 * 删除Timestamp not Number提示；
## 安装
* php: 7.4
* 设定网站根目录：/OneManager-php-3.5
* 设置伪静态：rewrite ^/(.*) /index.php?/$1 last;
## 下载
  [OneManager-php-3.5-Mediy](https://github.com/yiranxiamo/OneManager-php/releases/tag/v3.5)
 ## 示例图
![图示3](https://mediy.oss-cn-beijing.aliyuncs.com/github%E5%B1%95%E7%A4%BA%E5%9B%BE/2.png)
![图示1](https://mediy.oss-cn-beijing.aliyuncs.com/github%E5%B1%95%E7%A4%BA%E5%9B%BE/1.png)
![图示2](https://mediy.oss-cn-beijing.aliyuncs.com/github%E5%B1%95%E7%A4%BA%E5%9B%BE/3.png)
#


中文readme

NOTICE:
The Releases is used as archive, not newest code.

Please read the descriptions of settings before raising an issue.

Deploy to Vercel
Official
https://vercel.com/

Demo
https://onemanager-php.vercel.app/

Notice
you must wait 30-50s to make sure deploy READY after change config;

Vercel limit 100 deploy every day.

How to Install
https://scfonedrive.github.io/Vercel/Deploy.html .

Deploy to Replit
Official
https://repl.it/
https://replit.com/

Demo
https://onemanager.qkqpttgf.repl.co/

Notice
Import from Github useing the .replit file in code files will cause an empty web page, may someone help me?

How to Install
Click the "+" or "Create Repl", find template "PHP Web Server" (via input "php"), input a name for your project in "Title" or left it default, Click the "+ Create Repl".
After done, input git clone https://github.com/qkqpttgf/OneManager-php && mv -b OneManager-php/* ./ && mv -b OneManager-php/.[^.]* ./ && rm -rf *~ && rm -rf OneManager-php to Console or Shell on the right, press "Enter" to run it.
Click the green button "Run", it will show the web page on the right, you can open it in a new tab or window.
Deploy to Heroku
Official
https://heroku.com

Demo
https://herooneindex.herokuapp.com/

How to Install
Click the button Deploy to Deploy a new app("We couldn't deploy your app because the source code violates the Salesforce Acceptable Use and External-Facing Services Policy.")

Star this project, then Fork, create an app in Heroku, then turn to the Deploy tab, "Deployment method" via "Connect GitHub", select your github fork.

Deploy to Glitch
Official
https://glitch.com/

Demo
https://onemanager.glitch.me/

How to Install
[New Project] -> [Import form Github] -> paste "https://github.com/qkqpttgf/OneManager-php" , after done, [Show] -> [In a New Window].

Deploy to Tencent Serverless Cloud Function (SCF)
Official
https://cloud.tencent.com/product/scf

DEMO
null

How to Install
see CN readme.

Deploy to Huawei cloud Function Graph (FG)
Official
https://console.huaweicloud.com/functiongraph/

DEMO
null

How to Install
see CN readme.

Deploy to Aliyun Function Compute (FC)
Official:
https://fc.console.aliyun.com/

DEMO
null

How to Install
see CN readme.

Deploy to Baidu Cloud Function Compute (CFC)
Official
https://console.bce.baidu.com/cfc/#/cfc/functions

DEMO
null

How to Install
see CN readme.

Deploy to Virtual Private Server (VPS) or php host
DEMO
null

How to Install
Start web service on your server (httpd or other), make sure you can visit it.

Make the rewrite works, the rule is in .htaccess file, make sure any query redirect to index.php.

Upload code.

Change the file .data/config.php can be read&write (666 is suggested).

View the website in chrome or other.

Features
When downloading files, the program produce a direct url, visitor download files from MS OFFICE via the direct url, the server expend a few bandwidth in produce.

When uploading files, the program produce a direct url, visitor upload files to MS OFFICE via the direct url, the server expend a few bandwidth in produce.

The XXX_path in setting is the path in Onedrive, not in url, program will find the path in Onedrive.

LOGO ICON: put your 'favicon.ico' in the path you showed, make sure xxxxx.com/favicon.ico can be visited.

Program will show content of 'readme.md' & 'head.md'.

guest upload path, is a folder that the guest can upload files, but can not be list (exclude admin).

If there is 'index.html' file, program will only show the content of 'index.html', not list the files.

Click 'EditTime' or 'Size', the list will sort by time or size, Click 'File' can resume sort.

Functional files
favicon.ico
put it in the showing home folder of FIRST disk (maybe not root of onedrive).

index.html
show content of index.html as html.

head.md
readme.md
it will showed at top or bottom as markdown.

head.omf
foot.omf
it will showed at top or bottom as html (javascript works!).

A cup of coffee
https://paypal.me/qkqpttgf

Chat
Telegram Group
https://t.me/joinchat/I_RVc0bqxuxlT-d0cO7ozw
