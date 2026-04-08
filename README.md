# OptiDomain

**OptiDomain** 是一款现代、高性能的 CloudFlare 边缘路由智能优选前端面板。为了极致的连通性与低延迟体验，它具备智能调度三网（中国移动、中国电信、中国联通）路由方向的能力，让 CloudFlare 节点尽在掌握。

*（当前项目仅为纯前端展示端，数据动态下发与测速核心后端部署在隔离私有环境，保障绝对的数据安全。）*

## ✨ Features / 核心特性

- ⚡ **Live Network Radar (实时节点雷达)**: 24/7 全天候可视化追踪全链路，网络波动一目了然。
- 🚀 **ISP Route Dispatch (智能分发)**: 提供 CM / CT / CU / BGP / Wildcard 多方向优选 IP 切片，一键复制立即生效。
- 🎨 **Modern PWA UI (现代渐进式应用)**: 采用 Material Design 灵感的现代 UI，极具亲和力的动画和视觉设计。
- 🔒 **Military-grade Security (顶配安全)**: 严格的 `Content-Security-Policy (CSP)` 以及跨域 Iframe 隔离防护网。
- 📱 **Mobile First (移动端优先体验)**: 具备触觉震动反馈 (Haptic Feedback) 与骨架屏 (Skeleton Screen)，专为手机而生。
- ⚡ **Offline-first (离线与缓存抗灾)**: 基于 `Service Worker` 和 `Stale-While-Revalidate` 策略，无惧断网环境。

## 🛠️ Tech Stack / 技术栈

- 纯净无依赖的 **Vanilla HTML5, CSS3, ES6 JavaScript**
- **Service Worker** (深度自定义缓存拦截器与断网后备机制)
- 极致的 **SEO / Open Graph** 社交媒体卡片优化（无缝集成 Telegram、Discord 等平台解析）

## 🚀 Getting Started / 快速启动

本前端项目是一个开箱即用的静态网页，部署方式极其简单：

1. **克隆本仓库到本地**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/OptiDomain.git
   ```

2. **使用任何您喜欢的静态服务器进行托管（例如 Python）**:
   ```bash
   python -m http.server 8050
   ```

3. **浏览器访问**:
   打开 `http://localhost:8050` 开始体验。

> 注：本项目通过获取线上的 `optimized_cf_ips.csv` 接口（通常由您的后端脚本定时拉取更新）动态进行渲染。如果您想自定义测速节点，可直接覆盖此 `.csv` 文档即可。

## 📄 License

MIT License
