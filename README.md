flight_we
=========
index.html
----------
查询所要访问的页面。
flight.js
---------
页面内所有javascript代码。包括使用jquery-ui插件和Highcharts绘图工具，以及AJAX。
style.css
---------
界面css文件。
webservices.php
---------
通过调用网上免费的webService接口获取航班基本信息，存入数据库。
target.php
---------
- 机票信息抓取第一步所要访问的url由此php生成，提供需要抓取的网页。
- 抓取完成后到解析数据存入数据库的php文件链接，让MetaSeeker模拟点击，
- 实现抓取，解析自动化。
xml.php
---------
用来处理抓取来的机票数据并存入数据库的php文件。
test.php
---------
提供趋势图所需的数据。
process.php
---------
提供机票查询所需的数据。

