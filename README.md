# 网易云音乐免费下载MP3，免VIP

本项目针对2020年最新的网易云后台，对所有“vip下载”歌曲如[《我好想你》](https://music.163.com/#/song?id=26524510) 都能免vip下载，下载格式为MP3；尚不能破解“vip试听”的歌曲如[《那些你很冒险的梦》](https://music.163.com/#/song?id=108138) 。

## 项目上传时间

2020年5月18日

## 在线演示

网址：https://loveyou.kurochan.top/fake/music163_download

初次进入需授权码：miku_love_you_1314

点击进入置顶资源“网易云音乐免费下载MP3，免VIP”：

![Snipaste_2020-05-18_12-21-40](git_screenshoot/Snipaste_2020-05-18_12-21-40.png)

## 项目结构

```
├─src
│  ├─main
│  │  ├─java
│  │  │  └─com
│  │  │      └─jzy
│  │  │          ├─demo    //使用示例
│  │  │          ├─model   //模型类
│  │  │          └─util    //核心工具类
│  │  └─resources
│  └─test
│      └─java
```

## 环境

- jdk1.8
- maven3.x

## 使用说明

本项目的代码不是在线演示网页端的完整项目代码，但含其后台所有核心工具方法的封装，供参考调用。

* idea中直接导入本maven项目即可完成初始构建。
* 在`com.jzy.demo`包下有使用示例，可直接运行。
* 所有核心方法都在`com.jzy.util.Music163Utils`工具类中。