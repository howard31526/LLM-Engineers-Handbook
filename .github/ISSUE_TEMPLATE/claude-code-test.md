---
name: Claude Code Test
about: Describe this issue templaTemplate for testing Claude Code GitHub Actions integrationte's
  purpose here.
title: ''
labels: ''
assignees: ''

---

---
name: Claude Code 測試
about: 測試 Claude Code GitHub Actions 整合功能
title: '[TEST] Claude Code 功能測試'
labels: claude-test
assignees: ''

---

## 測試目的
@claude 這是測試 Claude Code GitHub Actions 整合的 Issue。

## 測試項目
請確認以下功能：
- [ ] Issue 事件觸發
- [ ] 內容解析功能
- [ ] 自動回應功能
- [ ] 中文回應能力

## 測試指令
@claude 請回應以下問題：
1. 是否成功接收到這個 Issue？
2. 能否解析 Issue 的內容？
3. 請用繁體中文回應確認訊息

## 預期結果
Claude 應該自動在此 Issue 中回應，確認功能正常運作。

---
**測試資訊**：
- 觸發事件：issues (opened)
- 檢查內容：issue.body 和 issue.title
- 預期延遲：2-5 分鐘內回應
