title: Constructors
---
# CompositeDisposable Constructors

Initializes a new instance of the [CompositeDisposable](CompositeDisposable/CompositeDisposable) class.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[CompositeDisposable()](CompositeDisposable/CompositeDisposable)Initializes a new instance of the [CompositeDisposable](CompositeDisposable/CompositeDisposable) class from a group of disposables.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[CompositeDisposable(IEnumerable<IDisposable>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.disposables.compositedisposable.#ctor(system.collections.generic.ienumerable%7bsystem.idisposable%7d)(v=VS.103))Initializes a new instance of the [CompositeDisposable](CompositeDisposable/CompositeDisposable) class from a group of disposables.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[CompositeDisposable(array<IDisposable[])](https://msdn.microsoft.com/en-us/library/m:system.reactive.disposables.compositedisposable.#ctor(system.idisposable%5b%5d)(v=VS.103))Initializes a new instance of the [CompositeDisposable](CompositeDisposable/CompositeDisposable) class from a group of disposables.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[CompositeDisposable(Int32)](https://msdn.microsoft.com/en-us/library/m:system.reactive.disposables.compositedisposable.#ctor(system.int32)(v=VS.103))Initializes a new instance of the [CompositeDisposable](CompositeDisposable/CompositeDisposable) class with the specified number of disposables.Top

## See Also

#### Reference

[CompositeDisposable Class](CompositeDisposable/CompositeDisposable)

[System.Reactive.Disposables Namespace](System.Reactive.Disposables/System.Reactive.Disposables)



<br />

# CompositeDisposable()

Initializes a new instance of the [CompositeDisposable](CompositeDisposable/CompositeDisposable) class from a group of disposables.

**Namespace:**  [System.Reactive.Disposables](System.Reactive.Disposables/System.Reactive.Disposables)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Sub New
```

```vb
'Usage

Dim instance As New CompositeDisposable()
```

```csharp
public CompositeDisposable()
```

```c++
public:
CompositeDisposable()
```

```fsharp
new : unit -> CompositeDisposable
```

```jscript
public function CompositeDisposable()
```

## See Also

#### Reference

[CompositeDisposable Class](CompositeDisposable/CompositeDisposable)

[System.Reactive.Disposables Namespace](System.Reactive.Disposables/System.Reactive.Disposables)



<br />

# CompositeDisposable(IEnumerable\<IDisposable\>)

Initializes a new instance of the [CompositeDisposable](CompositeDisposable/CompositeDisposable) class from a group of disposables.

**Namespace:**  [System.Reactive.Disposables](System.Reactive.Disposables/System.Reactive.Disposables)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Sub New ( _
    disposables As IEnumerable(Of IDisposable) _
)
```

```vb
'Usage
Dim disposables As IEnumerable(Of IDisposable)

Dim instance As New CompositeDisposable(disposables)
```

```csharp
public CompositeDisposable(
    IEnumerable<IDisposable> disposables
)
```

```c++
public:
CompositeDisposable(
    IEnumerable<IDisposable^>^ disposables
)
```

```fsharp
new : 
        disposables:IEnumerable<IDisposable> -> CompositeDisposable
```

```jscript
public function CompositeDisposable(
    disposables : IEnumerable<IDisposable>
)
```

#### Parameters

- disposables  
  Type: [System.Collections.Generic.IEnumerable](https://msdn.microsoft.com/en-us/library/9eekhta0)\<[IDisposable](https://msdn.microsoft.com/en-us/library/aax125c9)\>  
  The disposables that will be disposed together.

## See Also

#### Reference

[CompositeDisposable Class](CompositeDisposable/CompositeDisposable)

[System.Reactive.Disposables Namespace](System.Reactive.Disposables/System.Reactive.Disposables)



<br />

# CompositeDisposable(Int32)

Initializes a new instance of the [CompositeDisposable](CompositeDisposable/CompositeDisposable) class with the specified number of disposables.

**Namespace:**  [System.Reactive.Disposables](System.Reactive.Disposables/System.Reactive.Disposables)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Sub New ( _
    capacity As Integer _
)
```

```vb
'Usage
Dim capacity As Integer

Dim instance As New CompositeDisposable(capacity)
```

```csharp
public CompositeDisposable(
    int capacity
)
```

```c++
public:
CompositeDisposable(
    int capacity
)
```

```fsharp
new : 
        capacity:int -> CompositeDisposable
```

```jscript
public function CompositeDisposable(
    capacity : int
)
```

#### Parameters

- capacity  
  Type: [System.Int32](https://msdn.microsoft.com/en-us/library/td2s409d)  
  The number of disposables that the new CompositeDisposable can initially store.

## See Also

#### Reference

[CompositeDisposable Class](CompositeDisposable/CompositeDisposable)

[System.Reactive.Disposables Namespace](System.Reactive.Disposables/System.Reactive.Disposables)



<br />

# CompositeDisposable(array\<IDisposable\[\])

Initializes a new instance of the [CompositeDisposable](CompositeDisposable/CompositeDisposable) class from a group of disposables.

**Namespace:**  [System.Reactive.Disposables](System.Reactive.Disposables/System.Reactive.Disposables)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Sub New ( _
    ParamArray disposables As IDisposable() _
)
```

```vb
'Usage
Dim disposables As IDisposable()

Dim instance As New CompositeDisposable(disposables)
```

```csharp
public CompositeDisposable(
    params IDisposable[] disposables
)
```

```c++
public:
CompositeDisposable(
    ... array<IDisposable^>^ disposables
)
```

```fsharp
new : 
        disposables:IDisposable[] -> CompositeDisposable
```

```jscript
public function CompositeDisposable(
    ... disposables : IDisposable[]
)
```

#### Parameters

- disposables  
  Type: array\<[System.IDisposable](https://msdn.microsoft.com/en-us/library/aax125c9)\[\]  
  The disposables that will be disposed together.

## See Also

#### Reference

[CompositeDisposable Class](CompositeDisposable/CompositeDisposable)

[System.Reactive.Disposables Namespace](System.Reactive.Disposables/System.Reactive.Disposables)
