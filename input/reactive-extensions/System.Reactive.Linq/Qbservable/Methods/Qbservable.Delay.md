title: Delay
---
# Qbservable.Delay Method

Indicates the queryable observable sequence by due time.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Delay<TSource>(IQbservable<TSource>, DateTimeOffset)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.delay%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.datetimeoffset)(v=VS.103))Indicates the queryable observable sequence by due time with the specified source and dueTime.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Delay<TSource>(IQbservable<TSource>, TimeSpan)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.delay%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.timespan)(v=VS.103))Indicates the queryable observable sequence by due time with the specified source and dueTime.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Delay<TSource>(IQbservable<TSource>, DateTimeOffset, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.delay%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.datetimeoffset%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Indicates the queryable observable sequence by due time with the specified source, dueTime and scheduler.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Delay<TSource>(IQbservable<TSource>, TimeSpan, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.delay%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.timespan%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Indicates the queryable observable sequence by due time with the specified source, dueTime and scheduler.Top

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Delay\<TSource\>(IQbservable\<TSource\>, DateTimeOffset)

Indicates the queryable observable sequence by due time with the specified source and dueTime.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Delay(Of TSource) ( _
    source As IQbservable(Of TSource), _
    dueTime As DateTimeOffset _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim dueTime As DateTimeOffset
Dim returnValue As IQbservable(Of TSource)

returnValue = source.Delay(dueTime)
```

```csharp
public static IQbservable<TSource> Delay<TSource>(
    this IQbservable<TSource> source,
    DateTimeOffset dueTime
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ Delay(
    IQbservable<TSource>^ source, 
    DateTimeOffset dueTime
)
```

```fsharp
static member Delay : 
        source:IQbservable<'TSource> * 
        dueTime:DateTimeOffset -> IQbservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- source  
  Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
  The source sequence to delay values for.

- dueTime  
  Type: [System.DateTimeOffset](https://msdn.microsoft.com/en-us/library/Bb341783)  
  The absolute time used to shift the queryable observable sequence.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
The queryable observable sequence by due time with the specified source and dueTime.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Delay\<TSource\>(IQbservable\<TSource\>, TimeSpan)

Indicates the queryable observable sequence by due time with the specified source and dueTime.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Delay(Of TSource) ( _
    source As IQbservable(Of TSource), _
    dueTime As TimeSpan _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim dueTime As TimeSpan
Dim returnValue As IQbservable(Of TSource)

returnValue = source.Delay(dueTime)
```

```csharp
public static IQbservable<TSource> Delay<TSource>(
    this IQbservable<TSource> source,
    TimeSpan dueTime
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ Delay(
    IQbservable<TSource>^ source, 
    TimeSpan dueTime
)
```

```fsharp
static member Delay : 
        source:IQbservable<'TSource> * 
        dueTime:TimeSpan -> IQbservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- source  
  Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
  The source sequence to delay values for.

- dueTime  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The relative time by which to shift the queryable observable sequence.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
The queryable observable sequence by due time with the specified source and dueTime.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Delay\<TSource\>(IQbservable\<TSource\>, DateTimeOffset, IScheduler)

Indicates the queryable observable sequence by due time with the specified source, dueTime and scheduler.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Delay(Of TSource) ( _
    source As IQbservable(Of TSource), _
    dueTime As DateTimeOffset, _
    scheduler As IScheduler _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim dueTime As DateTimeOffset
Dim scheduler As IScheduler
Dim returnValue As IQbservable(Of TSource)

returnValue = source.Delay(dueTime, _
    scheduler)
```

```csharp
public static IQbservable<TSource> Delay<TSource>(
    this IQbservable<TSource> source,
    DateTimeOffset dueTime,
    IScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ Delay(
    IQbservable<TSource>^ source, 
    DateTimeOffset dueTime, 
    IScheduler^ scheduler
)
```

```fsharp
static member Delay : 
        source:IQbservable<'TSource> * 
        dueTime:DateTimeOffset * 
        scheduler:IScheduler -> IQbservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- source  
  Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
  The source sequence to delay values for.

- dueTime  
  Type: [System.DateTimeOffset](https://msdn.microsoft.com/en-us/library/Bb341783)  
  The absolute time used to shift the queryable observable sequence.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler to run the delay timers on.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
The queryable observable sequence by due time with the specified source, dueTime and scheduler.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Delay\<TSource\>(IQbservable\<TSource\>, TimeSpan, IScheduler)

Indicates the queryable observable sequence by due time with the specified source, dueTime and scheduler.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Delay(Of TSource) ( _
    source As IQbservable(Of TSource), _
    dueTime As TimeSpan, _
    scheduler As IScheduler _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim dueTime As TimeSpan
Dim scheduler As IScheduler
Dim returnValue As IQbservable(Of TSource)

returnValue = source.Delay(dueTime, _
    scheduler)
```

```csharp
public static IQbservable<TSource> Delay<TSource>(
    this IQbservable<TSource> source,
    TimeSpan dueTime,
    IScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ Delay(
    IQbservable<TSource>^ source, 
    TimeSpan dueTime, 
    IScheduler^ scheduler
)
```

```fsharp
static member Delay : 
        source:IQbservable<'TSource> * 
        dueTime:TimeSpan * 
        scheduler:IScheduler -> IQbservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- source  
  Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
  The source sequence to delay values for.

- dueTime  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The relative time by which to shift the queryable observable sequence.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler to run the delay timers on.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
The queryable observable sequence by due time with the specified source, dueTime and scheduler.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
