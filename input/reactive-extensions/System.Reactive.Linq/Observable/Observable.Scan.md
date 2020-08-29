title: Scan
---
# Observable.Scan Method

Applies an accumulator function over an observable sequence and returns each intermediate result.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Scan<TSource>(IObservable<TSource>, Func<TSource, TSource, TSource>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.scan%60%601(system.iobservable%7b%60%600%7d%2csystem.func%7b%60%600%2c%60%600%2c%60%600%7d)(v=VS.103))Applies an accumulator function over an observable sequence and returns each intermediate result with the specified source and accumulator.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Scan<TSource, TAccumulate>(IObservable<TSource>, TAccumulate, Func<TAccumulate, TSource, TAccumulate>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.observable.scan%60%602(system.iobservable%7b%60%600%7d%2c%60%601%2csystem.func%7b%60%601%2c%60%600%2c%60%601%7d)(v=VS.103))Applies an accumulator function over an observable sequence and returns each intermediate result with the specified source, seed and accumulator.Top

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Scan\<TSource\>(IObservable\<TSource\>, Func\<TSource, TSource, TSource\>)

Applies an accumulator function over an observable sequence and returns each intermediate result with the specified source and accumulator.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Scan(Of TSource) ( _
    source As IObservable(Of TSource), _
    accumulator As Func(Of TSource, TSource, TSource) _
) As IObservable(Of TSource)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim accumulator As Func(Of TSource, TSource, TSource)
Dim returnValue As IObservable(Of TSource)

returnValue = source.Scan(accumulator)
```

```csharp
public static IObservable<TSource> Scan<TSource>(
    this IObservable<TSource> source,
    Func<TSource, TSource, TSource> accumulator
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IObservable<TSource>^ Scan(
    IObservable<TSource>^ source, 
    Func<TSource, TSource, TSource>^ accumulator
)
```

```fsharp
static member Scan : 
        source:IObservable<'TSource> * 
        accumulator:Func<'TSource, 'TSource, 'TSource> -> IObservable<'TSource> 
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
  An observable sequence to accumulate over.

- accumulator  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb534647)\<TSource, TSource, TSource\>  
  An accumulator function to be invoked on each element.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
An observable sequence containing the accumulated values.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Scan\<TSource, TAccumulate\>(IObservable\<TSource\>, TAccumulate, Func\<TAccumulate, TSource, TAccumulate\>)

Applies an accumulator function over an observable sequence and returns each intermediate result with the specified source, seed and accumulator.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Scan(Of TSource, TAccumulate) ( _
    source As IObservable(Of TSource), _
    seed As TAccumulate, _
    accumulator As Func(Of TAccumulate, TSource, TAccumulate) _
) As IObservable(Of TAccumulate)
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim seed As TAccumulate
Dim accumulator As Func(Of TAccumulate, TSource, TAccumulate)
Dim returnValue As IObservable(Of TAccumulate)

returnValue = source.Scan(seed, accumulator)
```

```csharp
public static IObservable<TAccumulate> Scan<TSource, TAccumulate>(
    this IObservable<TSource> source,
    TAccumulate seed,
    Func<TAccumulate, TSource, TAccumulate> accumulator
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TAccumulate>
static IObservable<TAccumulate>^ Scan(
    IObservable<TSource>^ source, 
    TAccumulate seed, 
    Func<TAccumulate, TSource, TAccumulate>^ accumulator
)
```

```fsharp
static member Scan : 
        source:IObservable<'TSource> * 
        seed:'TAccumulate * 
        accumulator:Func<'TAccumulate, 'TSource, 'TAccumulate> -> IObservable<'TAccumulate> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

- TAccumulate  
  The type of accumulator.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  An observable sequence to accumulate over.

- seed  
  Type: TAccumulate  
  The initial accumulator value.

- accumulator  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb534647)\<TAccumulate, TSource, TAccumulate\>  
  An accumulator function to be invoked on each element.

#### Return Value

Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TAccumulate\>  
An observable sequence containing the accumulated values.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
