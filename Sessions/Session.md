## 5 月 6 日 （三）| 14:00 - 14:30 全面防護 AI
- 講者: **Richard Lee** (CrowdStrike 北亞區技術顧問)
- SUBTOPIC
    - AI Security
    - AI
    - Threat Detection & Response
---
### 主要內容:
#### 1.介紹CrowdStrike 產品以及為何使用
1. 透過他們的產品要先知道同仁使用哪些ai 工具
    (透過瀏覽器使用各家ai、MCP、內部ai 工具等等監測流量)

2. 是否有機敏資料被當成prompt送入llm

3. CrowdStrike 的產品會先擋下來，就不會被當成prompt送到llm
---
#### 2. 產品怎麼在用戶端使用
- 不管是文字/檔案/或是其他ai工具，CrowdStrike 的產品都可以介入，然後發出警告或是其他訊息
---
#### 3. 流程
CrowdStrike 的解決方案(以下用CrowdStrike代替)
1. Securing Workforce AI Use（保護員工使用 AI）
```
user(員工) -> CrowdStrike -> llm
```
- 核心目標：

    - Uncover Shadow AI

    - Prevent AI Data Leaks

    - Enforce AI Usage Policies


2. Securing Homegrown AI Agents & Workloads（保護自研 AI 代理與工作負載）
```
user(客戶) -> 企業自有的 AI 服務（Bot）-> CrowdStrike -> 企業內部模型/架構
```
- 核心目標：

    - Secure AI Workloads

    - Protect AI Agents

    - Stop Prompt Injection Attacks