---
layout: post
title:  "Mac OSX Linux 環境設定檔"
date:   2016-02-18 15:00:00
categories: jekyll update
---

真的不太懂自己幹嘛一定要搞清楚這些設定檔，

大概就是我在學習上有比較多的障礙。


了解自己怎麼學習也是很重要的事情，不想著跟別人不同。

而是靚亮發會自己的專長，彌補差太多的部分。

成熟是知道自己不竹的地方而不會搞到挫折吧。

成熟就是知道自己此時此刻要做的事而不被他人影響。



###Mac OSX root 的設定檔 

系統的設定檔 /etc/profile


###使用者的設定檔

個人的設定檔

###切換 bash , zsh

```
#檢查目前系統使用的 shell
$echo $SHELL
#切換 bash
$chsh -s /bin/bash
# 切換 zsh
$chsh -s /bin/zsh

```


bash 的設定檔

~/.bash_profile
~/.bashrc

ps.如果目前使用 zsh ，termial 開啟不會經過這兩隻設定檔。

iterm 2 的設定

~/.bash_prompt

zsh 的設定

~/.zshrc
~/.oh-my-zsh/


vim 的設定

~/.vimrc


###執行 bash shell

方法一

```
$. test.sh
$sh test.sh
$bash test.sh
$source test.sh
```

方法二

```
$./test.sh
```

ps.小心檔案權限不可執行 
```
$chmod +x test.sh
```

###bash shell 語法

註解 #

```
# 通常會在檔頭上註解，代表這隻 shell 為 bash shell
#!/bin/bash
```

參數

    -$? :
    -$0...,

.sh 檔案執行食，帶入參數

建立一個 test.sh

```
#!/bin/bash
echo -n 
```


for in 迴圈

流程控制

函式





###資料
1.(鳥哥 Linux 私房菜)[http://linux.vbird.org/linux_basic/0320bash.php]
2.(創建自己的 Shell 環境)[http://far.logdown.com/posts/87527-create-your-own-shell-environment]
3.(簡易的 Shell Scripts)[http://www.suse.url.tw/sles10/lesson10.htm]