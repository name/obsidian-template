---
title: Update AD Group Membership
date: 2024-05-03
type: note
---

### Command

```PowerShell
Add-ADGroupMember -Identity "GroupName" -Members "username1", "username2"
```

### Walkthrough

1. Open PowerShell as an administrator.
2. Replace `**"GroupName"**` with the name of the Active Directory group.
3. Replace `**"username1", "username2"**` with the usernames of the accounts you want to add to the group.
4. Execute the command to add the specified users to the group.