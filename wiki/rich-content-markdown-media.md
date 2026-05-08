---
title: 'Rich Content: Markdown & Media'
author: Rishabh Dotasara
date: '2026-05-08'
tags:
  - Guide
---

# Crafting Beautiful Articles
InstiWiki supports standard Markdown, but we've added premium GitHub-style features to help your documentation stand out.
## 1. Using Special Alerts
Use these specifically colored boxes to highlight important information. 
> [!NOTE]
> Use this for neutral background information, "Did you know?" facts, or general context.
> [!TIP]
> Use this for performance optimizations, best practices, or helpful shortcuts.
> [!IMPORTANT]
> Use this for essential requirements, critical setup steps, or must-read sections.
> [!WARNING]
> Use this for potential pitfalls, common errors, or things to be careful about.
> [!CAUTION]
> Use this for high-risk actions that could cause data loss or system instability.
## 2. Dynamic Images
Don't just use plain text—rich documentation needs visuals! 
- Use the **Image Upload** button in the editor.
- Images are automatically stored in the repository's media folder.
- **Syntax**: `![Description](image-url)`
## 3. Technical Code Blocks
For technical documentation, use fenced code blocks with language identifiers for syntax highlighting:
```python
def welcome():
    print("Welcome to InstiWiki!")
