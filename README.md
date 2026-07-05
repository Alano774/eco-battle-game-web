# unity_env_game_web

这个仓库是 `unity_env_game` 项目的 Unity WebGL 发布仓库，用于通过 GitHub Pages 提供浏览器在线试玩。

## 直接试玩

网页试玩地址：

`https://Alano774.github.io/unity_env_game_web/`

打开方式很简单：

1. 打开浏览器
2. 访问上面的链接
3. 等待页面加载完成
4. 点击页面中的游戏区域开始试玩

## 推荐打开方式

为了减少缓存和兼容性问题，建议这样打开：

- 优先使用 `Chrome` 或 `Edge`
- 如果页面刚更新过，优先使用无痕模式打开
- 如果页面一直停在旧内容，可以按 `Ctrl + F5` 强制刷新

## 进入游戏后怎么操作

当前网页版本基于 Unity WebGL 导出，默认操作方式为：

- 移动：`W A S D` 或方向键
- 视角：鼠标移动
- 跳跃：`Space`
- 冲刺：`Left Shift`
- 互动：`E`

## 如果打不开怎么办

如果你打开网页后没有正常进入游戏，可以按下面顺序排查：

1. 确认访问的是完整地址  
   `https://Alano774.github.io/unity_env_game_web/`
2. 等待 10 到 30 秒，让 WebGL 资源加载完成
3. 使用无痕窗口重新打开
4. 按 `Ctrl + F5` 强制刷新
5. 换用 `Chrome` 或 `Edge`

## 这个仓库和源码仓库的区别

这个仓库只用于网页发布，里面保存的是 WebGL 导出后的网页文件：

- `index.html`
- `Build/`
- `TemplateData/`

如果你想看项目源码、Unity 场景和 C# 脚本，请查看源码仓库，而不是这个发布仓库。

## 用途说明

这个仓库主要用于：

- 给访客提供一个可直接点击进入的试玩入口
- 通过 GitHub Pages 做网页展示
- 存放 Unity WebGL 打包后的静态文件
