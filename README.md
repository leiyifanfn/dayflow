# DayFlow 安装包与项目结构

此仓库仅公开软件安装包、使用说明和不包含实现代码的空结构。

## 下载

前往 [Release 发布页](https://github.com/leiyifanfn/dayflow/releases) 下载：

- Windows PC：DayFlow Setup 1.1.1.exe
- 项目空结构：dayflow-project-structure-v1.1.1.zip
- 文件校验：SHA256SUMS.txt

Android 安装包以后补充，本次只发布 PC 端。

## 使用

运行 Windows 安装包，按向导安装。当前发行版可直接使用游客模式，在本地管理清单、周计划、日记、画板和复盘。

云端账户及同步需要由软件维护者配置 Supabase 后端后重新构建；此发行版不包含原项目的云端配置或账号凭据。

project-structure 中的所有文件均为空，占位展示工程结构，不能用于构建软件。源码保存在维护者的私有仓库中。

## 官方更新

软件由维护者发布迭代。下载者不能直接修改此官方仓库；安装包本身仍可能被反编译或在本地修改。

## 校验

下载 SHA256SUMS.txt，用文件的 SHA256 值核对安装包和结构 ZIP 是否与官方发布一致。
