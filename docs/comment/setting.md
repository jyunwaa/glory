## random_comments.txt

`random_comments.txt`用于存放随机评论的内容。
  - 一行表示一条评论
  - 默认存放的是90条歌词评论
  - 你可以删掉或者注释掉默认的评论，添加自己的评论
  - 但是程序运行至少需要50条随机评论
  - 随机评论越多越好，300至1000条为最佳
  - 加`//`（双斜杠表示注释，不会采用为评论）
  - 空行也不会被采用
  - 每条随机评论不能超过 140 个字符

```txt
// 加//（双斜杠表示注释，不会采用为评论）
// 该条被注释，不会被采用
// 空行也不会被采用

//《多远都要在一起》
想听你听过的音乐 想看你看过的小说 我想收集每一刻 我想看到你眼里的世界 想到你到过的地方 和你曾渡过的时光 不想错过每一刻 多希望我一直在你身旁
未来何从何去 你快乐我也就没关系 对你我最熟悉 你爱自由我却更爱你 未来何从何去 你快乐我就随你而行 对你我最熟悉 你爱飞翔我却更爱你
我能习惯远距离 爱总是身不由己 宁愿换了方式 至少还能遥远爱着你 我能习惯远距离 爱是能放下自己 也许换了方式 至少还能遥远爱着你
爱能克服远距离 多远都要在一起 你已经不再存在我世界里 请不要离开我的回忆 想你说爱我的语气 想你望着我的眼睛 不想忘记每一刻 用思念让我们一直前进
想象你失落的唇印 想象你失约的旅行 想象你离开的一刻 如果我有留下你的勇气 就让我独自守着回忆 如果阳光永远都炽热 如果彩虹不会掉颜色 你能不能不离开呢

//《Where D U GO》
曾看着同星空 闲聊吹风 看日出多心动 曾每日缠一起 傻傻讲起 能爱到下世纪 而这夜月光中 再见影纵 再献花多感动 而似蜜甜的心 明明开心 为何又骤降温
怎麽你一下子抱紧 却一下子转身 不再亲近 独自苦等 仍然空等 难藏泪印 Tell me where did u go? 心声都不可细诉 Oh tell me baby where did u hide? 辛苦都未被谅解
Where did u go? 数数多久不碰到 我在每夜　彻夜狂想... Where did u go? Where did u go? 怎会当这刻我需要你　你却没在我身边 Where did u go? Where did u go? 这秒钟很挂牵　你却不可感觉到

// ...
```

## 获取一级评论信息

### 登录主号

登录用于发表主楼（一级评论）的账号，登录方法参考`安装脚本`>`获取 Cookie`>`登录新浪`步骤。

登录账号`GEM迷183007`（登录你自己的主号，我的主号是`GEM迷183007`），如图：

![](https://p.pstatp.com/origin/1388700000f244e523e9a)

### 发表一级评论

找到想要刷评论的微博，我们随便找一个，然后发表我们的评论，如图：

![](https://p.pstatp.com/origin/ff3a00025c4dedb8d26d)

评论成功后会在自动跳转的页面看到我们刚才的评论，如图：

![](https://p.pstatp.com/origin/138310000c61a79e85636)

点击`回复`，进入回复页面，如图：

![](https://p.pstatp.com/origin/1380900009f23b6a382e6)

我们把注意力放到地址上，如上图，红色划线部分是`微博ID`，绿色划线部分是`评论ID`，蓝色划线部分是`评论标识`。

### 保存一级评论信息

我们进入刚才的命令行窗口，输入以下命令（替换为自己的具体内容）：

```cmd
glory comment:add --weibo_id=JbkUKmL5B --comment_id=4542637854438788 --comment_sign=33471e
```

按下回车，结果如图：

![](https://p.pstatp.com/origin/138130000a63efb550280)

输入命令：

```cmd
glory comment:view
```

按下回车，如图：

![](https://p.pstatp.com/origin/1384700010d29e958f09e)

我们主要关注`TaskID`，即评论任务ID，在执行运行命令时需要通过它指定任务。
