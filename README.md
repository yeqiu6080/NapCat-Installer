# NapCat-Installer
还原了cli的安装脚本

## 使用
### Linux(支持Ubuntu 20+/Debian 10+, Centos系仅支持9)
在需要的文件夹 执行此代码 稍等片刻即可运行 任选一个 其余为镜像

```bash
curl -o napcat.sh https://github.moeyy.xyz/https://raw.githubusercontent.com/yeqiu6080/NapCat-Installer/refs/heads/main/script/install.sh && sudo bash napcat.sh
```

```bash
curl -o napcat.sh https://jiashu.1win.eu.org/https://raw.githubusercontent.com/yeqiu6080/NapCat-Installer/refs/heads/main/script/install.sh && sudo bash napcat.sh
```

```bash
curl -o napcat.sh https://jiashu.1win.eu.org/https://raw.githubusercontent.com/yeqiu6080/NapCat-Installer/refs/heads/main/script/install.sh && sudo bash napcat.sh
```

国外服务器可使用以下命令
```bash
curl -o napcat.sh https://raw.githubusercontent.com/yeqiu6080/NapCat-Installer/refs/heads/main/script/install.sh && sudo bash napcat.sh
```
注意：如果无法下载NapCat.Shell.zip以及QQ安装包请尝试手动下载并将QQ安装包重命名为QQ.deb或者QQ.rpm, NapCat.Shell.zip无需更改名字。
两者的下载链接脚本会给出，当然你也可以先下载再执行脚本。
<details>
  <summary>命令选项(高级用法)</summary>

  0. --tui: 使用tui可视化交互安装

  1. --docker [y/n]: --docker y 为使用docker安装反之为shell安装

  2. --qq \"123456789\": 传入docker安装时的QQ号

  3. --mode [ws|reverse_ws|reverse_http]: 传入docker安装时的运行模式

  4. --confirm: 传入docker安装时的是否确认执行安装

  5. --proxy [0|1|2|3|4|5|6]: 传入代理, 0为不使用代理, 1为使用内置的第一个,不支持自定义, docker安装可选0-7, shell安装可选0-5

  6. --cli [y/n]: shell安装时是否安装cli

  7. --force: 传入则执行shell强制重装
  
</details>
