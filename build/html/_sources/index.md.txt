% OpenFOAM documentation master file, created by
% sphinx-quickstart on Tue Mar 29 13:16:51 2022.
% You can adapt this file completely to your liking, but it should at least
% contain the root `toctree` directive.
%```{eval-rst}
%.. raw:: html
   
%   <b><font size="50">OpenFOAM 22年06月培训大纲</a></font></b>

%=========================

%.. image:: output.png
%   :width: 1760
%```
```{warning}
大纲以及相关内容还在修改过程中
```

# 2206 基于OpenFOAM开源软件的CFD入门课

## 课程引言

> * 使用计算流体力学(CFD)理论，结合现代计算机硬件以及编程语言(C++，Fortran)，对普遍存在的流动、传热等自然现象进行数值模拟，已成显学。因此许多同学也想较好的掌握CFD理论，更好的服务科研生产工作。但是由于CFD理论难度较大，使用商业软件很难理解其中真谛，并且商业软件版权费用昂贵一般个人用户难以承受，直到OpenFOAM软件出现。OpenFOAM是上世纪英国帝国理工学院在Linux平台使用现代C++语言开发，并于新千年开源，时至今日已衍生出诸多版本。因此种种，使用者只有具备良好的理论功底，了解Linux操作系统，掌握基础C++语法，才有可能通过OpenFOAM解决实际问题。通过自学，学习曲线较为陡峭，时间成本较大，容易导致从入门到放弃。课程目的就是希望通过十周时间解决OpenFOAM入门难的问题</td>
 

## 课程想法
* 教学教学，一起努力。
* 水平一般，还请海涵。
* 战战兢兢，如履薄冰。
* 课程结束，年内开源。
* 同行监督，加油加油。

## 致谢
* 谢谢那些文献上的大神们(你们是天上的星星)，
* 谢谢我的老师、朋友和同学们(名字太多)，
* 谢谢我的妻子、儿子和女儿，
* 谢谢参与培训的你们，感谢你们的信任，我们一起努力走完这十周，无论结局如何，我选择希望！

## 课程起始时间
```{tip}
2022年6月20日
```
## 课程周期
```{tip}
十周
```
#### 课程安排
|日期|时间|备注|
|---|---|---|
|周一|`19:00-21:00`|授课|
|周三|`19:00-21:00`|授课|
|周五|`19:00-21:00`|授课|
|周日|`19:00-21:00`|**答疑**|

```{error}
1. 请海外同学注意，为北京时间。
2. 为了高效沟通，后续会建立交流群。
3. 老师水平有限，只能尽力解惑。
```


## 课程教学大纲
-----------------------

%进一步阅读清参考{doc}`usage`
%可以参考指令{ref}`安装`

%那应该也可以参考第一级目录{ref}`使用`
%```{toctree}
%:caption: 'Linux:'
%:maxdepth: 2

%usage
%notebooks/tutorial.ipynb
%notebooks/wangyang.md
%```
%```{toctree}
%:caption: 'OpenFOAM:'
%:maxdepth: 2

%usage
%```

## 第一部分 Linux

-----------------
### Linux操作系统安装
```markdown
Ubuntu 20.04 LTS
```
### Linux文件系统
```console
.
├── bin -> usr/bin
├── boot
├── cdrom
├── dev
├── etc
├── home
├── lib -> usr/lib
├── lib32 -> usr/lib32
├── lib64 -> usr/lib64
├── libx32 -> usr/libx32
├── lost+found
├── media
├── mnt
├── opt
├── proc
├── root
├── run
├── sbin -> usr/sbin
├── snap
├── srv
├── swapfile
├── sys
├── tmp
├── usr
└── var

24 directories, 1 file

```
### Linux命令行基本命令
```console
sudo
ls
copy
move
touch
mkdir
cat
less
more
tail
```
### Linux命令行高级命令
```console
$ find
$ grep
$ sed
$ awk
```
### shell脚本语言入门
```markdown
1. 顺序
2. 条件
3. 循环
4. 函数
```
----------------------
## 第二部分 基于OpenFOAM的CFD入门
-----------------------
### 1 引言

### 2 流体力学控制方程与三类边界条件

### 3 有限体积法求解, 扩散方程

### 4 有限体积法求解, 对流-扩散方程

### 5 有限体积法求解, 定常流动-SIMPLE算法

### 6 有限体积法求解, 瞬态流动-PISO算法
-------------------------------
## 



