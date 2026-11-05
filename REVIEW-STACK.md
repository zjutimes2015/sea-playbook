# Sea Playbook 审稿栈 / Review Stack

对照笔记：晚间例行英文稿审查闸门。只用于**审查与导出**，不做一键灌书。

Playbook 仓库：https://github.com/zjutimes2015/sea-playbook

---

## 三个 Fork（zjutimes2015）

| 工具 | Fork | Upstream | Stars（约） | 角色 Role |
|------|------|----------|-------------|-----------|
| **proselint** | https://github.com/zjutimes2015/proselint | https://github.com/amperser/proselint | ~4.6k | 散文风格 / 冗余 / 口号腔 linter（去 AI 味） |
| **LanguageTool** | https://github.com/zjutimes2015/languagetool | https://github.com/languagetool-org/languagetool | ~15.2k | 英文语法 / 拼写（CLI 或自建服务） |
| **calibre** | https://github.com/zjutimes2015/calibre | https://github.com/kovidgoyal/calibre | ~26.4k | MD/EPUB 转换；上架前查目录与字体 |

---

## Nightly review gate（Sea Playbook English units）

对新增或变更的英文 `.md` 章节，按顺序过闸：

1. **proselint** — 风格与冗余  
   - 对 new/changed `.md` 跑 `proselint`  
   - 修：冗词、含糊、口号腔、被动堆砌  

2. **LanguageTool** — 英文语法与拼写  
   - CLI 或本地/自建 server  
   - 批跑 EN 章节；人工确认误报后再改  

3. **calibre（KDP 上传前）** — 导出与版式检查  
   - `MD → EPUB`（或既有 EPUB）  
   - 检查 TOC、内嵌字体、目录跳转  
   - 通过后再进 KDP，不跳过本步  

---

## Explicit / 明确禁令

**不要**使用一键 KDP 垃圾书生成器 / 自动灌书 / 自动上传类工具。  
本栈三仓用途仅为：**审查（proselint + LanguageTool）** 与 **导出检查（calibre）**。

Do **NOT** use one-click KDP spam generators or auto-upload bots. These three forks are **review/export only**.

---

## 与晚间例行的衔接

- 写作完成后 → 本文件闸门 1–2  
- 整书/整单元准备上架 → 闸门 3（calibre）  
- 例行编排由父 agent / routines 维护；本文只固定工具与顺序  

最后更新：2026-11-04（America/Los_Angeles）
