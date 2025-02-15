# 呆啵宠物 - 原神版
[![License](https://img.shields.io/github/license/ChaozhongLiu/DyberPet.svg)](LICENSE)
![DyberPet Version](https://img.shields.io/badge/DyberPet-v0.2.2-green.svg)  
呆啵宠物 (DyberPet) 原神版是基于[呆啵宠物](https://github.com/ChaozhongLiu/DyberPet)框架创造的原神桌宠，美术部分由[@栎曦_Nuo](https://space.bilibili.com/14004864)完成。  

🆕 **重构UI版本**已经在 [DyberPet 主页](https://github.com/ChaozhongLiu/DyberPet)上线！新版本包括备份存档、添加角色、更友好的UI，欢迎试用并提供反馈！
  
如果你喜欢这个桌宠小程序，请点击右上角的:star:**Star**，这对我们继续开发下去有很大的激励！  
同时，更多的角色、物品、功能将陆续加入，请关注[@栎曦_Nuo](https://space.bilibili.com/14004864) 和本仓库以获得最新的更新。  

如果在使用过程中遇到任何问题，可以私信我[@哦哟喔嚯](https://space.bilibili.com/39307302)或者在[Issues页面](https://github.com/ChaozhongLiu/DyberPet_GenshinImpact/issues)提出。
  
正在进行一轮新的UI重构，同时在增加便捷的操作功能，过于繁忙可能更新缓慢，见谅！
 
  
For **English and more language** version of the App, please see our [Alpha version of DyberPet](https://github.com/ChaozhongLiu/DyberPet/releases/tag/v0.3.0a).  
Please :star:**Star** to get the update later!



## 快速体验
### Windows 用户
  **初次使用**：将仓库[下载](https://github.com/ChaozhongLiu/DyberPet_GenshinImpact/archive/refs/heads/main.zip)至本地，解压后双击 **``呆啵宠物-原神.exe``** 即可  
  （.exe程序不能离开文件夹，但可以创建桌面快捷方式）
  
  
  **版本更新**：如果你已经在使用呆啵桌宠，将[下载](https://github.com/ChaozhongLiu/DyberPet_GenshinImpact/archive/refs/heads/main.zip)的最新文件覆盖已有的旧版  
  (全部覆盖，``data``文件夹会保留，数据不会丢失)
  
  **百度网盘**：[链接](https://pan.baidu.com/s/1dLY0ZfFcTRySuU4tXv1-pA?pwd=bs1d) | 提取码：bs1d  
  **夸克网盘**：[链接](https://pan.quark.cn/s/a070df462217) | 提取码：7RD4

### Linux / MacOS 用户
  
  **Mac测试版**
  **夸克网盘**：[链接](https://pan.quark.cn/s/6386f4b5efc9) | 提取码：D3VR  
  欢迎加群反馈bug和疑问，获得最新更新！``233305772``  
  **Q: 程序已损坏，打不开**:   
  **A:** 这是第三方应用程序权限的问题，并不是真的损坏了。解决办法请参考：https://macoshome.com/course/1699.html
  
  也可以通过[这个评论](https://www.bilibili.com/read/cv21890026)的方法实现 (感谢b站用户 [@洛天依_Linux](https://space.bilibili.com/495653264))
  

## 用户手册
请参考这个[简易用户手册](用户手册.pdf)，或者观看[B站视频](https://www.bilibili.com/video/BV1fd4y1W7ht)，体验现有功能。


## 更新日志

<details>
  <summary>版本更新列表</summary>
  
**  **
  
**v0.2.2 - 03/05/2023**
- 常驻动作数据结构修改，bug修复
- 同伴添加了常驻动作判定，需要在是主宠物时进行设定
  
**v0.2.2 - 03/05/2023**
- 新增角色：魈
- 添加了跟随鼠标的功能
- 右键菜单中增加了常驻动作选项，可以改变闲置时的默认动作，选中后将不在随机播放其他动作
- 背包分成了食物和收藏品两栏
  
**v0.2.1 - 02/23/2023**
- 优化了缩放机制
- 物品数量为1时不显示数字
- 优化了主宠物列表判断和默认宠物的保存方式
  
**v0.2.0 - 02/22/2023**
- 加入了好感度等级奖励补偿
- 流浪者和纳西妲分别增加了4组对话，将在好感度2、3、4、5级获得
  
**v0.2.0 - 02/19/2023**
- 缩小了纳西妲的体型
- 修复了切换角色时陪伴时间打开关闭的bug
  
**v0.2.0 - 02/18/2023**
- 新增角色 - 流浪者
- 好感度等级上限调整为8 （卷起来 doge）
- 设置中添加了启动默认角色的选择
  
**v0.1.19 - 02/16/2023**
- 设置中可以静音了
- 添加了统计陪伴天数及显示铭牌的功能
- 对话框自动添加上一步按钮（暂未实装素材）
- 调整了对特殊中文字符的长度计算
  
**v0.1.18 - 02/11/2023**
- 增加了附属宠物和主宠物的连接
- 保证收藏品在随机掉落中不重复出现
- 整理了可变更的系统数值
  
**v0.1.18 - 02/11/2023**
- 修复了使用右键菜单收回派蒙时，背包按钮显示的错误
  
**v0.1.18 - 02/10/2023**
- 添加了对话界面和功能（暂未实装素材）
- 物品增加属性：``pet_limit`` 将物品设定为只在某个宠物内出现的物品（为即将到来的多个角色做准备）
  
**v0.1.17 - 02/06/2023**
- 收藏品背包格置顶，背景色为淡蓝色
- 收藏品的使用可以在背包中收回 （如派蒙因bug走丢，可以在背包界面收回）
  
**v0.1.17 - 02/05/2023**
- 给通知系统语音添加了优先级``sound_priority``属性
- 增加了点击时的随机语音事件
- 增加了纳西妲的语音库
  
**v0.1.16 - 02/02/2023**
- 修复了同伴动作的锚点问题
- 全面支持多屏（测试中）
  
**v0.1.15 - 02/01/2023**
- 修复了派蒙在屏幕倍率放大时的大小变化
- 修复了附件的拖拽闪现
- 修复了召唤同伴放大时显示不全的问题
- 修复了一定条件下缩放宠物派蒙位置问题
  
**v0.1.15 - 01/31/2023**
- 规避了专注时间0分0秒相关的闪退bug
- 解决了不能言说的狂爆物品惊天大bug
- 停止按钮按下后会立刻失效，避免多次结算
- 修复了快速点击鼠标微小位移造成闪现的bug
  
**v0.1.15 - 01/30/2023**
- 数值栏字体固定为Times
- 设置内添加是否置顶的选项
- 饱食度下降单位时间变为4分钟
- 增加了好感度3级4级的升级奖励
- 为了简化更新过程，``data``文件夹删除了，首次运行会自动生成。
  
**v0.1.14 - 01/29/2023**
- 重力加速度最小值变为0.01
- 取消屏幕缩放对宠物大小的影响，用户可以在设置中自行调节
  
**v0.1.14 - 01/28/2023**
- 修复了缩放改变时边界判断的bug
- 改进了启动语音的选择逻辑
  
**v0.1.14 - 01/27/2023**
- 经过四个月的开发，呆啵宠物-原神版正式上线！


</details>

## 加入我们  

如果你也想开发一套新的宠物形象、动作、物品，可以参考目前还未完工的[素材开发文档](https://github.com/ChaozhongLiu/DyberPet/blob/main/docs/art_dev.md)，也欢迎B站私信我[@哦哟喔嚯](https://space.bilibili.com/39307302)和[@栎曦_Nuo](https://space.bilibili.com/14004864)，加入我们一起搞事！

如果你想一同开发呆啵宠物框架，欢迎B站私信我[@哦哟喔嚯](https://space.bilibili.com/39307302)，一起勇闯屎山！

## 版权声明
- 宠物素材版权归米哈游所属，请勿商用！
- 宠物素材的拆分和动作设计来自 B站[@栎曦_Nuo](https://space.bilibili.com/14004864)。转载、使用时请注明出处
- 呆啵宠物遵循 GPL v3.0 协议，开发、使用时，请注明作者 GitHub@ChaozhongLiu


