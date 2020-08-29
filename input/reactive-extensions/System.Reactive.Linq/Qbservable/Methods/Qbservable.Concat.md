title: Concat
---
# Qbservable.Concat Method

Concatenates the queryable observable sequences.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Concat<TSource>(IQbservable<IObservable<TSource>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.concat%60%601(system.reactive.linq.iqbservable%7bsystem.iobservable%7b%60%600%7d%7d)(v=VS.103))Concatenates an enumerable sequence of queryable observable sequences.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Concat<TSource>(IQbservable<TSource>, IObservable<TSource>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.concat%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.iobservable%7b%60%600%7d)(v=VS.103))Concatenates two observable sequences.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Concat<TSource>(IQbservableProvider, IEnumerable<IObservable<TSource>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.concat%60%601(system.reactive.linq.iqbservableprovider%2csystem.collections.generic.ienumerable%7bsystem.iobservable%7b%60%600%7d%7d)(v=VS.103))Concatenates all the queryable observable sequences.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Concat<TSource>(IQbservableProvider, array<IObservable<TSource>[])](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.concat%60%601(system.reactive.linq.iqbservableprovider%2csystem.iobservable%7b%60%600%7d%5b%5d)(v=VS.103))Concatenates a queryable observable sequence of queryable observable sequences.Top

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Concat\<TSource\>(IQbservableProvider, array\<IObservable\<TSource\>\[\])

Concatenates a queryable observable sequence of queryable observable sequences.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Concat(Of TSource) ( _
    provider As IQbservableProvider, _
    ParamArray sources As IObservable(Of TSource)() _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim provider As IQbservableProvider
Dim sources As IObservable(Of TSource)()
Dim returnValue As IQbservable(Of TSource)

returnValue = provider.Concat(sources)
```

```csharp
public static IQbservable<TSource> Concat<TSource>(
    this IQbservableProvider provider,
    params IObservable<TSource>[] sources
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ Concat(
    IQbservableProvider^ provider, 
    ... array<IObservable<TSource>^>^ sources
)
```

```fsharp
static member Concat : 
        provider:IQbservableProvider * 
        sources:IObservable<'TSource>[] -> IQbservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- provider  
  Type: [System.Reactive.Linq.IQbservableProvider](IQbservableProvider/IQbservableProvider)  
  The local Qbservable provider.

- sources  
  Type: array\<[System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>\[\]  
  The queryable observable sequence of inner observable sequences.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
A queryable observable sequence that contains the elements of each observed inner sequence, in sequential order.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservableProvider](IQbservableProvider/IQbservableProvider). When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Concat\<TSource\>(IQbservable\<IObservable\<TSource\>\>)

Concatenates an enumerable sequence of queryable observable sequences.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Concat(Of TSource) ( _
    sources As IQbservable(Of IObservable(Of TSource)) _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim sources As IQbservable(Of IObservable(Of TSource))
Dim returnValue As IQbservable(Of TSource)

returnValue = sources.Concat()
```

```csharp
public static IQbservable<TSource> Concat<TSource>(
    this IQbservable<IObservable<TSource>> sources
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ Concat(
    IQbservable<IObservable<TSource>^>^ sources
)
```

```fsharp
static member Concat : 
        sources:IQbservable<IObservable<'TSource>> -> IQbservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- sources  
  Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>\>  
  The queryable observable sequences to concatenate.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
A queryable observable sequence that contains the elements of each given sequence, in sequential order.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Concat\<TSource\>(IQbservableProvider, IEnumerable\<IObservable\<TSource\>\>)

Concatenates all the queryable observable sequences.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Concat(Of TSource) ( _
    provider As IQbservableProvider, _
    sources As IEnumerable(Of IObservable(Of TSource)) _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim provider As IQbservableProvider
Dim sources As IEnumerable(Of IObservable(Of TSource))
Dim returnValue As IQbservable(Of TSource)

returnValue = provider.Concat(sources)
```

```csharp
public static IQbservable<TSource> Concat<TSource>(
    this IQbservableProvider provider,
    IEnumerable<IObservable<TSource>> sources
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ Concat(
    IQbservableProvider^ provider, 
    IEnumerable<IObservable<TSource>^>^ sources
)
```

```fsharp
static member Concat : 
        provider:IQbservableProvider * 
        sources:IEnumerable<IObservable<'TSource>> -> IQbservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- provider  
  Type: [System.Reactive.Linq.IQbservableProvider](IQbservableProvider/IQbservableProvider)  
  The local Qbservable provider.

- sources  
  Type: [System.Collections.Generic.IEnumerable](https://msdn.microsoft.com/en-us/library/9eekhta0)\<[IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>\>  
  The queryable observable sequences to concatenate.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
A queryable observable sequence that contains the elements of each given sequence, in sequential order.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservableProvider](IQbservableProvider/IQbservableProvider). When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Concat\<TSource\>(IQbservable\<TSource\>, IObservable\<TSource\>)

Concatenates two observable sequences.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Concat(Of TSource) ( _
    first As IQbservable(Of TSource), _
    second As IObservable(Of TSource) _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim first As IQbservable(Of TSource)
Dim second As IObservable(Of TSource)
Dim returnValue As IQbservable(Of TSource)

returnValue = first.Concat(second)
```

```csharp
public static IQbservable<TSource> Concat<TSource>(
    this IQbservable<TSource> first,
    IObservable<TSource> second
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ Concat(
    IQbservable<TSource>^ first, 
    IObservable<TSource>^ second
)
```

```fsharp
static member Concat : 
        first:IQbservable<'TSource> * 
        second:IObservable<'TSource> -> IQbservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- first  
  Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
  The first observable sequence.

- second  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The second observable sequence.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
A queryable observable sequence that contains the elements of the first sequence, followed by those of the second the sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
