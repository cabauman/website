title: ITestableObservable<T>
---
# ITestableObservable\<T\> Interface

Defines an observable that records subscriptions and notifications sent by the observable.

**Namespace:**  [Microsoft.Reactive.Testing](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)  
**Assembly:**  Microsoft.Reactive.Testing (in Microsoft.Reactive.Testing.dll)

## Syntax

```vb
'Declaration
Public Interface ITestableObservable(Of T) _
    Inherits IObservable(Of T)
```

```vb
'Usage
Dim instance As ITestableObservable(Of T)
```

```csharp
public interface ITestableObservable<T> : IObservable<T>
```

```c++
generic<typename T>
public interface class ITestableObservable : IObservable<T>
```

```fsharp
type ITestableObservable<'T> =  
    interface
        interface IObservable<'T>
    end
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- T

The ITestableObservable\<T\> type exposes the following members.

## Properties

NameDescription![Public event](https://reactiveui.net/assets/img/Hh315336.pubevent(en-us,VS.103).gif "Public event")[Messages](OnNext/IEventSource(T).OnNext)Gets the recorded notifications sent by the observable.[Public property](https://reactiveui.net/assets/img/Hh315336.pubevent(en-us,VS.103).gif "Public property")[Subscriptions](OnNext/IEventSource(T).OnNext)Gets the subscriptions to the observable.

## Methods

NameDescription![Public method](https://reactiveui.net/assets/img/Hh315336.pubevent(en-us,VS.103).gif "Public event")[Subscribe](OnNext/IEventSource(T).OnNext)(Inherited from IObservable<T>.)

## See Also

#### Reference

[Microsoft.Reactive.Testing Namespace](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)
