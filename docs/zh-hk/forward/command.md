## 命令列表

與轉發相關的一共五個命令。

```cmd
forward:add       the 添加轉發任務 command
forward:alter     the 修改轉發任務 command
forward:delete    the 刪除轉發任務 command
forward:run       the 運行轉發任務 command
forward:view      the 查看轉發任務 command
```

## 查看命令幫助

我們只需在命令最後加上`--help`即可獲得相關命令的幫助信息，比如：

參考`評論`>`命令`>`查看命令幫助`。

## forward:add

> 該命令為添加轉發任務命令，支持七個參數：

```cmd
--weibo_id       必須，微博ID
--interval       可選，每轉發論間隔時間，單位：秒
--sleep          可選，每輪休息時間，單位：秒
--round          可選，輪數
--remark         可選，備註
```

## forward:view

> 該命令為查看轉發任務命令，沒有任何參數。

## forward:delete

> 該命令為刪除轉發任務命令，支持一個參數：

```cmd
--task_id       必須，任務ID
```

## forward:alter

> 該命令為修改轉發任務命令，支持八個參數：

```cmd
--task_id        必須，任務ID
--weibo_id       可選，微博ID
--interval       可選，每條轉發間隔時間，單位：秒
--sleep          可選，每輪休息時間，單位：秒
--round          可選，輪數
--remark         可選，備註
```

## forward:run

> 該命令為運行轉發任務命令，支持五個參數：

```cmd
--account_id     必須，賬號ID
--task_id        必須，任務ID
--interval       可選，每條轉發間隔時間，單位：秒
--sleep          可選，每輪休息時間，單位：秒
--round          可選，輪數
```

本節相對簡略，但是可以比照參考`評論`>`命令`。