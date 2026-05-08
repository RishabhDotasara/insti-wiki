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

# 2. Dynamic ImagesDon't just use plain text—rich documentation needs visuals!## How Image Upload Works1. Open the **Media Panel** on the right side of the editor.2. Upload your image using the upload button.3. The image is automatically stored in the repository's media folder.4. Click the **Copy Code** button next to the uploaded image.5. Paste the copied markdown anywhere inside your article.---## Example Workflow### Step 1 — Upload ImageUpload:```textcampus-map.png```from the Media Panel.---### Step 2 — Click "Copy Code"The editor automatically generates:```markdown![Campus Map](/media/campus-map.png)```---### Step 3 — Paste AnywhereYou can paste it anywhere in your article:```markdown# Campus NavigationHere is the official campus map:![Campus Map](/media/campus-map.png)```---## Preview![Campus Map](https://placehold.co/800x300)---## Supported Formats- PNG- JPG / JPEG- GIF- WEBP- SVG---## Tips> [!TIP]> Use meaningful filenames like `network-topology.png` instead of `image123.png`.> [!IMPORTANT]> Uploaded images are repository assets, meaning they are version controlled along with your documentation.> [!NOTE]> You can reuse the same uploaded image across multiple articles without uploading it again.

# 3. Technical Code Blocks

For technical documentation, use fenced code blocks with language identifiers for syntax highlighting.

## Python Example

### Markdown

````markdown
```python
def welcome():
    print("Welcome to InstiWiki!")
```
