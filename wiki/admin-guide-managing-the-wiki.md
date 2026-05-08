---
title: 'Admin Guide: Managing the Wiki'
author: Rishabh Dotasara
date: '2026-05-08'
tags: []
---

# Admin Moderation Workflow
As an Admin, you are the gatekeeper of InstiWiki. You have the power to publish content directly and review contributions from the community.
## 1. Direct Publishing
Admins can bypass the Pull Request system. When you edit and save an article:
- It is committed directly to the `main` branch.
- The **Wiki Registry** is updated instantly.
- The changes are live for all users immediately.
## 2. Reviewing the Queue
When Editors suggest changes, they appear in your **Moderation Queue**:
1.  Open the **Queue** from the navigation bar.
2.  Click on a request to see the **Diff Viewer**.
3.  Lines in <span style="color: green">green</span> are additions; <span style="color: red">red</span> are deletions.
## 3. Approving vs. Rejecting
- **Approve**: Merges the code into `main`. The system will automatically notify the Editor and update the Tag Index.
- **Reject**: Closes the request. **Crucial**: Always provide a reason in the comment box so the Editor knows what to improve.
## 4. System Maintenance (The Registry)
If articles or tags aren't appearing correctly due to manual changes made directly on GitHub.com:
1.  Go to the **Explore** page or the **Home Page**.
2.  Click **"Initialize / Rebuild Registry"**.
3.  This will force the system to re-scan every file and rebuild the search index.
> [!CAUTION]
> Deleting an article is permanent. Ensure you have a backup of the Markdown content if you intend to restore it later.
