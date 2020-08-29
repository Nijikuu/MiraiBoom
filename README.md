# ~~我不會放棄這個項目的~~ 停止維護
原因：~~MiraiConsoleM3有更完美的啓動方法，而且我懶~~
*我！開！學！了！*


# MiraiBoom

首個易語言寫的mirai一鍵包（大概）
隨時會爆炸的一鍵包（確信）

## 你知道嗎：這是一個套娃項目
 ### 主項目 [Mirai](https://github.com/mamoe/mirai)
 #### 套了個 [Mirai-Console](https://github.com/mamoe/mirai-console/)
 ##### 然後套了個用於啓動[Mirai-Console](https://github.com/mamoe/mirai-console/)的 [Mirai-Console-Stater](https://github.com/Pai2Chen/mirai-console-starter)
 ###### 最後套了個用於啓動[Mirai-Console-Stater](https://github.com/Pai2Chen/mirai-console-starter)的一鍵包
 
 然後源碼裏面套了用於啓動[Mirai-Console](https://github.com/mamoe/mirai-console/)的 [Mirai-Console-Stater](https://github.com/Pai2Chen/mirai-console-starter)的修改版
 - 然後裏面套了個个壓縮包
 - - 壓縮包裏套了[Mirai-Console-Stater](https://github.com/Pai2Chen/mirai-console-starter)倉庫裏面的Lib文件夾和jre

~~套，就硬套~~

# 使用方法
從Release裏面下載然後運行即可

## 魔改方法
~~不會真有人想要魔改這玩意吧！不會吧不會吧~~

因爲文件體積限制，所以CodeSource裏面的啓動+安裝.e是沒有包含必要的文件的，就是個空殼
- 從[這個倉庫](https://github.com/MizunaNako/mirai-console-starter/tree/master/lib/)下載mirai相關的包然後自己找32位jre，并把這堆東西打包為.zip，使其解壓后是**两个文件夹**，而不是一個文件夾裝了兩個文件夾，壓縮包作爲圖片資源，塞進易語言圖片資源表（文件），然後各種魔改+編譯即可
- 或者從ReleaseV0.0.1裏面直接下載Sources.zip，解壓了就是正常的塞了zip的文件，可以直接編譯的那種，撒！開始魔改吧



## 更新方式
[這裏（こ↑こ↓）](https://github.com/project-mirai/mirai-repo/tree/master/shadow/)每個文件夾都下載一個最新版本的文件就行（暴論），然後塞進content裏，把舊版本刪掉，備份，請

## 安全相關
有一説一，這個屑東西拿易語言寫的，到底有沒有問題我也不知道，反正我沒寫什麽問題代碼，如果你局的害怕我建議您不用

# 關於ISSUE
## 以下類型的ISSUE會被直接關閉
- 我不想回答的
- 詢問任何安裝問題（雙擊打開程序，不要放在C盤）
- 詢問如何下載的問題（兄啊，你都會發ISSUE了不會連從Release下載東西都不會吧）
- 詢問如何更新（別問，問就是我也不會）
- 提出bug（開學了沒時間修）

## 以下情況所有ISSUE都不會答復
- 我不在家
- 我開學
- 我梯子炸了
>請注意，開發者沒有義務回答您的問題，請學會自己看代碼

# 功能

## 已經實現
- [x] 自動解壓
- [x] 自動安裝
- [x] 一堆人要的自動登錄

## 正在咕咕
- [ ] 自動重啓
- [ ] 圖形界面

## 不會實現
- [ ] 自動更新
