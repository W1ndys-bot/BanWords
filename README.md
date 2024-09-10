# BanWords

违禁词监控系统

## 命令

bw-on 开启违禁词监控

bw-off 关闭违禁词监控

bw-list 查看违禁词列表

bw-add+违禁词 添加违禁词

bw-rm+违禁词 删除违禁词

## 更新日志

### 2024-9-10

- fix: 修复添加违禁词和删除违禁词的错误逻辑

### 2024-9-7

- feat: 违禁词提示词增加艾特管理员

### 2024-8-24

- [重大更新]feat: 增加违禁词检测到视频消息后，撤回视频消息的逻辑，检测到违禁词之后，遍历消息列表，撤回违禁词消息前 10 条消息，被检测者的视频消息

### 2024-8-23

- fix: 去掉指令中的空格，修改查看违禁词改为私发
- fix: 修复由于 qq 号获取没转成字符串导致的判断错误

### 2024-8-18

- fix: 修复私聊汇报携带的 cq 码无法解析导致 cq 码部分没显示发 bug

### 2024-8-13

- feat: 违禁词检测到视频消息后，撤回视频消息的逻辑，检测到违禁词之后，遍历消息列表，撤回违禁词消息前 10 条消息，被检测者的视频消息

### 2024-8-12

- feat: 重构代码，精简命令
