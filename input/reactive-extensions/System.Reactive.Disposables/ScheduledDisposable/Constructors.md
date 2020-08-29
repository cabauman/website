title: Constructors
---
# ScheduledDisposable Constructor

Initializes a new instance of the [ScheduledDisposable](ScheduledDisposable/ScheduledDisposable) class that uses a scheduler on which to dispose the disposable.

**Namespace:**  [System.Reactive.Disposables](System.Reactive.Disposables/System.Reactive.Disposables)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Sub New ( _
    scheduler As IScheduler, _
    disposable As IDisposable _
)
```

```vb
'Usage
Dim scheduler As IScheduler
Dim disposable As IDisposable

Dim instance As New ScheduledDisposable(scheduler, _
    disposable)
```

```csharp
public ScheduledDisposable(
    IScheduler scheduler,
    IDisposable disposable
)
```

```c++
public:
ScheduledDisposable(
    IScheduler^ scheduler, 
    IDisposable^ disposable
)
```

```fsharp
new : 
        scheduler:IScheduler * 
        disposable:IDisposable -> ScheduledDisposable
```

```jscript
public function ScheduledDisposable(
    scheduler : IScheduler, 
    disposable : IDisposable
)
```

#### Parameters

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The specified scheduler.

- disposable  
  Type: [System.IDisposable](https://msdn.microsoft.com/en-us/library/aax125c9)  
  The underlying disposable.

## See Also

#### Reference

[ScheduledDisposable Class](ScheduledDisposable/ScheduledDisposable)

[System.Reactive.Disposables Namespace](System.Reactive.Disposables/System.Reactive.Disposables)
