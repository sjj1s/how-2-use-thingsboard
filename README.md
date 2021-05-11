### Thingsboard使用
基于**3.2**分支的使用文档，包含基础、高阶、二开和扩展

### 准备
- Jdk，11+（因3.2.2版本需要11），用于编译运行
- Maven，3.2.1+，不强制需要，某些IDE也自带
- IDE，推荐Idea，查看代码和运行
- Html5浏览器，推荐使用Chorme，用于页面操作
- 容器引擎，推荐使用Docker，用于初始化环境，比如PG数据库
- Mqtt客户端，推荐使用MqttBox，用于模拟时序数据

### 基础入门
#### 编译
- 编译 [入口](doc/编译.md)

#### 运行
- 运行 [入口](doc/运行.md)

#### 调试
- 后端调试 [入口](doc/后端调试.md)
- 前端调试 [入口](doc/前端调试.md)

#### 使用
-  权限体系 [入口](doc/权限体系.md)
-  设备
	-  普通设备  [入口](doc/普通设备.md)
	-  智能网关  [入口](doc/智能网关.md)
-  资产 [入口](doc/资产.md)
-  规则引擎 [入口](doc/规则引擎.md)
-  部件 [入口](doc/部件.md)
-  仪表盘 [入口](doc/仪表盘.md)
-  示例 [入口](doc/示例.md)

#### 部署
- 单片部署 [入口](doc/单片部署.md)
- 微服务部署 [入口](doc/微服务部署.md)

#### 最佳实践
- 高可用集群

### 高阶使用

#### 源码分析
- 工程结构
  -  整体分析
  - application分析
  - common分析
  - dao分析
  - docker分析
  - ~~k8s分析~~（官方已不再推荐使用此包类容，抽取到新的github工程 [thingsboard-ce-k8s](https://github.com/thingsboard/thingsboard-ce-k8s)）
  - msa分析
  - netty-mqtt分析
  - packaging分析
  - rest-client分析
  - rule-engine分析
  - tools分析
  - transport分析
  - ui-ngx分析
- Actor模型
- 规则引擎
- 数据接入 	
  - 设备 [单片]() [微服务]()	
  - 网关 [单片]() [微服务]()
- 反向控制

#### 二次开发
- 仪表盘组件扩展
- 规则节点扩展
- 白标
- 定时任务
- 组织机构树
- Influxdb支持


### 扩展阅读
- IOT网关


### TIPS

- 录屏：https://space.bilibili.com/696589672/channel/index
- 镜像：https://gitee.com/blackstar-baba/how-2-use-thingsboard







