---
layout: page
permalink: /
---

- [课程介绍](#intro)
- [适用人群](#people)
- [预备知识](#prepare)
- [学习目标](#goals)
- [课程大纲](#syllabus)
- [培训安排](#contact)

<a name='intro'></a>

## 课程介绍

[本课程](https://github.com/TonyRobotics/TonyRobotics.github.io/blob/master/Readme.md)旨在帮助您学习机器人操作系统（ [Robot Operating System](http://wiki.ros.org/)，以下简称ROS）。本课程可以帮助学员排除使用开发ROS导航功能包的算法外的困难，理清建图定位导航的原理与关系，掌握移动机器人发展趋势及关键技术，以及学会如何解决移动机器人开发相关问题。

课程注重知识点的连贯性，从ROS安装开始，深入讲解了ROS C++客户端，tf，仿真，传感器，以及自主导航，建图。

课程注重实战操作，通过在移动机器人开发学习平台 [Abel05](abel05/)上的一系列的开发工作，使学生能够学习和实践移动机器人相关的内容，包含网络环境搭建、里程计构建、 SLAM、建图、定位、导航、避障等。

课程注重机器人的理论知识的讲解，穿插了多个实例及相关机器人学知识，手把手教您玩转二轮差速小车底盘，并最终通过本课程的学习。学习完本课程后，您可以系统全面的讲解了机器人操作系统相关知识，并可以上手开发小车底盘、机械臂等机器人。

<a name='goals'></a>

## 课程目标

- 系统性全面性讲解ROS基础知识
- 熟悉Ｌinux操作系统下代码的编写、编译和运行
- 掌握C/C++编程技能
- 从零开始学习机器人开发的流程
- 了解传感器、二轮差速小车的控制
- 了解小车里程计建模
- 掌握基本机电概念，应用于机器人平台开发
- 了解ARM微控制器的用途，使用树莓派平台
- 了解传感器(如激光雷达、编码器、摄像头)和步进电机
- 探索和应用网络和不同通信架构的概念机器人技术
- 探索并应用机器人技术中的人工智能概念
- 巩固在整个移动机器人设计模块中所学的概念
- 梳理建图定位导航的原理与关系
- 掌握移动机器人发展趋势及关键技术
- 学会如何解决移动机器人开发相关问题

<a name='people'></a>

## 适用人群

* 电子、软件专业大学生
* RoboCup 实体参赛选手
* SLAM 导航学习人员
* 机器人爱好者
* 机器人行业从业者
* 机器人和电子爱好者
* 电子专业、软件专业的学生
* 学习 ROS 基础的入门人员
* 树莓派爱好者
* 其他爱好者

<a name='prepare'></a>

## 课程须知

- 对ROS有一定的基础，在linux下跑过 http://wiki.ros.org/ROS/Tutorials 的初级教程
- 了解Linux操作系统的基本使用
- 有Ubuntu 或 linux基础、C++或Python编程基础
- 需要有一定的ROS机器人操作系统开发使用经验
- 所有的课程使用python和c++编写。如果你有编程的基本经验，但是使用的其他语言（C/javascript/shell等），你可能很快上手课程

为了取得更好的学习效果，在参加本次学习之前，建议您先自学一些基础知识。我们为您准备了[参考资料](reference/)。

<a name='syllabus'></a>

## 课程大纲

### Part1 机器人操作系统基础

在这一部分，您将了解到一个ROS应用是如何构建的，其文件组织结构和运行时结构。另外，您将了解ROS的通信机制，包含Master、Node、Topic、Service、Action等内容。学习完这一部分之后，您将能够构建简单的ROS应用。

1.1 ROS的前世今生

1.2 ROS文件层级概念

1.3 ROS计算图级概念

1.4 ROS 通信 - Topic

1.5 ROS 通信 - Service

1.6 ROS 通信 - Action

1.7 ROS Launch文件介绍

### Part2 移动机器人实战

在这一部分，您将学会从零开始驱动电机转动，搭建一个基于ROS的移动机器人底盘，最终实现底盘的遥控、建图、避障和自动导航。

2.1 ROS基础知识回顾

2.2 RoboWare Studio安装及使用

2.3 让底盘动起来！差速控制模型及串口驱动编写

2.4 将程序放到底盘上以及运动模型的标定

2.5 标定结果测试

2.6 激光传感器安装与显示

2.7 机器人SLAM-建图与导航

具体的课程安排，请点击： [课程安排](schedule/)

<a name='contact'></a>

## 往期培训

- [2019全国高校ROS智能机器人师资研修班](https://mp.weixin.qq.com/s?__biz=MzU4NzE2NzI3Mg==&mid=2247484205&idx=2&sn=2520df11df8e1eb25824b26795ef82d0&chksm=fdf1606aca86e97cbe3fbefb06dbf4e657ff410c4e693d2ece9efc4f22a242ae8d2caccc0749&mpshare=1&scene=1&srcid=0219XwK4iftSgIGRUxkZhxPK&pass_ticket=9LXrQGLaUIYttEGwjtDvEmN%2FLOpiKBh%2BIx68%2Ft5eTkLd4syhHL%2FQI4%2B4lEQCDvCG#rd)

## 课程硬件配置

本课程将用到以下的硬件设备：

- [Abel05](abel05/) 移动机器人开发学习平台、激光雷达 
- PC（自备，8GB内存以上，装有 Ubuntu16.04 系统、 ROS Kinetic、 RoboWare 机器人开发平台）

## 参与方式

1、时间：2019年3月18日-3月24日

2、地点：山东省济南市高新区奥盛大厦

3、收费标准

  xxx（元/人），自带电脑（按照要求提前安装学习开发环境），早鸟价：前10名每人优惠1000元（以缴费时间为准，先报先得），食宿自理

4、课堂和学习方式

* RoboSchool提供培训教材，集中培训，目标向导，完成特定任务；
* RoboSchool提供培训实物实战智能导航底盘和六轴机械臂；
* 小组式学习，相互促进与监督学习；
* 专业助教支持，紧跟培训步伐；
* 颁发ROS培训结业证书；

5、学习交流和报名方式

添加微信号：18653154153 

微信群

<img src="assets/img/wechat.jpg" width="200">


QQ群

<img src="assets/img/ros2019.jpg" width="200">
