---
layout: Order
title:  "2026/6/28 ALL Hermes "
date:   2026-6-28
description: SMB server OK 


---
## Command ID
CMD-20260714-001


📢 AI 園區重要公告（SMB 共用中心正式啟用）

公告日期：2026-07-14

經測試完成，AI 園區共用儲存中心已正式啟用。

SMB Server
Host : 192.168.2.203
OS   : Windows 10
正式共用
\\192.168.2.203\CastleData
→ D:\CastleBrain

\\192.168.2.203\inbox
→ D:\inbox

登入帳號：

User : new-chia
Password : （依管理員設定）
驗證結果
平台	狀態
Windows	✅ 通過
Ubuntu	✅ 通過
SMB Client	✅ 通過
SSH	✅ 通過

CastleData 與 inbox 已完成跨平台驗證。

開發規範（即日起生效）

建立 Windows SMB Share 時：

Share ACL 必須加入

new-chia
Full Control

不得僅建立專用帳號（例如 inbox_user）後直接結案。

完成後必須驗證：

\\192.168.2.203\CastleData
\\192.168.2.203\inbox

可正常存取。

AI 園區統一資料中心

所有 AI 系統：

Hermes
OpenClaw
Claude
GPT
Ubuntu
macOS

優先使用：

\\192.168.2.203\CastleData

作為共用知識庫。

臨時交換檔案請使用：

\\192.168.2.203\inbox
工程要求

任何 AI Agent 完成工作後，必須提供：

建立步驟
驗證結果
失敗原因（若有）
不得未驗證即宣告完成

包大人指示：

自即日起，AI 園區所有 Windows 共用儲存均以本架構為標準，不再各自建立不同的 SMB 規格。所有新建共享均須依此標準完成設定與驗證後方可結案。
