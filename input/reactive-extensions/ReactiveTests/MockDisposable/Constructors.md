title: Constructors
---
# MockDisposable Constructor

**Namespace:**  [ReactiveTests](ReactiveTests/ReactiveTests)  
**Assembly:**  Tests.System.Reactive (in Tests.System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Sub New ( _
    scheduler As TestScheduler _
)
```

```vb
'Usage
Dim scheduler As TestScheduler

Dim instance As New MockDisposable(scheduler)
```

```csharp
public MockDisposable(
    TestScheduler scheduler
)
```

```c++
public:
MockDisposable(
    TestScheduler^ scheduler
)
```

```fsharp
new : 
        scheduler:TestScheduler -> MockDisposable
```

```jscript
public function MockDisposable(
    scheduler : TestScheduler
)
```

#### Parameters

- scheduler  
  Type: [Microsoft.Reactive.Testing.TestScheduler](TestScheduler/TestScheduler)

## See Also

#### Reference

[MockDisposable Class](MockDisposable/MockDisposable)

[ReactiveTests Namespace](ReactiveTests/ReactiveTests)
