title: ObserveOn
---
# Observable.ObserveOn Method

Asynchronously notify observers on the specified scheduler and context.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[ObserveOn<TSource>(IObservable<TSource>, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.observeon%60%601(system.iobservable%7b%60%600%7d%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Asynchronously notify observers on the specified scheduler.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[ObserveOn<TSource>(IObservable<TSource>, SynchronizationContext)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.observeon%60%601(system.iobservable%7b%60%600%7d%2csystem.threading.synchronizationcontext)(v=VS.103))Asynchronously notify observers on the specified synchronization context.Top

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# ObserveOn\<TSource\>(IObservable\<TSource\>, SynchronizationContext)

Asynchronously notify observers on the specified synchronization context.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function ObserveOn(Of TSource) ( _
    source As IObservable(Of TSource), _
    context As SynchronizationContext _
) As IObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim context As SynchronizationContext
Dim returnValue As IObservable(Of TSource)

returnValue = source.ObserveOn(context)
```

```csharp
public static IObservable<TSource> ObserveOn<TSource>(
    this IObservable<TSource> source,
    SynchronizationContext context
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<TSource>^ ObserveOn(
    IObservable<TSource>^ source, 
    SynchronizationContext^ context
)
```

```fsharp
static member ObserveOn : 
        source:IObservable<'TSource> * 
        context:SynchronizationContext -> IObservable<'TSource> 
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
  The source sequence.

- context  
  Type: [System.Threading.SynchronizationContext](https://msdn.microsoft.com/en-us/library/wx31754f)  
  The synchronization context to notify observers on.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
The source sequence whose observations happen on the specified synchronization context.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# ObserveOn\<TSource\>(IObservable\<TSource\>, IScheduler)

Asynchronously notify observers on the specified scheduler.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function ObserveOn(Of TSource) ( _
    source As IObservable(Of TSource), _
    scheduler As IScheduler _
) As IObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim scheduler As IScheduler
Dim returnValue As IObservable(Of TSource)

returnValue = source.ObserveOn(scheduler)
```

```csharp
public static IObservable<TSource> ObserveOn<TSource>(
    this IObservable<TSource> source,
    IScheduler scheduler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<TSource>^ ObserveOn(
    IObservable<TSource>^ source, 
    IScheduler^ scheduler
)
```

```fsharp
static member ObserveOn : 
        source:IObservable<'TSource> * 
        scheduler:IScheduler -> IObservable<'TSource> 
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
  The source sequence.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler to notify observers on.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
The source sequence whose observations happen on the specified scheduler.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
