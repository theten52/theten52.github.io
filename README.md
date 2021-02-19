> 注意：在配置dns解析时不要使用通配符“\*”的A记录解析。会造成无法解析，会造成CNAME无法解析。因为先匹配的A记录通配符“\*”，再匹配的CNAME记录。详见[管理 GitHub Pages 站点的自定义域](https://docs.github.com/cn/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site)，及下图：
>
> ![阿里云禁用通配符解析A记录](/Users/wangjin/IdeaProjects/theten52/theten52.github.io/pic/阿里云禁用通配符解析A记录.png)
>
> ![通配符解析禁用前后对比](/Users/wangjin/IdeaProjects/theten52/theten52.github.io/pic/通配符解析禁用前后对比.png)

[网站搭建文章：《Jekyll+Github个人博客构建之路》](https://robotkang.cc/1733.html)

[网站搭建源码 MengZheK/githubblog github](https://github.com/MengZheK/githubblog)