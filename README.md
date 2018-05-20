# Weibo-Spider-Master
基于微博关键字的爬虫，用到了简单的模拟登陆和简单的自动化模拟


# 1. 项目简单介绍

  1.1 项目爬取网站：微博移动版https://weibo.cn/
  
  1.2 项目所用到的Python库
  
       selenium 
            用于自动化模拟，模拟登陆，获取由JavaScript自动生成的网页源代码，这里用到的模拟浏览器是FireFox火狐浏览器，注意浏览器的配置。 
            
       urllib   
            用了urllib.quote来编码关键字 
            
       time     
            主要用time.sleep这个函数
            
# 2. 各部分代码介绍

  2.1 WeiboSpider.py
  
      建立了一个类Spider类。
      
  2.2 Weibo.py
  
      建立了一个类WeiboConetnt类，用来储存每一条微博内容的类（包括作者的名字和微博的具体内容）。
      
  2.3 run.py
  
      主函数，直接设置关键词运行这个部分即可。
