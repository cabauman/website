title: Replay
---
# Observable.Replay Method

Returns a connectable observable sequence that shares a single subscription to the underlying sequence replaying all notifications.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Replay<TSource>(IObservable<TSource>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.replay%60%601(system.iobservable%7b%60%600%7d)(v=VS.103))Returns a connectable observable sequence that shares a single subscription to the underlying sequence replaying all notifications.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Replay<TSource, TResult>(IObservable<TSource>, Func<IObservable<TSource>, IObservable<TResult>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.replay%60%602(system.iobservable%7b%60%600%7d%2csystem.func%7bsystem.iobservable%7b%60%600%7d%2csystem.iobservable%7b%60%601%7d%7d)(v=VS.103))Returns an observable sequence that is the result of invoking the selector on a connectable observable sequence that shares a single subscription to the underlying sequence and starts with initial value.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Replay<TSource>(IObservable<TSource>, Int32)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.replay%60%601(system.iobservable%7b%60%600%7d%2csystem.int32)(v=VS.103))Returns a connectable observable sequence that shares a single subscription to the underlying sequence replaying bufferSize notifications.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Replay<TSource>(IObservable<TSource>, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.replay%60%601(system.iobservable%7b%60%600%7d%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Returns a connectable observable sequence that shares a single subscription to the underlying sequence replaying all notifications.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Replay<TSource>(IObservable<TSource>, TimeSpan)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.replay%60%601(system.iobservable%7b%60%600%7d%2csystem.timespan)(v=VS.103))Returns a connectable observable sequence that shares a single subscription to the underlying sequence replaying all notifications within window.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Replay<TSource, TResult>(IObservable<TSource>, Func<IObservable<TSource>, IObservable<TResult>>, Int32)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.replay%60%602(system.iobservable%7b%60%600%7d%2csystem.func%7bsystem.iobservable%7b%60%600%7d%2csystem.iobservable%7b%60%601%7d%7d%2csystem.int32)(v=VS.103))Returns an observable sequence that is the result of invoking the selector on a connectable observable sequence that shares a single subscription to the underlying sequence replaying bufferSize notifications.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Replay<TSource, TResult>(IObservable<TSource>, Func<IObservable<TSource>, IObservable<TResult>>, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.replay%60%602(system.iobservable%7b%60%600%7d%2csystem.func%7bsystem.iobservable%7b%60%600%7d%2csystem.iobservable%7b%60%601%7d%7d%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Returns an observable sequence that is the result of invoking the selector on a connectable observable sequence that shares a single subscription to the underlying sequence replaying all notifications.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Replay<TSource, TResult>(IObservable<TSource>, Func<IObservable<TSource>, IObservable<TResult>>, TimeSpan)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.replay%60%602(system.iobservable%7b%60%600%7d%2csystem.func%7bsystem.iobservable%7b%60%600%7d%2csystem.iobservable%7b%60%601%7d%7d%2csystem.timespan)(v=VS.103))Returns an observable sequence that is the result of invoking the selector on a connectable observable sequence that shares a single subscription to the underlying sequence replaying all notifications within window.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Replay<TSource>(IObservable<TSource>, Int32, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.replay%60%601(system.iobservable%7b%60%600%7d%2csystem.int32%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Returns a connectable observable sequence that shares a single subscription to the underlying sequence replaying bufferSize notifications.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Replay<TSource>(IObservable<TSource>, Int32, TimeSpan)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.replay%60%601(system.iobservable%7b%60%600%7d%2csystem.int32%2csystem.timespan)(v=VS.103))Returns a connectable observable sequence that shares a single subscription to the underlying sequence replaying bufferSize notifications within window.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Replay<TSource>(IObservable<TSource>, TimeSpan, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.replay%60%601(system.iobservable%7b%60%600%7d%2csystem.timespan%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Returns a connectable observable sequence that shares a single subscription to the underlying sequence replaying all notifications within window.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Replay<TSource, TResult>(IObservable<TSource>, Func<IObservable<TSource>, IObservable<TResult>>, Int32, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.replay%60%602(system.iobservable%7b%60%600%7d%2csystem.func%7bsystem.iobservable%7b%60%600%7d%2csystem.iobservable%7b%60%601%7d%7d%2csystem.int32%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Returns an observable sequence that is the result of invoking the selector on a connectable observable sequence that shares a single subscription to the underlying sequence replaying bufferSize notifications.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Replay<TSource, TResult>(IObservable<TSource>, Func<IObservable<TSource>, IObservable<TResult>>, Int32, TimeSpan)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.replay%60%602(system.iobservable%7b%60%600%7d%2csystem.func%7bsystem.iobservable%7b%60%600%7d%2csystem.iobservable%7b%60%601%7d%7d%2csystem.int32%2csystem.timespan)(v=VS.103))Returns an observable sequence that is the result of invoking the selector on a connectable observable sequence that shares a single subscription to the underlying sequence replaying bufferSize notifications within window.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Replay<TSource, TResult>(IObservable<TSource>, Func<IObservable<TSource>, IObservable<TResult>>, TimeSpan, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.replay%60%602(system.iobservable%7b%60%600%7d%2csystem.func%7bsystem.iobservable%7b%60%600%7d%2csystem.iobservable%7b%60%601%7d%7d%2csystem.timespan%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Returns an observable sequence that is the result of invoking the selector on a connectable observable sequence that shares a single subscription to the underlying sequence replaying all notifications within window.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Replay<TSource>(IObservable<TSource>, Int32, TimeSpan, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.replay%60%601(system.iobservable%7b%60%600%7d%2csystem.int32%2csystem.timespan%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Returns a connectable observable sequence that shares a single subscription to the underlying sequence replaying bufferSize notifications within window.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Replay<TSource, TResult>(IObservable<TSource>, Func<IObservable<TSource>, IObservable<TResult>>, Int32, TimeSpan, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.replay%60%602(system.iobservable%7b%60%600%7d%2csystem.func%7bsystem.iobservable%7b%60%600%7d%2csystem.iobservable%7b%60%601%7d%7d%2csystem.int32%2csystem.timespan%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Returns an observable sequence that is the result of invoking the selector on a connectable observable sequence that shares a single subscription to the underlying sequence replaying bufferSize notifications within window.Top

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Replay\<TSource\>(IObservable\<TSource\>, Int32, TimeSpan)

Returns a connectable observable sequence that shares a single subscription to the underlying sequence replaying bufferSize notifications within window.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Replay(Of TSource) ( _
    source As IObservable(Of TSource), _
    bufferSize As Integer, _
    window As TimeSpan _
) As IConnectableObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim bufferSize As Integer
Dim window As TimeSpan
Dim returnValue As IConnectableObservable(Of TSource)

returnValue = source.Replay(bufferSize, _
    window)
```

```csharp
public static IConnectableObservable<TSource> Replay<TSource>(
    this IObservable<TSource> source,
    int bufferSize,
    TimeSpan window
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IConnectableObservable<TSource>^ Replay(
    IObservable<TSource>^ source, 
    int bufferSize, 
    TimeSpan window
)
```

```fsharp
static member Replay : 
        source:IObservable<'TSource> * 
        bufferSize:int * 
        window:TimeSpan -> IConnectableObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence whose elements will be multicasted through a single shared subscription.

- bufferSize  
  Type: [System.Int32](https://msdn.microsoft.com/en-us/library/td2s409d)  
  The maximum element count of the replay buffer.

- window  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The maximum time length of the replay buffer.

#### Return Value

Type: [System.Reactive.Subjects.IConnectableObservable](IConnectableObservable/IConnectableObservable(T))\<TSource\>  
A connectable observable sequence that shares a single subscription to the underlying sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Replay\<TSource\>(IObservable\<TSource\>, Int32, IScheduler)

Returns a connectable observable sequence that shares a single subscription to the underlying sequence replaying bufferSize notifications.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Replay(Of TSource) ( _
    source As IObservable(Of TSource), _
    bufferSize As Integer, _
    scheduler As IScheduler _
) As IConnectableObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim bufferSize As Integer
Dim scheduler As IScheduler
Dim returnValue As IConnectableObservable(Of TSource)

returnValue = source.Replay(bufferSize, _
    scheduler)
```

```csharp
public static IConnectableObservable<TSource> Replay<TSource>(
    this IObservable<TSource> source,
    int bufferSize,
    IScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IConnectableObservable<TSource>^ Replay(
    IObservable<TSource>^ source, 
    int bufferSize, 
    IScheduler^ scheduler
)
```

```fsharp
static member Replay : 
        source:IObservable<'TSource> * 
        bufferSize:int * 
        scheduler:IScheduler -> IConnectableObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence whose elements will be multicasted through a single shared subscription.

- bufferSize  
  Type: [System.Int32](https://msdn.microsoft.com/en-us/library/td2s409d)  
  The maximum element count of the replay buffer.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler where connected observers will be invoked on.

#### Return Value

Type: [System.Reactive.Subjects.IConnectableObservable](IConnectableObservable/IConnectableObservable(T))\<TSource\>  
A connectable observable sequence that shares a single subscription to the underlying sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Replay\<TSource\>(IObservable\<TSource\>)

Returns a connectable observable sequence that shares a single subscription to the underlying sequence replaying all notifications.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Replay(Of TSource) ( _
    source As IObservable(Of TSource) _
) As IConnectableObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim returnValue As IConnectableObservable(Of TSource)

returnValue = source.Replay()
```

```csharp
public static IConnectableObservable<TSource> Replay<TSource>(
    this IObservable<TSource> source
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IConnectableObservable<TSource>^ Replay(
    IObservable<TSource>^ source
)
```

```fsharp
static member Replay : 
        source:IObservable<'TSource> -> IConnectableObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence whose elements will be multicasted through a single shared subscription.

#### Return Value

Type: [System.Reactive.Subjects.IConnectableObservable](IConnectableObservable/IConnectableObservable(T))\<TSource\>  
A connectable observable sequence that shares a single subscription to the underlying sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Replay\<TSource\>(IObservable\<TSource\>, TimeSpan)

Returns a connectable observable sequence that shares a single subscription to the underlying sequence replaying all notifications within window.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Replay(Of TSource) ( _
    source As IObservable(Of TSource), _
    window As TimeSpan _
) As IConnectableObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim window As TimeSpan
Dim returnValue As IConnectableObservable(Of TSource)

returnValue = source.Replay(window)
```

```csharp
public static IConnectableObservable<TSource> Replay<TSource>(
    this IObservable<TSource> source,
    TimeSpan window
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IConnectableObservable<TSource>^ Replay(
    IObservable<TSource>^ source, 
    TimeSpan window
)
```

```fsharp
static member Replay : 
        source:IObservable<'TSource> * 
        window:TimeSpan -> IConnectableObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence whose elements will be multicasted through a single shared subscription.

- window  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The maximum time length of the replay buffer.

#### Return Value

Type: [System.Reactive.Subjects.IConnectableObservable](IConnectableObservable/IConnectableObservable(T))\<TSource\>  
A connectable observable sequence that shares a single subscription to the underlying sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Replay\<TSource\>(IObservable\<TSource\>, Int32)

Returns a connectable observable sequence that shares a single subscription to the underlying sequence replaying bufferSize notifications.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Replay(Of TSource) ( _
    source As IObservable(Of TSource), _
    bufferSize As Integer _
) As IConnectableObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim bufferSize As Integer
Dim returnValue As IConnectableObservable(Of TSource)

returnValue = source.Replay(bufferSize)
```

```csharp
public static IConnectableObservable<TSource> Replay<TSource>(
    this IObservable<TSource> source,
    int bufferSize
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IConnectableObservable<TSource>^ Replay(
    IObservable<TSource>^ source, 
    int bufferSize
)
```

```fsharp
static member Replay : 
        source:IObservable<'TSource> * 
        bufferSize:int -> IConnectableObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence whose elements will be multicasted through a single shared subscription.

- bufferSize  
  Type: [System.Int32](https://msdn.microsoft.com/en-us/library/td2s409d)  
  The maximum element count of the replay buffer.

#### Return Value

Type: [System.Reactive.Subjects.IConnectableObservable](IConnectableObservable/IConnectableObservable(T))\<TSource\>  
A connectable observable sequence that shares a single subscription to the underlying sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Replay\<TSource\>(IObservable\<TSource\>, TimeSpan, IScheduler)

Returns a connectable observable sequence that shares a single subscription to the underlying sequence replaying all notifications within window.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Replay(Of TSource) ( _
    source As IObservable(Of TSource), _
    window As TimeSpan, _
    scheduler As IScheduler _
) As IConnectableObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim window As TimeSpan
Dim scheduler As IScheduler
Dim returnValue As IConnectableObservable(Of TSource)

returnValue = source.Replay(window, _
    scheduler)
```

```csharp
public static IConnectableObservable<TSource> Replay<TSource>(
    this IObservable<TSource> source,
    TimeSpan window,
    IScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IConnectableObservable<TSource>^ Replay(
    IObservable<TSource>^ source, 
    TimeSpan window, 
    IScheduler^ scheduler
)
```

```fsharp
static member Replay : 
        source:IObservable<'TSource> * 
        window:TimeSpan * 
        scheduler:IScheduler -> IConnectableObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence whose elements will be multicasted through a single shared subscription.

- window  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The maximum time length of the replay buffer.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler where connected observers will be invoked on.

#### Return Value

Type: [System.Reactive.Subjects.IConnectableObservable](IConnectableObservable/IConnectableObservable(T))\<TSource\>  
A connectable observable sequence that shares a single subscription to the underlying sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Replay\<TSource\>(IObservable\<TSource\>, Int32, TimeSpan, IScheduler)

Returns a connectable observable sequence that shares a single subscription to the underlying sequence replaying bufferSize notifications within window.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Replay(Of TSource) ( _
    source As IObservable(Of TSource), _
    bufferSize As Integer, _
    window As TimeSpan, _
    scheduler As IScheduler _
) As IConnectableObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim bufferSize As Integer
Dim window As TimeSpan
Dim scheduler As IScheduler
Dim returnValue As IConnectableObservable(Of TSource)

returnValue = source.Replay(bufferSize, _
    window, scheduler)
```

```csharp
public static IConnectableObservable<TSource> Replay<TSource>(
    this IObservable<TSource> source,
    int bufferSize,
    TimeSpan window,
    IScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IConnectableObservable<TSource>^ Replay(
    IObservable<TSource>^ source, 
    int bufferSize, 
    TimeSpan window, 
    IScheduler^ scheduler
)
```

```fsharp
static member Replay : 
        source:IObservable<'TSource> * 
        bufferSize:int * 
        window:TimeSpan * 
        scheduler:IScheduler -> IConnectableObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence whose elements will be multicasted through a single shared subscription.

- bufferSize  
  Type: [System.Int32](https://msdn.microsoft.com/en-us/library/td2s409d)  
  The maximum element count of the replay buffer.

- window  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The maximum time length of the replay buffer.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler where connected observers will be invoked on.

#### Return Value

Type: [System.Reactive.Subjects.IConnectableObservable](IConnectableObservable/IConnectableObservable(T))\<TSource\>  
A connectable observable sequence that shares a single subscription to the underlying sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Replay\<TSource\>(IObservable\<TSource\>, IScheduler)

Returns a connectable observable sequence that shares a single subscription to the underlying sequence replaying all notifications.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Replay(Of TSource) ( _
    source As IObservable(Of TSource), _
    scheduler As IScheduler _
) As IConnectableObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim scheduler As IScheduler
Dim returnValue As IConnectableObservable(Of TSource)

returnValue = source.Replay(scheduler)
```

```csharp
public static IConnectableObservable<TSource> Replay<TSource>(
    this IObservable<TSource> source,
    IScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IConnectableObservable<TSource>^ Replay(
    IObservable<TSource>^ source, 
    IScheduler^ scheduler
)
```

```fsharp
static member Replay : 
        source:IObservable<'TSource> * 
        scheduler:IScheduler -> IConnectableObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence whose elements will be multicasted through a single shared subscription.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler where connected observers will be invoked on.

#### Return Value

Type: [System.Reactive.Subjects.IConnectableObservable](IConnectableObservable/IConnectableObservable(T))\<TSource\>  
A connectable observable sequence that shares a single subscription to the underlying sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Replay\<TSource, TResult\>(IObservable\<TSource\>, Func\<IObservable\<TSource\>, IObservable\<TResult\>\>, TimeSpan, IScheduler)

Returns an observable sequence that is the result of invoking the selector on a connectable observable sequence that shares a single subscription to the underlying sequence replaying all notifications within window.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Replay(Of TSource, TResult) ( _
    source As IObservable(Of TSource), _
    selector As Func(Of IObservable(Of TSource), IObservable(Of TResult)), _
    window As TimeSpan, _
    scheduler As IScheduler _
) As IObservable(Of TResult)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim selector As Func(Of IObservable(Of TSource), IObservable(Of TResult))
Dim window As TimeSpan
Dim scheduler As IScheduler
Dim returnValue As IObservable(Of TResult)

returnValue = source.Replay(selector, _
    window, scheduler)
```

```csharp
public static IObservable<TResult> Replay<TSource, TResult>(
    this IObservable<TSource> source,
    Func<IObservable<TSource>, IObservable<TResult>> selector,
    TimeSpan window,
    IScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TResult>
static IObservable<TResult>^ Replay(
    IObservable<TSource>^ source, 
    Func<IObservable<TSource>^, IObservable<TResult>^>^ selector, 
    TimeSpan window, 
    IScheduler^ scheduler
)
```

```fsharp
static member Replay : 
        source:IObservable<'TSource> * 
        selector:Func<IObservable<'TSource>, IObservable<'TResult>> * 
        window:TimeSpan * 
        scheduler:IScheduler -> IObservable<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

- TResult  
  The type of result.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence whose elements will be multicasting through a single shared subscription.

- selector  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>, [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>\>  
  The selector function which can use the multicasted source sequence as many times as needed, without causing multiple subscriptions to the source sequence.

- window  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The maximum time length of the replay buffer.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler where connected observers within the selector function will be invoked on.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
An observable sequence that contains the elements of a sequence produced by multicasting the source sequence within a selector function.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Replay\<TSource, TResult\>(IObservable\<TSource\>, Func\<IObservable\<TSource\>, IObservable\<TResult\>\>, Int32, IScheduler)

Returns an observable sequence that is the result of invoking the selector on a connectable observable sequence that shares a single subscription to the underlying sequence replaying bufferSize notifications.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Replay(Of TSource, TResult) ( _
    source As IObservable(Of TSource), _
    selector As Func(Of IObservable(Of TSource), IObservable(Of TResult)), _
    bufferSize As Integer, _
    scheduler As IScheduler _
) As IObservable(Of TResult)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim selector As Func(Of IObservable(Of TSource), IObservable(Of TResult))
Dim bufferSize As Integer
Dim scheduler As IScheduler
Dim returnValue As IObservable(Of TResult)

returnValue = source.Replay(selector, _
    bufferSize, scheduler)
```

```csharp
public static IObservable<TResult> Replay<TSource, TResult>(
    this IObservable<TSource> source,
    Func<IObservable<TSource>, IObservable<TResult>> selector,
    int bufferSize,
    IScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TResult>
static IObservable<TResult>^ Replay(
    IObservable<TSource>^ source, 
    Func<IObservable<TSource>^, IObservable<TResult>^>^ selector, 
    int bufferSize, 
    IScheduler^ scheduler
)
```

```fsharp
static member Replay : 
        source:IObservable<'TSource> * 
        selector:Func<IObservable<'TSource>, IObservable<'TResult>> * 
        bufferSize:int * 
        scheduler:IScheduler -> IObservable<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

- TResult  
  The type of result.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence whose elements will be multicasting through a single shared subscription.

- selector  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>, [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>\>  
  The selector function which can use the multicasted source sequence as many times as needed, without causing multiple subscriptions to the source sequence.

- bufferSize  
  Type: [System.Int32](https://msdn.microsoft.com/en-us/library/td2s409d)  
  The maximum element count of the replay buffer.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler where connected observers within the selector function will be invoked on.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
An observable sequence that contains the elements of a sequence produced by multicasting the source sequence within a selector function.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Replay\<TSource, TResult\>(IObservable\<TSource\>, Func\<IObservable\<TSource\>, IObservable\<TResult\>\>)

Returns an observable sequence that is the result of invoking the selector on a connectable observable sequence that shares a single subscription to the underlying sequence and starts with initial value.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Replay(Of TSource, TResult) ( _
    source As IObservable(Of TSource), _
    selector As Func(Of IObservable(Of TSource), IObservable(Of TResult)) _
) As IObservable(Of TResult)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim selector As Func(Of IObservable(Of TSource), IObservable(Of TResult))
Dim returnValue As IObservable(Of TResult)

returnValue = source.Replay(selector)
```

```csharp
public static IObservable<TResult> Replay<TSource, TResult>(
    this IObservable<TSource> source,
    Func<IObservable<TSource>, IObservable<TResult>> selector
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TResult>
static IObservable<TResult>^ Replay(
    IObservable<TSource>^ source, 
    Func<IObservable<TSource>^, IObservable<TResult>^>^ selector
)
```

```fsharp
static member Replay : 
        source:IObservable<'TSource> * 
        selector:Func<IObservable<'TSource>, IObservable<'TResult>> -> IObservable<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

- TResult  
  The type of result.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence whose elements will be multicasted through a single shared subscription.

- selector  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>, [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>\>  
  The selector function which can use the multicasted source sequence as many times as needed, without causing multiple subscriptions to the source sequence.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
An observable sequence that contains the elements of a sequence produced by multicasting the source sequence within a selector function.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Replay\<TSource, TResult\>(IObservable\<TSource\>, Func\<IObservable\<TSource\>, IObservable\<TResult\>\>, TimeSpan)

Returns an observable sequence that is the result of invoking the selector on a connectable observable sequence that shares a single subscription to the underlying sequence replaying all notifications within window.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Replay(Of TSource, TResult) ( _
    source As IObservable(Of TSource), _
    selector As Func(Of IObservable(Of TSource), IObservable(Of TResult)), _
    window As TimeSpan _
) As IObservable(Of TResult)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim selector As Func(Of IObservable(Of TSource), IObservable(Of TResult))
Dim window As TimeSpan
Dim returnValue As IObservable(Of TResult)

returnValue = source.Replay(selector, _
    window)
```

```csharp
public static IObservable<TResult> Replay<TSource, TResult>(
    this IObservable<TSource> source,
    Func<IObservable<TSource>, IObservable<TResult>> selector,
    TimeSpan window
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TResult>
static IObservable<TResult>^ Replay(
    IObservable<TSource>^ source, 
    Func<IObservable<TSource>^, IObservable<TResult>^>^ selector, 
    TimeSpan window
)
```

```fsharp
static member Replay : 
        source:IObservable<'TSource> * 
        selector:Func<IObservable<'TSource>, IObservable<'TResult>> * 
        window:TimeSpan -> IObservable<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

- TResult  
  The type of result.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence whose elements will be multicasting through a single shared subscription.

- selector  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>, [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>\>  
  The selector function which can use the multicasted source sequence as many times as needed, without causing multiple subscriptions to the source sequence.

- window  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The maximum time length of the replay buffer.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
An observable sequence that contains the elements of a sequence produced by multicasting the source sequence within a selector function.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Replay\<TSource, TResult\>(IObservable\<TSource\>, Func\<IObservable\<TSource\>, IObservable\<TResult\>\>, Int32, TimeSpan, IScheduler)

Returns an observable sequence that is the result of invoking the selector on a connectable observable sequence that shares a single subscription to the underlying sequence replaying bufferSize notifications within window.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Replay(Of TSource, TResult) ( _
    source As IObservable(Of TSource), _
    selector As Func(Of IObservable(Of TSource), IObservable(Of TResult)), _
    bufferSize As Integer, _
    window As TimeSpan, _
    scheduler As IScheduler _
) As IObservable(Of TResult)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim selector As Func(Of IObservable(Of TSource), IObservable(Of TResult))
Dim bufferSize As Integer
Dim window As TimeSpan
Dim scheduler As IScheduler
Dim returnValue As IObservable(Of TResult)

returnValue = source.Replay(selector, _
    bufferSize, window, scheduler)
```

```csharp
public static IObservable<TResult> Replay<TSource, TResult>(
    this IObservable<TSource> source,
    Func<IObservable<TSource>, IObservable<TResult>> selector,
    int bufferSize,
    TimeSpan window,
    IScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TResult>
static IObservable<TResult>^ Replay(
    IObservable<TSource>^ source, 
    Func<IObservable<TSource>^, IObservable<TResult>^>^ selector, 
    int bufferSize, 
    TimeSpan window, 
    IScheduler^ scheduler
)
```

```fsharp
static member Replay : 
        source:IObservable<'TSource> * 
        selector:Func<IObservable<'TSource>, IObservable<'TResult>> * 
        bufferSize:int * 
        window:TimeSpan * 
        scheduler:IScheduler -> IObservable<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

- TResult  
  The type of result.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence whose elements will be multicasting through a single shared subscription.

- selector  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>, [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>\>  
  The selector function which can use the multicasted source sequence as many times as needed, without causing multiple subscriptions to the source sequence.

- bufferSize  
  Type: [System.Int32](https://msdn.microsoft.com/en-us/library/td2s409d)  
  The maximum element count of the replay buffer.

- window  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The maximum time length of the replay buffer.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler where connected observers within the selector function will be invoked on.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
An observable sequence that contains the elements of a sequence produced by multicasting the source sequence within a selector function.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Replay\<TSource, TResult\>(IObservable\<TSource\>, Func\<IObservable\<TSource\>, IObservable\<TResult\>\>, Int32, TimeSpan)

Returns an observable sequence that is the result of invoking the selector on a connectable observable sequence that shares a single subscription to the underlying sequence replaying bufferSize notifications within window.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Replay(Of TSource, TResult) ( _
    source As IObservable(Of TSource), _
    selector As Func(Of IObservable(Of TSource), IObservable(Of TResult)), _
    bufferSize As Integer, _
    window As TimeSpan _
) As IObservable(Of TResult)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim selector As Func(Of IObservable(Of TSource), IObservable(Of TResult))
Dim bufferSize As Integer
Dim window As TimeSpan
Dim returnValue As IObservable(Of TResult)

returnValue = source.Replay(selector, _
    bufferSize, window)
```

```csharp
public static IObservable<TResult> Replay<TSource, TResult>(
    this IObservable<TSource> source,
    Func<IObservable<TSource>, IObservable<TResult>> selector,
    int bufferSize,
    TimeSpan window
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TResult>
static IObservable<TResult>^ Replay(
    IObservable<TSource>^ source, 
    Func<IObservable<TSource>^, IObservable<TResult>^>^ selector, 
    int bufferSize, 
    TimeSpan window
)
```

```fsharp
static member Replay : 
        source:IObservable<'TSource> * 
        selector:Func<IObservable<'TSource>, IObservable<'TResult>> * 
        bufferSize:int * 
        window:TimeSpan -> IObservable<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

- TResult  
  The type of result.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence whose elements will be multicasting through a single shared subscription.

- selector  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>, [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>\>  
  The selector function which can use the multicasted source sequence as many times as needed, without causing multiple subscriptions to the source sequence.

- bufferSize  
  Type: [System.Int32](https://msdn.microsoft.com/en-us/library/td2s409d)  
  The maximum element count of the replay buffer.

- window  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The maximum time length of the replay buffer.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
An observable sequence that contains the elements of a sequence produced by multicasting the source sequence within a selector function.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Replay\<TSource, TResult\>(IObservable\<TSource\>, Func\<IObservable\<TSource\>, IObservable\<TResult\>\>, Int32)

Returns an observable sequence that is the result of invoking the selector on a connectable observable sequence that shares a single subscription to the underlying sequence replaying bufferSize notifications.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Replay(Of TSource, TResult) ( _
    source As IObservable(Of TSource), _
    selector As Func(Of IObservable(Of TSource), IObservable(Of TResult)), _
    bufferSize As Integer _
) As IObservable(Of TResult)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim selector As Func(Of IObservable(Of TSource), IObservable(Of TResult))
Dim bufferSize As Integer
Dim returnValue As IObservable(Of TResult)

returnValue = source.Replay(selector, _
    bufferSize)
```

```csharp
public static IObservable<TResult> Replay<TSource, TResult>(
    this IObservable<TSource> source,
    Func<IObservable<TSource>, IObservable<TResult>> selector,
    int bufferSize
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TResult>
static IObservable<TResult>^ Replay(
    IObservable<TSource>^ source, 
    Func<IObservable<TSource>^, IObservable<TResult>^>^ selector, 
    int bufferSize
)
```

```fsharp
static member Replay : 
        source:IObservable<'TSource> * 
        selector:Func<IObservable<'TSource>, IObservable<'TResult>> * 
        bufferSize:int -> IObservable<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

- TResult  
  The type of result.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence whose elements will be multicasted through a single shared subscription.

- selector  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>, [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>\>  
  The selector function which can use the multicasted source sequence as many times as needed, without causing multiple subscriptions to the source sequence.

- bufferSize  
  Type: [System.Int32](https://msdn.microsoft.com/en-us/library/td2s409d)  
  The maximum element count of the replay buffer.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
An observable sequence that contains the elements of a sequence produced by multicasting the source sequence within a selector function.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Replay\<TSource, TResult\>(IObservable\<TSource\>, Func\<IObservable\<TSource\>, IObservable\<TResult\>\>, IScheduler)

Returns an observable sequence that is the result of invoking the selector on a connectable observable sequence that shares a single subscription to the underlying sequence replaying all notifications.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Replay(Of TSource, TResult) ( _
    source As IObservable(Of TSource), _
    selector As Func(Of IObservable(Of TSource), IObservable(Of TResult)), _
    scheduler As IScheduler _
) As IObservable(Of TResult)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim selector As Func(Of IObservable(Of TSource), IObservable(Of TResult))
Dim scheduler As IScheduler
Dim returnValue As IObservable(Of TResult)

returnValue = source.Replay(selector, _
    scheduler)
```

```csharp
public static IObservable<TResult> Replay<TSource, TResult>(
    this IObservable<TSource> source,
    Func<IObservable<TSource>, IObservable<TResult>> selector,
    IScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TResult>
static IObservable<TResult>^ Replay(
    IObservable<TSource>^ source, 
    Func<IObservable<TSource>^, IObservable<TResult>^>^ selector, 
    IScheduler^ scheduler
)
```

```fsharp
static member Replay : 
        source:IObservable<'TSource> * 
        selector:Func<IObservable<'TSource>, IObservable<'TResult>> * 
        scheduler:IScheduler -> IObservable<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

- TResult  
  The type of result.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence whose elements will be multicasting through a single shared subscription.

- selector  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>, [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>\>  
  The selector function which can use the multicasted source sequence as many times as needed, without causing multiple subscriptions to the source sequence.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler where connected observers within the selector function will be invoked on.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
An observable sequence that contains the elements of a sequence produced by multicasting the source sequence within a selector function.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
