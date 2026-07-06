# Capture Storage Spec

## Purpose

Capture Storage 的目的，是把每一則 Capture 實際保存下來。

目前先使用 Markdown 檔案保存。

未來再由 Codex 轉入 SQLite 資料庫。

---

## Core Principle

Capture should be effortless.

Research should be intentional.

---

## Storage Flow

User Input

↓

Capture

↓

Markdown File

↓

GitHub

↓

Future SQLite Database

---

## Folder Structure

captures/
└── YYYY/
    └── MM/
        └── YYYYMMDD_001.md

Example:

captures/
└── 2026/
    └── 07/
        └── 20260706_001.md

---

## Markdown Capture Format

每一則 Capture 都使用固定格式：

```markdown
# Capture Title

Date:

Status: Waiting

Type: AI decides later

Source:

Summary:

Tags:

Raw Note:
