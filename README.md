<!-- SPDX-FileCopyrightText: 2026 Progmasoft <support@progmasoft.com> -->
<!-- SPDX-License-Identifier: MIT -->

# TalaFS

TalaFS, the Tala File System, is the file system of TalaOS: a traditional file system with full journaling. This
repository also holds the layout of a TalaOS installation:

```text
/
├── bin -> usr/bin/           Essential user commands
├── boot/                     Bootloader, kernel, boot configuration
├── dev/                      Device files
├── etc/                      Base system configuration
├── home -> usr/home/         User home directories
├── lib -> usr/lib/           Essential system libraries
├── libexec -> usr/libexec/   Essential system utilities
├── media/                    Removable media mount points
├── mnt/                      Temporary mount point
├── proc/                     Process filesystem (optional mount)
├── rescue/                   Emergency recovery utilities
├── root/                     Root user's home directory
├── sbin -> usr/sbin/         Essential administrative utilities
├── tmp/                      Temporary files
├── usr/
│   ├── bin/                  Base system user commands
│   ├── home/                 User home directories
│   ├── include/              C header files
│   ├── lib/                  System libraries
│   ├── libexec/              System helper programs
│   ├── local/                Third-party applications
│   │   ├── bin/              Installed user commands
│   │   ├── etc/              Installed application configurations
│   │   ├── lib/              Installed libraries
│   │   ├── sbin/             Installed administrative commands
│   │   └── share/            Application resources
│   ├── obj/                  Build output
│   ├── sbin/                 System administrative commands
│   └── share/                Architecture-independent system data
└── var/
    ├── cache/                Cached data
    ├── db/                   System and application databases
    ├── log/                  System logs
    ├── run/                  Runtime state
    ├── spool/                Queued jobs
    └── tmp/                  Persistent temporary files
```

It is written in GNU99 under the
[Progmasoft Core C Coding Guidelines](https://github.com/Progmasoft/progmasoft-cpp) and built with BSD Make.

No code is written yet.

## License

[MIT](LICENSE.txt), also covered by the [Progmasoft Patent Grant 1.1](PATENTS.md). Participation follows the
[Code of Conduct](CODE_OF_CONDUCT.md).
