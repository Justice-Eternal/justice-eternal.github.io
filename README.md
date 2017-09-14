# Justice_Eternal (Mobile)
> 一个ACG口琴众的大家庭

![license](https://img.shields.io/github/license/mashape/apistatus.svg)  [![](https://img.shields.io/badge/%E8%B4%B4%E5%90%A7%20-%20justice__eternal%20-orange.svg)](https://tieba.baidu.com/f?kw=justice_eternal&ie=utf-8)  ![](https://img.shields.io/badge/Made-%E2%9D%A4-ff69b4.svg)

## 本Webapp的主要功能：

- 利用github的谱库接口来进行谱子的搜索
- B站热门口琴（贴吧朋友）视频展示及播放
- 大神录音以及吧众录音的展示
- 骗新人入坑（将贴吧置顶帖中的教学贴全都放在了新手入门页面）
- 交流平台，每个口琴谱的issue都是可以用github账号评论的，也就是说每个谱子下面可以交流吹奏经验，附上自己吹奏的录音链接或者视频链接。
- 号召更多苦力来搬运谱曲。。。嗯。。。
- 更多功能等你们发现~

### 项目展示
![image](https://github.com/Justice-Eternal/justice-eternal.github.io/blob/master/demo.gif)

## 网站说明

Justice_eternal吧网站[vue](https://github.com/vuejs/vue)版本

移动端网址：[http://jefun.top/](http://jefun.top/)

![demo6.png](http://upload-images.jianshu.io/upload_images/2141706-11ab2c7280c2a865.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![demo7.png](http://upload-images.jianshu.io/upload_images/2141706-9a8a0bb7f30f1ae2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

PC端网址：[http://lightmoon.pw](http://lightmoon.pw)

曲库地址：[https://github.com/zytx121/justice_eternal/issues](https://github.com/zytx121/justice_eternal/issues)

在[Vue-bilibili](https://github.com/youhonglian/Vue-bilibili)的基础上进行改造~感谢youhonglian在网站开发过程中的帮助！

> 技术栈：vue + vue-router + vuex + axios  全家桶，以及mint-ui



## 关于本站

本站完全出于兴趣构建，基本零成本，如果大家喜欢，还请在github上star一下本项目，顺便follow一下本人~~阿里嘎多！

另外，如果对本站有什么建议也一定要在issue中提出来哦！要是能够PR那就再好不过了- -！


## Contributors

<a href="http://www.jianshu.com/u/d15860c8c592"><img src="http://upload-images.jianshu.io/upload_images/2141706-61866430b6007437.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240" height="66px" width="66px"></a>
<a href="https://tieba.baidu.com/f?kw=justice_eternal&fr=index"><img src="http://upload-images.jianshu.io/upload_images/2141706-4bdf2f2289334639.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240" height="66px" width="66px"></a>



## 版本日志

> 版本号命名规则 vX.Y.Z
> 
> X: 主版本号, Y: 次版本号, Z: 修订号


### v1.3.3 SAO特别版
* 2017.09.14 发布
* 优化完善
  * 庆祝《刀剑神域 -序列之争-》上映皮肤上线


### v1.3.2 七夕特别版
* 2017.08.28 发布
* 修复BUG
  * 修复了顶部导航条不吸顶的bug
* 优化完善
  * 七夕特别皮肤上线

### v1.3.1 Matthew
* 2017.08.22 发布
* 修复BUG
  * 修复了谱子显示不全问题
  * 修复了评论框底部显示不全问题
* 优化完善
  * fgo学妹紫皮肤上线


### v1.3.0 
* 2017.08.04 发布
* 修复BUG
  * 修复了部分字体太小的问题
* 优化完善
  * 将原来的移动端布局升级为响应式布局，支持ipad及pc端的使用
  * 随着曲库谱子数量的增加，增加了上拉加载更多功能，以及各种情况对应的文字提示
  * 增加 loading 时的趣味提示框
  * 优化了 bottombar 的外观
  * 优化了视频部分的布局及外观，增加了视频教学专区
  * 将指向外部网站的链接设定为弹出新窗口
  * 在教学视频播放页面和谱子详情页面引入了 gitalk ，支持用 github 账号在当前页面进行评论
  * 在谱子详情页面和佳作欣赏页面加入了悬浮效果边框
* 移除
  * ~删除了谱子详情页面跳转到github的评论按钮~
  * ~删除了侧边栏跳转到佳作欣赏的链接~


### v1.2.0 miku
* 2017.08.1 发布
* 修复BUG
  * 修复了手机端视频无法播放的问题
* 优化完善
  * 首屏进行了简化，突出了搜索的功能，加载速度提升，提高用户体验。
  * 将顶部的bar改到了底部
  * 对搜索结果页面进行了简化，去除了多余的功能，优化了搜索的逻辑，添加了搜索推荐功能
  * 增加了搜索为空时的页面，点击绿色字体会跳转到曲谱库进行谱子的提交
  * 夏日清凉版初音皮肤上线，点击侧边栏按钮可以刷新皮肤
  * 将原来的视频及音频合到了一个页面，分为视频专区以及录音专区
* 移除
  * ~删除了首字母分类功能~
  * ~删除了搜索结果分页展示功能~



### v1.1.0  
* 2017.07.30 发布
* 修复BUG
  * 修复图片分辨率过高导致加载过慢
  * 修复顶部tap栏没有对齐

### v1.0.0  
* 2017.07.29 发布
* 利用[vuex](https://github.com/vuejs/vuex)添加了标签部分隐藏/展示功能~
* 使用[api.imjad.cn](https://github.com/journey-ad/api.imjad.cn)的b站API
* 引入[vue-aplayer播放器](http://aplayer.quq.cat/)

## License

Justice_Eternal is released under the MIT license. See LICENSE for details.

