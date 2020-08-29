title: Accept
---
# Notification\<T\>.Accept Method

Invokes the delegate corresponding to the notification.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[Accept(IObserver<T>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.notification%601.accept(system.iobserver%7b%600%7d)(v=VS.103))Invokes the observer's method corresponding to the notification.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[Accept(Action<T>, Action<Exception>, Action)](https://msdn.microsoft.com/en-us/library/m:system.reactive.notification%601.accept(system.action%7b%600%7d%2csystem.action%7bsystem.exception%7d%2csystem.action)(v=VS.103))Invokes the delegate corresponding to the notification.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")[Accept<TResult>(Func<T, TResult>, Func<Exception, TResult>, Func<TResult>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.notification%601.accept%60%601(system.func%7b%600%2c%60%600%7d%2csystem.func%7bsystem.exception%2c%60%600%7d%2csystem.func%7b%60%600%7d)(v=VS.103))Invokes the delegate corresponding to the notification and returns the produced result.Top

## See Also

#### Reference

[Notification\<T\> Class](Notification/Notification(T))

[System.Reactive Namespace](System.Reactive/System.Reactive)



<br />

# Accept(IObserver\<T\>)

Invokes the observer's method corresponding to the notification.

**Namespace:**  [System.Reactive](System.Reactive/System.Reactive)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public MustOverride Sub Accept ( _
    observer As IObserver(Of T) _
)
```

```vb
'Usage
Dim instance As Notification
Dim observer As IObserver(Of T)

instance.Accept(observer)
```

```csharp
public abstract void Accept(
    IObserver<T> observer
)
```

```c++
public:
virtual void Accept(
    IObserver<T>^ observer
) abstract
```

```fsharp
abstract Accept : 
        observer:IObserver<'T> -> unit 
```

```jscript
public abstract function Accept(
    observer : IObserver<T>
)
```

#### Parameters

- observer  
  Type: [System.IObserver](https://msdn.microsoft.com/en-us/library/Dd783449)\<[T](Notification/Notification(T))\>  
  The observer to invoke the notification on.

## See Also

#### Reference

[Notification\<T\> Class](Notification/Notification(T))

[System.Reactive Namespace](System.Reactive/System.Reactive)



<br />

# Accept(Action\<T\>, Action\<Exception\>, Action)

Invokes the delegate corresponding to the notification.

**Namespace:**  [System.Reactive](System.Reactive/System.Reactive)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public MustOverride Sub Accept ( _
    onNext As Action(Of T), _
    onError As Action(Of Exception), _
    onCompleted As Action _
)
```

```vb
'Usage
Dim instance As Notification
Dim onNext As Action(Of T)
Dim onError As Action(Of Exception)
Dim onCompleted As Action

instance.Accept(onNext, onError, onCompleted)
```

```csharp
public abstract void Accept(
    Action<T> onNext,
    Action<Exception> onError,
    Action onCompleted
)
```

```c++
public:
virtual void Accept(
    Action<T>^ onNext, 
    Action<Exception^>^ onError, 
    Action^ onCompleted
) abstract
```

```fsharp
abstract Accept : 
        onNext:Action<'T> * 
        onError:Action<Exception> * 
        onCompleted:Action -> unit 
```

```jscript
public abstract function Accept(
    onNext : Action<T>, 
    onError : Action<Exception>, 
    onCompleted : Action
)
```

#### Parameters

- onNext  
  Type: [System.Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<[T](Notification/Notification(T))\>  
  The delegate to invoke for an OnNext notification.

- onError  
  Type: [System.Action](https://msdn.microsoft.com/en-us/library/018hxwa8)\<[Exception](https://msdn.microsoft.com/en-us/library/c18k6c59)\>  
  The delegate to invoke for an OnError notification.

- onCompleted  
  Type: [System.Action](https://msdn.microsoft.com/en-us/library/Bb534741)  
  The delegate to invoke for an OnCompleted notification.

## See Also

#### Reference

[Notification\<T\> Class](Notification/Notification(T))

[System.Reactive Namespace](System.Reactive/System.Reactive)



<br />

# Accept\<TResult\>(Func\<T, TResult\>, Func\<Exception, TResult\>, Func\<TResult\>)

Invokes the delegate corresponding to the notification and returns the produced result.

**Namespace:**  [System.Reactive](System.Reactive/System.Reactive)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public MustOverride Function Accept(Of TResult) ( _
    onNext As Func(Of T, TResult), _
    onError As Func(Of Exception, TResult), _
    onCompleted As Func(Of TResult) _
) As TResult
```

```vb
'Usage
Dim instance As Notification
Dim onNext As Func(Of T, TResult)
Dim onError As Func(Of Exception, TResult)
Dim onCompleted As Func(Of TResult)
Dim returnValue As TResult

returnValue = instance.Accept(onNext, _
    onError, onCompleted)
```

```csharp
public abstract TResult Accept<TResult>(
    Func<T, TResult> onNext,
    Func<Exception, TResult> onError,
    Func<TResult> onCompleted
)
```

```c++
public:
generic<typename TResult>
virtual TResult Accept(
    Func<T, TResult>^ onNext, 
    Func<Exception^, TResult>^ onError, 
    Func<TResult>^ onCompleted
) abstract
```

```fsharp
abstract Accept : 
        onNext:Func<'T, 'TResult> * 
        onError:Func<Exception, 'TResult> * 
        onCompleted:Func<'TResult> -> 'TResult 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TResult  
  The result argument type.

#### Parameters

- onNext  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<[T](Notification/Notification(T)), TResult\>  
  The delegate to invoke for an OnNext notification.

- onError  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<[Exception](https://msdn.microsoft.com/en-us/library/c18k6c59), TResult\>  
  The delegate to invoke for an OnError notification.

- onCompleted  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb534960)\<TResult\>  
  The delegate to invoke for an OnCompleted notification.

#### Return Value

Type: TResult  
The result produced by the observation..

## See Also

#### Reference

[Notification\<T\> Class](Notification/Notification(T))

[System.Reactive Namespace](System.Reactive/System.Reactive)
