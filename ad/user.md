```markdown
---
title: AD User Report
---

# AD User Report Script

```powershell
Get-ADUser -Filter * |
Select Name, Enabled
