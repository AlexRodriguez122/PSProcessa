---
external help file: PSProcessa-help.xml
online version: 
schema: 2.0.0
---

# Get-AppSettingSection

## SYNOPSIS
Obtiene los valores de la sección AppSettings de un archivo de configuración.

## SYNTAX

```
Get-AppSettingSection [-Path] <String>
```

## DESCRIPTION
Obtiene un diccionario Clave/Valor con el contenido de la sección AppSettings de un archivo de configuración.

## EXAMPLES

### -------------------------- EXAMPLE 1 --------------------------
```
Get-AppSettingSection -Path 'C:\MyConfig.config'
```

### -------------------------- EXAMPLE 2 --------------------------
```
'C:\MyConfig.config' | Get-AppSettingSection
```

## PARAMETERS

### -Path
Ruta de acceso del archivo de configuración.

```yaml
Type: String
Parameter Sets: (All)
Aliases: ConfigFile

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

## INPUTS

### Puede canalizar el valor de Path.

## OUTPUTS

### Diccionario Clave/Valor con el contenido de la sección AppSettings de un archivo de configuración.

## NOTES
Autor: Atorres

## RELATED LINKS

[[Get-AppSetting](Get-AppSetting.md)]()
