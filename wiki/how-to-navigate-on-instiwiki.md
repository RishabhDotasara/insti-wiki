---
title: How to navigate on InstiWiki?
author: Rishabh Dotasara
date: '2026-05-08'
tags:
  - Guide
---

# Mastering the Hierarchical Tagging System
Welcome to InstiWiki! To keep our institutional knowledge organized without the chaos of unorganized folders, we use a **Hierarchical Tagging System**. This system powers our search and allows for deep categorization of content.
## 1. How to Add Tags
When you are creating or editing an article, you will see a **Tags** section below the title. 
- Type your tag name.
- Press **Enter** or click **Add**.
- Your tag will appear as a badge. To remove it, just click the small **X**.
## 2. Creating Hierarchies (The "/" Magic)
We don't use separate folders for categories. Instead, we use **Slashes** directly in the tag names to create subcategories.
### Example:
- If you use the tag `Academics`, it creates a top-level category.
- If you use the tag `Academics/Computer Science`, it creates a sub-category called "Computer Science" inside "Academics".
- If you go deeper, like `Academics/Computer Science/First Year`, you create a three-level deep tunnel for users to explore.
## 3. The Tag Explorer
By clicking **"Explore Tags"** in the navigation bar, you can see all top-level categories. 
- Clicking a category will show you all articles inside it AND any sub-categories.
- We use **Breadcrumbs** at the top (`Root > Category > Subcategory`) to help you find your way back.
## 4. Why is it so fast? (The Registry)
InstiWiki uses a scalable **Wiki Registry**. Every time an Admin approves a change, the system updates a central index (`registry.json`) in the repository. This allows our Tag Explorer to show thousands of articles instantly without scanning the whole repository every time you click.
> [!TIP]
> If you notice a newly approved article isn't appearing in the tags yet, an Admin can click **"Rebuild Index"** on the Explore page to force a fresh scan of the repository.
---
*Keep the Wiki clean, keep the tags precise!*
