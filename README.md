## 启动前需要安装好依赖库，如scrapy，selenium,json等，selenium还需要配置Chrom驱动
----
## 启动命令:
```
scrapy crawl sogou_weixin0 -o filename.csv
```
----
## 爬取结果导出csv:
```
scrapy crawl sogou_weixin0
```
## 注意事项：
* 登陆操作的时候一定要等登陆页面跳转后加载完，才能按回车

* 默认只开启了文章抓取，如果要开启公众号抓取，请去掉/spider/sogou_weixin.py中公众号Request的注释
