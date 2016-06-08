04组 黑逗士

* 队长：Krystal
* 梁靖
* 紫易千荷
* 肩吾
### 问题3：用实例介绍如何使用 Pull Request 和 Merge 实现团队工作协同
#### 第一步：创建一个公共项目：
* 在一个合作项目中，首先需要创建一个公共项目，创建这个项目的人，就是项目的管理者，需要去处理其他协作者发送的pull request请求，需要审核提交内容，选择合并。首先管理者创建一个新的项目--blackbean
![1.png](http://upload-images.jianshu.io/upload_images/249863-3e96ca878df9b545.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
* 然后根据下图将本地创建的库Publish到Github仓库中去。 
![2.png](http://upload-images.jianshu.io/upload_images/249863-2d3a409943c94b22.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
* 项目创建人为项目新增了一个README.md文件
![3.png](http://upload-images.jianshu.io/upload_images/249863-9acf2974d8e57935.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 第二步：协作成员fork项目
* 有了公共项目之后，其他成员首先要fork。以下使用账号jacklyy为例，演示如何fork。 去到库管理员的主页，找到目标项目（blackbean）。
![4.png](http://upload-images.jianshu.io/upload_images/249863-e7acbdc14e9e48e1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
* 进入项目中。点击fork按钮
![5.png](http://upload-images.jianshu.io/upload_images/249863-cb480bebdba84f34.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
* 然后fork后的项目会在你的项目列表中出现
![6.png](http://upload-images.jianshu.io/upload_images/249863-ae2d4cdddd586c36.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 第三步：将fork后的项目clone到本地。
* 如下图，第一在github中点击clone按键复制SSH，第二在命令板中操作 输入口令 git clone +粘贴SSH 完成克隆 第三步 在 github desk 手动添加 clone文件 balckbean（拼写小错误，嘿嘿嘿~）
![7.png](http://upload-images.jianshu.io/upload_images/249863-78ffee294e6c40fd.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
* 添加成功之后：
![8.png](http://upload-images.jianshu.io/upload_images/249863-f800c319ee5235be.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

##### PS:

这里强烈建议使用SSH url来Clone项目。因为用https url Clone的项目默认没有write权限，只有read-only权限，所以当你要更新一个你fork的项目,则会报错，如： 
* “The requested URL returned error: 403”.但是！但是！但是！你自己的项目用https url Clone下来，自己推送更新又是没问题的。
* 不要用Github去列表中clone项目，经常会报错，请用命令版Clone，然后用Github客户端收到Add项目到客户端中。 

下面是具体操作：再次注意，请使用图中最右红框中的Clone with SSH项目地址样式，在面板中clone。
