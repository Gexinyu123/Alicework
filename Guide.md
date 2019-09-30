# 使用git的方法

git是目前最流行的版本控制工具，如使用得当可大大提高组内ass文件的管理效率。但是大部分人都不适应使用命令行的软件，故有此篇教程。

## 注册一个GitHub账号

打开 github.com ，您就会看见一个巨大的注册表格。

![github.com](https://i.loli.net/2019/09/29/LqQpxMvfysGeBS5.png)

填入用户名、邮箱、密码，就注册成功了，十分简单。

## 接受协作者邀请

将您的用户名(Username)提供给scrpr，他将会为您发送协作者邀请。您必须接受邀请后才能开始工作。

## 使用图形化git客户端

### 下载和安装

如果您不介意软件界面是英文的话，建议使用[GitHub for Desktop](https://desktop.github.com/)，这是一个简单易用的客户端，即使您不懂英文应该也很快就能上手。

↑国内网络环境下载可能有困难，`群文件`>`其他`文件夹中提供了安装包。

### 使用

#### 复制远程仓库到本地

您必须把所有文件下载到本地才能开始工作，这就是为什么我们把已完成工作丢到了另外一个分支。

首先，当然是打开软件。

![MainPage](https://i.loli.net/2019/09/29/A4RTJkdc19LYHw7.png)

选择第一个，也就是从 Internet 复制仓库到本地。

![clone](https://i.loli.net/2019/09/29/lJhKWavncf6wNX5.png)

![signin](https://i.loli.net/2019/09/29/V6iZWnGdA3c1LUa.png)

登录后，选择一个本地文件夹来保存仓库。请尽量选一个常用的路径，这个文件夹将成为您以后的**工作文件夹**。

![localpath](https://i.loli.net/2019/09/29/j8v6MEDQX9qLy4z.png)

#### 开始工作

现在您可以像以往一样开始工作了。打轴、填轴、校对什么的。

当您活干完了之后，再次打开GitHub Desktop，文件的改动和对比都会显示出来。

![changed](https://i.loli.net/2019/09/29/LDQ46s91UYTOZuF.png)

请在箭头所指处填写说明文字（如空轴、已校等），然后点击“Commit to **master**”，提交您的更改。

![push](https://i.loli.net/2019/09/29/HMkcmQxEUvlpPXg.png)

随后，点击红框所示来把您的更改推送到远程仓库。**直到这一步才会对远程仓库产生影响，不然所有的改动都是在本地进行的。**

![fetch](https://i.loli.net/2019/09/29/IKca7fB5pPLzxjg.png)

有时会出现这样的提示，那是因为有人在您推送更改之前就推送了其他更改，此时您需要刷新一下来跟远程仓库同步。点击“Fetch”即可。

Fetch之后再Pull，然后再Push，就可以了。

有时在您没事打开看软件的时候也会提示pull，照做即可，这不会对您目前修改过的文件产生影响。