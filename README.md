﻿# EscapeRoom  
## Developed with Unreal Engine 4   


---

虚幻引擎初学者学习项目

---

# 项目开发说明

### 游戏标题

Project.EscapeRoom(待定)

### 游戏类型

密室逃脱类恐怖游戏

### 游戏平台

Windows平台

### 游戏目标用户

恐怖游戏爱好者
追求躲避怪物探索刺激感的用户

### 关键字

恐怖游戏
探索 密室逃脱

### 参考游戏

恐怖老奶奶

## 游戏背景设定

你被关在一个怪物的密室中,你需要小心的探索密室躲避怪物,利用场景中的道具找到钥匙,打开密室的房间门逃离密室。（暂定）

## 游戏核心机制

### AI

AI有视觉和听觉感知功能,会在场景中巡逻寻找玩家，场景中的物体被玩家撞倒后会发出噪声,AI能够感知到噪音前往噪音发出的地点。AI看到玩家后会追踪玩家,当玩家进入AI攻击范围后会播放攻击动画,命中玩家后玩家会死亡.

### 探索

场景中有一些可以被利用的道具,玩家需要依靠这些道具来通过关卡.（道具内容等待关卡设计完成后编辑）

### 胜负条件

胜利:玩家成功避开所有危险找到钥匙，打开密室大门逃脱.

失败:玩家被AI击杀或落入关卡陷阱（关卡陷阱待设计）

> 最后编辑日期:2024年1月18日 0:03
