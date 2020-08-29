title: Timeout
---
# Observable.Timeout Method

Returns the observable sequence with a TimeoutException in case of a timeout.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Timeout<TSource>(IObservable<TSource>, DateTimeOffset)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.timeout%60%601(system.iobservable%7b%60%600%7d%2csystem.datetimeoffset)(v=VS.103))Returns either the observable sequence or a TimeoutException if dueTime elapses.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Timeout<TSource>(IObservable<TSource>, TimeSpan)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.timeout%60%601(system.iobservable%7b%60%600%7d%2csystem.timespan)(v=VS.103))Returns either the observable sequence or an TimeoutException if dueTime elapses.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Timeout<TSource>(IObservable<TSource>, DateTimeOffset, IObservable<TSource>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.timeout%60%601(system.iobservable%7b%60%600%7d%2csystem.datetimeoffset%2csystem.iobservable%7b%60%600%7d)(v=VS.103))Returns either the observable sequence or an TimeoutException if dueTime elapses.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Timeout<TSource>(IObservable<TSource>, DateTimeOffset, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.timeout%60%601(system.iobservable%7b%60%600%7d%2csystem.datetimeoffset%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Returns either the observable sequence or an TimeoutException if dueTime elapses.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Timeout<TSource>(IObservable<TSource>, TimeSpan, IObservable<TSource>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.timeout%60%601(system.iobservable%7b%60%600%7d%2csystem.timespan%2csystem.iobservable%7b%60%600%7d)(v=VS.103))Returns the source observable sequence or the other observable sequence if dueTime elapses.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Timeout<TSource>(IObservable<TSource>, TimeSpan, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.timeout%60%601(system.iobservable%7b%60%600%7d%2csystem.timespan%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Returns either the observable sequence or an TimeoutException if dueTime elapses.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Timeout<TSource>(IObservable<TSource>, DateTimeOffset, IObservable<TSource>, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.timeout%60%601(system.iobservable%7b%60%600%7d%2csystem.datetimeoffset%2csystem.iobservable%7b%60%600%7d%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Returns the source observable sequence or the other observable sequence if dueTime elapses.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Timeout<TSource>(IObservable<TSource>, TimeSpan, IObservable<TSource>, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.timeout%60%601(system.iobservable%7b%60%600%7d%2csystem.timespan%2csystem.iobservable%7b%60%600%7d%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Returns the source observable sequence or the other observable sequence if dueTime elapses.Top

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Timeout\<TSource\>(IObservable\<TSource\>, DateTimeOffset)

Returns either the observable sequence or a TimeoutException if dueTime elapses.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Timeout(Of TSource) ( _
    source As IObservable(Of TSource), _
    dueTime As DateTimeOffset _
) As IObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim dueTime As DateTimeOffset
Dim returnValue As IObservable(Of TSource)

returnValue = source.Timeout(dueTime)
```

```csharp
public static IObservable<TSource> Timeout<TSource>(
    this IObservable<TSource> source,
    DateTimeOffset dueTime
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<TSource>^ Timeout(
    IObservable<TSource>^ source, 
    DateTimeOffset dueTime
)
```

```fsharp
static member Timeout : 
        source:IObservable<'TSource> * 
        dueTime:DateTimeOffset -> IObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence to perform a timeout for.

- dueTime  
  Type: [System.DateTimeOffset](https://msdn.microsoft.com/en-us/library/Bb341783)  
  The maximum duration between values before a timeout occurs.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
The source sequence with a TimeoutException in case of a timeout.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Timeout\<TSource\>(IObservable\<TSource\>, DateTimeOffset, IObservable\<TSource\>, IScheduler)

Returns the source observable sequence or the other observable sequence if dueTime elapses.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Timeout(Of TSource) ( _
    source As IObservable(Of TSource), _
    dueTime As DateTimeOffset, _
    other As IObservable(Of TSource), _
    scheduler As IScheduler _
) As IObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim dueTime As DateTimeOffset
Dim other As IObservable(Of TSource)
Dim scheduler As IScheduler
Dim returnValue As IObservable(Of TSource)

returnValue = source.Timeout(dueTime, _
    other, scheduler)
```

```csharp
public static IObservable<TSource> Timeout<TSource>(
    this IObservable<TSource> source,
    DateTimeOffset dueTime,
    IObservable<TSource> other,
    IScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<TSource>^ Timeout(
    IObservable<TSource>^ source, 
    DateTimeOffset dueTime, 
    IObservable<TSource>^ other, 
    IScheduler^ scheduler
)
```

```fsharp
static member Timeout : 
        source:IObservable<'TSource> * 
        dueTime:DateTimeOffset * 
        other:IObservable<'TSource> * 
        scheduler:IScheduler -> IObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence to perform a timeout for.

- dueTime  
  Type: [System.DateTimeOffset](https://msdn.microsoft.com/en-us/library/Bb341783)  
  The maximum duration between values before a timeout occurs.

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The sequence to return in case of a timeout.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler to run the timeout timers on.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
The source sequence switching to the other sequence in case of a timeout.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Timeout\<TSource\>(IObservable\<TSource\>, DateTimeOffset, IScheduler)

Returns either the observable sequence or an TimeoutException if dueTime elapses.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Timeout(Of TSource) ( _
    source As IObservable(Of TSource), _
    dueTime As DateTimeOffset, _
    scheduler As IScheduler _
) As IObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim dueTime As DateTimeOffset
Dim scheduler As IScheduler
Dim returnValue As IObservable(Of TSource)

returnValue = source.Timeout(dueTime, _
    scheduler)
```

```csharp
public static IObservable<TSource> Timeout<TSource>(
    this IObservable<TSource> source,
    DateTimeOffset dueTime,
    IScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<TSource>^ Timeout(
    IObservable<TSource>^ source, 
    DateTimeOffset dueTime, 
    IScheduler^ scheduler
)
```

```fsharp
static member Timeout : 
        source:IObservable<'TSource> * 
        dueTime:DateTimeOffset * 
        scheduler:IScheduler -> IObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence to perform a timeout for.

- dueTime  
  Type: [System.DateTimeOffset](https://msdn.microsoft.com/en-us/library/Bb341783)  
  The maximum duration between values before a timeout occurs.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler to run the timeout timers on.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
The source sequence with a TimeoutException in case of a timeout.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Timeout\<TSource\>(IObservable\<TSource\>, TimeSpan)

Returns either the observable sequence or an TimeoutException if dueTime elapses.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Timeout(Of TSource) ( _
    source As IObservable(Of TSource), _
    dueTime As TimeSpan _
) As IObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim dueTime As TimeSpan
Dim returnValue As IObservable(Of TSource)

returnValue = source.Timeout(dueTime)
```

```csharp
public static IObservable<TSource> Timeout<TSource>(
    this IObservable<TSource> source,
    TimeSpan dueTime
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<TSource>^ Timeout(
    IObservable<TSource>^ source, 
    TimeSpan dueTime
)
```

```fsharp
static member Timeout : 
        source:IObservable<'TSource> * 
        dueTime:TimeSpan -> IObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence to perform a timeout for.

- dueTime  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The time when a timeout occurs.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
The source sequence with a TimeoutException in case of a timeout.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Timeout\<TSource\>(IObservable\<TSource\>, DateTimeOffset, IObservable\<TSource\>)

Returns either the observable sequence or an TimeoutException if dueTime elapses.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Timeout(Of TSource) ( _
    source As IObservable(Of TSource), _
    dueTime As DateTimeOffset, _
    other As IObservable(Of TSource) _
) As IObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim dueTime As DateTimeOffset
Dim other As IObservable(Of TSource)
Dim returnValue As IObservable(Of TSource)

returnValue = source.Timeout(dueTime, _
    other)
```

```csharp
public static IObservable<TSource> Timeout<TSource>(
    this IObservable<TSource> source,
    DateTimeOffset dueTime,
    IObservable<TSource> other
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<TSource>^ Timeout(
    IObservable<TSource>^ source, 
    DateTimeOffset dueTime, 
    IObservable<TSource>^ other
)
```

```fsharp
static member Timeout : 
        source:IObservable<'TSource> * 
        dueTime:DateTimeOffset * 
        other:IObservable<'TSource> -> IObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence to perform a timeout for.

- dueTime  
  Type: [System.DateTimeOffset](https://msdn.microsoft.com/en-us/library/Bb341783)  
  The maximum duration between values before a timeout occurs.

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence switching to the other sequence in case of a timeout.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
The source sequence with a TimeoutException in case of a timeout.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Timeout\<TSource\>(IObservable\<TSource\>, TimeSpan, IObservable\<TSource\>)

Returns the source observable sequence or the other observable sequence if dueTime elapses.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Timeout(Of TSource) ( _
    source As IObservable(Of TSource), _
    dueTime As TimeSpan, _
    other As IObservable(Of TSource) _
) As IObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim dueTime As TimeSpan
Dim other As IObservable(Of TSource)
Dim returnValue As IObservable(Of TSource)

returnValue = source.Timeout(dueTime, _
    other)
```

```csharp
public static IObservable<TSource> Timeout<TSource>(
    this IObservable<TSource> source,
    TimeSpan dueTime,
    IObservable<TSource> other
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<TSource>^ Timeout(
    IObservable<TSource>^ source, 
    TimeSpan dueTime, 
    IObservable<TSource>^ other
)
```

```fsharp
static member Timeout : 
        source:IObservable<'TSource> * 
        dueTime:TimeSpan * 
        other:IObservable<'TSource> -> IObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence to perform a timeout for.

- dueTime  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The time when a timeout occurs.

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The sequence to return in case of a timeout.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
The source sequence switching to the other sequence in case of a timeout.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Timeout\<TSource\>(IObservable\<TSource\>, TimeSpan, IScheduler)

Returns either the observable sequence or an TimeoutException if dueTime elapses.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Timeout(Of TSource) ( _
    source As IObservable(Of TSource), _
    dueTime As TimeSpan, _
    scheduler As IScheduler _
) As IObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim dueTime As TimeSpan
Dim scheduler As IScheduler
Dim returnValue As IObservable(Of TSource)

returnValue = source.Timeout(dueTime, _
    scheduler)
```

```csharp
public static IObservable<TSource> Timeout<TSource>(
    this IObservable<TSource> source,
    TimeSpan dueTime,
    IScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<TSource>^ Timeout(
    IObservable<TSource>^ source, 
    TimeSpan dueTime, 
    IScheduler^ scheduler
)
```

```fsharp
static member Timeout : 
        source:IObservable<'TSource> * 
        dueTime:TimeSpan * 
        scheduler:IScheduler -> IObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence to perform a timeout for.

- dueTime  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The maximum duration between values before a timeout occurs.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler to run the timeout timers on.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
The source sequence with a TimeoutException in case of a timeout.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Timeout\<TSource\>(IObservable\<TSource\>, TimeSpan, IObservable\<TSource\>, IScheduler)

Returns the source observable sequence or the other observable sequence if dueTime elapses.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Timeout(Of TSource) ( _
    source As IObservable(Of TSource), _
    dueTime As TimeSpan, _
    other As IObservable(Of TSource), _
    scheduler As IScheduler _
) As IObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim dueTime As TimeSpan
Dim other As IObservable(Of TSource)
Dim scheduler As IScheduler
Dim returnValue As IObservable(Of TSource)

returnValue = source.Timeout(dueTime, _
    other, scheduler)
```

```csharp
public static IObservable<TSource> Timeout<TSource>(
    this IObservable<TSource> source,
    TimeSpan dueTime,
    IObservable<TSource> other,
    IScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<TSource>^ Timeout(
    IObservable<TSource>^ source, 
    TimeSpan dueTime, 
    IObservable<TSource>^ other, 
    IScheduler^ scheduler
)
```

```fsharp
static member Timeout : 
        source:IObservable<'TSource> * 
        dueTime:TimeSpan * 
        other:IObservable<'TSource> * 
        scheduler:IScheduler -> IObservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source sequence to perform a timeout for.

- dueTime  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The time when a timeout occurs.

- other  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The sequence to return in case of a timeout.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler to run the timeout timers on.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
The source sequence switching to the other sequence in case of a timeout.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
