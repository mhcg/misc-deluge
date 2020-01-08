# Deluge (Zoho) Scripts

## convertSnakeCaseToCamelCase.dg

Does what it says on the tin, coverts something like 'this_is_me' to 'ThisIsMe'.

## globalVars.dg

Contains two functions: `getGlobalVarValue` and `setGlobalVarValue`.  Wrapper funtions to get and set records from/to GlobalVars form.  Therefore needs a GlobalVars form creating with at least two fields, one called `VarName` the other called `VarValue`, both strings.
