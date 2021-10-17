---
title: 主题设置相关
group:
  title: 常见问题
  order: 5
---

## 保存设置之后配置项全部清空？

> 本主题设置项请勿添加 emoji 表情，否则可能导致其他配置项被清空的情况。<br>
> 重启主题重新配置

## 导航点击相册、书单、影单后显示 404

> 未开启伪静态，宝塔开启伪静态方法如下：
> ![](https://cdn.jsdelivr.net/gh/iRoZhi/irils-imgs/picgo/202110172218297.png)
> 若不是宝塔，请联系 qq80360650

## 开启总访问量显示之后，出现 500 错误？

> 数据表前缀不一样，请进入主题文件：<code>A-My/lib/Utils.php</code>，搜索：<code>总访问量</code><br>
> 将<code>typecho</code>更换为你的数据表前缀
> ![](https://cdn.jsdelivr.net/gh/iRoZhi/irils-imgs/picgo/202110172227960.png)
