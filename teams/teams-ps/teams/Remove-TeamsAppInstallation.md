---
external help file: Microsoft.TeamsCmdlets.PowerShell.Custom.dll-Help.xml
Module Name: MicrosoftTeams
online version: https://learn.microsoft.com/powershell/module/teams/remove-teamsappinstallation
title: Remove-TeamsAppInstallation
schema: 2.0.0
author: serdarsoysal
ms.author: serdars
ms.reviewer:
---

# Remove-TeamsAppInstallation

## SYNOPSIS
Removes a Teams App installed in Microsoft Teams.

## SYNTAX

### TeamScope
```
Remove-TeamsAppInstallation [-AppInstallationId <String>] [-AppId <String>] -TeamId <String>
 [<CommonParameters>]
```

### UserScope
```
Remove-TeamsAppInstallation [-AppInstallationId <String>] [-AppId <String>] -UserId <String>
 [<CommonParameters>]
```

## DESCRIPTION
Removes a Teams App installed in Microsoft Teams.

Note: This cmdlet is part of the Public Preview version of Teams PowerShell Module, for more information see [Install Teams PowerShell public preview](https://learn.microsoft.com/microsoftteams/teams-powershell-install#install-teams-powershell-public-preview) and also see [Microsoft Teams PowerShell Release Notes](https://learn.microsoft.com/microsoftteams/teams-powershell-release-notes).

## EXAMPLES

### Example 1
```powershell
PS C:\> Remove-TeamsAppInstallation -AppId b9cc7986-dd56-4b57-ab7d-9c4e5288b775 -TeamId 31f1ff6c-d48c-4f8a-b2e1-abca7fd399df
```

This example removes a Teams App in Microsoft Teams specifying its AppId and TeamId.

## PARAMETERS

### -AppId
Teams App identifier in Microsoft Teams.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -AppInstallationId
Installation identifier of the Teams App.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -TeamId
Team identifier in Microsoft Teams.

```yaml
Type: String
Parameter Sets: TeamScope
Aliases: GroupId

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -UserId
User identifier in Microsoft Teams.

```yaml
Type: String
Parameter Sets: UserScope
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### System.String

## OUTPUTS

### System.Object

## NOTES

## RELATED LINKS
