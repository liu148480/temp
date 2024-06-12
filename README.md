markdown，文本修饰语言，用特殊符号修饰正文效果

##标题修饰符\#
# 标题修饰符 一个#一级标题
## 二级标题
### 三级标题

## 正文内容
用\<br\>标签换行
*一段测试文本*
**一段测试文本**
***一段测试文本***
~~一段测试文本~~

将`关键字`重点显示
## 分割线

-\-\-\表示分割线

## 引用效果\>表示
>一级引用
>>二级引用
>>>三级引用
>>>>四级语言
## 列表修饰符
### 无需列表\*
* 二次元
 * 咒术
  * 七海
* 游戏
 * MOBO
  * RPG
### 有序列表
1. 工科
 1. 计算机
 2. 机械
 3. 土木
2. 理科
 1. 数学
 2. 物理
### 混合列表
1. 测试1
 * 测试2
 2. 测试3


名字|技能|排行
 --|:--|:--|
 小红|卷|2
 小王|游泳|6

### 代码片段

```c
#include<stdio.h>
int mian()
{
printf("test");
return 0;
}
```
```cpp
#include<iostream>
```

## 超链接技术
[https://github.com/liu148480/temp](https://www.github.com "点击访问")

## 插入图片
![七海建人](C://Users//HP//Pictures//Saved Pictures//七海建人.jpg "悬停窗口")
# 手写笔记
## github三要素
### 仓库repository
1. 仓库是GitHub项目管理储存基本单位
2. 一个仓库中储存一个项目，一个用户可以有多个仓库，一般仓库分为public，private
### 提交
1. 在整个开发周期，有大量的对代码资源的选代和修改，都可以通过commit的方式进行记录便于程序员回溯代码，即是这些代码被蒯提交便于使用書观察整个工程的开发流程以及设计流程。
### 分支branch
1. 在仓库中可以包含多个分支，分支才是代码文件的第一存储单位，默认的仓库主分支为master/main。
 * 不仅可以管理代码存储，便于多人协助开发
## 仓库内容
1. code：资源存储，代码管理，二进制，项目管理脚本，许可证等
2. issues：使用时遇到的bug或 进行提交, 等待反馈
README,使用markdown语言编写，“工程自述文件, 开发进度, 版本更新, 使用介绍等等
  * LICENSE 许可证
GPL2.0,3.0.Apahce2.0，Mt，这些许可证，给使用者展大使用权限以及最少的限制
## git软件，分布式版本控制系统
1. 仓库管理软件，使用gi管理私人代码或企业代码
2. 仓库管理软件，使用git管理私人代码或企业代码
## 设备认证
1. 何让网站的账户与设备绑定, 后续完成代码的管理， 上传下载
 * git inin /创本地仓库
 * gi connig ….list /查看git的配置文件
 * git config -global user.email "邮箱"
 * git config -global user.name "用户名"
 * ssh-keygen -t rsa -Ç“注册邮箱” //创建本地密文
2. 为目标仓库起别名，定位目标仓库，后续上传
 * git remote add origin "ssh地址" 添加
 * git remote remove origin  删除
## 本地设备与云端仓库的交互逻辑
[图片](C:\Users\HP\Pictures\Saved Pictures\4.1.png "悬停窗口")
## 代码更新的依赖关系被破坏
1. 本地内容要比云端新，完成更新替换。但是如果直接修改云端内容，导致本地内容无法再提交。
 * 先拉取git pull云端内容，与本地内容合并或操作。
 * git pull --rebase origin master
 * git rebase--skip
 * git rebase --abort
 * git rebase --continue 都是忽略本地，保留云端
## 下载开源代码
git clone "https仓库地址"

## markdown语言
github可以编写readme，文本修饰语言
