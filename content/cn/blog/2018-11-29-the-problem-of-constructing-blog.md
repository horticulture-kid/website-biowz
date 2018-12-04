---
title: 创建博客时想删除最下面的内容，解决方法。
author: wz
date: '2018-11-29'
slug: the-problem-of-constructing-blog
categories: []
tags:
  - blog
---

 when i constructed the blog ,i wanna to remove “Powered by the Academic theme for Hugo.” i found it was so diffcult.Luckly, i got the solution of it.
 
 for academic theme of hugo:
 
 you can clone the data to your computer,then you should open file "D:\blog\my_academic\themes\hugo-academic\layouts\partials\footer_container.html".and you can edit the file.such as :delete or modify it<br>
 ```{r}
  Powered by the
      <a href="https://sourcethemes.com/academic/" target="_blank" rel="noopener">Academic theme</a> for
      <a href="https://gohugo.io" target="_blank" rel="noopener">Hugo</a>.
 ```
 
 then , the problem was solved.
 
 reference:[参考1](https://github.com/kakawait/hugo-tranquilpeak-theme/issues/243)
 
 #### 在修改的时候遇到网站最下面有地图定位，想删了
 
 you can clone the data to your computer,then you should open file "D:\blog\my_academic\themes\hugo-academic\layouts\partials\footer.html".and you can edit the file.such as :delete or modify it<br>
 then , the problem was solved.
 