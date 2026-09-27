CZ9-2026
A module of the Long March 9

[Development Status: Highly Unfinished / 开发状态：高度未完成]

This mod is currently in a highly unfinished state.
本模组目前处于高度未完成状态。

Design Philosophy & Scale / 设计理念与规模

Given the highly speculative nature (PPT status) of the Long March 9, I did not attempt to find a balance among contradictory sources. Instead, this mod is based on official information, references to the Starship system, and artistic creation. The rocket's scale has been strengthened compared to reality, and it does not pursue extreme realism.
鉴于长征九号目前高度的PPT状态，我并没有在大量相互矛盾的信源之间寻找平衡，而是基于已有的官方信息、星舰系统参考加上艺术创作制作。其火箭规模在现实基础上得到加强，并不追求极度考究。

For example:

The first stage does not use the officially proposed 33x YF-215 engines, but rather a more ambitious 38 engines.

A thrust multiplier has been added to all engines in the ThrustRate.cfg file, with a default setting of 1.4.

If you seek realism, you can revert it to 1. However, under current configurations, this will cause the fully loaded rocket's thrust-to-weight ratio to be less than 1, making it unable to take off. You will need to reduce the fuel load manually. A realistic version of the CZ-9 may be optimized and released in the future.

例如：

一级不使用官方提供的33台YF-215方案，而是更大胆地使用了38台。

在 ThrustRate.cfg 文件中给所有发动机都添加了推力倍增系数，默认设定为 1.4。

如果追求现实性可以改回1，但是在目前情况下会导致满载火箭推重比小于1，无法起飞，需要自行减少燃料装载量。后续可能跟进优化现实版本的CZ-9。

Environment Compatibility / 环境适配

Most functions are primarily designed for RSSRO and FAR environments. In non-RSSRO/FAR environments, it only has limited compatibility with pure vanilla, and further testing is still needed.
目前大部分功能主要针对RSSRO系统和FAR环境，在非上述环境中仅仅在纯原版环境有一定的适配，但还需充分试验。

Features & Current State / 功能与现状

kOS Support: Included in the Ships folder are experimental kOS configurations based on Chris's program. These can utilize MechJeb (MJ) to complete the full process from launch, hot-staging, to downrange landing. However, the landing accuracy is not high and requires a recovery zone with a diameter of several dozen kilometers.

运力 (Payload Capacity): Currently features a three-stage version of the CZ-9 (Stage 1 recoverable, Stages 2 and 3 expendable).

Expendable maximum capacity: TLI ≤ 160t.

Downrange recovery maximum capacity: TLI ≤ 144t.

kOS支持：在 Ships 文件里包含了试验性的KOS的配置，基于Chris的程序创建，能利用MJ完成发射、热分离到航迹下回收的全流程，但是回收精度不高，需要几十公里直径的回收场用以承载火箭。

运力：现在已有的是三级版本CZ-9，一级可回收，二三级全消耗。

全消耗极限运力，TLI不大于160t。

航迹下回收极限运力，TLI不大于144t。

Roadmap / 路线图

Work in Progress (WIP) / 正在进行的工作:

Two-stage version (including fully expendable second stage and fully recoverable second stage. The fully recoverable version has some innovative work in principles and appearance, but it is uncertain if it will enter the final version).

Launch pad and recovery system.

Future Work / 未来的工作:

Complete the second-stage recovery automatic guidance program.

Optimize the automatic guidance program (including Return-to-Launch-Site (RTLS) and downrange landing).

Complete environment adaptations.

Complete the realistic version of CZ-9.

If possible, also plan to create other earlier versions of CZ-9 and aggressive future variants.

正在进行的工作：

制作两级版本（含二级全消耗和二级全回收版本，其中二级全回收版本就其原理和外形做了一些创新性的工作，但不确定会不会进入到最终版本中）。

制作发射塔和回收系统。

未来的工作：

完成二级回收自动制导程序。

优化自动制导程序（含返场回收和航迹下回收）。

完成各环境适配。

完成现实版本的CZ-9。

如有可能，还计划制作其他更早期版本的CZ-9和目前版本在未来激进变体。

============

DEPENDENCIES / 前置依赖

============

Required / 必需：

ModuleManager (v4.2.3)

Resurfaced

B9PartSwitch

DeployableEngines

Waterfall

Choose ONE of the following setups / 以下组合二选一：

Option A (Stock-alike / 原版平衡):

CommunityResourcePack (1.4.2)

CryoTanks

CryoEngines

OR / 或者
Option B (Realism / 真实向):

RealismOverhaul

============

INSTALLATION / 安装方法

============

To install, place the GameData & Ship folder inside your Kerbal Space Program folder. If asked to overwrite files, do so.
解压后，将 GameData & Ship 文件夹放入您的 KSP 游戏根目录。如果提示覆盖文件，请选择覆盖。

============

LOCALIZATION / 本地化

============

English

Simplified Chinese / 简体中文
