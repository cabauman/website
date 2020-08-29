title: Constructors
---
# DispatcherScheduler Constructor

Constructs an DispatcherScheduler that schedules units of work on dispatcher.

**Namespace:**  [System.Reactive.Concurrency](System.Reactive.Concurrency/System.Reactive.Concurrency)  
**Assembly:**  System.Reactive.Windows.Threading (in System.Reactive.Windows.Threading.dll)

## Syntax

```vb
'Declaration
Public Sub New ( _
    dispatcher As Dispatcher _
)
```

```vb
'Usage
Dim dispatcher As Dispatcher

Dim instance As New DispatcherScheduler(dispatcher)
```

```csharp
public DispatcherScheduler(
    Dispatcher dispatcher
)
```

```c++
public:
DispatcherScheduler(
    Dispatcher^ dispatcher
)
```

```fsharp
new : 
        dispatcher:Dispatcher -> DispatcherScheduler
```

```jscript
public function DispatcherScheduler(
    dispatcher : Dispatcher
)
```

#### Parameters

- dispatcher  
  Type: [System.Windows.Threading.Dispatcher](https://msdn.microsoft.com/en-us/library/ms615907)  
  The dispatcher to schedule work on.

## See Also

#### Reference

[DispatcherScheduler Class](DispatcherScheduler/DispatcherScheduler)

[System.Reactive.Concurrency Namespace](System.Reactive.Concurrency/System.Reactive.Concurrency)
