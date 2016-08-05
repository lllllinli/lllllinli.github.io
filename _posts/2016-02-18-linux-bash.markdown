---
layout: post
title:  "Mac OSX iTerm 2 ,Zsh, Oh my Zsh 設定"
date:   2016-02-18 15:00:00
categories: jekyll update
---

想了解 Mac OSX 上， Term 。

寫席寫程式也已經六年了，對 Linux 還是一知半解。

想秤著歇息的這段時間，了解自己的作業環境和 Linux 的指令操作。

這大概就是轉換 Mac 的原因。



###Mac 上遇到 bash shell


在 Mac 上開終端機，直接使用終端機是很陽春的 黑白介面。

一般都會推薦使用 iterm 2 (Link)[https://www.iterm2.com/]

當初選擇的原因是因為他是彩色的，總之就是浮誇。

因為要調整顏色，搜尋到了一些修改 shell 的資料，看了半天，能做的只有複製貼上。

這幾天都在學習 Linux 指令。 進度總算到了學習 bash shell 的進度。

###iTerm 2 的設定檔 ~/.bash_prompt

iTerm 2 執行食，會先跑個這個 shell 把設定帶入。


###{工具}Zsh, oh-my-zsh

shell 有很多種 linux 內建為 bash shell。

Mac OSX 也是。

Zsh 是另一種 shell ，網路查了一下，除了有更多人性化的樣式提示（浮誇），另外有。

1.兼容 Bash

2.自動補齊與自動拼字糾正

3.顯示 git 分支


筆記：

oh-my-zsh 設定檔 ~/.zshrc

1.切換 style

```
ZSH_THEME="powerline"
# 目前使用 style :powerline
```

2.PATH 繼成

修改 ~/.zshrc 中 PATH 變數

```
# 原來設定
PATH=PATH....
```

```
# 修該 (繼持原有的 PATH 變數)
PATH=$PATH....
```

3.plugin 一些工具加入，比如說：git npm nvm rvm

可以搜尋 ~/.oh-my-zsh/plugin 如果有

可在設定檔 ~/.zshrc

```
# 修改
plugins=(git nvm npm)
```

4.alias ，

原本設定 alias 會放在， ~/.bashrc 

使用 oh-my-zsh 需要將 alias 複製一份到，~/.oh-my-zsh/lib/





其他...

1.(我在用的mac軟件(2)-終端環境之zsh和z(*nix都適用))[http://foocoder.com/blog/wo-zai-yong-de-macruan-jian-2.html/]
2.(如何設定iTerm2環境?)[http://oomusou.io/osx/iterm2-setup/]
3.(oh my zsh 的快速鍵)[https://github.com/robbyrussell/oh-my-zsh/wiki/Cheatsheet]
4.(oh-my-zsh 設定)[http://michaelhsu.tw/2013/05/07/%E5%96%94-%E6%88%91%E7%9A%84-zsh-/]

安裝完成之後，又發現了 fish ，這個 shell

多了一些新的功能，這都是工具追了沒太大意義。

1.(比 Zsh 比好用的 Shell：Fish Shell 介紹與安裝)[https://nodejust.com/fish-shell-zsh/]


###待解決問題


還不清楚 shell 執行的順序，這一階段的心得是，還是很苦惱，這個學習 Linux 的路徑。

一個一個來吧。

###資料
