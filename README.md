# 挂机放置类小游戏

> 一个全随机的刷装备刷词条小游戏

# 游戏设计

  * 装备分为四个等级：破旧、普通、神话、史诗
  * 主角默认每秒回血2%
  * 默认暴击伤害150%  

# 更新内容

  ## 11-5 更新

  这次更新优先添加了下面这些比较重要的功能，以及修复了一些奇奇怪怪的bug，后续的更新将会着重于游戏内容。

  #### 功能调整

  * （功能）添加装备锁定功能


  ## 11-4 更新

  这次更新优先添加了下面这些比较重要的功能，以及修复了一些奇奇怪怪的bug，后续的更新将会着重于游戏内容。

  #### 功能调整

  * （功能）添加自动挑战功能（装备多于25件时自动停止）
  * （功能）手动中断副本挑战
  * （功能）五分钟自动保存游戏

  #### 优化

  * （优化）添加背包容量指示，高于25件装备会有提示
  * （优化）再次大幅加强暴击与暴击伤害，与此同时加强了一丢丢60级副本

  #### bub修复
  
  * （bug）修复了第一次进游戏不显示装备对比信息的bug
  * （bug）副本进程中切换至后台将不能回血（非副本状态仍然可以）
  * （bug）某些情况下金币并不是整数
  

# 版本更新计划



  ##  1.1

  * 1. lv10副本太弱（副本整体都有点偏低）
  * 2. 一级装备会出现0属性值（完成）
  * 3. 商店刷新物品等级不符合预期
  * 4. 售出装备不为整数（完成）
  * 5. 商店出售价格前期调低后期调高
  * 6. 加个格挡伤害词条
  * 7. 血量（削弱）（完成）

  ## 1.0

  * 1. 加一个随机商店
  * 2. 支持存档功能
  * 3. 装备强化与洗词条功能
  * 4. 移入装备详情时显示对比
  * 5. 削弱攻击力系数带来的影响 同时加强暴击
  * 6. 减少金币获取

  

# 本地运行
### 安装依赖
```sh
  npm install
```

### 启动项目
```sh
  npm run serve
```

### 打包项目
```sh
  npm run build
```