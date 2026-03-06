#### 环境变量
 保存生效  source ~/.zshrc
 打开环境变量  nano ~/.zshrc
#### mac地址
修改：sudo ifconfig en5（端口） ether b0:25:aa:6e:7f:6c（mac地址）
访问git：sudo ifconfig en7 ether b0:25:aa:6e:7f:6c

Hardware Port: Wi-Fi
Device: en0
Ethernet Address: bc:d0:74:4b:23:80
网关30.3.49.254
ip30.3.49.174
sudo route -n add -net 30.3.0.0/30.3.49.254
sudo route -n add -net 30.3.0.0/16 30.3.49.1

-------------------
重启后,切换内外网
sudo route -n add -net 30.3.0.0/16 30.3.49.254
ping 30.3.37.132


### 开启隐藏文件
Command + Shift + .

### 格式化代码
安卓：梅花两键+L




## vim
	ctrl+o 保存，再按一次，回车键
	ctrl+x 退出
### 在终端中
win+c，停止--》mac：梅花+句号
再打开一个终端：梅花+n

### cursor
- 出现聊天框-梅花+i

### 日常
- 梅花+shift+3---截图（全屏



# 从Windows迁移到Mac的开发者指南

## 基本快捷键对照表

**通用操作**
- 复制：⌘+C (Win: Ctrl+C)
- 粘贴：⌘+V (Win: Ctrl+V)
- 剪切：⌘+X (Win: Ctrl+X)
- 撤销：⌘+Z (Win: Ctrl+Z)
- 重做：⌘+Shift+Z (Win: Ctrl+Y)
- 全选：⌘+A (Win: Ctrl+A)
- 查找：⌘+F (Win: Ctrl+F)
- 保存：⌘+S (Win: Ctrl+S)
- 新建：⌘+N (Win: Ctrl+N)
- 关闭窗口：⌘+W (Win: Alt+F4)
- 切换应用：⌘+Tab (Win: Alt+Tab)
- 截图：⌘+Shift+3/4/5 (Win: Win+Shift+S)

**文本编辑**
- 行首/行尾：⌘+←/→ (Win: Home/End)
- 文档开始/结束：⌘+↑/↓ (Win: Ctrl+Home/End)
- 单词移动：Option+←/→ (Win: Ctrl+←/→)
- 删除一个词：Option+Delete (Win: Ctrl+Backspace)
- 向前删除：Fn+Delete (Win: Delete)

**开发相关**
- 强制退出：⌘+Option+Esc (Win: Ctrl+Alt+Delete)
- 终端：Terminal.app (Win: cmd)
- 查看隐藏文件：⌘+Shift+. (Win: 文件资源管理器选项)

## 使用技巧

### 1. Finder(文件管理器)技巧
- 使用列表视图(⌘+2)查看更详细信息
- ⌘+Shift+G可直接跳转到指定路径
- 使用标签(⌘+T)代替多窗口
- 空格键可快速预览几乎任何文件

### 2. 终端和Shell
- 使用Homebrew安装软件：`brew install 软件名`
- 考虑使用iTerm2替代默认Terminal
- 配置zsh或oh-my-zsh提升终端体验
- 设置.bash_profile或.zshrc自定义环境变量

### 3. 开发工具
- VSCode/JetBrains IDE快捷键可设置为Windows模式
- 使用Spectacle/Rectangle进行窗口管理(类似Win分屏)
- Alfred可替代Spotlight提供更多功能(类似Win搜索)

### 4. 系统设置
- 触控板设置：
  - 启用三指拖拽(辅助功能→指针控制→触控板选项)
  - 调整滚动方向(系统偏好设置→触控板)
- 键盘设置：
  - 增加按键重复速率
  - 设置功能键默认行为(F1-F12)

### 5. 开发环境搭建
- 使用Homebrew安装开发依赖
- 使用Docker避免环境差异
- 熟悉Mac上的路径格式(正斜杠/)

### 6. 必备工具推荐
- Homebrew：软件包管理器
- Rectangle：窗口管理
- iTerm2：终端替代品
- Alfred：Spotlight增强版
- Karabiner-Elements：键盘自定义
- CheatSheet：长按⌘显示当前应用快捷键

### 7. 常见痛点解决
- 没有右键菜单：使用双指点按或Control+点击
- 没有Home/End：使用⌘+←/→代替
- 没有Delete键：使用Fn+Delete向前删除
- 应用卡死：⌘+Option+Esc强制退出

习惯Mac需要时间，但其高效的工作流程一旦掌握，会显著提升开发效率。建议先从键盘快捷键开始适应，逐步探索Mac特有功能。

 