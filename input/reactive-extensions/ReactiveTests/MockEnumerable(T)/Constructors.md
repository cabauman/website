title: Constructors
---
# MockEnumerable\<T\> Constructor

**Namespace:**  [ReactiveTests](ReactiveTests/ReactiveTests)  
**Assembly:**  Tests.System.Reactive (in Tests.System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Sub New ( _
    scheduler As TestScheduler, _
    underlyingEnumerable As IEnumerable(Of T) _
)
```

```vb
'Usage
Dim scheduler As TestScheduler
Dim underlyingEnumerable As IEnumerable(Of T)

Dim instance As New MockEnumerable(scheduler, _
    underlyingEnumerable)
```

```csharp
public MockEnumerable(
    TestScheduler scheduler,
    IEnumerable<T> underlyingEnumerable
)
```

```c++
public:
MockEnumerable(
    TestScheduler^ scheduler, 
    IEnumerable<T>^ underlyingEnumerable
)
```

```fsharp
new : 
        scheduler:TestScheduler * 
        underlyingEnumerable:IEnumerable<'T> -> MockEnumerable
```

```jscript
public function MockEnumerable(
    scheduler : TestScheduler, 
    underlyingEnumerable : IEnumerable<T>
)
```

#### Parameters

- scheduler  
  Type: [Microsoft.Reactive.Testing.TestScheduler](TestScheduler/TestScheduler)

- underlyingEnumerable  
  Type: [System.Collections.Generic.IEnumerable](https://msdn.microsoft.com/en-us/library/9eekhta0)\<[T](MockEnumerable/MockEnumerable(T))\>

## See Also

#### Reference

[MockEnumerable\<T\> Class](MockEnumerable/MockEnumerable(T))

[ReactiveTests Namespace](ReactiveTests/ReactiveTests)
