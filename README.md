# ProcNode

<div align="center">
<img width="320" height="308" alt="icon" src="https://github.com/user-attachments/assets/5346b5d7-ca07-4ea3-a101-28fd9087c7f3" />
</div>

A high-performance proxy client &amp; process-level traffic dispatcher supporting multi-node isolation, independent app routing, and multi-path concurrency.
<img width="1280" height="720" alt="bandicam-2026-08-16-20-58-52-365" src="https://github.com/user-attachments/assets/9c306561-47c2-47cb-aeaf-b98ae8253581" />


# ProcNode

> **多节点 · 多端口 · 进程级独立分流 · 极低开销**  
> 一体化替代 v2rayN / Clash Verge + Proxifier，单程序搞定节点管理、端口映射、规则分流、多路加速与 Cloudflare 优选。

## 核心特性

* **多节点与多端口映射**
  * 支持解析 Clash / V2Ray 订阅链接，支持 `Ctrl + V` 剪贴板快捷导入。
  * 每个标签页独立分配一个本地监听端口（如 7890、7891、7892...）。
* **进程级独立分流（完全替代 Proxifier）**
  * 点击「规则」一键绑定目标进程，各应用流量完全物理隔离。
  * 支持不同软件走不同节点，如：Chrome 走节点 A，Telegram 走节点 B，Antigravity 走节点 C。
* **智能调度与加速引擎**
  * **[ A ] 自动选优**：实时监控延迟与连通性，自动切换最佳节点。
  * **[⚡] 多路加速**：并发调度 2~3 个节点进行负载均衡，提升多连接吞吐。
  * **[ ☁ ] CF 优选**：内置本地测速，自动替换为 Cloudflare 运营商最优 Clean IP。
  * *(推荐组合：A + ⚡ + ☁，从容对抗晚高峰)*
* **极致能效比**
  * 主程序常驻内存仅 **个位数（10MB以内）**，大幅降低系统资源开销。

## 适用场景

* 浏览器、通讯软件、下载器等需要各自独立指定代理出口的环境。
* 多任务并行与多平台运营。
* 聚合多节点带宽对抗网络拥堵。
* 追求极低后台资源占用的极简工作流。

---
*注：请根据当地法律法规使用相关网络功能。*
