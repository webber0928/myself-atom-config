## 文件切換

* `ctrl-shift-s` 保存所有打開的文件
* `cmd-shift-o` 打開目錄
* `cmd-\` 顯示或隱藏目錄樹
* `ctrl-0` 焦點移到目錄樹
目錄樹下，使用a，m，delete來增加，修改和刪除
* `cmd-t`或`cmd-p` 查找文件
* `cmd-b` 在打開的文件之間切換
* `cmd-shift-b` 只搜索從上次git commit後修改或者新增的文件

## 導航
（等價於上下左右）
* `ctrl-p` 前一行
* `ctrl-n` 後一行
* `ctrl-f` 前一個字符
* `ctrl-b` 後一個字符

* `alt-B`, `alt-left` 移動到單詞開始
* `alt-F`, `alt-right` 移動到單詞末尾

* `cmd-right`, `ctrl-E` 移動到一行結束
* `cmd-left`, `ctrl-A` 移動到一行開始

* `cmd-up` 移動到文件開始
* `cmd-down` 移動到文件結束

* `ctrl-g` 移動到指定行 row:column 處

* `cmd-r` 在方法之間跳轉

## 目錄樹操作
* `cmd-\` 或者`cmd-k cmd-b` 顯示(隱藏)目錄樹
* `ctrl-0` 焦點切換到目錄樹(再按一次或者`Esc`退出目錄樹)
* `a` 添加文件
* `d` 將當前文件另存為(duplicate)
* `i` 顯示(隱藏)版本控制忽略的文件
* `alt-right` 和`alt-left` 展開(隱藏)所有目錄
* `ctrl-al-]` 和 `ctrl-al-[` 同上
* `ctrl-[` 和`ctrl-]` 展開(隱藏)當前目錄
* `ctrl-f` 和 `ctrl-b` 同上
* `cmd-k h` 或者`cmd-k left` 在左半視圖中打開文件
* `cmd-k j` 或者`cmd-k down` 在下半視圖中打開文件
* `cmd-k k` 或者`cmd-k up` 在上半視圖中打開文件
* `cmd-k l` 或者`cmd-k right` 在右半視圖中打開文件
* `ctrl-shift-C` 複製當前文件絕對路徑


## 書籤
* `cmd-F2` 在本行增加書籤
* `F2` 跳到當前文件的下一條書籤
* `shift-F2` 跳到當前文件的上一條書籤
* `ctrl-F2` 列出當前工程所有書籤

## 選取
> 大部分和導航一致，只不過加上shift

* `ctrl-shift-P` 選取至上一行
* `ctrl-shift-N` 選取至下一樣
* `ctrl-shift-B` 選取至前一個字符
* `ctrl-shift-F` 選取至後一個字符
* `alt-shift-B`, `alt-shift-left` 選取至字符開始
* `alt-shift-F`, `alt-shift-right` 選取至字符結束
* `ctrl-shift-E`, `cmd-shift-right` 選取至本行結束
* `ctrl-shift-A`, `cmd-shift-left` 選取至本行開始
* `cmd-shift-up` 選取至文件開始
* `cmd-shift-down` 選取至文件結尾
* `cmd-A` 全選
* `cmd-L` 選取一行，繼續按回選取下一行
* `ctrl-shift-W` 選取當前單詞

## 編輯和刪除文本
### 基本操作
* `ctrl-T` 使光標前後字符交換
* `cmd-J` 將下一行與當前行合併
* `ctrl-cmd-up`, `ctrl-cmd-down` 使當前行向上或者向下移動
* `cmd-shift-D` 複製當前行到下一行
* `cmd-K`, `cmd-U` 使當前字符大寫
* `cmd-K`, `cmd-L` 使當前字符小寫

### 刪除和剪切
* `ctrl-shift-K` 刪除當前行
* `cmd-backspace` 刪除到當前行開始
* `cmd-fn-backspace` 刪除到當前行結束
* `ctrl-K` 剪切到當前行結束
* `alt-backspace` 或`alt-H` 刪除到當前單詞開始
* `alt-delete` 或`alt-D` 刪除到當前單詞結束

### 多光標和多處選取
* `cmd-click` 增加新光標
* `cmd-shift-L` 將多行選取改為多行光標
* `ctrl-shift-up`, `ctrl-shift-down` 增加上（下）一行光標
* `cmd-D` 選取文檔中和當前單詞相同的下一處
* `ctrl-cmd-G` 選取文檔中所有和當前光標單詞相同的位置

### 括號跳轉
* `ctrl-m` 相應括號之間，html tag之間等跳轉
* `ctrl-cmd-m` 括號(tag)之間文本選取
* `alt-cmd-.` 關閉當前XML/HTML tag

### 編碼方式
* `ctrl-shift-U` 調出切換編碼選項

## 查找和替換
* `cmd-F` 在buffer中查找
* `cmd-shift-f` 在整個工程中查找

## 代碼片段
* `alt-shift-S` 查看當前可用代碼片段
> 在`~/.atom`目錄下`snippets.cson`文件中存放了你定制的snippets

[定制說明](https://atom.io/docs/v1.0.0/using-atom-snippets)

## 自動補全
* `ctrl-space` 提示補全信息

## 折疊
* `alt-cmd-[` 折疊
* `alt-cmd-]` 展開
* `alt-cmd-shift-{` 折疊全部
* `alt-cmd-shift-}` 展開全部
* `cmd-k cmd-N` 指定折疊層級 N為層級數

## 文件語法高亮
* `ctrl-shift-L` 選擇文本類型

## 使用Atom進行寫作
* `ctrl-shift-M` Markdown預覽
可用代碼片段
> b, legal, img, l, i, code, t, table

## git操作
* `cmd-alt-Z` checkout HEAD 版本
* `cmd-shift-B` 彈出untracked 和modified文件列表
* `alt-g down` `alt-g up` 在修改處跳轉
* `alt-G D` 彈出diff列表
* `alt-G O`​​ 在github上打開文件
* `alt-G G` 在github上打開項目地址
* `alt-G B` 在github上打開文件blame
* `alt-G H` 在github上打開文件history
* `alt-G I` 在github上打開issues
* `alt-G R` 在github打開分支比較
* `alt-G C` 拷貝當前文件在gihub上的網址

## 推荐一些好用的插件
- 主題
[atom-material-ui](https://atom.io/themes/atom-material-ui) 好看到爆
[atom-material-syntax](https://atom.io/themes/atom-material-syntax)
- 美化
[atom-beautify](https://atom.io/packages/atom-beautify) 一鍵代碼美化
[file-icons](https://atom.io/packages/file-icons) 給文件加上好看的圖標
[atom-minimap](https://atom.io/users/atom-minimap) 方便美觀的縮略滾動圖
- git
[atomatigit](https://atom.io/packages/atomatigit) 可視化git操作
- 代碼提示
[emmet](https://atom.io/packages/emmet) 這個不用介紹了吧
[atom-ternjs](https://atom.io/packages/atom-ternjs) js代碼提示很強大，高度定制化
[docblockr](https://atom.io/packages/docblockr) jsdoc 給js添加註釋
[autoclose-html](https://atom.io/packages/autoclose-html) 閉合html標籤
[color-picker](https://atom.io/packages/color-picker) 取色器必備插件
[pigments](https://atom.io/packages/pigments) 顏色顯示插件必裝
[terminal-panel](https://atom.io/packages/terminal-panel) 直接在atom裡面寫命令了
[svg-preview](https://atom.io/packages/svg-preview) svg預覽
