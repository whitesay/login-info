# MLP 机器与登录信息

_自动生成于 UTC 2026-03-25 06:46:23Z_

## 图例

| 符号 | 含义 |
| --- | --- |
| ✅ | Running，容器 IP 可用（可 SSH 做环境激活） |
| ❌ | Failed / Error，不可用 |
| ⏳ | 等待/创建中 |
| ⚠️ | 其他状态 |
| ❔ | 无状态信息 |

同一 **Task** 下多行表示多次 **重试/重启**（按接口返回顺序：一般靠后为较新一次）。

## Run 1 — `jobId=psx1qhixrjzmgsfz`

### 机器 1 — Task `0` · Worker

| 次序 | 状态 | 符号 | 容器 IP | containerId | 其他 ID | 说明 |
| --- | --- | --- | --- | --- | --- | --- |
| 1/1 | Running | ✅ | 33.235.255.57 | `psx1qhixrjzmgsfz-worker-0-0` | `attemptId`=0 `podName`=psx1qhixrjzmgsfz-worker-0-0 | 可用（当前次序末条） |

### 机器 2 — Task `1` · Worker

| 次序 | 状态 | 符号 | 容器 IP | containerId | 其他 ID | 说明 |
| --- | --- | --- | --- | --- | --- | --- |
| 1/1 | Running | ✅ | 33.235.222.122 | `psx1qhixrjzmgsfz-worker-1-0` | `attemptId`=0 `podName`=psx1qhixrjzmgsfz-worker-1-0 | 可用（当前次序末条） |

### 机器 3 — Task `2` · Worker

| 次序 | 状态 | 符号 | 容器 IP | containerId | 其他 ID | 说明 |
| --- | --- | --- | --- | --- | --- | --- |
| 1/2 | Running | ✅ | 33.235.255.139 | `psx1qhixrjzmgsfz-worker-2-1` | `attemptId`=1 `podName`=psx1qhixrjzmgsfz-worker-2-1 | 可用 |
| 2/2 | Failed | ❌ | 33.235.205.58 | `psx1qhixrjzmgsfz-worker-2-0` | `attemptId`=0 `podName`=psx1qhixrjzmgsfz-worker-2-0 | 不可用（当前次序末条） |

## Run 2 — `jobId=psxms5xrk5sv7fh`

### 机器 1 — Task `0` · Worker

| 次序 | 状态 | 符号 | 容器 IP | containerId | 其他 ID | 说明 |
| --- | --- | --- | --- | --- | --- | --- |
| 1/2 | Running | ✅ | 33.236.215.11 | `psxms5xrk5sv7fh-worker-0-1` | `attemptId`=1 `podName`=psxms5xrk5sv7fh-worker-0-1 | 可用 |
| 2/2 | Failed | ❌ | 33.235.222.113 | `psxms5xrk5sv7fh-worker-0-0` | `attemptId`=0 `podName`=psxms5xrk5sv7fh-worker-0-0 | 不可用（当前次序末条） |

### 机器 2 — Task `1` · Worker

| 次序 | 状态 | 符号 | 容器 IP | containerId | 其他 ID | 说明 |
| --- | --- | --- | --- | --- | --- | --- |
| 1/2 | Running | ✅ | 33.236.247.170 | `psxms5xrk5sv7fh-worker-1-1` | `attemptId`=1 `podName`=psxms5xrk5sv7fh-worker-1-1 | 可用 |
| 2/2 | Failed | ❌ | 33.235.254.12 | `psxms5xrk5sv7fh-worker-1-0` | `attemptId`=0 `podName`=psxms5xrk5sv7fh-worker-1-0 | 不可用（当前次序末条） |

### 机器 3 — Task `2` · Worker

| 次序 | 状态 | 符号 | 容器 IP | containerId | 其他 ID | 说明 |
| --- | --- | --- | --- | --- | --- | --- |
| 1/2 | Running | ✅ | 33.236.214.64 | `psxms5xrk5sv7fh-worker-2-1` | `attemptId`=1 `podName`=psxms5xrk5sv7fh-worker-2-1 | 可用 |
| 2/2 | Failed | ❌ | 33.235.254.88 | `psxms5xrk5sv7fh-worker-2-0` | `attemptId`=0 `podName`=psxms5xrk5sv7fh-worker-2-0 | 不可用（当前次序末条） |

## Run 3 — `jobId=psxmifxrk5ssjk8`

### 机器 1 — Task `0` · Worker

| 次序 | 状态 | 符号 | 容器 IP | containerId | 其他 ID | 说明 |
| --- | --- | --- | --- | --- | --- | --- |
| 1/1 | Running | ✅ | 33.236.239.107 | `psxmifxrk5ssjk8-worker-0-0` | `attemptId`=0 `podName`=psxmifxrk5ssjk8-worker-0-0 | 可用（当前次序末条） |

### 机器 2 — Task `1` · Worker

| 次序 | 状态 | 符号 | 容器 IP | containerId | 其他 ID | 说明 |
| --- | --- | --- | --- | --- | --- | --- |
| 1/1 | Running | ✅ | 33.236.206.136 | `psxmifxrk5ssjk8-worker-1-0` | `attemptId`=0 `podName`=psxmifxrk5ssjk8-worker-1-0 | 可用（当前次序末条） |

### 机器 3 — Task `2` · Worker

| 次序 | 状态 | 符号 | 容器 IP | containerId | 其他 ID | 说明 |
| --- | --- | --- | --- | --- | --- | --- |
| 1/2 | Running | ✅ | 33.236.207.111 | `psxmifxrk5ssjk8-worker-2-1` | `attemptId`=1 `podName`=psxmifxrk5ssjk8-worker-2-1 | 可用 |
| 2/2 | Failed | ❌ | 33.235.223.49 | `psxmifxrk5ssjk8-worker-2-0` | `attemptId`=0 `podName`=psxmifxrk5ssjk8-worker-2-0 | 不可用（当前次序末条） |

---

同步脚本: 与本仓库同机目录下的 `mlp_login_info_github_sync.py`；数据源为 MLP `/mlapi/kub/job/{jobId}/attempts`。
