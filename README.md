Automatic privilege escalation on unix systems by exploiting misconfigured setuid/setgid binaries, capabilities and sudo permissions. Designed for CTFs but also applicable in real world pentests.
____________________________________________________________________________________________________________________________________________________________________________________________________
✅ Features

    Automatically exploit misconfigured sudo permissions.
    Automatically exploit misconfigured suid, sgid permissions.
    Automatically exploit misconfigured capabilities.
    Automatically convert arbitrary file read primitive into shell by stealing SSH keys.
    Automatically convert arbitrary file write primitive into shell by dropping SSH keys.
    Automatically convert arbitrary file write primitive into shell by writing to cron.
    Automatically convert arbitrary file write primitive into shell using LD_PRELOAD.
    -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
By design autoprivilage is a backwards compatible, stdlib only python script, meaning it should work on any variant of Unix if Python is installed.

    Python2.*
    Python3.*
    No 3rd party dependencies
    Any Unix Variant (Linux, MacOS,*Nix)
    Any architecture eg (X86/ARM64/X86-64)

🙏 Credits

    Payloads thanks to Roxox.
