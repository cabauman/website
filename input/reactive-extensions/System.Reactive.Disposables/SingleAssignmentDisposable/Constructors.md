title: Constructors
---
# SingleAssignmentDisposable Constructor

Initializes a new instance if the [SingleAssignmentDisposable](SingleAssignmentDisposable/SingleAssignmentDisposable) class.

**Namespace:**  [System.Reactive.Disposables](System.Reactive.Disposables/System.Reactive.Disposables)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Sub New
```

```vb
'Usage

Dim instance As New SingleAssignmentDisposable()
```

```csharp
public SingleAssignmentDisposable()
```

```c++
public:
SingleAssignmentDisposable()
```

```fsharp
new : unit -> SingleAssignmentDisposable
```

```jscript
public function SingleAssignmentDisposable()
```

## Remarks

A SingleAssignmentDisposable only allows a single assignment of its disposable object. If it has already been assigned, attempts to set the underlying object will throw an InvalidOperationException.

## See Also

#### Reference

[SingleAssignmentDisposable Class](SingleAssignmentDisposable/SingleAssignmentDisposable)

[System.Reactive.Disposables Namespace](System.Reactive.Disposables/System.Reactive.Disposables)
