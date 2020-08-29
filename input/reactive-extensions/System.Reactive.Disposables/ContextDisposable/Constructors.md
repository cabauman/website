title: Constructors
---
# ContextDisposable Constructor

Initializes a new instance of the [ContextDisposable](ContextDisposable/ContextDisposable) class that uses a SynchronizationContext on which to dispose the disposable.

**Namespace:**  [System.Reactive.Disposables](System.Reactive.Disposables/System.Reactive.Disposables)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Sub New ( _
    context As SynchronizationContext, _
    disposable As IDisposable _
)
```

```vb
'Usage
Dim context As SynchronizationContext
Dim disposable As IDisposable

Dim instance As New ContextDisposable(context, _
    disposable)
```

```csharp
public ContextDisposable(
    SynchronizationContext context,
    IDisposable disposable
)
```

```c++
public:
ContextDisposable(
    SynchronizationContext^ context, 
    IDisposable^ disposable
)
```

```fsharp
new : 
        context:SynchronizationContext * 
        disposable:IDisposable -> ContextDisposable
```

```jscript
public function ContextDisposable(
    context : SynchronizationContext, 
    disposable : IDisposable
)
```

#### Parameters

- context  
  Type: [System.Threading.SynchronizationContext](https://msdn.microsoft.com/en-us/library/wx31754f)  
  The context to perform disposal on.

- disposable  
  Type: [System.IDisposable](https://msdn.microsoft.com/en-us/library/aax125c9)  
  The disposable whose Dispose operation to run on the given synchronization context.

## See Also

#### Reference

[ContextDisposable Class](ContextDisposable/ContextDisposable)

[System.Reactive.Disposables Namespace](System.Reactive.Disposables/System.Reactive.Disposables)
