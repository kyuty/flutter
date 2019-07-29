- git clone this repo

- set path in .bash_profile.

export PATH=/Users/wangdong/github/flutter/bin:${PATH}

- run "flutter doctor" in terminal.

see : install some plugin in AndroidStudio.

- install dart.

https://dart.dev/get-dart

- 用AndroidStudio打开根目录工程。随便打开一个.dart文件，提示设置dart语言环境.

项目跳转有问题，随意打开一个工程，如flutter/dev/integration_tests/simple_codegen，

该工程目录下有个叫`pubspec.yaml`，在terminal进入该目录，然后`flutter packages get`即可解决项目跳转问题

该命令会生成`.packages`文件和`pubspec.lock`文件

- 用AndroidStudio打开根目录工程，是没办法直接在AndroidStudio上run某个flutter程序的，需要打开单个flutter程序。

详见flutter/examples/flutter_gallery/README.md

这个readme里就有如何运行单个flutter程序，用命令行运行可以，用AndroidStudio打开也可以运行
