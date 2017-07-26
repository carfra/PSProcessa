---
external help file: PSProcessa-help.xml
online version: 
schema: 2.0.0
---

# Out-Custom

## SYNOPSIS
Envía la salida al formateador predeterminado anexando información de la hora de ejecución.

## SYNTAX

```
Out-Custom [[-InputObject] <String>] [[-Type] <String>] [[-FormatTime] <String>] [[-NewLine] <Boolean>]
```

## DESCRIPTION
{{Fill in the Description}}

## EXAMPLES

### -------------------------- EXAMPLE 1 --------------------------
```
'Hola Mundo'| Out-Custom
```

### -------------------------- EXAMPLE 2 --------------------------
```
'Hola Mundo'| Out-Custom -NewLine $false
```

### -------------------------- EXAMPLE 3 --------------------------
```
Get-Variable | Out-String | Out-Custom -Type Info
```

## PARAMETERS

### -InputObject
Objeto que se quiere enviar al formateador predeterminado.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 1
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Type
Tipo de mensaje que se envia.
Valor predeterminado 'Info'

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 2
Default value: Info
Accept pipeline input: False
Accept wildcard characters: False
```

### -FormatTime
Formato que se debe aplicar a la hora antes de enviarla al formateador predeterminado.
Valor predeterminado 'HH:mm:ss tt'

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 3
Default value: HH:mm:ss tt
Accept pipeline input: False
Accept wildcard characters: False
```

### -NewLine
Cuando se estabece, se agrega un retorno de carro entre la hora y el objeto en InputObject.
Valor predeterminado $true.

```yaml
Type: Boolean
Parameter Sets: (All)
Aliases: 

Required: False
Position: 4
Default value: True
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

### System.Void

## NOTES
Autor: Atorres

## RELATED LINKS
