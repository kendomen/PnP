#Enable-SPOFeature
*Topic automatically generated on: 2015-04-02*

Enables a feature
##Syntax
```powershell
Enable-SPOFeature [-Force [<SwitchParameter>]] [-Scope [<FeatureScope>]] -Identity [<GuidPipeBind>]
```
&nbsp;

##Parameters
Parameter|Type|Required|Description
---------|----|--------|-----------
Force|SwitchParameter|False|Forcibly enable the feature.
Identity|GuidPipeBind|True|The id of the feature to enable.
Scope|FeatureScope|False|
##Examples

###Example 1
    PS:> Enable-SPOFeature -Identity 99a00f6e-fb81-4dc7-8eac-e09c6f9132fe -Scope Web


###Example 2
    PS:> Enable-SPOFeature -Identity 99a00f6e-fb81-4dc7-8eac-e09c6f9132fe


###Example 3
    PS:> Enable-SPOFeature -Identity 99a00f6e-fb81-4dc7-8eac-e09c6f9132fe -Force

