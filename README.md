# 挚科天枢

挚科天枢是面向 Windows 的智能体桌面工作台，可连接已配置的模型进行对话、执行计划任务、组织团队协作并预览生成的文件。本仓库只用于分发正式安装包和应用内更新，不托管产品源码。

## 当前正式版：1.0.1 · Windows x64

**[下载安装包（ZIP，保留中文文件名）](https://github.com/h1343195614-cpu/zhike-tianshu-releases/releases/download/v1.0.1/ZhikeTianshu-1.0.1-Windows-x64.zip)**　·　[直接下载 EXE](https://github.com/h1343195614-cpu/zhike-tianshu-releases/releases/download/v1.0.1/ZhikeTianshu-1.0.1-setup.exe)　·　[查看版本说明](https://github.com/h1343195614-cpu/zhike-tianshu-releases/releases/tag/v1.0.1)

1. 下载并解压 ZIP，双击 **挚科天枢-1.0.1.exe**。直接下载的 EXE 使用英文文件名，内容完全相同。
2. 按安装向导选择目录及快捷方式。已在使用的用户请先保存工作，并从系统托盘退出旧程序后再安装。
3. 安装后可从「设置 → 软件更新」检查后续正式版；无需 GitHub 账户。1.0.1 测试版用户请手动安装本正式版一次。

## 校验下载

正式版安装程序大小 **506,456,860 字节**。此版未使用 Windows 代码签名。要核对安装文件，请在解压后的目录打开 PowerShell：

~~~powershell
Get-FileHash -Algorithm SHA256 -LiteralPath '.\挚科天枢-1.0.1.exe'
~~~

应得的 SHA-256：`DFA2556FB11B2332C68F3436DF4C6AB68436B9602CA6B99B9D21FF375C7BBE5D`。[全部下载文件校验值](https://github.com/h1343195614-cpu/zhike-tianshu-releases/releases/download/v1.0.1/SHA256SUMS.txt) 也可用于核对 ZIP。

后续版本请以 **[最新正式发行](https://github.com/h1343195614-cpu/zhike-tianshu-releases/releases/latest)** 为准。`latest.yml` 和 `.blockmap` 供客户端自动更新使用，无需手动下载。
