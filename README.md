# Linux 系统监控工具大全

这是一个收集 **Linux 系统监控工具** 的仓库，按类别整理，方便大家查阅和使用。

## 目录

- [基础命令行工具](#基础命令行工具)
- [高级交互式工具](#高级交互式工具)
- [网络监控工具](#网络监控工具)
- [磁盘与 I/O 监控](#磁盘与-io-监控)
- [全栈监控平台](#全栈监控平台)
- [可视化与仪表盘](#可视化与仪表盘)

## 基础命令行工具

| 工具       | 描述                  | 安装命令                     |
|------------|-----------------------|------------------------------|
| `top`      | 经典实时进程监控      | 已内置                       |
| `htop`     | 增强版 top（推荐）    | `sudo apt install htop`      |
| `free -h`  | 内存使用情况          | 已内置                       |
| `vmstat`   | 系统虚拟内存统计      | `sudo apt install procps`    |
| `iostat`   | CPU + 磁盘 I/O        | `sudo apt install sysstat`   |
| `sar`      | 历史系统活动报告      | `sudo apt install sysstat`   |

## 高级交互式工具

| 工具     | 描述                          | 安装命令                    |
|----------|-------------------------------|-----------------------------|
| `glances` | 全系统概览（超级实用）        | `sudo apt install glances`  |
| `atop`    | 详细进程历史与资源监控        | `sudo apt install atop`     |
| `nmon`    | IBM 风格性能监控              | `sudo apt install nmon`     |
| `btop`    | 现代化漂亮界面                | `sudo apt install btop`     |

## 网络监控工具

| 工具       | 描述                    | 安装命令                     |
|------------|-------------------------|------------------------------|
| `iftop`    | 实时带宽使用监控        | `sudo apt install iftop`     |
| `nethogs`  | 按进程显示流量          | `sudo apt install nethogs`   |
| `ss`       | 网络连接（推荐）        | 已内置                       |
| `tcpdump`  | 网络抓包分析            | `sudo apt install tcpdump`   |

## 磁盘与 I/O 监控

| 工具    | 描述                  | 安装命令                  |
|---------|-----------------------|---------------------------|
| `iotop` | 实时磁盘 I/O 按进程   | `sudo apt install iotop`  |
| `df -h` | 磁盘空间使用          | 已内置                    |
| `du -sh`| 目录大小统计          | 已内置                    |

## 全栈监控平台

- **[Netdata](https://github.com/netdata/netdata)**：实时、漂亮、资源占用低
- **[Prometheus + Grafana](https://prometheus.io/)**：云原生监控黄金组合
- **[Zabbix](https://www.zabbix.com/)**：企业级分布式监控
- **[Nagios / Icinga](https://www.icinga.com/)**：经典监控系统
- **Checkmk**：基于 Nagios 的现代化版本

## 可视化与仪表盘

- Grafana
- Netdata 内置仪表盘
- Cockpit (Web 界面)

欢迎大家补充更多工具、使用示例或截图！
