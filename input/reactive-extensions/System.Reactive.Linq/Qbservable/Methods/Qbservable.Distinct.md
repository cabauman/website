title: Distinct
---
# Qbservable.Distinct Method

Returns a queryable observable sequence that contains only distinct elements.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Distinct<TSource>(IQbservable<TSource>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.distinct%60%601(system.reactive.linq.iqbservable%7b%60%600%7d)(v=VS.103))Returns a queryable observable sequence that contains only distinct elements with a specified source.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Distinct<TSource>(IQbservable<TSource>, IEqualityComparer<TSource>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.distinct%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.collections.generic.iequalitycomparer%7b%60%600%7d)(v=VS.103))Returns a queryable observable sequence that contains only distinct elements according to the comparer.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Distinct<TSource, TKey>(IQbservable<TSource>, Expression<Func<TSource, TKey>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.distinct%60%602(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.linq.expressions.expression%7bsystem.func%7b%60%600%2c%60%601%7d%7d)(v=VS.103))Returns a queryable observable sequence that contains only distinct elements according to the keySelector.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Distinct<TSource, TKey>(IQbservable<TSource>, Expression<Func<TSource, TKey>>, IEqualityComparer<TKey>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.distinct%60%602(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.linq.expressions.expression%7bsystem.func%7b%60%600%2c%60%601%7d%7d%2csystem.collections.generic.iequalitycomparer%7b%60%601%7d)(v=VS.103))Returns a queryable observable sequence that contains only distinct elements according to the keySelector and comparer.Top

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Distinct\<TSource\>(IQbservable\<TSource\>)

Returns a queryable observable sequence that contains only distinct elements with a specified source.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Distinct(Of TSource) ( _
    source As IQbservable(Of TSource) _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim returnValue As IQbservable(Of TSource)

returnValue = source.Distinct()
```

```csharp
public static IQbservable<TSource> Distinct<TSource>(
    this IQbservable<TSource> source
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ Distinct(
    IQbservable<TSource>^ source
)
```

```fsharp
static member Distinct : 
        source:IQbservable<'TSource> -> IQbservable<'TSource> 
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
  A queryable observable sequence to retain distinct elements for.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
A queryable observable sequence only containing the distinct elements from the source sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Distinct\<TSource\>(IQbservable\<TSource\>, IEqualityComparer\<TSource\>)

Returns a queryable observable sequence that contains only distinct elements according to the comparer.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Distinct(Of TSource) ( _
    source As IQbservable(Of TSource), _
    comparer As IEqualityComparer(Of TSource) _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim comparer As IEqualityComparer(Of TSource)
Dim returnValue As IQbservable(Of TSource)

returnValue = source.Distinct(comparer)
```

```csharp
public static IQbservable<TSource> Distinct<TSource>(
    this IQbservable<TSource> source,
    IEqualityComparer<TSource> comparer
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static IQbservable<TSource>^ Distinct(
    IQbservable<TSource>^ source, 
    IEqualityComparer<TSource>^ comparer
)
```

```fsharp
static member Distinct : 
        source:IQbservable<'TSource> * 
        comparer:IEqualityComparer<'TSource> -> IQbservable<'TSource> 
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
  A queryable observable sequence to retain distinct elements for.

- comparer  
  Type: [System.Collections.Generic.IEqualityComparer](https://msdn.microsoft.com/en-us/library/ms132151)\<TSource\>  
  The equality comparer for source elements.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
A queryable observable sequence only containing the distinct elements from the source sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Distinct\<TSource, TKey\>(IQbservable\<TSource\>, Expression\<Func\<TSource, TKey\>\>, IEqualityComparer\<TKey\>)

Returns a queryable observable sequence that contains only distinct elements according to the keySelector and comparer.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Distinct(Of TSource, TKey) ( _
    source As IQbservable(Of TSource), _
    keySelector As Expression(Of Func(Of TSource, TKey)), _
    comparer As IEqualityComparer(Of TKey) _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim keySelector As Expression(Of Func(Of TSource, TKey))
Dim comparer As IEqualityComparer(Of TKey)
Dim returnValue As IQbservable(Of TSource)

returnValue = source.Distinct(keySelector, _
    comparer)
```

```csharp
public static IQbservable<TSource> Distinct<TSource, TKey>(
    this IQbservable<TSource> source,
    Expression<Func<TSource, TKey>> keySelector,
    IEqualityComparer<TKey> comparer
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TKey>
static IQbservable<TSource>^ Distinct(
    IQbservable<TSource>^ source, 
    Expression<Func<TSource, TKey>^>^ keySelector, 
    IEqualityComparer<TKey>^ comparer
)
```

```fsharp
static member Distinct : 
        source:IQbservable<'TSource> * 
        keySelector:Expression<Func<'TSource, 'TKey>> * 
        comparer:IEqualityComparer<'TKey> -> IQbservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

- TKey  
  The type of key.

#### Parameters

- source  
  Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
  A queryable observable sequence to retain distinct elements for.

- keySelector  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<TSource, TKey\>\>  
  A function to compute the comparison key for each element.

- comparer  
  Type: [System.Collections.Generic.IEqualityComparer](https://msdn.microsoft.com/en-us/library/ms132151)\<TKey\>  
  The equality comparer for source elements.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
A queryable observable sequence only containing the distinct elements, based on a computed key value, from the source sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# Distinct\<TSource, TKey\>(IQbservable\<TSource\>, Expression\<Func\<TSource, TKey\>\>)

Returns a queryable observable sequence that contains only distinct elements according to the keySelector.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Distinct(Of TSource, TKey) ( _
    source As IQbservable(Of TSource), _
    keySelector As Expression(Of Func(Of TSource, TKey)) _
) As IQbservable(Of TSource)
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim keySelector As Expression(Of Func(Of TSource, TKey))
Dim returnValue As IQbservable(Of TSource)

returnValue = source.Distinct(keySelector)
```

```csharp
public static IQbservable<TSource> Distinct<TSource, TKey>(
    this IQbservable<TSource> source,
    Expression<Func<TSource, TKey>> keySelector
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TKey>
static IQbservable<TSource>^ Distinct(
    IQbservable<TSource>^ source, 
    Expression<Func<TSource, TKey>^>^ keySelector
)
```

```fsharp
static member Distinct : 
        source:IQbservable<'TSource> * 
        keySelector:Expression<Func<'TSource, 'TKey>> -> IQbservable<'TSource> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

- TKey  
  The type of key.

#### Parameters

- source  
  Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
  A queryable observable sequence to retain distinct elements for.

- keySelector  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<TSource, TKey\>\>  
  A function to compute the comparison key for each element.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
A queryable observable sequence only containing the distinct elements, based on a computed key value from the source sequence.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
