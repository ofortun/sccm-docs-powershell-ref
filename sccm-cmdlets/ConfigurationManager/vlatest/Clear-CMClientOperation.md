---
external help file: AdminUI.PS.ClientOperations.dll-Help.xml
online version: https://go.microsoft.com/fwlink/?linkid=833835
schema: 2.0.0
ms.assetid: DFCB60F1-211A-46E1-8E16-A494AC4DCCA6
---

# Clear-CMClientOperation

## SYNOPSIS
Clears a Configuration Manager client operation object.

## SYNTAX

### ByValue (Default)
```
Clear-CMClientOperation -ClientOperation <IResultObject> [-DisableWildcardHandling] [-ForceWildcardHandling]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### ById
```
Clear-CMClientOperation -Id <String> [-DisableWildcardHandling] [-ForceWildcardHandling] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
The **Clear-CMClientOperation** cmdlet clears a Microsoft System Center Configuration Manager client operation object.
Specify the operation to clear by using its ID.

You can use the Remove-CMClientOperation cmdlet to remove a client operation object.

## EXAMPLES

### Example 1: Clear a client operation
```
PS C:\>Clear-CMClientOperation -Id "CMCO217"
```

This command clears the client operation that has the ID CMCO217.

## PARAMETERS

### -ClientOperation


```yaml
Type: IResultObject
Parameter Sets: ByValue
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisableWildcardHandling
Indicates that wildcard handling is disabled.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ForceWildcardHandling
Indicates that wildcard handling is enabled.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id


```yaml
Type: String
Parameter Sets: ById
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Remove-CMClientOperation](./Remove-CMClientOperation.md)

[Invoke-CMClientOperationSummarization](./Invoke-CMClientOperationSummarization.md)

