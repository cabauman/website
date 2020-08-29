title: CancellationDisposable
---
# CancellationDisposable Class

Represents an IDisposable that can be checked for cancellation status.

## Inheritance Hierarchy

[System.Object](https://msdn.microsoft.com/en-us/library/e5kfa45b)  
  System.Reactive.Disposables.CancellationDisposable

**Namespace:**  [System.Reactive.Disposables](System.Reactive.Disposables/System.Reactive.Disposables)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public NotInheritable Class CancellationDisposable _
    Implements IDisposable
```

```vb
'Usage
Dim instance As CancellationDisposable
```

```csharp
public sealed class CancellationDisposable : IDisposable
```

```c++
public ref class CancellationDisposable sealed : IDisposable
```

```fsharp
[<SealedAttribute>]
type CancellationDisposable =  
    class
        interface IDisposable
    end
```

```jscript
public final class CancellationDisposable implements IDisposable
```

The CancellationDisposable type exposes the following members.

## Constructors

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[CancellationDisposable()](CancellationDisposable/CancellationDisposable)Initializes a new instance of the CancellationDisposable class that uses a new CancellationTokenSource.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[CancellationDisposable(CancellationTokenSource)](https://msdn.microsoft.com/en-us/library/m:system.reactive.disposables.cancellationdisposable.#ctor(system.threading.cancellationtokensource)(v=VS.103))Initializes a new instance of the CancellationDisposable class that uses an existing CancellationTokenSource.Top

## Properties

NameDescription![Public property](https://reactiveui.net/assets/img/Hh211972.pubproperty(en-us,VS.103).gif "Public property")[IsDisposed](IsDisposed/CancellationDisposable.IsDisposed)Gets a value that indicates whether the object is disposed.![Public property](https://reactiveui.net/assets/img/Hh211972.pubproperty(en-us,VS.103).gif "Public property")[Token](Token/CancellationDisposable.Token)Gets the CancellationToken used by this CancellationDisposable.Top

## Methods

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[Dispose](Dispose/CancellationDisposable.Dispose)Cancels the CancellationTokenSource.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[Equals](https://msdn.microsoft.com/en-us/library/m:system.object.equals(system.object)(v=VS.103))(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Protected method](https://reactiveui.net/assets/img/Hh303103.protmethod(en-us,VS.103).gif "Protected method")[Finalize](https://msdn.microsoft.com/en-us/library/4k87zsw7)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[GetHashCode](https://msdn.microsoft.com/en-us/library/zdee4b3y)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[GetType](https://msdn.microsoft.com/en-us/library/dfwy45w9)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Protected method](https://reactiveui.net/assets/img/Hh303103.protmethod(en-us,VS.103).gif "Protected method")[MemberwiseClone](https://msdn.microsoft.com/en-us/library/57ctke0a)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[ToString](https://msdn.microsoft.com/en-us/library/7bxwbwt2)(Inherited from [Object](https://msdn.microsoft.com/en-us/library/e5kfa45b).)Top

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[System.Reactive.Disposables Namespace](System.Reactive.Disposables/System.Reactive.Disposables)
