---
title: 'Rich Content: Markdown & Media'
author: Rishabh Dotasara
date: '2026-05-08'
tags:
  - Guide
---

# Crafting Beautiful Articles

InstiWiki supports standard Markdown, but we've added premium GitHub-style features to help your documentation stand out.

---

# 1. Using Special Alerts

Use these specifically colored boxes to highlight important information.

## NOTE Alert

### Markdown

```
> [!NOTE]
> Use this for neutral background information, "Did you know?" facts, or general context.
```

### Preview

> [!NOTE]
> Use this for neutral background information, "Did you know?" facts, or general context.

---

## TIP Alert

### Markdown

```
> [!TIP]
> Use this for performance optimizations, best practices, or helpful shortcuts.
```

### Preview

> [!TIP]
> Use this for performance optimizations, best practices, or helpful shortcuts.

---

## IMPORTANT Alert

### Markdown

```
> [!IMPORTANT]
> Use this for essential requirements, critical setup steps, or must-read sections.
```

### Preview

> [!IMPORTANT]
> Use this for essential requirements, critical setup steps, or must-read sections.

---

## WARNING Alert

### Markdown

```
> [!WARNING]
> Use this for potential pitfalls, common errors, or things to be careful about.
```

### Preview

> [!WARNING]
> Use this for potential pitfalls, common errors, or things to be careful about.

---

## CAUTION Alert

### Markdown

```
> [!CAUTION]
> Use this for high-risk actions that could cause data loss or system instability.
```

### Preview

> [!CAUTION]
> Use this for high-risk actions that could cause data loss or system instability.

---

# 2. Dynamic Images

Don't just use plain text—rich documentation needs visuals!

- Use the **Image Upload** button in the editor.
- Images are automatically stored in the repository's media folder.

## Markdown

```markdown
![Description](image-url)
```

## Example

```markdown
![Campus Map](https://example.com/campus-map.png)
```

## Preview

![Campus Map](https://placehold.co/800x300)

---

# 3. Technical Code Blocks

For technical documentation, use fenced code blocks with language identifiers for syntax highlighting.

## Python Example

### Markdown

````markdown
```python
def welcome():
    print("Welcome to InstiWiki!")
```
