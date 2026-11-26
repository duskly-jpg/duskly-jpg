### 黄运新

构建能自我校验的 AI 应用：自然语言取数 Agent、技能路由工具链、端云完整性验证、Android 端侧。项目全部真实上线，代码与文档公开。

## 项目

### AI 应用与 Agent

- **[data-agent](https://github.com/duskly-jpg/data-agent)** — 自然语言问数 DataAgent：LLM 生成 SQL，四道闸（语法 / 权限 / 口径 / 资源限额）+ 三裁判裁决，ODS→ADS 分层与 10 项指标口径全落库；13 个负样本注入全部拦截（fail-closed）。
- **[dobby-handbook](https://github.com/duskly-jpg/dobby-handbook)** — Agent 运维纪律开源课本：30 起真实事故的失败分类学、验证纪律、无梯度等价方法论，附 20 题 agent 自测评测集。

### 移动端与端云安全

- **[huandou](https://github.com/duskly-jpg/huandou)** — Android WebView 浏览器客户端：无 Gradle 纯构建链（aapt2 / javac / R8 / apksigner），媒体嗅探 + HLS 播放，394 KB 轻量成品。
- **[huandou-attest](https://github.com/duskly-jpg/huandou-attest)** — Android Key Attestation 服务端验签：X.509 证书链 + DER 解析零第三方依赖，58 项测试四层覆盖（单元 / 集成 / 负例 / 端到端）。

### 基础设施与应用

- **[cloud-infra](https://github.com/duskly-jpg/cloud-infra)** — Cloudflare Workers 通用组件：webhook 接收桥（HMAC 验签 / 防重放 / KV 去重）与 cron 调度器，域名泛化、零硬编码断言 CI。
- **[dusk](https://github.com/duskly-jpg/dusk)** — 出租屋管理系统：Workers + D1 免费档零月费，租约状态机、发票式账单、逾期罚金引擎、水电分摊；PBKDF2 口令哈希 + HMAC 会话，移动端适配。在线运行：[dusk.flaros.xyz](https://dusk.flaros.xyz)

### 安全研究

- **[offense-lab](https://github.com/duskly-jpg/offense-lab)** — 自建授权攻防靶场：LLM 红队狩猎框架、变体化弹药库、蜜罐与评测三方解耦的方法论。

---

<!-- easter egg -->
> [resume.flaros.xyz](https://resume.flaros.xyz) · 所有数字都能复跑
