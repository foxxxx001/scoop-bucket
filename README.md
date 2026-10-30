# sysenv Scoop Bucket

自建 Scoop bucket，托管 [sysenv](https://github.com/foxxxx001/sysenv)（系统 PATH/环境变量管理与 httpie 兼容 HTTP 客户端）的安装清单。

## 使用

```powershell
scoop bucket add sysenv https://github.com/foxxxx001/scoop-bucket
scoop install sysenv
```

## 应用清单

| 应用 | 版本 | 说明 |
|---|---|---|
| sysenv | 0.6.41 | `sys` 命令：系统 PATH 与环境变量管理、httpie 兼容 HTTP 客户端 |

清单带 `checkver` + `autoupdate`：发新版后运行 `scoop update sysenv` 自动刷新（或 `scoop checkver sysenv -u` 更新清单哈希）。