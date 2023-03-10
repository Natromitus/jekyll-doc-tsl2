---
layout: default
title: WriteToMemory
grand_parent: 
parent: Command
has_children: False
permalink: /(REDACTED_FRAMEWORK)-api/(REDACTED).(REDACTED_OTHER_FRAMEWORK)/Command/WriteToMemory
---
# Command.WriteToMemory&lt;T&gt; method

Action that writes to the memory space through Channel.

```csharp
public static WriteToMemory<T> WriteToMemory<T>(MemorySpace memorySpace, int address, 
    T[] desiredValue, int offset = 0)
    where T : struct
```

| parameter | description |
| --- | --- |
| memorySpace | The FW memory space |
| address | The address |
| desiredValue | The desired value to write (only supported types are byte[], short[], int[] and long[], use types based on memory space) |
| offset | The number of values to offset by before writing |

## See Also

* class [WriteToMemory&lt;T&gt;](../../(REDACTED).(REDACTED_OTHER_FRAMEWORK).CommandActions/WriteToMemory-1Type)
* enum [MemorySpace](../MemorySpaceType)
* class [Command](../CommandType)
* namespace [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../CommandType)
* assembly [(REDACTED).(REDACTED_OTHER_FRAMEWORK)](../../ReSoundSETTestwareTestCaseActionsRatatoskAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for (REDACTED).(REDACTED_OTHER_FRAMEWORK).dll -->
