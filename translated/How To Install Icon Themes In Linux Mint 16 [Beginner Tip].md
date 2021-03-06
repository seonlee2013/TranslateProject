如何在Linux Mint 16中安装图标主题[新手教程]
================================================================================

你是否想过默认的Mint主题和图标并不足以满足你，为何不来点改变那？在这篇初学者快速教程中，我们会告诉你如何**在Linux Mint 16中安装图标主题**以及**如何改变图标**。通过这篇快速教程你将安装上Moka图标主题。

小小提一下，可能你以前不知道，主题和图标主题之间是有区别的。图标主题只是改变图标的外观，而主题则是改变了包括图标在内其余很多东西的外观。

### 在Linux Mint 16中安装图标主题: ###

在Linux Mint（以及其他大部分的Linux发行版）中有个两种方法来安装图标主题。如果你下载了图标主题的压缩包，你可以在~/.icons目录下解压它。通常这个目录并不存在。你可以随意创建它。

安装图标主题的第二种方法是使用[PPA][1]。大多数流行的图标主题都有自己的PPA。让我们来看看如何使用PPA在Mint中安装Moka图标。

### 在Linux Mint 16中安装Moka图标主题: ###

打开terminal（Ctrl+Alt+T）并输入下面的命令：

    sudo add-apt-repository ppa:moka/moka-icon-theme
    sudo apt-get update
    sudo apt-get install moka-icon-theme

### 在Linux Mint 16中改变图标: ###

改变一个[在Ubuntu的图标主题][2]是非常直接简单地。不过在Linux Mint中稍微隐藏了一下。你安装了图标主题后，在菜单中选择**Setting**，然后选择**Themes**。

![](http://itsfoss.com/wp-content/uploads/2014/01/Chnage_Icon_themes_1.jpeg)

现在你可能已经意识到为什么我说在Linux Mint的图标更改稍微隐藏了。至少第一眼，你不会找到一个选项来改变图标。只改变图标，选择**Other settings**并点击**Icons**。你会在这找到所有的图标设置。选择你喜欢的一个。

![](http://itsfoss.com/wp-content/uploads/2014/01/Change_Icon_Linux_Mint.jpeg)

改变会立即生效，并不需要重启。下面是我的Linux Mint使用Moka图标主题后的桌面：

![](http://itsfoss.com/wp-content/uploads/2014/01/Moka_Linux_Mint_16.jpeg)

我希望这篇教程能帮助你实现图标主题的修改。不要忘记Ubuntu 13.10的5个最好图标主题，你可以使用任何你喜欢的图标主题来使你的桌面变得更漂亮。有任何问题，建议，想法？随时联系。

--------------------------------------------------------------------------------

via: http://itsfoss.com/install-icon-linux-mint/

译者：[乌龙茶](https://github.com/yechunxiao19) 校对：[校对者ID](https://github.com/校对者ID)

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创翻译，[Linux中国](http://linux.cn/) 荣誉推出

[1]:http://en.wikipedia.org/wiki/Personal_Package_Archive
[2]:http://itsfoss.com/how-to-install-themes-in-ubuntu-13-10/