# Search搜索导航

### 项目描述：

**简洁的浏览器主页，采用原生js编写，可选择不同的搜索引擎，展示网址收藏，查看天气，本地设置，无聊时玩玩小游戏以及小工具合集...**

**偏向练手，代码中可能会出现风格混乱、命名不规范、每次推送代码变动过多等问题，欢迎给我提意见优化代码**

**支持二次开发，如果你觉得不错的话请添加上项目地址**

### 在线地址：

https://search.virs.xyz

### 使用说明：

建议使用 **VS Code（Visual Studio Code）** 并安装 **Live Server** 插件，否则无法处理json文件

部署服务器无其他要求

### 近期计划：

1. 模块化js文件

### 版本控制：

- master：主分支/后续仅同步稳定版本代码

  当前版本：0.9.0

- dev：开发分支

  当前版本：1.0.0(重构代码中...)

**Tips：**

- 功能性 > 外观/样式 > 兼容性
- 第一步仅保证Chrome浏览器下的体验

### 预计添加的功能：

1. 多引擎搜索（默认必应）

2. 常用网址导航

3. 网站主题色

4. 天气

   调用第三方接口❎

5. 设置

   本地设置（导入，导出）

   - 配色❎

   - 背景❎

   - ......

6. 小游戏

   - 别踩白块❎
   - 贪吃蛇❎
   - 打砖块❎
   - 迷宫❎
   - 像素鸟❎
   - 2048❎
   - ......

7. 随机名言✅

8. 启动动画✅，细节动画❎

9. 更流畅的设计❎

10. 响应式布局❎

11. 侧边栏返回顶部按钮❎

12. 随机更换Logo❎

13. 多彩样式✅

14. 应用中心
    常用应用添加至侧边栏❎
    快速添加至侧边栏❎
    自定义添加至侧边栏❎

###  数据格式：

1. #### 搜索引擎相关数据：

   ┌engine（搜索引擎数据）

   ├─name（搜索引擎名称）

   ├─value（搜索引擎值，默认为英文名称）

   ├─href（搜索引擎链接）

   ├─icon（搜索引擎图标）

   └─select（选中状态，默认选中必应搜索）

2. #### 收藏网址相关数据：

   ┌website（收藏网址数据）

   ├─name（网址分类标题）

   ├─value（分类英文名）

   ├─icon（分类标题图标）

   ├─color（分类标题颜色）

   └─content（网址分类内容）

   ​	├─name（网站名称）
   
   ​	├─href（网站链接）
   
   ​	├─icon（网站图标）
   
   ​	└─color（网站字体颜色）

### 命名规则：

1. 功能名 + 具体名
2. id一般为驼峰命名
3. class一般为中间加 “ - ” 命名

### 后续计划：

2. 使用vue重写代码（有生之年系列）
3. 使用nodejs部署服务器（有生之年系列）
4. 账号登陆同步书签设置及其他信息功能（有生之年系列）

### 配色方案：

啥配色都能让我配丑系列

- **落日海滩**
  在以灰色作为主色调的画面中加入高纯度的色彩，这种配色方法非常常见，也很容易搭配出出人意料的效果，这个的搭配方法可以使设计主题突出，并其他吸引观者的效果。
  HEX：FFFFFF RGB：255,255,255
  HEX：F0F0F0 RGB：240,240,240
  HEX：E7E7E7 RGB：231,231,231
  HEX：FFC549 RGB：255,197,73
  HEX：FF59AC RGB：255,89,172
- **办公室故事**
  十分素雅的配色，带有一定的日式风格的颜色搭配，当然现在在很多地方都有使用，如商业场合，家庭家居，即使在网页设计中也屡见不鲜，同时也多见于男性服装的色彩搭配上。
  HEX：7C7C7E RGB：124,124,126
  HEX：E9E9E9 RGB：233,233,233
  HEX：90AFC3 RGB：144,175,195
  HEX：303052 RGB：48,48,82
  HEX：A4A7D2 RGB：164,167,210
- **风的色彩**
  风是什么颜色？只有最无聊的人会去考虑这个问题，的确——我很无聊，但是这个色彩带给我们的感觉和微风拂面时候带来的感觉是相似的，同样清凉，舒适，如果你能享受这样简单的愉悦，就能体会这个色彩搭配带来的乐趣。HEX：88C6E5 RGB：136,198,229
  HEX：A6D3E8 RGB：166,211,232
  HEX：C3DFEA RGB：195,223,235
  HEX：E1ECED RGB：225,236,237
  HEX：FEF9EF RGB：254,249,239