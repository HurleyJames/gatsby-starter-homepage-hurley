---
title: Train Schedule
tags: [ Android ]
date: 2018-08-13T06:25:44.226Z
path: project/train-schedule
slug: train-schedule
cover: ./train-schedule.png
excerpt: 火车时刻表是一款可以根据车站和车次来查询火车运行时刻表的安卓应用。
---

## Introduction

1. 受到高铁管家的正晚点功能和列车时刻表启发，自己编写的Android应用，感谢高铁管家和列车时刻表原作者。  
2. 采用Gson+OkHttp+Glide+ButterKnife等开源框架搭建，感谢上述开源项目。  
3. ~~默认首页的高铁线路图来自[铁路迷Railwayfan](https://weibo.com/u/2535241775)微博免费提供，之后版本新增加的地区高铁高清线路图也可能会来自其微博，感谢该作者免费提供。~~ 
4. 目前功能支持通过输入具体车次或者输入出发车站和到达车站来查询具体车次信息和两站之间的所有车次。  
5. 未来功能：目前想法是增加各个局部地区的高铁高清线路图，以及增加一个添加收集火车票的功能。因为我个人是个火车迷，也收集了我每次乘车的火车票，我希望做一个通过录入信息或者扫描的方式收集火车票的功能，希望广大火车迷或者收藏迷能够喜欢。  

## Technology
* 使用MVP模式
* 使用OkHttp + Gson + ButterKnife等框架开发

## Screenshot

<img src="https://raw.githubusercontent.com/HurleyJames/ImageHosting/master/IMG_3560.JPG" width="100%" />

## Source Code

Available at: https://github.com/HurleyJames/TrainSchedule.