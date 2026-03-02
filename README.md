# 智能协做云图库平台（前端实现）


一个支持**多人实时协作编辑**、**AI扩图**、**多维度搜索**的现代图片管理与协作平台前端。

![项目主界面截图](https://raw.githubusercontent.com/你的用户名/你的仓库名/main/docs/screenshots/home.png)
![实时协作演示](https://raw.githubusercontent.com/你的用户名/你的仓库名/main/docs/screenshots/collaboration.gif)
![AI扩图效果](https://raw.githubusercontent.com/你的用户名/你的仓库名/main/docs/screenshots/ai-expand.png)

## ✨ 在线体验（强烈推荐放上去）

https://你的域名.vercel.app 或 https://你的用户名.github.io/仓库名

> 如果还没有部署，优先花1–2小时用 Vercel / Netlify / GitHub Pages 部署一下，哪怕是只读版本，也比纯代码仓库吸引力大10倍。

## 核心功能亮点

- 🖼️ 多维度图片搜索（关键词、标签、分类、主色调、以图搜图）
- ✍️ **实时多人协同编辑**（WebSocket + 编辑锁 + 冲突检测）
- 🪄 AI一键扩图（对接后端异步大模型任务）
- 📊 空间数据分析看板（ECharts 词云、趋势图、颜色分布等）
- 🚀 图片上传优化（拖拽 / URL / 进度条 / 失败重试）
- 🎨 图片编辑器（裁剪、旋转、缩放、滤镜）
- 🔐 权限与路由控制（动态菜单 + 页面级权限）
- 📱 响应式布局

## 技术栈

| 分类         | 技术                              | 说明                              |
|--------------|-----------------------------------|-----------------------------------|
| 框架         | Vue 3 + `<script setup>`          | 组合式 API + 最新语法糖           |
| 构建工具     | Vite                              | 极速开发体验                      |
| 语言         | TypeScript                        | 全项目类型安全                    |
| 状态管理     | Pinia                             | 轻量、组合式、devtools友好        |
| UI 组件      | Ant Design Vue                    | 企业级组件库                      |
| 网络请求     | Axios                             | 全局拦截器 + 类型安全响应         |
| 实时通信     | WebSocket (原生)                  | 心跳重连 + 事件总线封装           |
| 数据可视化   | ECharts 5                         | 动态图表 + 自适应                 |
| 图片处理     | vue-cropper / file-saver          | 裁剪 + 下载                       |
| 工程化       | ESLint + Prettier + husky         | 代码规范 + 提交检查               |
| API 生成     | OpenAPI / swagger-typescript-api  | 自动生成类型安全的请求代码        |
| 部署         | Vercel / Nginx + CDN              | 静态托管 + 图片加速               |

## 项目结构（推荐展示，显得专业）
