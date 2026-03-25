# MLP 机器与登录信息

_自动生成于 UTC 2026-03-25 06:36:56Z_

## 图例

| 符号 | 含义 |
| --- | --- |
| ✅ | Running，容器 IP 可用（可 SSH 做环境激活） |
| ❌ | Failed / Error，不可用 |
| ⏳ | 等待/创建中 |
| ⚠️ | 其他状态 |
| ❔ | 无状态信息 |

## Run 1 — `jobId=psx1qhixrjzmgsfz`

| 机器序号 | Task ID | 角色 | 状态 | 符号 | 容器 IP | 说明 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | 0 | Worker | Running | ✅ | 33.235.255.57 | 可用 |
| 2 | 1 | Worker | Running | ✅ | 33.235.222.122 | 可用 |
| 3 | 2 | Worker | Failed | ❌ | 33.235.205.58 | 不可用 |

## Run 2 — `jobId=psxms5xrk5sv7fh`

| 机器序号 | Task ID | 角色 | 状态 | 符号 | 容器 IP | 说明 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | 0 | Worker | Failed | ❌ | 33.235.222.113 | 不可用 |
| 2 | 1 | Worker | Failed | ❌ | 33.235.254.12 | 不可用 |
| 3 | 2 | Worker | Failed | ❌ | 33.235.254.88 | 不可用 |

## Run 3 — `jobId=psxmifxrk5ssjk8`

| 机器序号 | Task ID | 角色 | 状态 | 符号 | 容器 IP | 说明 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | 0 | Worker | Running | ✅ | 33.236.239.107 | 可用 |
| 2 | 1 | Worker | Running | ✅ | 33.236.206.136 | 可用 |
| 3 | 2 | Worker | Failed | ❌ | 33.235.223.49 | 不可用 |

---

同步脚本: 与本仓库同机目录下的 `mlp_login_info_github_sync.py`；数据源为 MLP `/mlapi/kub/job/{jobId}/attempts`。
