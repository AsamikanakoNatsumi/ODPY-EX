# DoctoratePy-EX-Public

本项目旨在作为OpenDoctoratePy的分支，拓展与完善功能。短期目标为尽可能防止因404或未知错误被踹回登录界面，长期目标为实现类似SPT-AKI项目的单人游玩本地服务

公开版仓库不提供任何游戏数据或与客户端修改相关的内容

开发仅为个人兴趣，鄙人技术有限，随缘更新，如有问题请提issue，但不保证可以第一时间修复bug（学生党只有假期期间和课余时间才有空~~堆屎山~~写代码）

此项目无任何交流群，且禁止任何以盈利为目的的分发、二次开发等行为

## 拓展进度

| 目标功能 | 进度 | 完成情况 | 备注 |
|:---:|:---:|:---:|:---:|
| 公开招募 | 编写完成 | 基本完成 | 需要测试 |
| 定向寻访 | 编写完成 | 基本完成 | 需要测试 |
| 基建 | 编写完成 | 基本完成 | 需要测试 |
| 商店 | 编写完成 | 基本完成 | 需要测试 |
| 生息演算 | 正在研究 |  |  |
| 好友 | 正在研究 |  |  |

## EX_Config参数说明

### virtualtime

供开启旧卡池使用，值小于0时为返回实时时间

可能导致基建出现问题，确定后勿随意减小该值

### Gacha

isFree控制抽卡是否消耗资源，但抽卡时仍需拥有足够资源才能进行

saveCharacter控制是否保存抽取角色

## 更新日志

- 2024年 7 月 20日

    添加：卡池消耗资源与保存抽取信息开关，活动商店获取数据与购买相关代码的初始化

    修改：优化pay模块导入，mail模块添加注释

- 2024年 7 月 15 日

    添加：gacha寻访功能完善，全部卡池信息文件

    修改：virtualtime移至exConfig.json中保存

- 2024 年 5 月 25 日

    添加：virtualtime功能，social模块，building部分功能

    修改：全部time函数从virtualtime获取

- 2024 年 4 月 8 日

    修改：building基建副手功能完善

- 2024 年 4 月 7 日

    添加：building部分功能（别问为什么水，我自己看得也迷糊）

- 2024 年 3 月 22 日

    添加：pay充值功能，GiveItem函数

-  2024 年 3 月 4 日

    添加：助理更换保存功能
    
    修改：从config设置全角色语音语言

- 2024 年 3 月 2 日

    添加：背景修改保存功能

- 2024 年 2 月 28 日

    添加：shop家具商店购买功能

- 2024 年 2 月 26 日

    添加：shop皮肤商店购买、资质凭证商店购买、高级凭证商店购买、通用凭证功商店能

- 2024 年 2 月 25 日

    初始化：building相关内容

    初始化：shop相关内容

- 2024 年 2 月 23 日

    初始化仓库、上传源代码
    
    增加env与README

