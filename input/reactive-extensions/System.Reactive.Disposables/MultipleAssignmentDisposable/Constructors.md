title: Constructors
---
# MultipleAssignmentDisposable Constructor

Initializes a new instance of the [MultipleAssignmentDisposable](MultipleAssignmentDisposable/MultipleAssignmentDisposable) class with no current underlying disposable.

**Namespace:**  [System.Reactive.Disposables](System.Reactive.Disposables/System.Reactive.Disposables)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Sub New
```

```vb
'Usage

Dim instance As New MultipleAssignmentDisposable()
```

```csharp
public MultipleAssignmentDisposable()
```

```c++
public:
MultipleAssignmentDisposable()
```

```fsharp
new : unit -> MultipleAssignmentDisposable
```

```jscript
public function MultipleAssignmentDisposable()
```

## Remarks

By default, the MultipleAssignmentDisposable will dispose the current value of the Disposable property before assigning a new value.

## See Also

#### Reference

[MultipleAssignmentDisposable Class](MultipleAssignmentDisposable/MultipleAssignmentDisposable)

[System.Reactive.Disposables Namespace](System.Reactive.Disposables/System.Reactive.Disposables)
