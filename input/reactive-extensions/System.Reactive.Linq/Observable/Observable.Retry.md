title: Retry
---
# Observable.Retry Method

Repeats the source observable sequence until it successfully terminates.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Retry<TSource>(IObservable<TSource>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.retry%60%601(system.iobservable%7b%60%600%7d)(v=VS.103))Repeats the source observable sequence until it successfully terminates.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Retry<TSource>(IObservable<TSource>, Int32)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.retry%60%601(system.iobservable%7b%60%600%7d%2csystem.int32)(v=VS.103))Repeats the source observable sequence until it successfully terminates.Top

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Retry\<TSource\>(IObservable\<TSource\>)

Repeats the source observable sequence until it successfully terminates.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Retry(Of TSource) ( _
    source As IObservable(Of TSource) _
) As IObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim returnValue As IObservable(Of TSource)

returnValue = source.Retry()
```

```csharp
public static IObservable<TSource> Retry<TSource>(
    this IObservable<TSource> source
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<TSource>^ Retry(
    IObservable<TSource>^ source
)
```

```fsharp
static member Retry : 
        source:IObservable<'TSource> -> IObservable<'TSource> 
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
  Observable sequence to repeat until it successfully terminates.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
Observable sequence producing the elements of the given sequence repeatedly until it terminates successfully.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Retry\<TSource\>(IObservable\<TSource\>, Int32)

Repeats the source observable sequence until it successfully terminates.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Retry(Of TSource) ( _
    source As IObservable(Of TSource), _
    retryCount As Integer _
) As IObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim retryCount As Integer
Dim returnValue As IObservable(Of TSource)

returnValue = source.Retry(retryCount)
```

```csharp
public static IObservable<TSource> Retry<TSource>(
    this IObservable<TSource> source,
    int retryCount
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<TSource>^ Retry(
    IObservable<TSource>^ source, 
    int retryCount
)
```

```fsharp
static member Retry : 
        source:IObservable<'TSource> * 
        retryCount:int -> IObservable<'TSource> 
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
  Observable sequence to repeat until it successfully terminates.

- retryCount  
  Type: [System.Int32](https://msdn.microsoft.com/en-us/library/td2s409d)  
  Number of times to repeat the sequence.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
Observable sequence producing the elements of the given sequence repeatedly until it terminates successfully.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
