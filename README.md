# Listen 1 (Browser Extension) 
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](LICENSE)

## 缘起
当我发现找个想听的歌因为版权听不了，需要打开好几个网站开始搜索，来回切换让我抓狂的时候，我知道是时候该做点什么了。

妈妈再也不用担心我找不到我想听的歌了。这里包含了网易云音乐，虾米，QQ音乐的曲库，够全够大了吧。

搜歌，听歌，就用 `Listen1`。

[![imgur](http://i.imgur.com/yblr3KO.gif)]()

还有精选歌单哦。


## 更新日志
`2017-09-11`
* 更新QQ音乐地址，修复方法取自 https://github.com/listen1/listen1_chrome_extension/issues/90#issuecomment-328397516 (@huangzhongxin)

`2017-08-24`，YF 完成。
* 更新 jQuery 库，1.x至3.x。
* 更新 angular 相关库，迁移 $http 语法到新格式。

`2017-07-31`，由 jyma1991 完成，YF 合并。
* 搜索结果支持多选

`2017-07-15`，由 ConstLhq 完成
* 增加搜索分页功能

`2017-07-13`，由 ConstLhq 完成
* 调整歌单来源按钮到顶部
* 更改滚动条的样式
* 增加歌词Tab

`2016-05-27`
* 增加快捷键功能（输入?查看快捷键设置）
* 支持同步播放记录到last.fm
* 增加搜索loading时的图标(感谢@richdho的提交）
* 页面标题增加显示当前播放信息
* 修复了在收藏对话框点击取消出现新建歌单的bug
* 重新组织代码文件夹结构

`2016-05-21`
* 增加歌单分页加载功能(感谢@wild-flame的提交)
* 修复关闭按钮随网页滚动的bug
* 修复点击暂停按钮会重置进度条和歌词的bug
* 修复点击歌单名称不跳转的bug
* 调整歌单水平位置居中

`2016-05-14`
* 增加firefox插件支持（感谢fulesdle的提交）

`2016-05-13`
* 增加我的歌单功能，可以收藏现有歌单，并创建自己的歌单
* 点击Listen 1和图标可以回到首页
* 标记了部分因版权无法播放的歌曲,增加版权提示
* 重构了音乐平台代码，使用统一的接口规范
* 重构了歌单接口，合并歌手，专辑和歌单接口
* 修复了阿里云歌手链接点击错误的bug


`2016-05-08`
* 增加歌词显示
* 精选歌单：添加歌单到当前播放列表，可点击跳转到原始链接
* 修复了搜索qq音乐时的乱码问题
* 修复了循环播放网易歌曲一段时间后暂停的bug
* 修复了可能导致微信公众号无法登录的bug
* 优化性能，删除了不必要的事件消息触发

`2016-05-02`
* 增加音量控制

## TODO
* 分页加载
* 搜索结果多选时，单击条目可正常选中，单击左侧的复选框无效果，需修正。
* last.fm的授权窗口，会被Firefox的弹窗拦截器拦截。

## License
MIT
