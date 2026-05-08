---
title: 'Rich Content: Markdown & Media'
author: Rishabh Dotasara
date: '2026-05-08'
tags: []
---

# Crafting Beautiful Articles
InstiWiki supports standard Markdown, but we've added some premium features to help your documentation stand out.
## 1. Using Special Alerts
Use these to highlight important information. Choose the one that fits your context:
> [!NOTE]
> Use this for neutral, background information or interesting facts.
> [!TIP]
> Use this for performance optimizations, best practices, or shortcuts.
> [!IMPORTANT]
> Use this for essential requirements or critical steps.
> [!WARNING]
> Use this for potential problems or things to be careful about.
> [!CAUTION]
> Use this for high-risk actions that could cause data loss.
## 2. Dynamic Images
Don't just use text! 
- Use the **Image Upload** button in the editor.
- Once uploaded, the image is stored in your article's dedicated media folder on GitHub.
- Markdown syntax: `![Alt Text](/api/media/article-slug/image-name.png)`
## 3. Code Blocks
For technical documentation, use fenced code blocks with language identifiers for syntax highlighting:
```python
def welcome():
    print("Welcome to InstiWiki!")
