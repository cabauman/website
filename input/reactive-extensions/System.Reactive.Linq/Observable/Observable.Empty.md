title: Empty
---
# Observable.Empty Method

Returns an empty observable sequence.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Empty<TResult>()](Empty/Observable.Empty(TResult))Returns an empty observable sequence.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Empty<TResult>(IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.empty%60%601(system.reactive.concurrency.ischeduler)(v=VS.103))Returns an empty observable sequence with the specified scheduler.Top

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Observable.Empty\<TResult\> Method

Returns an empty observable sequence.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Shared Function Empty(Of TResult) As IObservable(Of TResult)
```

```vb
'Usage
Dim returnValue As IObservable(Of TResult)

returnValue = Observable.Empty()
```

```csharp
public static IObservable<TResult> Empty<TResult>()
```

```c++
public:
generic<typename TResult>
static IObservable<TResult>^ Empty()
```

```fsharp
static member Empty : unit -> IObservable<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TResult  
  The type of result.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
The observable sequence with no elements.

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Empty\<TResult\>(IScheduler)

Returns an empty observable sequence with the specified scheduler.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Shared Function Empty(Of TResult) ( _
    scheduler As IScheduler _
) As IObservable(Of TResult)
```

```vb
'Usage
Dim scheduler As IScheduler
Dim returnValue As IObservable(Of TResult)

returnValue = Observable.Empty(scheduler)
```

```csharp
public static IObservable<TResult> Empty<TResult>(
    IScheduler scheduler
)
```

```c++
public:
generic<typename TResult>
static IObservable<TResult>^ Empty(
    IScheduler^ scheduler
)
```

```fsharp
static member Empty : 
        scheduler:IScheduler -> IObservable<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TResult  
  The type of result.

#### Parameters

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler to send the termination call.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
The observable sequence with no elements.

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
