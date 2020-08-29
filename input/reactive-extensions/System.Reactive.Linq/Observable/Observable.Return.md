title: Return
---
# Observable.Return Method

Returns an observable sequence that contains a single element or value.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Return<TResult>(TResult)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.return%60%601(%60%600)(v=VS.103))Returns an observable sequence that contains a single element with a specified value.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Return<TResult>(TResult, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.return%60%601(%60%600%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Returns an observable sequence that contains a single value with a specified value and scheduler.Top

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Return\<TResult\>(TResult, IScheduler)

Returns an observable sequence that contains a single value with a specified value and scheduler.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Shared Function Return(Of TResult) ( _
    value As TResult, _
    scheduler As IScheduler _
) As IObservable(Of TResult)
```

```vb
'Usage
Dim value As TResult
Dim scheduler As IScheduler
Dim returnValue As IObservable(Of TResult)

returnValue = Observable.Return(value, _
    scheduler)
```

```csharp
public static IObservable<TResult> Return<TResult>(
    TResult value,
    IScheduler scheduler
)
```

```c++
public:
generic<typename TResult>
static IObservable<TResult>^ Return(
    TResult value, 
    IScheduler^ scheduler
)
```

```fsharp
static member Return : 
        value:'TResult * 
        scheduler:IScheduler -> IObservable<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TResult  
  The type of result.

#### Parameters

- value  
  Type: TResult  
  The single element in the resulting observable sequence.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler to send the single element on.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
Observable sequence containing the single specified element.

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Return\<TResult\>(TResult)

Returns an observable sequence that contains a single element with a specified value.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Shared Function Return(Of TResult) ( _
    value As TResult _
) As IObservable(Of TResult)
```

```vb
'Usage
Dim value As TResult
Dim returnValue As IObservable(Of TResult)

returnValue = Observable.Return(value)
```

```csharp
public static IObservable<TResult> Return<TResult>(
    TResult value
)
```

```c++
public:
generic<typename TResult>
static IObservable<TResult>^ Return(
    TResult value
)
```

```fsharp
static member Return : 
        value:'TResult -> IObservable<'TResult> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TResult  
  The type of result.

#### Parameters

- value  
  Type: TResult  
  The single element in the resulting observable sequence.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
Observable sequence containing the single specified element.

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
