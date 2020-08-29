title: MaxBy
---
# Qbservable.MaxBy Method

Returns the elements in a queryable observable sequence with the maximum key value.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[MaxBy<TSource, TKey>(IQbservable<TSource>, Expression<Func<TSource, TKey>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.maxby%60%602(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.linq.expressions.expression%7bsystem.func%7b%60%600%2c%60%601%7d%7d)(v=VS.103))Returns the elements in a queryable observable sequence with the maximum key value.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[MaxBy<TSource, TKey>(IQbservable<TSource>, Expression<Func<TSource, TKey>>, IComparer<TKey>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.maxby%60%602(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.linq.expressions.expression%7bsystem.func%7b%60%600%2c%60%601%7d%7d%2csystem.collections.generic.icomparer%7b%60%601%7d)(v=VS.103))Returns the elements in a queryable observable sequence with the maximum key value.Top

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# MaxBy\<TSource, TKey\>(IQbservable\<TSource\>, Expression\<Func\<TSource, TKey\>\>)

Returns the elements in a queryable observable sequence with the maximum key value.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function MaxBy(Of TSource, TKey) ( _
    source As IQbservable(Of TSource), _
    keySelector As Expression(Of Func(Of TSource, TKey)) _
) As IQbservable(Of IList(Of TSource))
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim keySelector As Expression(Of Func(Of TSource, TKey))
Dim returnValue As IQbservable(Of IList(Of TSource))

returnValue = source.MaxBy(keySelector)
```

```csharp
public static IQbservable<IList<TSource>> MaxBy<TSource, TKey>(
    this IQbservable<TSource> source,
    Expression<Func<TSource, TKey>> keySelector
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TKey>
static IQbservable<IList<TSource>^>^ MaxBy(
    IQbservable<TSource>^ source, 
    Expression<Func<TSource, TKey>^>^ keySelector
)
```

```fsharp
static member MaxBy : 
        source:IQbservable<'TSource> * 
        keySelector:Expression<Func<'TSource, 'TKey>> -> IQbservable<IList<'TSource>> 
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
  A queryable observable sequence to get the maximum elements for.

- keySelector  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<TSource, TKey\>\>  
  The key selector function.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<[IList](https://msdn.microsoft.com/en-us/library/5y536ey6)\<TSource\>\>  
The elements in a queryable observable sequence with the maximum key value.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# MaxBy\<TSource, TKey\>(IQbservable\<TSource\>, Expression\<Func\<TSource, TKey\>\>, IComparer\<TKey\>)

Returns the elements in a queryable observable sequence with the maximum key value.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function MaxBy(Of TSource, TKey) ( _
    source As IQbservable(Of TSource), _
    keySelector As Expression(Of Func(Of TSource, TKey)), _
    comparer As IComparer(Of TKey) _
) As IQbservable(Of IList(Of TSource))
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim keySelector As Expression(Of Func(Of TSource, TKey))
Dim comparer As IComparer(Of TKey)
Dim returnValue As IQbservable(Of IList(Of TSource))

returnValue = source.MaxBy(keySelector, _
    comparer)
```

```csharp
public static IQbservable<IList<TSource>> MaxBy<TSource, TKey>(
    this IQbservable<TSource> source,
    Expression<Func<TSource, TKey>> keySelector,
    IComparer<TKey> comparer
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TKey>
static IQbservable<IList<TSource>^>^ MaxBy(
    IQbservable<TSource>^ source, 
    Expression<Func<TSource, TKey>^>^ keySelector, 
    IComparer<TKey>^ comparer
)
```

```fsharp
static member MaxBy : 
        source:IQbservable<'TSource> * 
        keySelector:Expression<Func<'TSource, 'TKey>> * 
        comparer:IComparer<'TKey> -> IQbservable<IList<'TSource>> 
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
  A queryable observable sequence to get the maximum elements for.

- keySelector  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<TSource, TKey\>\>  
  The key selector function.

- comparer  
  Type: [System.Collections.Generic.IComparer](https://msdn.microsoft.com/en-us/library/8ehhxeaf)\<TKey\>  
  The comparer used to compare key values.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<[IList](https://msdn.microsoft.com/en-us/library/5y536ey6)\<TSource\>\>  
The elements in a queryable observable sequence with the maximum key value.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
