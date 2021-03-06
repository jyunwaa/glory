## 獲取點贊微博信息

### 登錄一個賬號

隨便登陸一個賬號，登錄方法參考`安裝腳本`>`獲取 Cookie`>`登錄新浪`步驟。

登錄賬號`GEM迷183007`（這裡登陸的不一定是主號，我們只需要查看微博信息，不做任何操作），如圖：

![](https://p.pstatp.com/origin/1388700000f244e523e9a)

### 找到需要點贊的微博

我們這裡找一條比較古老的微博，注意點贊數量，如圖：

![](https://p.pstatp.com/origin/ff53000175b3378144a0)

然後點擊`評論`，進入評論界面，如圖：

![](https://p.pstatp.com/origin/ffd9000278c29dabfda7)

我們把重心放到地址欄上，畫紅線的部分就是該條微博的ID。

### 保存微博信息

我們再`Glory`目錄下打開命令行窗口，輸入以下命令（替換為自己的具體內容）：

```cmd
glory like:add --weibo_id=Bx987cXus
```

按下回車，結果如圖：

![](https://p.pstatp.com/origin/137880000bd248ef95e25)

上圖我們還執行了點贊任務查看命令：

```cmd
glory like:view
```

我們主要關注`TaskID`，即點贊任務ID，在執行運行命令時需要通過它指定點贊任務。









