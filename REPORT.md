# WEB应用软件开发实训 — 第二次作业 — 开发一个静态网站

网站的公网网址           

https://ethan0430.github.io/

网站源代码Github仓库网址

https://github.com/ETHAN0430/ETHAN0430.github.io

## 一、网站目录结构

    .
    ├── _authors
    │   ├── jill.md
    │   └── ted.md
    ├── _config.yml
    ├── _data
    │   └── navigation.yml
    ├── _includes
    │   └── navigation.html
    ├── _layouts
    │   ├── author.html
    │   ├── default.html
    │   └── post.html
    ├── _posts
    │   ├── 2018-08-20-bananas.md
    │   ├── 2018-08-21-apples.md
    │   ├── 2018-08-22-kiwifruit.md
    │   ├── 2021-05-12-Markdown 代码.md
    │   ├── 2021-05-12-Markdown 列表.md
    │   ├── 2021-05-12-Markdown 区块.md
    │   ├── 2021-05-12-Markdown 图片.md
    │   ├── 2021-05-12-Markdown 教程.md
    │   ├── 2021-05-12-Markdown 标题.md
    │   ├── 2021-05-12-Markdown 段落.md
    │   ├── 2021-05-12-Markdown 表格.md
    │   ├── 2021-05-12-Markdown 链接.md
    │   └── 2021-05-12-Markdown 高级技巧.md
    ├── _sass
    │   └── main.scss
    ├── _site
    │   ├── 2018
    │   │   └── 08
    │   │       ├── 20
    │   │       │   └── bananas.html
    │   │       ├── 21
    │   │       │   └── apples.html
    │   │       └── 22
    │   │           └── kiwifruit.html
    │   ├── 2021
    │   │   └── 05
    │   │       └── 12
    │   │           ├── Markdown-代码.html
    │   │           ├── Markdown-列表.html
    │   │           ├── Markdown-区块.html
    │   │           ├── Markdown-图片.html
    │   │           ├── Markdown-教程.html
    │   │           ├── Markdown-标题.html
    │   │           ├── Markdown-段落.html
    │   │           ├── Markdown-表格.html
    │   │           ├── Markdown-链接.html
    │   │           └── Markdown-高级技巧.html
    │   ├── about.html
    │   ├── assets
    │   │   └── css
    │   │       ├── styles.css
    │   │       └── styles.css.map
    │   ├── authors
    │   │   ├── jill.html
    │   │   └── ted.html
    │   ├── blog.html
    │   ├── index.html
    │   └── staff.html
    ├── about.md
    ├── assets
    │   └── css
    │       └── styles.scss
    ├── blog.html
    ├── index.html
    └── staff.html

## 二、网站截图
截图内容：

-首页
![image](https://user-images.githubusercontent.com/71263363/118358172-3ac82980-b5b0-11eb-9160-74b6cb394ad8.png)
-Blog列表页
![image](https://user-images.githubusercontent.com/71263363/118358182-41ef3780-b5b0-11eb-92b0-b18d4dad01c8.png)
-两篇Post（至少有一篇是Markdown练习）
![image](https://user-images.githubusercontent.com/71263363/118358211-68ad6e00-b5b0-11eb-9625-1ba78cf86373.png)
![image](https://user-images.githubusercontent.com/71263363/118358226-719e3f80-b5b0-11eb-9a79-aaff474dc6d4.png)!
-Staff列表页
![image](https://user-images.githubusercontent.com/71263363/118358249-8da1e100-b5b0-11eb-9fb3-27c5788bd7d5.png)
-一个作者简介页面
![image](https://user-images.githubusercontent.com/71263363/118358323-d3f74000-b5b0-11eb-97ff-fcb1c677aaa6.png)
-一个About页面
![image](https://user-images.githubusercontent.com/71263363/118358333-e1142f00-b5b0-11eb-940f-c2274d7f5e67.png)


## 三、实验过程
根据Step by Step Tutorial完成实验
https://jekyllrb.com/docs/step-by-step/01-setup/
遇到不懂的问题利用百度必应搜索引擎搜索大量信息直到达成目的


## 四、总结
1.一开始直接jekyll new整了一个自带的网站 后来询问过老师才知道要新建一个文件夹

2.在git push时遇到了许多问题 
  通过搜索引擎找到了解决办法
  比如git clone
      git add .
      git commit -m
      git config --global user.name
      git config --global user.email
      
3.在写实验报告时碰到了目录树的问题，通过搜索引擎搜索和wsl自带的提示 sudo apt install tree 解决了问题
  复制进来后又发现并不是一个目录树的形状 通过搜索引擎搜索了解到在前面按两下tab即可解决问题
  
本次实验令我受益匪浅，初步了解了静态网站开发的过程，也给予本人极大的信心和自豪感继续深入学习。

