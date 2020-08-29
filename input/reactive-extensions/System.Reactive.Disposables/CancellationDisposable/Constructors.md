title: Constructors
---
# CancellationDisposable Constructor

Initializes a new instance of the [CancellationDisposable](CancellationDisposable/CancellationDisposable) class.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[CancellationDisposable()](CancellationDisposable/CancellationDisposable)Initializes a new instance of the [CancellationDisposable](CancellationDisposable/CancellationDisposable) class that uses a new CancellationTokenSource.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[CancellationDisposable(CancellationTokenSource)](https://msdn.microsoft.com/en-us/library/m:system.reactive.disposables.cancellationdisposable.#ctor(system.threading.cancellationtokensource)(v=VS.103))Initializes a new instance of the [CancellationDisposable](CancellationDisposable/CancellationDisposable) class that uses an existing CancellationTokenSource.

## See Also

#### Reference

[CancellationDisposable Class](CancellationDisposable/CancellationDisposable)

[System.Reactive.Disposables Namespace](System.Reactive.Disposables/System.Reactive.Disposables)



<br />

# CancellationDisposable()

Initializes a new instance of the [CancellationDisposable](CancellationDisposable/CancellationDisposable) class that uses a new CancellationTokenSource.

**Namespace:**  [System.Reactive.Disposables](System.Reactive.Disposables/System.Reactive.Disposables)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Sub New
```

```vb
'Usage

Dim instance As New CancellationDisposable()
```

```csharp
public CancellationDisposable()
```

```c++
public:
CancellationDisposable()
```

```fsharp
new : unit -> CancellationDisposable
```

```jscript
public function CancellationDisposable()
```

## See Also

#### Reference

[CancellationDisposable Class](CancellationDisposable/CancellationDisposable)

[System.Reactive.Disposables Namespace](System.Reactive.Disposables/System.Reactive.Disposables)



<br />

# CancellationDisposable(CancellationTokenSource)

Initializes a new instance of the [CancellationDisposable](CancellationDisposable/CancellationDisposable) class that uses an existing CancellationTokenSource.

**Namespace:**  [System.Reactive.Disposables](System.Reactive.Disposables/System.Reactive.Disposables)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Sub New ( _
    cts As CancellationTokenSource _
)
```

```vb
'Usage
Dim cts As CancellationTokenSource

Dim instance As New CancellationDisposable(cts)
```

```csharp
public CancellationDisposable(
    CancellationTokenSource cts
)
```

```c++
public:
CancellationDisposable(
    CancellationTokenSource^ cts
)
```

```fsharp
new : 
        cts:CancellationTokenSource -> CancellationDisposable
```

```jscript
public function CancellationDisposable(
    cts : CancellationTokenSource
)
```

#### Parameters

- cts  
  Type: [System.Threading.CancellationTokenSource](https://msdn.microsoft.com/en-us/library/Dd321629)  
  The CancellationTokenSource used for cancellation.

## See Also

#### Reference

[CancellationDisposable Class](CancellationDisposable/CancellationDisposable)

[System.Reactive.Disposables Namespace](System.Reactive.Disposables/System.Reactive.Disposables)
