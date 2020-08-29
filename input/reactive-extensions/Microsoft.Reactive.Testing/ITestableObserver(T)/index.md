title: ITestableObserver<T>
---
# ITestableObserver\<T\> Interface

Defines an observer that records received notifications.

**Namespace:**  [Microsoft.Reactive.Testing](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)  
**Assembly:**  Microsoft.Reactive.Testing (in Microsoft.Reactive.Testing.dll)

## Syntax

```vb
'Declaration
Public Interface ITestableObserver(Of T) _
    Inherits IObserver(Of T)
```

```vb
'Usage
Dim instance As ITestableObserver(Of T)
```

```csharp
public interface ITestableObserver<T> : IObserver<T>
```

```c++
generic<typename T>
public interface class ITestableObserver : IObserver<T>
```

```fsharp
type ITestableObserver<'T> =  
    interface
        interface IObserver<'T>
    end
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- T

The ITestableObserver<T> type exposes the following members.

## Properties

NameDescription![Public property](https://reactiveui.net/assets/img/Hh315336.pubevent(en-us,VS.103).gif "Public event")[Messages](OnNext/IEventSource(T).OnNext)Gets the recorded notifications received by the observer.

## Methods

NameDescription![Public method](https://reactiveui.net/assets/img/Hh315336.pubevent(en-us,VS.103).gif "Public event")[OnCompleted](OnNext/IEventSource(T).OnNext)(Inherited from IObserver<T>.)[Public method](https://reactiveui.net/assets/img/Hh315336.pubevent(en-us,VS.103).gif "Public event")[OnError](OnNext/IEventSource(T).OnNext)(Inherited from IObserver<T>.)[Public method](https://reactiveui.net/assets/img/Hh315336.pubevent(en-us,VS.103).gif "Public event")[OnNext](OnNext/IEventSource(T).OnNext)(Inherited from IObserver<T>.)

## Extension Methods

NameDescription![Public method](https://reactiveui.net/assets/img/Hh315336.pubevent(en-us,VS.103).gif "Public event")[AsObserver<T>](OnNext/IEventSource(T).OnNext)(Defined by Observer.)[Public method](https://reactiveui.net/assets/img/Hh315336.pubevent(en-us,VS.103).gif "Public event")[ToNotifier<T>](OnNext/IEventSource(T).OnNext)(Defined by Observer.)

## See Also

#### Reference

[Microsoft.Reactive.Testing Namespace](Microsoft.Reactive.Testing/Microsoft.Reactive.Testing)
