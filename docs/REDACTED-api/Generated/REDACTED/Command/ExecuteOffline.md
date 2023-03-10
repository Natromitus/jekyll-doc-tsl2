---
layout: default
title: ExecuteOffline
grand_parent: 
parent: Command
has_children: False
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/Command/ExecuteOffline
---
# Command.ExecuteOffline method

Creates an action that executes HI program (incl. OS) offline commands (i.e without a channel) and stores any return value in the test case context collection under the provided name.

```csharp
public static CommandOffline ExecuteOffline(string commandName, ProgramLocation program, 
    string returnValueName = "returnValue", params object[] parameters)
```

| parameter | description |
| --- | --- |
| commandName | Command name |
| program | Program |
| returnValueName | &gt;The name to use when storing the command return value in the test case context collection (Default: "returnValue") |
| parameters | Command parameters |

## See Also

* class [CommandOffline](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).CommandActions/CommandOfflineType)
* enum [ProgramLocation](../ProgramLocationType)
* class [Command](../CommandType)
* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../CommandType)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->
