---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.Mail

# A UPN can also be used as -UserId.
Get-MgUserMessage -UserId $userId -Filter "MentionsPreview/IsMentioned eq true" -Property "Subject,Sender,ReceivedDateTime,MentionsPreview"  -OutFile $outFileId

```