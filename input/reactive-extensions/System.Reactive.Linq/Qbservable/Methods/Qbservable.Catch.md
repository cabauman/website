title: Catch
---
# Qbservable.Catch Method

Continues a queryable observable sequence that is terminated by an exception.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Catch<TSource>(IQbservable<TSource>, IObservable<TSource>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.catch%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.iobservable%7b%60%600%7d)(v=VS.103))Continues a queryable observable sequence that is terminated by an exception with the next queryable observable sequence.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Catch<TSource, TException>(IQbservable<TSource>, Expression<Func<TException, IObservable<TSource>>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.catch%60%602(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.linq.expressions.expression%7bsystem.func%7b%60%601%2csystem.iobservable%7b%60%600%7d%7d%7d)(v=VS.103))Continues a queryable observable sequence that is terminated by an exception of the specified type with the queryable observable sequence produced by the handler.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Catch<TSource>(IQbservableProvider, IEnumerable<IObservable<TSource>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.catch%60%601(system.reactive.linq.iqbservableprovider%2csystem.collections.generic.ienumerable%7bsystem.iobservable%7b%60%600%7d%7d)(v=VS.103))Continues a queryable observable sequence that is terminated by an exception with the next queryableobservable sequence.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Catch<TSource>(IQbservableProvider, array<IObservable<TSource>[])](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.catch%60%601(system.reactive.linq.iqbservableprovider%2csystem.iobservable%7b%60%600%7d%5b%5d)(v=VS.103))Continues a queryable observable sequence that is terminated by an exception with the next queryable observable sequence.Top

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Catch\<TSource\>(IQbservable\<TSource\>, IObservable\<TSource\>)

Continues a queryable observable sequence that is terminated by an exception with the next queryable observable sequence.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Catch(Of TSource) ( _
    first As IQbservable(Of TSource), _
    second As IObservable(Of TSource) _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim first As IQbservable(Of TSource)
Dim second As IObservable(Of TSource)
Dim returnValue As IQbservable(Of TSource)

returnValue = first.Catch(second)
```

```csharp
public static IQbservable<TSource> Catch<TSource>(
    this IQbservable<TSource> first,
    IObservable<TSource> second
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ Catch(
    IQbservable<TSource>^ first, 
    IObservable<TSource>^ second
)
```

```fsharp
static member Catch : 
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
  First queryable observable sequence whose exception (if any) is caught.

- second  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The second queryable observable sequence used to produce results when an error occurred in the first sequence.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
A queryable observable sequence containing the first sequence's elements, followed by the elements of the second sequence in case an exception occurred.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Catch\<TSource\>(IQbservableProvider, IEnumerable\<IObservable\<TSource\>\>)

Continues a queryable observable sequence that is terminated by an exception with the next queryableobservable sequence.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Catch(Of TSource) ( _
    provider As IQbservableProvider, _
    sources As IEnumerable(Of IObservable(Of TSource)) _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim provider As IQbservableProvider
Dim sources As IEnumerable(Of IObservable(Of TSource))
Dim returnValue As IQbservable(Of TSource)

returnValue = provider.Catch(sources)
```

```csharp
public static IQbservable<TSource> Catch<TSource>(
    this IQbservableProvider provider,
    IEnumerable<IObservable<TSource>> sources
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ Catch(
    IQbservableProvider^ provider, 
    IEnumerable<IObservable<TSource>^>^ sources
)
```

```fsharp
static member Catch : 
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
  The queryable observable sequences to catch exceptions for.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
A queryable observable sequence containing elements from consecutive source sequences until a source sequence terminates successfully.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservableProvider](IQbservableProvider/IQbservableProvider). When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Catch\<TSource\>(IQbservableProvider, array\<IObservable\<TSource\>\[\])

Continues a queryable observable sequence that is terminated by an exception with the next queryable observable sequence.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Catch(Of TSource) ( _
    provider As IQbservableProvider, _
    ParamArray sources As IObservable(Of TSource)() _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim provider As IQbservableProvider
Dim sources As IObservable(Of TSource)()
Dim returnValue As IQbservable(Of TSource)

returnValue = provider.Catch(sources)
```

```csharp
public static IQbservable<TSource> Catch<TSource>(
    this IQbservableProvider provider,
    params IObservable<TSource>[] sources
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ Catch(
    IQbservableProvider^ provider, 
    ... array<IObservable<TSource>^>^ sources
)
```

```fsharp
static member Catch : 
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
  The queryable observable sequences to catch exceptions for.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
A queryable observable sequence containing elements from consecutive source sequences until a source sequence terminates successfully.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservableProvider](IQbservableProvider/IQbservableProvider). When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Catch\<TSource, TException\>(IQbservable\<TSource\>, Expression\<Func\<TException, IObservable\<TSource\>\>\>)

Continues a queryable observable sequence that is terminated by an exception of the specified type with the queryable observable sequence produced by the handler.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Catch(Of TSource, TException) ( _
    source As IQbservable(Of TSource), _
    handler As Expression(Of Func(Of TException, IObservable(Of TSource))) _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim handler As Expression(Of Func(Of TException, IObservable(Of TSource)))
Dim returnValue As IQbservable(Of TSource)

returnValue = source.Catch(handler)
```

```csharp
public static IQbservable<TSource> Catch<TSource, TException>(
    this IQbservable<TSource> source,
    Expression<Func<TException, IObservable<TSource>>> handler
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TException>
static IQbservable<TSource>^ Catch(
    IQbservable<TSource>^ source, 
    Expression<Func<TException, IObservable<TSource>^>^>^ handler
)
```

```fsharp
static member Catch : 
        source:IQbservable<'TSource> * 
        handler:Expression<Func<'TException, IObservable<'TSource>>> -> IQbservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

- TException  
  The type of the exception.

#### Parameters

- source  
  Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
  The source sequence.

- handler  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<TException, [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>\>\>  
  The exception handler function, producing another queryable observable sequence.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
A queryable observable sequence containing the source sequence's elements, followed by the elements produced by the handler's resulting queryable observable sequence in case an exception occurred.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
