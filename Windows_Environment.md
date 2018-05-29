# Windows Environment Setup

## Abstract

Below dev tools are needed installing with setting.

- Hidemaru Editor
- [Git for Windows](https://gitforwindows.org/)
- [Golang](https://golang.org/)
- [Visual Studio Code](https://www.microsoft.com/ja-jp/dev/products/code-vs.aspx)
- JDK later 8
- sbt
- Gradle
- Maven
- [IntelliJ IDEA](https://www.jetbrains.com/idea/download/#section=windows)
- Ruby by [RubyInstaller](https://rubyinstaller.org/)
- [Tera Term](https://ttssh2.osdn.jp/)
- [VirtualBox](http://www.oracle.com/technetwork/server-storage/virtualbox/downloads/index.html?ssSourceSiteId=otnjp)
- [Vagrant](https://www.vagrantup.com/)
- [Python3](https://www.python.org/downloads/windows/)
- [C Compiler](https://www.python.jp/install/windows/install_vstools2017.html) for Python.

- [Orchis](http://www.eonet.ne.jp/~gorota/)
- [WinSCP](https://ja.osdn.net/projects/winscp/)
- DF(Diff Tool)
- IDManager
- Process Explorer

Then, construct Virtual Machine for local.

- cent7_local

## Specific setting needed tools

### Git for Windows

```bash
$ git config --global user.name [GitHub UserId]
$ git config --global user.email [GitHub MailAddress]
$ git config --global user.signingkey [GitHub GPG Key]
$ git config --global gpg.program /usr/bin/gpg
```

### Golang

### Visual Studio Code

- Setup for Golang development.

### Ruby by RubyInstaller

- Install develop environment gems.

```bash
$ gem install rake
$ gem install bunlder
```

### VirtualBox

- Set `Default VirtualMachine Folder` to `C:\Develop\Environment\VirtualMachine`

