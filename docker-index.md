# Docker 全量分类索引

> 本文件为 [awesome-docker](https://github.com/veggiemonk/awesome-docker) README 的全量分类索引。
> 统计口径：2026-10-06 实测上游 master 分支 README.md 全文逐行计数。
> 共 **22 个主分类**，含子分类共 **43 个叶子分类**，**402 条精选资源**。

---

## Projects（项目工具）

### 官方项目 Official Projects — 4 条
> 上游锚点：`#official-projects`
- Moby / Docker Hub / Docker Compose / Docker Registry

### 引擎与运行时 Engine & Runtime — 10 条
> 上游锚点：`#engine--runtime`
- colima / containerd / cri-o / gVisor / lxc / Mocker / podman / runc / runtime-tools / youki

### 构建镜像 Building Images — 33 条
> 上游锚点：`#building-images`

| 子分类 | 条目数 | 上游锚点 |
|--------|-------|---------|
| Builder（构建器） | 21 | `#builder` |
| Base Images（基础镜像） | 5 | `#base-images` |
| Dockerfile | 4 | `#dockerfile` |
| Linter（检查器） | 3 | `#linter` |

代表：BuildKit / buildx / DockerSlim / earthly / ko / distroless / Wolfi / Hadolint

### 镜像生命周期 Image Lifecycle — 43 条
> 上游锚点：`#image-lifecycle`

| 子分类 | 条目数 | 上游锚点 |
|--------|-------|---------|
| Registry（镜像仓库） | 24 | `#registry` |
| Registry CLI（仓库命令行） | 5 | `#registry-cli` |
| Image Scanning & SBOM（镜像扫描） | 10 | `#image-scanning--sbom` |
| Supply Chain（供应链） | 4 | `#supply-chain` |

代表：Harbor / Docker Hub / Trivy / Grype / Syft / cosign / crane / skopeo

### 运行容器 Running Containers — 41 条
> 上游锚点：`#running-containers`

| 子分类 | 条目数 | 上游锚点 |
|--------|-------|---------|
| Composition（组合） | 6 | `#composition` |
| Orchestration（编排） | 8 | `#orchestration` |
| Deployment & Platforms（部署平台） | 25 | `#deployment--platforms` |
| Garbage Collection（垃圾回收） | 2 | `#garbage-collection` |

代表：Kubernetes / Nomad / Rancher / Dokku / kompose / werf

### 网络与代理 Networking & Proxies — 18 条
> 上游锚点：`#networking--proxies`

| 子分类 | 条目数 | 上游锚点 |
|--------|-------|---------|
| Networking（网络） | 6 | `#networking` |
| Reverse Proxy（反向代理） | 12 | `#reverse-proxy` |

代表：Calico / Flannel / Traefik / nginx-proxy / Caddy / Nginx Proxy Manager

### 存储与数据 Storage & Data — 7 条
> 上游锚点：`#storage--data`
- Docker Volume Backup / Label Backup / Netshare / portworx / quobyte / resq / REX-Ray

### 可观测性 Observability — 23 条
> 上游锚点：`#observability`
- cAdvisor / Prometheus / Grafana / Dozzle / dockprom / Datadog / Sysdig Monitor / Better Stack

### 安全 Security — 16 条
> 上游锚点：`#security`
- docker-bench-security / Falco / Checkov / KICS / Trivy / Aqua Security / Prisma Cloud / docker-socket-proxy

### 用户界面 User Interfaces — 49 条
> 上游锚点：`#user-interfaces`

| 子分类 | 条目数 | 上游锚点 |
|--------|-------|---------|
| Desktop（桌面端） | 5 | `#desktop` |
| Terminal（终端 UI） | 29 | `#terminal` |
| Web（网页端） | 12 | `#web` |
| IDE Integrations（IDE 集成） | 3 | `#ide-integrations` |

代表：Portainer / lazydocker / dockge / Docker Desktop / dive / Swarmpit

### 开发者工作流 Developer Workflow — 55 条
> 上游锚点：`#developer-workflow`

| 子分类 | 条目数 | 上游锚点 |
|--------|-------|---------|
| API Client（API 客户端） | 12 | `#api-client` |
| CI/CD | 21 | `#cicd` |
| Development Environment（开发环境） | 10 | `#development-environment` |
| Serverless（无服务器） | 3 | `#serverless` |
| Testing（测试） | 4 | `#testing` |
| Wrappers（封装工具） | 5 | `#wrappers` |

代表：Drone / GitLab Runner / Tekton / Lando / Laradock / OpenFaaS / dockerode

### 容器内工具 In-Container Tooling — 11 条
> 上游锚点：`#in-container-tooling`
- cdebug / ckron / CoreOS / docker-gen / dockerize / GoSu / is-docker / microcheck / Ofelia / su-exec / supercronic

---

## Learning Resources（学习资源）

### 入门指南 Where to Start — 21 条
> 上游锚点：`#where-to-start`
- Docker 官方文档 / Play With Docker / The Docker Handbook / Learn Docker / Docker Curriculum / Dockerlings / cheatsheets ×4

### Windows 入门 Where to Start (Windows) — 7 条
> 上游锚点：`#where-to-start-windows`
- Windows Containers 快速入门 / ASP.NET Core + Docker / Docker 防火墙配置

### 书籍与教程 Books & Tutorials — 10 条
> 上游锚点：`#books--tutorials`
- Docker in Action / Docker in Practice / Learn Docker in a Month of Lunches / CNCF Landscape

### 精选列表 Awesome Lists — 6 条
> 上游锚点：`#awesome-lists`
- Awesome Compose / Awesome Kubernetes / Awesome Selfhosted / Awesome Sysadmin

### 演示与示例 Demos and Examples — 3 条
> 上游锚点：`#demos-and-examples`
- Local Docker DB / Webstack-micro / 前端 Docker 配置注解

### 实用技巧 Good Tips — 5 条
> 上游锚点：`#good-tips`
- Docker Caveats / Dockerfile 最佳实践 / Docker Compose 锚点技巧 / GUI Apps with Docker

### 树莓派与 ARM Raspberry Pi & ARM — 4 条
> 上游锚点：`#raspberry-pi--arm`
- HypriotOS / balena / armhf Wiki

### 安全文章 Security Articles — 13 条
> 上游锚点：`#security-articles`
- Snyk 镜像安全最佳实践 / Docker 安全部署指南 / CVE 扫描 / Lynis 审计

### 视频教程 Videos — 16 条
> 上游锚点：`#videos`
- Docker for Developers / Docker Swarm from scratch / Docker in Production / 容器入门讲座

### 社区与聚会 Communities and Meetups — 7 条
> 上游锚点：`#communities-and-meetups`

| 子分类 | 条目数 | 上游锚点 |
|--------|-------|---------|
| Brazilian（巴西） | 1 | `#brazilian` |
| English（英文） | 4 | `#english` |
| Russian（俄语） | 1 | `#russian` |
| Spanish（西班牙语） | 1 | `#spanish` |

代表：Docker Reddit / DockerOne (中文) / Docker BR Telegram

---

## 统计方法说明

1. **数据来源**：`https://raw.githubusercontent.com/veggiemonk/awesome-docker/master/README.md`（经 jsDelivr CDN 获取全文 17,219 字符）
2. **分类计数**：统计 `## ` 主标题（排除 TOC、Stargazers over time、页脚链接定义区）= 22 个主分类；`### ` 子标题计入叶子分类层级
3. **条目计数**：逐条计数分类标题下的 `- [链接](url)` 列表项；含粗体子标题（如 Cheatsheets）下的列表项一并计入
4. **核实日期**：2026-10-06（UTC+8）
5. **星数来源**：GitHub REST API `https://api.github.com/repos/veggiemonk/awesome-docker` → `stargazers_count = 34,671`
6. **许可来源**：同上 API → `license.spdx_id = Apache-2.0`
