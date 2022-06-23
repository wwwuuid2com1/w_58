# w_58
Cloudreve云盘系统源码，支持本地储存和对接各大对象储存,界面美观
<br/></br>
[下载地址](https://www.uuid2.com/58.html "下载地址")
<br/></br>
<h3>源码简介：</h3>
<p>云盘系统安装教程<p>
<p>测试环境:PHP7.1 + MYSQL5.6 + Apache<p>
<p>1. 上传源码到根目录<p>
<p>2. 安装程序:  浏览器数据 http://localhost/CloudreveInstallerlocalhost更换成你的网址<p>
<p>3. 安装完毕 记住系统默认的账号密码<p>
<p>温馨提示:如果默认的伪静态不行就替换一下的,没问题就不用换!<p>
<p>伪静态配置<p>
<p><IfModule mod_rewrite.c><p>
<p>RewriteEngine on<p>
<p>RewriteCond %{REQUEST_FILENAME} !-f<p>
<p>RewriteCond $1 !^(index\.php|samples|robots\.txt|views|plugins|backup|upload|images|install|admin123|plug|test|install|make|js|favicon\.ico|templates|mqqt|scl|app)<p>
<p>RewriteRule ^(.*)$ index.php/$1 [L]<p>
<p></IfModule><p>
<h3>截图：</h3>
<img src="https://www.uuid2.com/wp-content/uploads/img/202105/c4ec129930.png" alt="Cloudreve云盘系统源码，支持本地储存和对接各大对象储存,界面美观">
