title: Repeat
---
# Observable.Repeat Method

Repeats the observable sequence.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Repeat<TSource>(IObservable<TSource>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.repeat%60%601(system.iobservable%7b%60%600%7d)(v=VS.103))Repeats the observable sequence indefinitely.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Repeat<TResult>(TResult)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.repeat%60%601(%60%600)(v=VS.103))Generates an observable sequence that repeats the given element infinitely.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Repeat<TSource>(IObservable<TSource>, Int32)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.repeat%60%601(system.iobservable%7b%60%600%7d%2csystem.int32)(v=VS.103))Repeats the observable sequence indefinitely.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Repeat<TResult>(TResult, Int32)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.repeat%60%601(%60%600%2csystem.int32)(v=VS.103))Generates an observable sequence that repeats the given element the specified number of times.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Repeat<TResult>(TResult, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.repeat%60%601(%60%600%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Generates an observable sequence that repeats the given element infinitely.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Repeat<TResult>(TResult, Int32, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.repeat%60%601(%60%600%2csystem.int32%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Generates an observable sequence that repeats the given element of the specified number of times.Top

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Repeat\<TSource\>(IObservable\<TSource\>, Int32)

Repeats the observable sequence indefinitely.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Repeat(Of TSource) ( _
    source As IObservable(Of TSource), _
    repeatCount As Integer _
) As IObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim repeatCount As Integer
Dim returnValue As IObservable(Of TSource)

returnValue = source.Repeat(repeatCount)
```

```csharp
public static IObservable<TSource> Repeat<TSource>(
    this IObservable<TSource> source,
    int repeatCount
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<TSource>^ Repeat(
    IObservable<TSource>^ source, 
    int repeatCount
)
```

```fsharp
static member Repeat : 
        source:IObservable<'TSource> * 
        repeatCount:int -> IObservable<'TSource> 
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
  The observable sequence to repeat.

- repeatCount  
  Type: [System.Int32](https://msdn.microsoft.com/en-us/library/td2s409d)  
  The number of times to repeat the sequence.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
The observable sequence producing the elements of the given sequence repeatedly.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Repeat\<TSource\>(IObservable\<TSource\>)

Repeats the observable sequence indefinitely.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Repeat(Of TSource) ( _
    source As IObservable(Of TSource) _
) As IObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim returnValue As IObservable(Of TSource)

returnValue = source.Repeat()
```

```csharp
public static IObservable<TSource> Repeat<TSource>(
    this IObservable<TSource> source
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<TSource>^ Repeat(
    IObservable<TSource>^ source
)
```

```fsharp
static member Repeat : 
        source:IObservable<'TSource> -> IObservable<'TSource> 
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
  The observable sequence to repeat.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
The observable sequence producing the elements of the given sequence repeatedly and sequentially.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Repeat\<TResult\>(TResult, Int32, IScheduler)

Generates an observable sequence that repeats the given element of the specified number of times.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Shared Function Repeat(Of TResult) ( _
    value As TResult, _
    repeatCount As Integer, _
    scheduler As IScheduler _
) As IObservable(Of TResult)
```

```vb
'Usage
Dim value As TResult
Dim repeatCount As Integer
Dim scheduler As IScheduler
Dim returnValue As IObservable(Of TResult)

returnValue = Observable.Repeat(value, _
    repeatCount, scheduler)
```

```csharp
public static IObservable<TResult> Repeat<TResult>(
    TResult value,
    int repeatCount,
    IScheduler scheduler
)
```

```c++
public:
generic<typename TResult>
static IObservable<TResult>^ Repeat(
    TResult value, 
    int repeatCount, 
    IScheduler^ scheduler
)
```

```fsharp
static member Repeat : 
        value:'TResult * 
        repeatCount:int * 
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
  The element to repeat.

- repeatCount  
  Type: [System.Int32](https://msdn.microsoft.com/en-us/library/td2s409d)  
  The number of times to repeat the element.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler to run the producer loop on.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
An observable sequence that repeats the given element of the specified number of times.

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Repeat\<TResult\>(TResult, Int32)

Generates an observable sequence that repeats the given element the specified number of times.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Shared Function Repeat(Of TResult) ( _
    value As TResult, _
    repeatCount As Integer _
) As IObservable(Of TResult)
```

```vb
'Usage
Dim value As TResult
Dim repeatCount As Integer
Dim returnValue As IObservable(Of TResult)

returnValue = Observable.Repeat(value, _
    repeatCount)
```

```csharp
public static IObservable<TResult> Repeat<TResult>(
    TResult value,
    int repeatCount
)
```

```c++
public:
generic<typename TResult>
static IObservable<TResult>^ Repeat(
    TResult value, 
    int repeatCount
)
```

```fsharp
static member Repeat : 
        value:'TResult * 
        repeatCount:int -> IObservable<'TResult> 
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
  The element to repeat.

- repeatCount  
  Type: [System.Int32](https://msdn.microsoft.com/en-us/library/td2s409d)  
  The number of times to repeat the element.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
An observable sequence that repeats the given element the specified number of times.

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Repeat\<TResult\>(TResult)

Generates an observable sequence that repeats the given element infinitely.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Shared Function Repeat(Of TResult) ( _
    value As TResult _
) As IObservable(Of TResult)
```

```vb
'Usage
Dim value As TResult
Dim returnValue As IObservable(Of TResult)

returnValue = Observable.Repeat(value)
```

```csharp
public static IObservable<TResult> Repeat<TResult>(
    TResult value
)
```

```c++
public:
generic<typename TResult>
static IObservable<TResult>^ Repeat(
    TResult value
)
```

```fsharp
static member Repeat : 
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
  The element to repeat.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
An observable sequence that repeats the given element infinitely.

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Repeat\<TResult\>(TResult, IScheduler)

Generates an observable sequence that repeats the given element infinitely.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public Shared Function Repeat(Of TResult) ( _
    value As TResult, _
    scheduler As IScheduler _
) As IObservable(Of TResult)
```

```vb
'Usage
Dim value As TResult
Dim scheduler As IScheduler
Dim returnValue As IObservable(Of TResult)

returnValue = Observable.Repeat(value, _
    scheduler)
```

```csharp
public static IObservable<TResult> Repeat<TResult>(
    TResult value,
    IScheduler scheduler
)
```

```c++
public:
generic<typename TResult>
static IObservable<TResult>^ Repeat(
    TResult value, 
    IScheduler^ scheduler
)
```

```fsharp
static member Repeat : 
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
  The element to repeat.

- scheduler  
  Type: [System.Reactive.Concurrency.IScheduler](IScheduler/IScheduler)  
  The scheduler to run the producer loop on.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TResult\>  
The observable sequence that repeats the given element infinitely.

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
