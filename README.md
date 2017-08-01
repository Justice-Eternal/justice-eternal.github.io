# Justice_Eternal (移动端)
—— 一个ACG口琴众的大家庭

![license](https://img.shields.io/github/license/mashape/apistatus.svg)  [![](https://img.shields.io/badge/%E8%B4%B4%E5%90%A7%20-%20justice__eternal%20-orange.svg)](https://tieba.baidu.com/f?kw=justice_eternal&ie=utf-8)  ![](https://img.shields.io/badge/Made-%E2%9D%A4-ff69b4.svg)

## 网站说明

Justice_eternal吧网站[vue](https://github.com/vuejs/vue)版本

移动端网址：[https://justice-eternal.github.io/](https://justice-eternal.github.io)

![demo6.png](http://upload-images.jianshu.io/upload_images/2141706-11ab2c7280c2a865.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![demo7.png](http://upload-images.jianshu.io/upload_images/2141706-9a8a0bb7f30f1ae2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

PC端网址：[http://lightmoon.pw](http://lightmoon.pw)

曲库地址：[https://github.com/zytx121/justice_eternal/issues](https://github.com/zytx121/justice_eternal/issues)

在[Vue-bilibili](https://github.com/youhonglian/Vue-bilibili)的基础上进行改造~感谢youhonglian在网站开发过程中的帮助！

> 技术栈：vue + vue-router + vuex + axios  全家桶，以及mint-ui

## 本Webapp的主要功能：

- 利用github的谱库接口来进行谱子的搜索
- B站热门口琴（贴吧朋友）视频展示及播放
- 大神录音以及吧众录音的展示
- 骗新人入坑（将贴吧置顶帖中的教学贴全都放在了新手入门页面）
- 交流平台，每个口琴谱的issue都是可以用github账号评论的，也就是说每个谱子下面可以交流吹奏经验，附上自己吹奏的录音链接或者视频链接。
- 号召更多苦力来搬运谱曲。。。嗯。。。
- 更多功能等你们发现~


## 关于本站

本站完全出于兴趣构建，基本零成本，如果大家喜欢，还请在github上star一下本项目，顺便follow一下本人~~阿里嘎多！

另外，如果对本站有什么建议也一定要在issue中提出来哦！要是能够PR那就再好不过了- -！



## 版本日志

> 版本号命名规则 vX.Y.Z
> 
> X: 主版本号, Y: 次版本号, Z: 修订号


### v1.2.0 
- 2017.08.1 发布
- 修复BUG
  - 修复了手机端视频无法播放的问题
- 优化完善
  - 首屏进行了简化，突出了搜索的功能，加载速度提升，提高用户体验。
  - 将顶部的bar改到了底部
  - 对搜索结果页面进行了简化，去除了多余的功能，优化了搜索的逻辑，添加了搜索推荐功能
  - 增加了搜索为空时的页面，点击绿色字体会跳转到曲谱库进行谱子的提交
  - 夏日清凉版初音皮肤上线，点击侧边栏按钮可以刷新皮肤
  - 将原来的视频及音频合到了一个页面，分为视频专区以及录音专区
  
### v1.1.0  
- 2017.07.30 发布
- 修复BUG
  - 修复图片分辨率过高导致加载过慢
  - 修复顶部tap栏没有对齐

### v1.0.0  
- 2017.07.29 发布
- 利用[vuex](https://github.com/vuejs/vuex)添加了标签部分隐藏/展示功能~
- 使用[api.imjad.cn](https://github.com/journey-ad/api.imjad.cn)的b站API
- 引入[vue-aplayer播放器](http://aplayer.quq.cat/)


