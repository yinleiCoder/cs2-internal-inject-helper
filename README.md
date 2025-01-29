# CS2 游戏外挂助手 - 内部注入

C++ [ESP 游戏外挂](https://github.com/yinleiCoder/cs2-cheat-cpp)的常维护版本（可能会在别的仓库写 Driver 外挂），涵盖能想到的各种功能。

## 软件功能

- 方框透视
- 骨骼透视
- 静默自瞄
- 后坐力补偿
- 雷达监测
- 实时显示敌方玩家信息
- 绕过 VAC 反作弊系统

## 软件使用

## 代码构建

- `git clone`本仓库
- 更改 Debug 为`Release`
- 项目右击`属性`
  - 配置属性->常规->C++语言标准：`c++20`
  - 配置属性->高级->字符集:`使用多字节字符集`
  - 链接器->输入->附加依赖项: `d3d11.lib`

## 第三方依赖

> 本项目依赖于通用 ImGui 实现：[ImGui-DirectX-11-Kiero-Hook](https://github.com/rdbo/ImGui-DirectX-11-Kiero-Hook)

- ImGui
- MinHook
- Kiero
- [Extreme Injector](https://github.com/master131/ExtremeInjector)

## 捐赠

代码仅供学习交流使用，软件采用 github actions 进行 ci/cd，不妨请我喝一杯咖啡？后续推出更实用的桌面端软件、app 等，谢谢您的关注。

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=yinleiCoder/cs2-internal-inject-helper&type=Date)](https://star-history.com/#yinleiCoder/cs2-internal-inject-helper&Date)
