---
layout: post
title: 使用HTTrack和Github进行网站“硬核备份”
comments: true
---

# 使用HTTrack和Github进行网站“硬核备份”

<p style="text-indent: 2em;">网站备份有多种方式，常见的如使用WordPress插件备份[1]或者在主机中自行打包数据库备份[2]等。但有没有一种能够快速、又能保持原貌的网站备份方式呢？答案是肯定的。最近我发现了一种“硬核”的备份方式：配合使用网站下载工具HTTrack和Github，可以将网站完整的下载至本地硬盘或者上传到安全的网络空间上。</p>
<p style="text-indent: 2em;">首先，这是我的网站原始地址：<strong><a href="https://dayday.plus/">原网页</a></strong> ，这是我的网站备份地址：<strong><a href="https://world-fantasy.github.io/dayday.plus/index.html">备份地址</a></strong> 。可见这种网站备份方式完整保留了网站的外观、评论、插件、外部链接等。</p>
<p style="text-indent: 2em;">1  <strong>下载并安装HTTrack</strong> (<a href="https://www.httrack.com/">下载地址</a>)</p>
<img class="aligncenter size-medium" src="https://i.loli.net/2019/12/15/OnHGy1uUlWZCKQ9.png" width="1044" height="561" />
<p style="text-indent: 2em;">2<strong> 新建工程，填写网站链接，下载网站。</strong>下载完毕后即可以在本地浏览自己的网站。</p>
<img class="aligncenter size-medium" src="https://i.loli.net/2019/12/15/u42mKSf9BRpChtk.png" width="1012" height="643" />

<img class="aligncenter size-medium" src="https://i.loli.net/2019/12/15/C8Ve3DfnkMPvg6y.png" width="1008" height="642" />
<p style="text-indent: 2em;">3 <strong>上传至Github。</strong>使用Github Desktop软件将HTTrack下载的网站文件夹完整的上传至一个新的repository，并将这个repository命名为your-github-username.github.io的形式。</p>
<img class="aligncenter size-medium" src="https://i.loli.net/2019/12/15/SpQxUG4bsdJwr7K.png" width="960" height="660" />
<p style="text-indent: 2em;">4 <strong>开启Github Pages。</strong>进入repository的设置页面，确认该仓库为"Public"，然后打开Github Pages，这样就可以在网站上浏览自己的备份网站了。</p>
<img class="aligncenter size-medium" src="https://i.loli.net/2019/12/15/wQh6oG7rCcgmRqs.png" width="1031" height="461" />

<img class="aligncenter size-medium" src="https://i.loli.net/2019/12/15/l6pJsnbTGOf54aW.png" width="687" height="735" />
<p style="text-indent: 2em;">我为什么喜欢这种备份方式呢？最重要的原因是可以完整的保留网站的原貌。我的网站所有图片都是免费托放在外部的图床上的，主机也没有使用的可靠的大企业的主机（如阿里云、微软github等），这让我一直很没有安全感。通过这种方式将网站完整的保存在本地，并上传到Github上，即便未来某天图床或者主机商挂掉，我依然可以将自己的网站完美的展示出来。</p>


<hr />

<ul>
 	<li>[1] <a href="https://www.wpbeginner.com/plugins/7-best-wordpress-backup-plugins-compared-pros-and-cons/">7 Best WordPress Backup Plugins Compared (Pros and Cons)</a> , 2019-12-15</li>
 	<li>[2] <a href="https://www.seoimo.com/wordpress-backup/">WordPress备份: 整站备份+MySQL导出+还原/恢复+FTP迁移【自动脚本】</a> , 2019-12-15</li>
</ul>
