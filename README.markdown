custom [Vim](http://vim.org) like [TextMate](http://macromates.com) for Ruby Developers.

##从huacnlee那里frok来的，挺好用，添加了一些插件和因应自己的一些习惯对配置作了一些修改，thx huacnlee

## Features

* Simple UI, removed the Menu,Toolbar,Scrollbar etc.;
* Textmate bundles like snippets, and you can custom is in vimfiles/snippets;
* -Word,Keyword autocomplete- ;
* BufExplorer? with mulit-file edit, press F8.
* NERD tree with Project list,press F7 and then press ? to view help
* Zen Coding
* Show color as background with hex color code in CSS file 

## Install

```bash
git clone git://github.com/huacnlee/vimmate.git
cd vimmate
./install
```
   
## 使用说明
   
### 快捷键说明

* F7 -- 开关 NERD tree (文件目录树)
* Ctrl+b -- 开关 BufExplorer? (用于切换已经打开的文件，Tab的替代品)
* Ctrl+F12 -- 显示/隐藏 主菜单 (默认隐藏)
* Ctrl+上，下，左，右 -- 窗口区域间切换，切换光标到 NERD tree、编辑区...
* Ctrl+Shift+p 或者 Ctrl+Shift+n -- 调用自动完成
* = -- 自动根据代码缩进
* \cc -- 注释
* \c空格 -- 去掉注释
* \ci -- 开关注视
* \ff -- Javascript 代码自动排版
* \P -- 在浏览器中预览 rdoc/html/markdown/textile 文件
* v -- 进入键盘选择模式
* V -- 进入键盘行选择模式 

### NERD tree 快捷键

* b -- 开/关 收藏夹
* D -- 删除 选中的 收藏
* ? -- 显示帮助
* Enter -- 选择/展开关闭 目录
* m -- 显示文件操作菜单，用它来创建/移动/删除 目录或文件
* u -- 跳到上一个文件夹
* C -- 将跟节点转入当前选中的目录
* r -- 刷新选中的目录
* R -- 刷新根节点的目录
* cd -- 将vim的运行时目录改为选中的目录
* Bookmark 别名 收藏 NERD tree 里面当前选择的目录 

### BufExplorer

* D -- 关闭选中的文件
* d -- 清楚选中的文件
* Enter -- 切换到选中的文件
* p -- 显示隐藏 文件名列
* R -- 显示隐藏 文件目录列
* u -- 显示隐藏 未列出的 Buffers
* s -- 改变排序方式 "编号(打开的顺序)","文件名","目录名","mru","扩展名"
* r -- 倒序排列 

## 截图

![vim1](http://farm6.static.flickr.com/5090/5285851000_92618eddb4_b.jpg)
![vim2](http://farm6.static.flickr.com/5045/5285850816_7df1afe88c_b.jpg)

