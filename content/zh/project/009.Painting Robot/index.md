---
title: 喷涂机器人
summary: 用于室内装修的喷涂机器人
date: 2023-09-01
type: docs
math: true
tags:
  - 喷涂机器人
  - 建筑场景
featured: featured.png
---

## 概述
本项目是我硕士论文的主题。

在建筑喷涂作业中，喷涂机器人相比人工劳动具有显著优势。然而，为了满足高精度要求，喷涂机器人必须准确感知大型物体。此外，喷涂过程的需求要求喷涂机器人在其墙面覆盖喷涂的路径规划中纳入新的程序约束。本研究主要需要解决以下两个问题：
1. 考虑机器人可达性约束的全覆盖喷涂轨迹规划。
2. 可跨系统、平台的易部署、验证的算法。与具体硬件结合的整体喷涂软件。

## 机器人模型
![SolidWorks模型](/media/projects/painting-robot/PaintingRobot_SW.png)

## 感知
最初，我们使用基于区域生长的方法进行感知，将墙面投影到2D平面上。这种方法有效地将问题从3D覆盖路径规划转变为2D覆盖路径规划。
然而，我们发现这种方法不足以处理涉及角落和曲面的任务。因此，我们现在正在探索基于切片的方法来解决这些挑战。

## 基于切片的喷涂点生成
基于切片的喷涂点生成方法通过使用一系列平行的平面对待喷涂区域进行切割，这种方法在工件喷涂中常常使用。然而在建筑喷涂中，机器人喷涂范围由已知的面片（Mesh）文件变成了感知得到的点云（Point Cloud）文件，因此需要需要对喷涂点的生成方式进行改进。
![喷涂点生成](/media/projects/painting-robot/painting_point_generation.png)

## 基于喷涂可达地图的轨迹优化
本文提出了一种紧凑可达图和喷涂可达图，并基于这两图将喷涂轨迹生成问题构造为一个优化问题。
### 紧凑可达地图
![紧凑可达图](/media/projects/painting-robot/compact_reach_map.png)
### 喷涂可达地图
![喷涂可达图](/media/projects/painting-robot/painting_reach_map.png)
### 优化
结合喷涂可达图的约束，可以将轨迹生成构造为一个凸优化问题进行求解
![仿真结果（含门窗情况）](/media/projects/painting-robot/simulation_result.png)

## 项目状态

此项目仍在进行中...

## 实验
![乳胶漆挂漆测试](/media/projects/painting-robot/single-spray.gif "乳胶漆挂漆测试")
![宽范围](/media/projects/painting-robot/wide-range.gif "宽范围")
<!--more-->
