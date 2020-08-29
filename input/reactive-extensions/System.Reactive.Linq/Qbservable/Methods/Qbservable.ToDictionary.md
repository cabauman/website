title: ToDictionary
---
# Qbservable.ToDictionary Method

Creates a dictionary from a queryable observable sequence.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[ToDictionary<TSource, TKey>(IQbservable<TSource>, Expression<Func<TSource, TKey>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.todictionary%60%602(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.linq.expressions.expression%7bsystem.func%7b%60%600%2c%60%601%7d%7d)(v=VS.103))Creates a dictionary from a queryable observable sequence according to a specified key selector function.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[ToDictionary<TSource, TKey>(IQbservable<TSource>, Expression<Func<TSource, TKey>>, IEqualityComparer<TKey>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.todictionary%60%602(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.linq.expressions.expression%7bsystem.func%7b%60%600%2c%60%601%7d%7d%2csystem.collections.generic.iequalitycomparer%7b%60%601%7d)(v=VS.103))Creates a dictionary from a queryable observable sequence according to a specified key selector function, and a comparer.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[ToDictionary<TSource, TKey, TElement>(IQbservable<TSource>, Expression<Func<TSource, TKey>>, Expression<Func<TSource, TElement>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.todictionary%60%603(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.linq.expressions.expression%7bsystem.func%7b%60%600%2c%60%601%7d%7d%2csystem.linq.expressions.expression%7bsystem.func%7b%60%600%2c%60%602%7d%7d)(v=VS.103))Creates a dictionary from a queryable observable sequence according to a specified key selector function, and an element selector function.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[ToDictionary<TSource, TKey, TElement>(IQbservable<TSource>, Expression<Func<TSource, TKey>>, Expression<Func<TSource, TElement>>, IEqualityComparer<TKey>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.todictionary%60%603(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.linq.expressions.expression%7bsystem.func%7b%60%600%2c%60%601%7d%7d%2csystem.linq.expressions.expression%7bsystem.func%7b%60%600%2c%60%602%7d%7d%2csystem.collections.generic.iequalitycomparer%7b%60%601%7d)(v=VS.103))Creates a dictionary from a queryable observable sequence according to a specified key selector function, a comparer, and an element selector function.Top

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# ToDictionary\<TSource, TKey\>(IQbservable\<TSource\>, Expression\<Func\<TSource, TKey\>\>)

Creates a dictionary from a queryable observable sequence according to a specified key selector function.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function ToDictionary(Of TSource, TKey) ( _
    source As IQbservable(Of TSource), _
    keySelector As Expression(Of Func(Of TSource, TKey)) _
) As IQbservable(Of IDictionary(Of TKey, TSource))
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim keySelector As Expression(Of Func(Of TSource, TKey))
Dim returnValue As IQbservable(Of IDictionary(Of TKey, TSource))

returnValue = source.ToDictionary(keySelector)
```

```csharp
public static IQbservable<IDictionary<TKey, TSource>> ToDictionary<TSource, TKey>(
    this IQbservable<TSource> source,
    Expression<Func<TSource, TKey>> keySelector
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TKey>
static IQbservable<IDictionary<TKey, TSource>^>^ ToDictionary(
    IQbservable<TSource>^ source, 
    Expression<Func<TSource, TKey>^>^ keySelector
)
```

```fsharp
static member ToDictionary : 
        source:IQbservable<'TSource> * 
        keySelector:Expression<Func<'TSource, 'TKey>> -> IQbservable<IDictionary<'TKey, 'TSource>> 
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
  A queryable observable sequence to create a dictionary for.

- keySelector  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<TSource, TKey\>\>  
  A function to extract a key from each element.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<[IDictionary](https://msdn.microsoft.com/en-us/library/s4ys34ea)\<TKey, TSource\>\>  
A dictionary from a queryable observable sequence according to a specified key selector function.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# ToDictionary\<TSource, TKey, TElement\>(IQbservable\<TSource\>, Expression\<Func\<TSource, TKey\>\>, Expression\<Func\<TSource, TElement\>\>)

Creates a dictionary from a queryable observable sequence according to a specified key selector function, and an element selector function.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function ToDictionary(Of TSource, TKey, TElement) ( _
    source As IQbservable(Of TSource), _
    keySelector As Expression(Of Func(Of TSource, TKey)), _
    elementSelector As Expression(Of Func(Of TSource, TElement)) _
) As IQbservable(Of IDictionary(Of TKey, TElement))
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim keySelector As Expression(Of Func(Of TSource, TKey))
Dim elementSelector As Expression(Of Func(Of TSource, TElement))
Dim returnValue As IQbservable(Of IDictionary(Of TKey, TElement))

returnValue = source.ToDictionary(keySelector, _
    elementSelector)
```

```csharp
public static IQbservable<IDictionary<TKey, TElement>> ToDictionary<TSource, TKey, TElement>(
    this IQbservable<TSource> source,
    Expression<Func<TSource, TKey>> keySelector,
    Expression<Func<TSource, TElement>> elementSelector
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TKey, typename TElement>
static IQbservable<IDictionary<TKey, TElement>^>^ ToDictionary(
    IQbservable<TSource>^ source, 
    Expression<Func<TSource, TKey>^>^ keySelector, 
    Expression<Func<TSource, TElement>^>^ elementSelector
)
```

```fsharp
static member ToDictionary : 
        source:IQbservable<'TSource> * 
        keySelector:Expression<Func<'TSource, 'TKey>> * 
        elementSelector:Expression<Func<'TSource, 'TElement>> -> IQbservable<IDictionary<'TKey, 'TElement>> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

- TKey  
  The type of key.

- TElement  
  The type of element.

#### Parameters

- source  
  Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
  A queryable observable sequence to create a dictionary for.

- keySelector  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<TSource, TKey\>\>  
  A function to extract a key from each element.

- elementSelector  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<TSource, TElement\>\>  
  A transform function to produce a result element value from each element.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<[IDictionary](https://msdn.microsoft.com/en-us/library/s4ys34ea)\<TKey, TElement\>\>  
A dictionary from a queryable observable sequence according to a specified key selector function, and an element selector function.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# ToDictionary\<TSource, TKey, TElement\>(IQbservable\<TSource\>, Expression\<Func\<TSource, TKey\>\>, Expression\<Func\<TSource, TElement\>\>, IEqualityComparer\<TKey\>)

Creates a dictionary from a queryable observable sequence according to a specified key selector function, a comparer, and an element selector function.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function ToDictionary(Of TSource, TKey, TElement) ( _
    source As IQbservable(Of TSource), _
    keySelector As Expression(Of Func(Of TSource, TKey)), _
    elementSelector As Expression(Of Func(Of TSource, TElement)), _
    comparer As IEqualityComparer(Of TKey) _
) As IQbservable(Of IDictionary(Of TKey, TElement))
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim keySelector As Expression(Of Func(Of TSource, TKey))
Dim elementSelector As Expression(Of Func(Of TSource, TElement))
Dim comparer As IEqualityComparer(Of TKey)
Dim returnValue As IQbservable(Of IDictionary(Of TKey, TElement))

returnValue = source.ToDictionary(keySelector, _
    elementSelector, comparer)
```

```csharp
public static IQbservable<IDictionary<TKey, TElement>> ToDictionary<TSource, TKey, TElement>(
    this IQbservable<TSource> source,
    Expression<Func<TSource, TKey>> keySelector,
    Expression<Func<TSource, TElement>> elementSelector,
    IEqualityComparer<TKey> comparer
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TKey, typename TElement>
static IQbservable<IDictionary<TKey, TElement>^>^ ToDictionary(
    IQbservable<TSource>^ source, 
    Expression<Func<TSource, TKey>^>^ keySelector, 
    Expression<Func<TSource, TElement>^>^ elementSelector, 
    IEqualityComparer<TKey>^ comparer
)
```

```fsharp
static member ToDictionary : 
        source:IQbservable<'TSource> * 
        keySelector:Expression<Func<'TSource, 'TKey>> * 
        elementSelector:Expression<Func<'TSource, 'TElement>> * 
        comparer:IEqualityComparer<'TKey> -> IQbservable<IDictionary<'TKey, 'TElement>> 
```

```jscript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

- TKey  
  The type of key.

- TElement  
  The type of element.

#### Parameters

- source  
  Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<TSource\>  
  A queryable observable sequence to create a dictionary for.

- keySelector  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<TSource, TKey\>\>  
  A function to extract a key from each element.

- elementSelector  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<TSource, TElement\>\>  
  A transform function to produce a result element value from each element.

- comparer  
  Type: [System.Collections.Generic.IEqualityComparer](https://msdn.microsoft.com/en-us/library/ms132151)\<TKey\>  
  An equality comparer to compare keys.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<[IDictionary](https://msdn.microsoft.com/en-us/library/s4ys34ea)\<TKey, TElement\>\>  
A dictionary from a queryable observable sequence according to a specified key selector function, a comparer, and an element selector function.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)



<br />

# ToDictionary\<TSource, TKey\>(IQbservable\<TSource\>, Expression\<Func\<TSource, TKey\>\>, IEqualityComparer\<TKey\>)

Creates a dictionary from a queryable observable sequence according to a specified key selector function, and a comparer.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive.Providers (in System.Reactive.Providers.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function ToDictionary(Of TSource, TKey) ( _
    source As IQbservable(Of TSource), _
    keySelector As Expression(Of Func(Of TSource, TKey)), _
    comparer As IEqualityComparer(Of TKey) _
) As IQbservable(Of IDictionary(Of TKey, TSource))
```

```vb
'Usage
Dim source As IQbservable(Of TSource)
Dim keySelector As Expression(Of Func(Of TSource, TKey))
Dim comparer As IEqualityComparer(Of TKey)
Dim returnValue As IQbservable(Of IDictionary(Of TKey, TSource))

returnValue = source.ToDictionary(keySelector, _
    comparer)
```

```csharp
public static IQbservable<IDictionary<TKey, TSource>> ToDictionary<TSource, TKey>(
    this IQbservable<TSource> source,
    Expression<Func<TSource, TKey>> keySelector,
    IEqualityComparer<TKey> comparer
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource, typename TKey>
static IQbservable<IDictionary<TKey, TSource>^>^ ToDictionary(
    IQbservable<TSource>^ source, 
    Expression<Func<TSource, TKey>^>^ keySelector, 
    IEqualityComparer<TKey>^ comparer
)
```

```fsharp
static member ToDictionary : 
        source:IQbservable<'TSource> * 
        keySelector:Expression<Func<'TSource, 'TKey>> * 
        comparer:IEqualityComparer<'TKey> -> IQbservable<IDictionary<'TKey, 'TSource>> 
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
  A queryable observable sequence to create a dictionary for.

- keySelector  
  Type: [System.Linq.Expressions.Expression](https://msdn.microsoft.com/en-us/library/Bb335710)\<[Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<TSource, TKey\>\>  
  A function to extract a key from each element.

- comparer  
  Type: [System.Collections.Generic.IEqualityComparer](https://msdn.microsoft.com/en-us/library/ms132151)\<TKey\>  
  An equality comparer to compare keys.

#### Return Value

Type: [System.Reactive.Linq.IQbservable](IQbservable/IQbservable(TSource))\<[IDictionary](https://msdn.microsoft.com/en-us/library/s4ys34ea)\<TKey, TSource\>\>  
A dictionary from a queryable observable sequence according to a specified key selector function, and a comparer.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IQbservable](IQbservable/IQbservable(TSource))\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Qbservable Class](Qbservable/Qbservable)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)
