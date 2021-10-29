# 对于一些指令的说明

- 下载项目 `git clone ssh://root@61.130.53.150:3001/NewCenturyRobotics/HZII_ChangeUp.git`
- 项目初始化
  1. 清除已编译文件 `make clean`
  2. 解决莫名其妙的报错。构建 compile_commands.json 文件 `prosv5 build-compile-commands`
- 常用命令
  1. 全部重新编译 `make all -j`
  2. 清除已编译文件 `make clean`
  3. 上传编译好的程序到机器人 `prosv5 mut`
  4. 上传编译好的程序到机器人其他程序槽 `prosv5 mut --slot 2`
  5. 新建一个 pros 项目 `prosv5 c n ./xxxx`
  6. 更新 prosv5 cli `prosv5 upgrade`
  7. 更新 prosv5 项目 `prosv5 c u`
- 如果按 vscode 的`更新`或者` 上传`按钮无效就使用命令行上传下载 如果报错就多试几次.
  1. 下载 `git pull origin master`
  2. 上传 `git push origin master`
