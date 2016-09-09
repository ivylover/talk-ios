##  Test Case for Talk-iOS

> **所有流程均需要验证**  
>
- **客户端登陆用户于客户端操作**  
- **客户端登陆用户于其他平台操作**  
- **其他用户于其他平台操作**	

> **三种情况下的结果**  

### 关于特殊属性与权限

优先级自上至下递减  

- 团队noJoinable无成员相关操作
- general话题无法改名、踢出成员
- 仅团队管理员可以进行团队设置
- 仅团队管理员可以进行成员管理（角色、移除）
- 仅团队管理员或话题创建者可以进行话题设置

### 登陆
- teambition 账号登录
- 微信登录
- 普通注册流程
- 退出登录

### 团队

- 创建团队流程
- 二维码扫描加入团队
- 更改团队名称
- 更改团队颜色
- 设置团队别名
- 切换团队
- 退出团队

### 话题

- 创建话题
- 更改话题名称、目标、颜色
- 更改置顶属性
- 更改静音属性
- 更改私有话题属性
- 添加新成员
- 从团队添加成员
- 私有话题踢出成员
- 归档话题、删除话题
- 退出话题

### 成员
- 添加团队成员

		1. 邮件邀请
		2. 手机号邀请		
		3. 二维码邀请
		
- 更改成员角色
- 移除成员
- 已离开成员查看
- 查看已离开成员聊天记录

### 最近
- 隐藏最近聊天消息
- 显示网络连接状态


### 消息

- 发送消息
  1. 文本消息
  2. 图片消息
  3. 语音消息
- 修改文字消息
- 删除消息
- 最近消息置顶
- 支持图片、文件和文本分享到简聊
- 支持静音消息显示（包括当前团队和其他团队）
- 被邀请进其他团队通知
- 聚合消息显示、teambiton聚合消息跳转到Teambition客户端
- 消息转发（聊天界面入口、图片浏览器入口、收藏和消息整理入口）
- 支持失败消息重发，和删除操作

### 更多
- 个人收藏
   1. 长按消息添加收藏（图片浏览器收藏）
   2. 单个收藏左滑删除
   3. 批量删除收藏
   4. 搜索收藏
- 自动整理
   1. 各种整理查看
   2. 过滤整理
- 标签
   1. 长按消息添加标签
   2. 删除标签
   3. 进入标签入口，点击查看标签

- 团队设置
   1. 管理员修改团队颜色与名称
   2. 退出团队
- 个人设置
   1. 个人头像、姓名、电话、团队别名修改
   2. 账号绑定：邮件、手机、微信等 流程
   3. 通知设置：设置通知与振动
   4. 意见反馈与服务条款
   5. 退出登录
   
### 搜索
- 实时搜索本地话题与成员
- 记录搜索记录
- 点击搜索相关消息并可以跳转到消息上下文
   
### 语音通话
- 通话功能
   	1. 成员列表发起单人通话
	2. 聊天页面发起单人通话
	3. 首页发起群组通话
	4. 话题聊天页面发起群组通话
	5. 发起后取消当前通话
- 手机绑定提示
   	1. 提示用户绑定手机
	2. 对方未绑定手机提示