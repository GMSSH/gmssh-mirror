# 🚀 GMSSH 公益镜像加速站：不让技术被“墙”阻隔
<p align="left">
  <strong>English</strong> | <a href="./README_EN.md">English</a>
</p>

[![](https://img.shields.io/badge/Status-Online-brightgreen)](#) 
[![](https://img.shields.io/badge/Powered%20By-GMSSH-blue)](#)
[![](https://img.shields.io/badge/License-GPL--3.0-lightgrey)](#)

## 📖 我们的故事：为什么要坚持做这件事？

作为开发者，我们都曾经历过那样的时刻：
当你在深夜敲下一行 `docker pull`，等待你的不是进度条的飞驰，而是无尽的 `Context canceled` 或 `Connection refused`。

网络环境的波动、官方镜像站的不可达，正在一点点蚕食我们的开发热情。原本几秒钟的部署，可能要折腾一个下午。**技术本不该有边界，工具更不该成为障碍。**

**GMSSH 团队** 作为服务器运维工具的深耕者，我们深知其中的痛苦。为了让每一位中国开发者能重新找回“丝滑”的拉取体验，我们决定拿出我们的服务器资源，建立并维护这个**纯公益、不设限**的 Docker 镜像加速站。

**这不是什么伟大的商业计划，这只是 GMSSH 社区对中国开发者的一份致敬。**

---

## ⚡ 极速接入

### 推荐：一键配置 (支持 Ubuntu, CentOS, Debian, AlmaLinux 等)
使用GMSSH应用 Docker管理器 只需点击即可完成配置
<img width="2416" height="1432" alt="image" src="https://github.com/user-attachments/assets/3ba1d6be-04c2-4ef7-8834-aa677524c022" />

### 手动配置

编辑 `/etc/docker/daemon.json`，添加如下内容：

```json
{
  "registry-mirrors": ["[https://docker.gmssh.com](https://docker.gmssh.com)"]
}

```

*配置完成后请执行 `systemctl restart docker` 重启服务。*

---

## 🌐 维护计划

| 资源名称 | 官方地址 | GMSSH 加速地址 | 状态 |
| --- | --- | --- | --- |
| **Docker Hub** | `docker.io` | `https://docker.gmssh.com` | ✅ 极速 |
| **GHCR** | `ghcr.io` | `https://ghcr.gmssh.com` | ⚠️ 待支持 |
| **K8s Registry** | `registry.k8s.io` | `https://k8s.gmssh.com` | ⚠️ 待支持 |

---

## 🛠 申请同步冷门镜像 (Issue Trigger)

如果您需要的镜像在加速站中未命中，请通过以下方式告诉我们：

1. **[发起同步 Issue]()**
2. 我们的自动化机器人会在 5 分钟内完成同步，并回复加速路径。

---

## 📱 关于 GMSSH 运维终端

本加速站由 **GMSSH** 官方提供支持。
GMSSH 是一款专为 AI 时代设计的 **桌面级 AI 运维终端**。

* **可视化换源**：内置全国镜像站，点击即换，无需记忆繁琐命令。
* **AI 助手**：自动诊断终端报错，一键修复 Linux 环境问题，比 StackOverflow 更懂你的服务器。
* **完全免费**：我们致力于为开发者提供最纯粹、最高效的运维体验。

👉 [访问 GMSSH 官网](https://gmssh.com) | [加入微信交流群](https://gmb-prod-gw.oss-accelerate.aliyuncs.com/up/1/act_banner/18212068cd2ea0123d5Gv9nJK.png)

---

<p align="center">
<b>愿代码的世界再无阻碍。Made with ❤️ by GMSSH Team.</b>
</p>
