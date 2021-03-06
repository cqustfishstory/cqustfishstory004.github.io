---
layout: post
title: 由写作环境引发的反思：单一入口的智能化
categories: [思考]
tags: [写作, Sublime, Google, Evernote]
published: True

---

## 绪论

```python

def hello(name):
	print "hello" + name

```

## 减少操作/思考成本

### 直达目标：文本先行，不用担心其他额外的事情

1. 比如现在我要记笔记、写博客就只需要打开写就是了，然后存到哪里，在哪里看，在哪里改格式，都不用管，或者说不是在写之前要考虑的事情。

2. 目标导向，释放大脑，只需要肌肉记忆 Cmd+Space 打开 Spotlight 里面输入 subl，打开了写就是，先做了再说，最重要就是“写”，剩下的事情之后再解决，内容先行。

3. 不用考虑文字格式，一切都是文本，只是 Markdown 语法，就像写代码一样顺畅和优雅，然后根据 Markdown 语法还可以马上转换成其他任何格式，HTML、Word、PPT、各种随意。

4. 至于存成`.md`文件之后，我可以加上 tag，选择不同的 note 直接转发到 Evernote。也可以存入 Dropbox，之后的查看和修改都是以文本形式的，也就是说我可以用任何与 Dropbox 连接的写作工具进行修改。当然也可以用文件和文件夹的方式管理，这里有一个叫 Marboo 的工具可以进行可视化管理，文件就是文件，显示效果就是 HTML 效果，只做管理功能，不参与编辑，这个理念真是太棒太纯粹。

5. 文本格式还有一个好处就是随处可编辑，就像代码一样，你也可以用 Git 来管理和记录整个写作过程，绝不会丢失任何一处你所涌现的想法，还可以任意回退到你想要的版本。还有就是结合 Jekyll 框架来写博客，把`.md`文件部署到 GitHub Page 上就可以自动生成静态 HTML 了。

6. 技术学习笔记都会用 Markdown 语法以书的形式写在 GitBook 里面，新技术的全面了解最好能够有一个清晰良好的结构组织，而书的形式就再好不过了，就可以用章节的方式来全面管理知识架构。博客的作用主要就用来记录一些技术总结、感悟和思考等等，反正就是偶尔扯扯淡。

### Sublime编辑器：各种强大的快捷键和扩展功能

1. Cmd+R 可以直接搜索`#`、`##`标题，太喜欢这样的层级关系显示。

2. 最棒的就是编辑功能是用代码编辑器，就像写代码一样，当然还有很多快捷键像多处光标，词间跳转这样的功能。

3. 作为一个颜控和工具控，太多的主题和插件可以折腾了呀，可以预想的是到时候就自己写扩展、写工具了。

4. 沉浸模式，完全就是为写作而生，不管是写文本和写代码。


## 工具统一化与入口单一化

### 第二大脑：印象笔记/Evernote

- 最初是觉得把 Evernote 作为信息到知识的终点，储存知识的第二大脑，然后一切资料都在这里被整理，在这里被找到。

- 但是最终发现 Evernote 越来越卡了，打开和搜索的速度都太慢，搜索的效果其实并不好，不能够懂我到底想要什么，总之就是随着加入的东西越来越多，管理和检索知识的成本变高了。

- 此处是不是要思考一下人的大脑的检索过程，人脑在搜索的时候应该是结合多方面因素比如今天的天气、情绪、处境，绝不仅仅只是一个关键词就可以了。

- 并且问题出现了，大脑在你搜索之前就已经给你整理过大量的内容，而且进行了一定程度的空间/时间压缩，所以在需要的时候就能够直接给出最优/最简化的结果。

### 谷歌做搜索和做产品的思路

- Google 在互联网初期的 web 时代以搜索起家，也是以搜索为其网络服务的第一入口，至今也保持了无比简洁的首页。Google 并不像其他巨头加入了各种元素建立起所谓的门户网站，门户网站这种东西服务于为其他网站的流量导流，利益至上，再看看百度的搜索主页吧，只能呵呵。

- 而 Google 大概是在搜索之后才会大做文章，比如根据你搜索的内容之后才会推送相应的广告，而不是一开始就在首页给你摆出广告，这实在是资源的合理分配、智能化搜索和用户体验的多重收益。

- 在 Chrome 浏览器里面也是同样的，地址栏不仅仅只是输入 URL 的，别称 Omnibar，可以搜索和实现大量的操作，当你输入相应的内容，根据内容的不同智能提示相应的 URL 或者书签或者搜索建议。

- 而单一化入口在 Google 的一些尝试中也不是那么简单和有效，比如 Android OS 最初的手机按键是四个，除了现在能够看到的之外还有第四个即搜索按钮，Google 就是想把 PC 时代的单一入口化思路带到移动端。

- 其实我是非常喜欢这种为手机的搜索功能设立一个独立按键的思路，但可能是由于在移动设备上人们更喜欢点击图标而不是输入文字，当然这也是由于屏幕太小，虚拟键盘太难用的结果吧，更甚者，语音输入都比打字来得轻松。

- 最近 Google 在做的事情就是将无处不在的搜索入口与移动端相连接，只需要在搜索栏输入`send to note`/`set a alarm`就可以给自己的手机发送内容或者设闹钟，简直就是又一个通过单一入口、文本先行、目标导向的典范。

### 搜索与人脑的关系

- 搜索的概念其实是非常符合大脑逻辑的，但是纯以关键词的方式进入就远没有人类大脑那么智能化，大脑所考虑的可不仅仅是关键词。

- 回到大脑的自动处理功能，大脑并不仅仅是记录下一切，而是会选择性遗忘一些我们并不需要的东西，并且会从中提取相应的结构，从而建立起最优化策略防患于未然，在我们遇到问题的时候以最快速给出答案。

- 而搜索与大脑类似的功能就是，虽只是给出几个搜索建议/搜索结果，但是背后的自动优化处理是我们看不到的，我们的大脑在睡觉的时候可是为我们做了非常大量的工作。


## 关于未来的畅想：机器人、互联网、部落

### 搜索引擎与机器人的距离有多远？

- 在未来的世界里，可能就会有更加完善的输入输出方式，比如我们输入声音、图像、视频（不限于文本），搜索引擎就会根据这个显性输入和额外隐形输入（比如现在的时间，你身处的地点等等），然后智能化得给出我们最想要的那个结果。那个时候“搜索”大概就不再需要我们再去检“索”了吧，一“搜”，直接给出的就是答案。

- 所以，当一台电脑或者任何一个智能设备具备了多样性的输入模式之后，它跟我们人类的差距还有多远呢？而且，输入的东西其实都是数据，这些数据并不一定要像人类一样具备耳朵、鼻子、眼睛等感官之后才可以获得。如果智能设备可以联网，可以从一些专业部门 Hack 到比人类器官更加准确的数据之后，加上自身强大的存储和运输能力，那是不是要比人类更加强大？

- 更可怕的人工智能的输出模式也不局限于人体所拥有的肢体力量，在全球网络连接之后，人工智能可以随意篡改任何地方的军事情报，也就是国家间的信息战时代，可能会加入第三方势力：人工智能。

- 由此，我不得不再推荐一下《疑犯追踪》这部美剧，The Machine 输入输出的，还有，感情。

### 组织与结构

- 大脑的结构很像互联网，各个神经节点之间协同交流、工作又各有功能分区，层级状的组织架构又使不同神经节点具备不同的基础处理功能。互联网也可以看做是一个巨大的分布式机器群，当它整体发挥作用的时候是否也有与人脑一样的快速优化策略？它又会输出什么的力量来改变世界？

- 另一个有趣的话题是，当每个机器都拥有超高智能的时候，它们会是一个怎么的部落群体？或者说，根本不会像人类一样，从而形成部落。