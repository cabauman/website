title: Constructors
---
# RefCountDisposable Constructor

Initializes a new instance of the [RefCountDisposable](RefCountDisposable/RefCountDisposable) class with the specified disposable.

**Namespace:**  [System.Reactive.Disposables](System.Reactive.Disposables/System.Reactive.Disposables)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Sub New ( _
    disposable As IDisposable _
)
```

```vb
'Usage
Dim disposable As IDisposable

Dim instance As New RefCountDisposable(disposable)
```

```csharp
public RefCountDisposable(
    IDisposable disposable
)
```

```c++
public:
RefCountDisposable(
    IDisposable^ disposable
)
```

```fsharp
new : 
        disposable:IDisposable -> RefCountDisposable
```

```jscript
public function RefCountDisposable(
    disposable : IDisposable
)
```

#### Parameters

- disposable  
  Type: [System.IDisposable](https://msdn.microsoft.com/en-us/library/aax125c9)  
  The underlying disposable.

## See Also

#### Reference

[RefCountDisposable Class](RefCountDisposable/RefCountDisposable)

[System.Reactive.Disposables Namespace](System.Reactive.Disposables/System.Reactive.Disposables)
