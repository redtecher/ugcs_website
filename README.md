# UgCS 官方网站

UgCS 通用地面控制站产品官方网站

## 项目简介

本项目是 UgCS（Universal Ground Control Station）通用地面控制站软件的官方网站，用于展示和介绍 UgCS 产品的功能特点、购买方案、SDK 开发等内容。

## 技术栈

- **HTML5** - 页面结构
- **CSS3** - 样式设计
- **Bootstrap 3** - 响应式前端框架
- **JavaScript/jQuery** - 交互功能

## 目录结构

```
ugcs_website/
├── css/                # 样式文件
│   ├── bootstrap.css
│   └── bootstrap-theme.css
├── js/                 # JavaScript 文件
│   └── bootstrap.min.js
├── fonts/              # 字体文件（Bootstrap 图标）
├── images/             # 图片资源
├── index.html          # 中文首页
├── index_en.html       # 英文首页
├── WhyUgCS.html        # 为何选用 UgCS
├── purchase_cn.html    # 购买页面（中文）
├── purchase_en.html    # 购买页面（英文）
├── ddc_cn.html         # 无人机编队表演
├── sdk_cn.html         # SDK 二次开发（中文）
├── sdk_en.html         # SDK 二次开发（英文）
├── dowload_cn.html     # 资料下载（中文）
├── dowload_en.html     # 资料下载（英文）
├── demo.html           # 视频演示
├── connectus_cn.html   # 联系我们（中文）
├── connectus_en.html   # 联系我们（英文）
└── SuccessStories.html # 成功案例
```

## 页面说明

| 页面                                       | 描述                            |
| ------------------------------------------ | ------------------------------- |
| [index.html](index.html)                   | 网站中文首页                    |
| [index_en.html](index_en.html)             | 网站英文首页                    |
| [WhyUgCS.html](WhyUgCS.html)               | 介绍选用 UgCS 的十大理由        |
| [purchase_cn.html](purchase_cn.html)       | UgCS 授权购买方案（中文版）     |
| [ddc_cn.html](ddc_cn.html)                 | 无人机编队表演服务介绍          |
| [sdk_cn.html](sdk_cn.html)                 | UgCS SDK 二次开发指南（中文版） |
| [dowload_cn.html](dowload_cn.html)         | 相关资料下载（中文版）          |
| [demo.html](demo.html)                     | UgCS 功能视频演示               |
| [connectus_cn.html](connectus_cn.html)     | 联系方式（中文版）              |
| [SuccessStories.html](SuccessStories.html) | 成功案例展示                    |

## 本地运行

1. 克隆或下载本项目
2. 直接用浏览器打开 `index.html` 文件
3. 或使用本地服务器（推荐）：
   ```bash
   # 使用 Python 3
   python -m http.server 8000

   # 使用 Node.js http-server
   npx http-server
   ```
4. 在浏览器中访问 `http://localhost:8000`

## 产品功能

- **多无人机支持** - 同时控制多台不同品牌的无人机
- **三维任务规划** - 支持导入 3D 建筑模型和地形数据
- **路径规划** - 直观的航线创建和编辑
- **飞行后期分析** - 地理标记、视频录制、遥测回放
- **禁飞区设置** - 自定义飞行安全区域
- **SDK 二次开发** - 支持集成到自有系统

## 支持的无人机品牌

- DJI（大疆）
- ArduPilot
- PX4
- InnoFlight
- Mikrokopter
- Microdrones
- MicroPilot
- 及其他多种品牌

## 许可证

本项目仅供展示使用。

## 联系方式

南京欣亿盛电子科技有限公司

详见 [联系我们](connectus_cn.html) 页面。
