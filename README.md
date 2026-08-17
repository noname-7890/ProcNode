# ProcNode
A high-performance proxy client &amp; process-level traffic dispatcher supporting multi-node isolation, independent app routing, and multi-path concurrency.
<img width="1280" height="720" alt="bandicam-2026-08-16-20-58-52-365" src="https://github.com/user-attachments/assets/9c306561-47c2-47cb-aeaf-b98ae8253581" />

一款可以代替 v2rayN / Clash Verge + Proxifier 的代理客户端。  
一款高性能、多节点、多端口、多应用支持、资源占用极低的代理与流量调度工具。  
节点管理 + 多端口 + 进程级分流 + 自动选优 + 多节点加速 + Cloudflare 优选，一个软件解决以前需要多个软件才能完成的事情。  

📡 多节点 / 多端口：  
默认页面 "全部 7890" 显示所有已导入节点。  
点击 “+” 可导入：Clash 订阅 / V2Ray 订阅 / Ctrl + V 直接粘贴节点  

每个标签页对应一个独立端口，例如：  
7890 · 7891 · 7892 · 自定义端口  
应用可以直接使用对应端口，也可以通过规则指定应用走某个端口。

🎯代理 + 路由：无需再同时运行代理客户端和 Proxifier。  
ProcNode 支持进程级代理与独立分流，可以让不同应用使用不同节点。

例如：  
Chrome      → 节点 A  
Edge        → 节点 B  
Firefox     → 节点 C  
Telegram    → 节点 D  
Antigravity → 节点 E  

点击节点列表右上角 「规则」，即可指定应用通过当前端口运行。

节点列表右上角提供多种功能：  
A · 自动选择最优节点  
自动选择延迟、速度等表现更好的节点。  
⚡ · 多节点加速  
同时启用 2～3 个节点进行负载调度，提高多任务、多连接场景下的稳定性与速度。  
☁ · Cloudflare 优选  
自动进行 Cloudflare IP 优选，以优选 IP 替代原节点 IP。  

推荐组合：  
自动 + 加速 + 优选  
在多网站、多视频、Telegram 等多任务场景下，可获得更好的使用体验，更可以对抗晚高峰。  

🚀 极低资源占用:  
ProcNode 的核心特点之一就是轻量。  
主程序常驻内存仅个位数 MB 级别（5M左右）。  

相比同时运行：  
v2rayN / Clash Verge + Proxifier（200-500M）  
ProcNode 可以用一个程序完成更多功能，同时显著降低系统资源占用。  
功能更集中，资源占用更低。  

🖥️ 适合  
多浏览器同时运行  
多应用独立代理  
多节点、多端口并行  
游戏 / 软件 / Telegram / 浏览器分别走不同节点  
多任务、多连接场景  
对抗晚高峰网络环境  

📌 一句话  
ProcNode：一个客户端，搞定节点、端口、规则、分流、加速与优选。  
注：请根据当地法律法规使用相关网络功能。
