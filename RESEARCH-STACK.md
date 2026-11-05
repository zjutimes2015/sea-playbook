# Sea Playbook 选题 / 市场调研栈 / Research Stack

对照笔记：亚马逊图书选题、关键词与 BSR 调研工具。只用于**选题与验证需求**，不做一键灌书或违规抓取上架。

Playbook 仓库：https://github.com/zjutimes2015/sea-playbook  
审稿栈见：`REVIEW-STACK.md`

最后更新：2026-11-04（America/Los_Angeles）

---

## 五个 Fork（zjutimes2015）

| 工具 | Fork | Upstream | 角色 Role |
|------|------|----------|-----------|
| **sealeap-amazon-skills** | https://github.com/zjutimes2015/sealeap-amazon-skills | https://github.com/xjli360/sealeap-amazon-skills | 选品 / 竞品 / BSR 流程（可迁到图书类目做主题调研） |
| **keepa** | https://github.com/zjutimes2015/keepa | https://github.com/akaszynski/keepa | ASIN 价格史 / BSR / 销量代理（需 Keepa token） |
| **beyondwords** | https://github.com/zjutimes2015/beyondwords | https://github.com/beyondtahir/beyondwords | **仅学 research niches**；禁止 spam publish / 整仓灌书 |
| **kdp-scout** | https://github.com/zjutimes2015/kdp-scout | https://github.com/rxpelle/kdp-scout | KDP 关键词 + 竞品 CLI（七词槽位 / 选题） |
| **Amazon-Bestsellers-Scraper** | https://github.com/zjutimes2015/Amazon-Bestsellers-Scraper | https://github.com/angeloestelle88/Amazon-Bestsellers-Scraper | 畅销榜主题热度（**见合规警告**） |

---

## 建议用法（Sea Playbook）

1. **kdp-scout** — 关键词与竞品，优先服务作者选题与七词槽位  
2. **keepa** — 用 BSR / 价格史验证类目是否有真实需求  
3. **sealeap-amazon-skills** — 对标选品/竞品工作流，迁到 Books / Kindle 主题调研  
4. **beyondwords** — 只读 / 对照 **research niches** 编排；**不要**一键生成垃圾书或自动上架  
5. **Amazon-Bestsellers-Scraper** — 可选扫榜看主题密度；默认谨慎

---

## 合规 / Explicit warnings

### Amazon-Bestsellers-Scraper — ToS / 合规风险

抓取亚马逊畅销榜可能违反 Amazon 网站服务条款（ToS），并有反爬、IP 封禁与账号风险。  
**默认不自动跑；不写入晚间例行。** 若人工使用：低频、只读学习、遵守当地法律与平台政策，不将原始抓取结果商用分发。

### beyondwords — niches only

仅参考其 **research niches** 步骤。  
**禁止** spam publish、批量灌书、自动上传 KDP。你们已有 Sea 方法论，只学选题编排。

### Keepa

官方 API，需自备 token / 配额；勿滥用请求。

---

## Explicit / 明确禁令

**不要**把本栈接到一键灌书或自动上传流水线。  
本栈用途：**选题、关键词、BSR / 竞品验证**。审稿与导出见 `REVIEW-STACK.md`。
