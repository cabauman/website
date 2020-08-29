title: Scan
---
# Qbservable.Scan Method

Applies an accumulator function over a queryable observable sequence and returns each intermediate result.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Scan<TSource>(IQbservable<TSource>, Expression<Func<TSource, TSource, TSource>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.scan%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.linq.expressions.expression%7bsystem.func%7b%60%600%2c%60%600%2c%60%600%7d%7d)(v=VS.103))Applies an accumulator function over a queryable observable sequence and returns each intermediate result with the specified source and accumulator.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Scan<TSource, TAccumulate>(IQbservable<TSource>, TAccumulate, Expression<Func<TAccumulate, TSource, TAccumulate>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.scan%60%602(system.reactive.linq.iqbservable%7b%60%600%7d%2c%60%601%2csystem.linq.expressions.expression%7bsystem.func%7b%60%601%2c%60%600%2c%60%601%7d%7d)(v=VS.103))Applies an accumulator function over a queryable observable sequence and returns each intermediate result with the specified source, seed and accumulator.Top

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Scan\<TSource\>(IQbservable\<TSource\>, Expression\<Func\<TSource, TSource, TSource\>\>)

Applies an accumulator function over a queryable observable sequence and returns each intermediate result with the specified source and accumulator.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Scan(Of TSource) ( _
    source As IQbservable(Of TSource), _
    accumulator As Expression(Of Func(Of TSource, TSource, TSource)) _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim accumulator As Expression(Of Func(Of TSource, TSource, TSource))
Dim returnValue As IQbservable(Of TSource)

returnValue = source.Scan(accumulator)
```

```csharp
public static IQbservable<TSource> Scan<TSource>(
    this IQbservable<TSource> source,
    Expression<Func<TSource, TSource, TSource>> accumulator
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ Scan(
    IQbservable<TSource>^ source, 
    Expression<Func<TSource, TSource, TSource>^>^ accumulator
)
```

```fsharp
static member Scan : 
        source:IQbservable<'TSource> * 
        accumulator:Expression<Func<'TSource, 'TSource, 'TSource>> -> IQbservable<'TSource> 
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
  A queryable observable sequence to accumulate over.

- accumulator  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Func](https://msdn.microsoft.com/en-us/library/Bb534647)\<TSource, TSource, TSource\>\>  
  An accumulator function to be invoked on each element.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
A queryable observable sequence containing the accumulated values.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Scan\<TSource, TAccumulate\>(IQbservable\<TSource\>, TAccumulate, Expression\<Func\<TAccumulate, TSource, TAccumulate\>\>)

Applies an accumulator function over a queryable observable sequence and returns each intermediate result with the specified source, seed and accumulator.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Scan(Of TSource, TAccumulate) ( _
    source As IQbservable(Of TSource), _
    seed As TAccumulate, _
    accumulator As Expression(Of Func(Of TAccumulate, TSource, TAccumulate)) _
) As IQbservable(Of TAccumulate)
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim seed As TAccumulate
Dim accumulator As Expression(Of Func(Of TAccumulate, TSource, TAccumulate))
Dim returnValue As IQbservable(Of TAccumulate)

returnValue = source.Scan(seed, accumulator)
```

```csharp
public static IQbservable<TAccumulate> Scan<TSource, TAccumulate>(
    this IQbservable<TSource> source,
    TAccumulate seed,
    Expression<Func<TAccumulate, TSource, TAccumulate>> accumulator
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TAccumulate>
static IQbservable<TAccumulate>^ Scan(
    IQbservable<TSource>^ source, 
    TAccumulate seed, 
    Expression<Func<TAccumulate, TSource, TAccumulate>^>^ accumulator
)
```

```fsharp
static member Scan : 
        source:IQbservable<'TSource> * 
        seed:'TAccumulate * 
        accumulator:Expression<Func<'TAccumulate, 'TSource, 'TAccumulate>> -> IQbservable<'TAccumulate> 
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
  Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
  A queryable observable sequence to accumulate over.

- seed  
  Type: TAccumulate  
  The initial accumulator value.

- accumulator  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Func](https://msdn.microsoft.com/en-us/library/Bb534647)\<TAccumulate, TSource, TAccumulate\>\>  
  An accumulator function to be invoked on each element.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TAccumulate\>  
A queryable observable sequence containing the accumulated values.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
