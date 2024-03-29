Automatic privilege escalation on unix systems by exploiting misconfigured setuid/setgid binaries, capabilities and sudo permissions. Designed for CTFs but also applicable in real world pentests.
____________________________________________________________________________________________________________________________________________________________________________________________________
✅ Features

通过利用错误配置的 setuid/setgid 二进制文件、功能和 sudo 权限，在 unix 系统上自动提升权限。专为 CTF 设计，但也适用于现实世界的渗透测试。✅ 功能 自动利用配置错误的 sudo 权限。自动利用配置错误的 suid、sgid 权限。自动利用配置错误的功能。通过窃取 SSH 密钥自动将任意文件读取原语转换为 shell。通过删除 SSH 密钥自动将任意文件写入原语转换为 shell。通过写入 cron 自动将任意文件写入原语转换为 shell。使用 LD_PRELOAD 自动将任意文件写入原语转换为 shell。根据设计，autoprivilage 是一个向后兼容的、仅限 stdlib 的 python 脚本，这意味着如果安装了 Python，它应该可以在任何 Unix 变体上运行。
    -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
By design autoprivilage is a backwards compatible, stdlib only python script, meaning it should work on any variant of Unix if Python is installed.

    Python2.*
    Python3.*
    No 3rd party dependencies
    Any Unix Variant (Linux, MacOS,*Nix)
    Any architecture eg (X86/ARM64/X86-64)

🙏 Credits

    Payloads thanks to Roxox.
