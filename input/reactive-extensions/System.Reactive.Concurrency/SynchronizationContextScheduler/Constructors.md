title: Constructors
---
# SynchronizationContextScheduler Constructor

Creates an object that schedules units of work on the provided SynchronizationContext.

**Namespace:**  [System.Reactive.Concurrency](System.Reactive.Concurrency/System.Reactive.Concurrency)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Sub New ( _
    context As SynchronizationContext _
)
```

```vb
'Usage
Dim context As SynchronizationContext

Dim instance As New SynchronizationContextScheduler(context)
```

```csharp
public SynchronizationContextScheduler(
    SynchronizationContext context
)
```

```c++
public:
SynchronizationContextScheduler(
    SynchronizationContext^ context
)
```

```fsharp
new : 
        context:SynchronizationContext -> SynchronizationContextScheduler
```

```jscript
public function SynchronizationContextScheduler(
    context : SynchronizationContext
)
```

#### Parameters

- context  
  Type: [System.Threading.SynchronizationContext](https://msdn.microsoft.com/en-us/library/wx31754f)  
  The synchronization context to schedule units of work on.

## See Also

#### Reference

[SynchronizationContextScheduler Class](SynchronizationContextScheduler/SynchronizationContextScheduler)

[System.Reactive.Concurrency Namespace](System.Reactive.Concurrency/System.Reactive.Concurrency)
