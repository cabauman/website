title: Sample
---
# Qbservable.Sample Method

Samples the queryable observable sequence.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Sample<TSource, TSample>(IQbservable<TSource>, IObservable<TSample>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.sample%60%602(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.iobservable%7b%60%601%7d)(v=VS.103))Samples the queryable observable sequence at sampling ticks with the specified source and sampler.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Sample<TSource>(IQbservable<TSource>, TimeSpan)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.sample%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.timespan)(v=VS.103))Samples the queryable observable sequence at each interval.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Sample<TSource>(IQbservable<TSource>, TimeSpan, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.sample%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.timespan%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Samples the queryable observable sequence at each interval with the specified source, interval and scheduler.Top

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Sample\<TSource\>(IQbservable\<TSource\>, TimeSpan, IScheduler)

Samples the queryable observable sequence at each interval with the specified source, interval and scheduler.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Sample(Of TSource) ( _
    source As IQbservable(Of TSource), _
    interval As TimeSpan, _
    scheduler As IScheduler _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim interval As TimeSpan
Dim scheduler As IScheduler
Dim returnValue As IQbservable(Of TSource)

returnValue = source.Sample(interval, _
    scheduler)
```

```csharp
public static IQbservable<TSource> Sample<TSource>(
    this IQbservable<TSource> source,
    TimeSpan interval,
    IScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ Sample(
    IQbservable<TSource>^ source, 
    TimeSpan interval, 
    IScheduler^ scheduler
)
```

```fsharp
static member Sample : 
        source:IQbservable<'TSource> * 
        interval:TimeSpan * 
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
  The source sequence to sample.

- interval  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The interval at which to sample.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler to run the sampling timer on.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
The sampled queryable observable sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Sample\<TSource\>(IQbservable\<TSource\>, TimeSpan)

Samples the queryable observable sequence at each interval.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Sample(Of TSource) ( _
    source As IQbservable(Of TSource), _
    interval As TimeSpan _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim interval As TimeSpan
Dim returnValue As IQbservable(Of TSource)

returnValue = source.Sample(interval)
```

```csharp
public static IQbservable<TSource> Sample<TSource>(
    this IQbservable<TSource> source,
    TimeSpan interval
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ Sample(
    IQbservable<TSource>^ source, 
    TimeSpan interval
)
```

```fsharp
static member Sample : 
        source:IQbservable<'TSource> * 
        interval:TimeSpan -> IQbservable<'TSource> 
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
  The source sequence to sample.

- interval  
  Type: [System.TimeSpan](https://msdn.microsoft.com/en-us/library/269ew577)  
  The interval at which to sample.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
The sampled queryable observable sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Sample\<TSource, TSample\>(IQbservable\<TSource\>, IObservable\<TSample\>)

Samples the queryable observable sequence at sampling ticks with the specified source and sampler.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Sample(Of TSource, TSample) ( _
    source As IQbservable(Of TSource), _
    sampler As IObservable(Of TSample) _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim sampler As IObservable(Of TSample)
Dim returnValue As IQbservable(Of TSource)

returnValue = source.Sample(sampler)
```

```csharp
public static IQbservable<TSource> Sample<TSource, TSample>(
    this IQbservable<TSource> source,
    IObservable<TSample> sampler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TSample>
static IQbservable<TSource>^ Sample(
    IQbservable<TSource>^ source, 
    IObservable<TSample>^ sampler
)
```

```fsharp
static member Sample : 
        source:IQbservable<'TSource> * 
        sampler:IObservable<'TSample> -> IQbservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

- TSample  
  The type of sample.

#### Parameters

- source  
  Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
  The source sequence to sample.

- sampler  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSample\>  
  The sampling tick sequence.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
The sampled queryable observable sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
