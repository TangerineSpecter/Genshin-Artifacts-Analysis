<div align="center">

<br/>
<br/>

  <h1 align="center">
    GenshinImpact Artifacts Analysis
  </h1>
  <h4 align="center">
    原 神 圣 遗 物 分 析，一款圣遗物扫描分析打分工具
  </h4>
</div>

<p align="center">
    <a href="#">
        <img src="https://img.shields.io/badge/StarRail Auto Tools-1.0.0-green.svg" alt="HuTaoWallet version">
    </a>        
    <a href="#">
        <img src="https://img.shields.io/badge/Python-3.11.6-green.svg" alt="Vue Version">
    </a>
</p>

<div align="center">
  <img  width="92%" style="border-radius:10px;margin-top:20px;margin-bottom:20px;box-shadow: 2px 0 6px gray;" src="Resource/docs/img.png" />
</div>
<br>

## 项目介绍
> 原神圣遗物分析工具。

本项目主要用于背包圣遗物扫描分析打分，方便日常背包圣遗物清理判断，目前还在开发阶段...

> 敲黑板
```
本项目主要根据个人使用习惯进行开发，目前仅开发个人使用，有兴趣的小伙伴也可以Fork去使用。
```

## 当前系统版本
```
1.0.0
```

## 相关技术

| 库名 | 版本号 |
| --  | -- |
| Python | 3.11.6 |
| opencv | 4.6.0.66 |
| pyside6 | 6.6.2 |
| pyautogui | 0.9.54 |
| keyboard | 0.13.5 |

## 帮助

1. 环境和库安装
~~~
# 创建conda环境
conda create --name genshin-impact python=3.11.6
# 库安装
conda install pyside6
conda install keyboard
python -m pip python-opencv==4.6.0.66
python -m pip install cnocr[ort-cpu]
python -m pip install pyautogui
~~~